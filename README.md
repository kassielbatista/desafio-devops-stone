# Stone DevOps Challenge

## Presentation

Hello there Stone Candidates!

To better assess you technical skills, we prepared this small challenge as part of our hiring process.

## The Challenge

Pretend that you are a **Infrastructure Developer at Stone Co.** inside a development team working in a new product for the financial market. The team (including you) has agreed to use **Jenkins as your CI/CD tool**, and Node.js with React as the official tech stack. Your team **needs a staging environment** ready to test their first features, and you are tasked to build one, completely as code, for review of the team. You are expected to place the infrastructure code inside the app's own source code repo (this one).

Once you clone this repo, you will note that we have a `source` folder, inside that folder you will find a simple React application.

What you must know about the app:

1. `npm install` downloads the dependencies of the project.
1. `npm start` runs the application.
1. `npm test` runs the application tests.
1. `npm test -- --coverage` (yes, with duplicated `--`) runs the coverage and generates a `/coverage` folder with all the data.
1. `npm build` will build the application for the production environment.


### Checkpoints

Here are some of the checkpoints to guide you through this challenge, you **don't need to do all of them**, but do as much as you can. They **are not** in any particular order, use your analytical skills to prioritize them.

- [ ] You must use slaves to run your builds on Jenkins.
- [ ] You must create a Jenkins job that will deploy your app.
- [ ] Your job must use continuous integration approach.
- [ ] Continuous Deployment will be a plus.
- [ ] You might want to use Docker to run your application, if you choose this way it will be a plus, we like containers ;)
- [ ] All tasks should be done with some IaC Tool (Ansible , Puppet, Bolt, Chef, Terraform...).
- [ ] We want to change the default user and password for Jenkins.
- [ ] You can use any opensource lib, but you need to explain why you choose that one and references that on docs.
- [ ] Docs Docs Docs. We know that writing docs its not the coolest thing ever, but we need to know how to run your scripts. So documentation will be evaluated in the same way as your code.

#### Advanced

- [ ] Deploy a SonarQube server to run static code analysis.
- [ ] Report code coverage on SonarQube
- [ ] Build one of your own opensource application built in Python, Go, Elixir, C#, Java or Node!

## Requirements and Deliverables

You will need to complete the challenge:

- A computer with internet
- A free account for <a href="https://goo.gl/1gzFRE" target="_blank">Microsoft Azure</a>, <a href="https://goo.gl/GQRLct" target="_blank">AWS (Amazon Web Services)</a>> or Vagrant.

The deliverable for this challenge is code, inside a public GitHub repository of yours. You should provide us the URL for it.

We should be able to build all your infrastructure with few steps, or even with just one command, in our own Azure, AWS or Vagrant environment. Please specify the command to execute and any setup required to ensure a successful run. Also, please specify the URls you would expect us to use for accessing each service:

- The provided React application
- Jenkins
- SonarQube (if you choose doing it)
- Other applications you add (if you choose doing it)

## Useful Keywords

- Ansible
- Continuous Delivery
- Docker
- Puppet
- Makefile
- CentOS
- SonarQube
- `sonar-project.properties`
- Coveralls
- Heroku

## Questions?

If you have any questions, please send an email to your contact at Stone that we will reply as fast as we can :)
