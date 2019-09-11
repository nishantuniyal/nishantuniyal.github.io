---
title: "My Python Development Environment"
date: 2019-08-05T11:46:04-07:00
draft: true
comments: false
slug: ""
tags: []
categories: []

showpagemeta: true
showcomments: true
---

## Intro

Let's face it, the python development environment setup is not an easy task. The xkcd comic below accurately sums it up. To clear the confusion around "properly" setting up your development environment, I decided to write this post (I put properly in quotes because the subjectivity of the term). I hope you find it helpful. Any comments, corrections, improvements are welcome.

![XKCD Comic](https://imgs.xkcd.com/comics/python_environment.png )

## Tools I am Using

* pyenv
* pipx
* pipenv

Let's go into the whys', which might help us understand the rationale behind choosing these tools.

### pyenv

I use Homebrew on my mac and have installed python through it. As I find myself working on different projects with different python version requirements,  and along with the need to have the latest version of Python3 as my default python version, I felt that Homebrew no longer fit the bill for it. So, I did some research and found pyenv. After evaluating things like, active development and maintenance on Github, and widespread adoption, I chose pyenv.

### pipx

In the past, I used Pipsi to install python cli tools. As pipsi is no longer actively maintained, I decided to look for an alternative. Through the Python Bytes podcast, I found pipx.

### pipenv

I like most things by Kenneth Reitz, and when he first released Pipenv, I was one of the early adopters. I loved the auto-generated, auto-updated TOML configuration file, and in my modest opinion, most things by Kenneth are just awesome.

## Related Articles and Inspiration

[Simplify Your Python Developer Environment](https://medium.com/expedia-group-tech/simplify-your-python-developer-environment-aba90f32dddb)
