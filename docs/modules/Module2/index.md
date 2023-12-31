---
title: Module 2 - Project Management

has_children: true

---

## Module 2 - Introduction 

“Shifting left” is a key tenant of the DevSecOps mindset, and this process begins well before code is even committed into a repository and deployed via a pipeline, by adopting secure coding best practices and using IDE (integrated development environments) tools & plugins for code analysis during the development phase can go a long way with addressing security issues earlier in the development lifecycle when it's much easier to fix.

![shift-left-model](../../assets/images/module2/shift-left.png)

## Best practice - Use Integrated Development Environment (IDE) security plugins 

Most popular IDEs (Integrated Development Environments) like Visual Studio, Visual Studio Code, IntelliJ IDEA, and Eclipse support plugins or extensions that developers can use to get immediate feedback and recommendations around potential security issues they may have introduced while writing their application code or inherited by using 3rd party open source code libraries.


## Best practice – Perform Static Code Analysis (SAST)

Use GitHub Security scanning capabilities for code scanning using CodeQL which is the code analysis engine developed by GitHub. Code scanning is a feature that you use to analyze the code in a GitHub repository to find security vulnerabilities and coding errors. After you enable CodeQL, GitHub Actions will execute workflow runs to scan your code and display the results as code scanning alerts. The alerts provide detailed information on the source of the issue and along with details on remediation and fixes.

## Best Practice - Use pre-commit hooks

It's a best practice to establish checks for your repositories before and right after commits happen to catch a potential security vulnerability, Git pre-commit hooks allow you to check for sensitive information within your application source code and prevent a commit from happening if a security issue is found. The pre-commit framework provides built-in hooks that can be easily configured for a specific project, for example, there are pre-built hooks to scan for secrets, private keys and credentials and prevent a commit if any of these issues are found. Their are also third party pre-commit hooks that can be used for security use cases.

## Prerequisites

The following prerequisites are required to complete the labs in the Develop section

1. Visual Studio Code (VS Code)
2. Java JDK 11
3. Maven
4. GitHub account
5. Git client