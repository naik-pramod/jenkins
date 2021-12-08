# Continuous Integration
Continuous Integration (CI) is the process of automating the build and testing of code every time a team member commits changes to version control.


# CI Pipeline

![ci-pipeline](/images/ci-pipeline.PNG)

Build is triggred when a developer commits the code to Github respository
Jenkins runs unit test and all the pre-integration tests such as quality and secirity tests
Builds the artificat for example war file in case of java, or docker image
Runs accpetance tests and pushed the results to an artifactory-management repository. for example, docker resgistry, JFrog Artifactory