# Step 1

## About this 'test'

The purpose of this test is to know more about each candidate to the DevOps Engineer position at Geru. This is not an objective test that will quantify a candidate's performance by generating a score, but rather a case study that aims to grasp your knowledge, experience and the way you work. 

If any question comes up, please, let us know by sending an email to devops`at`geru.com.br.

## Scenario

Inside of the `app` directory there is a very simple Flask application. When this app starts it will read an environment variable called `GERU_PASS` that will represent the API's password. Hence, a call to the application needs an `Authorization` `Header` containing a specific token. E.g.: `curl -H "Authorization: Token VALUE_OF_GERU_PASS_VAR " http://localhost/`. You should tell us how to modify this environment variable in an easy way.

Your goal is to deploy this application in AWS (Amazon Web Service). We want you to show us how to recreate all the infrastructure necessary to deploy this application in **our** account in the simplest way imaginable. Be creative. Create a `part1.md` file describing all the steps needed to deploy your stack in our environment. Be careful with the following:

* You should start in a totally new AWS account.
* This application needs to be running in a Docker container.

Feel free to modify the application code if needed.

# Step 2

## About this 'test'

This test aims at understanding your knowdlege about AWS. We want to know if you are familiar with AWS' range of products and how this cluster of offerings communicate with one another.

## Scenario

Look at the image below and create a `part2.md` file containing a technical description of the topology presented in the image.

![aws-test-scenario](https://user-images.githubusercontent.com/29125605/29424258-5d7d5c2a-8355-11e7-9701-2fb26621b6b0.png)

# Ship it! :shipit:

* You should clone this repo and commit all your changes, but **don't** open a pull request or leave your code visible to the world just like in a fork for example.
* When you finish it, compact all the directory and send it to us. **We wanna see your commits, don't forget the `.git`directory.**
* Send an email to devops`at`geru.com.br with your compacted file.

Happy coding and good luck!
