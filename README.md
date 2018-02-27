# go-git-webook
Webhooks for GO and GIT

# install
add the files to your projects .git/hooks folder

# what it does
## Pre-Commit
This step executes when you run "git commit"
* Executes go build to ensure your project builds 
* Executes go test to ensure your test cases still pass
* Executes go-fmt to check the format of the files
* Executes go-vet to check the files for potential issues
