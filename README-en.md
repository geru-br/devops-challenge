# Step 1

## About this 'test'

The purpose of this test is know more about each candidate to DevOps Engineer position at Geru. It's not about a objective test, that can generate a score or an assertive rate, but it's a study case to know about your knowledges, experience and the way that you work. Feel free to code your solution to the problem that we are proposing to you and if have any question, please, let we know by devops`at`geru.com.br email address.

## Scenario

Inside of the `app` directory there is a very simple Flask application. When this app will starts it will read a environment variable called `GERU_PASS` that will be the API password. And so, a call to the application needs a `Header` of `Authorization` with a specific token. Eg: `curl -H "Authorization: Token VALUE_OF_GERU_PASS_VAR " http://localhost/`. You should tell us how to define/change this token in a easy way.

Your goal is to deploy this application in AWS (Amazon Web Service). Probably, you'll need to create a free-tier AWS account, or use an already created account, but don't worry about it, we won't look at your account or call the application already running. We want that you show us how to recreate all this infrastructure in our account as simple as possible. You choose the way. Create a `part1.md` file describing all the steps to deploy your stack in our environment. Take care with this:

* You should start in a totally new AWS account.
* This application need to be into a Docker container.

Feel free to change the code of the application if you need it.

# Step 2

## About this 'test'

This test wants to understand your knowdlege about AWS scenarios, observing it. We want to know if you know AWS and it products and how this products talk one with each other.

## Scenario

Look at the following image, create a `part2.md` file with the technical desscription about this topology.

![aws-test-scenario](https://user-images.githubusercontent.com/29125605/29424258-5d7d5c2a-8355-11e7-9701-2fb26621b6b0.png)

# Ship it! 

* You should clone this repo and commit all your changes, but **don't** open a pull request or leave your code visible to the world just like in a fork.
* When you finish it, compact all the directory and send it to us. **We wanna see your commits, don't forget the `.git`directory.**
* Send a email to devops`at`geru.com.br with your compacted file.

Good coding!
