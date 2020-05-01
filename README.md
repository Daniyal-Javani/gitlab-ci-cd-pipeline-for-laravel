# gitlab-ci-cd-pipeline-for-laravel
A Gitlab CI pipeline optimized for use with Laravel applications

# What does it do?
It runs your test automatically in Gitlab with no pain! Then deploy it on your production server.

# How to use it?
1- put these two files into your root folder
2- install and config https://github.com/lorisleiva/laravel-deployer
3- on your local machine run ssh-add USERNAME@SERVERIP
4- On gitlab, go to your repository > settings > CI/CD > Variables
5- Add a new variable SSH_PRIVATE_KEY. The value is your ssh private key

That's it!
