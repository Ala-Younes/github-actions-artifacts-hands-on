# artifacts-hands-on

Notice the Repository name is - **github-actions-artifacts-hands-on**
Go through the repository, there is a workflow file named artifact.yml
Go to Actions Tab click on **I understand my workflows**, go ahead and enable them.
Do the following:

1.  Append a new job named - download

    a. This job should execute after the - build job

    b. This jobs runs on - ubuntu-latest

    c. Add step to download the text file from previous job and place it in path: ./artifacts

    d. Add step to display the content of hello.txt file

2.  Use cat ./artifacts/hello.txt command