---
title: "An Introduction to Git"
date: 2018-04-15T11:01:03-07:00
draft: true
comments: true
slug: ""
tags: []
categories: []

showpagemeta: true
showcomments: true
---
# Git - Version Control

Version Control is arguably the most important software developer skill that everyone should master.

## Motivation

The thought of writing this post came to my mind when one day my friend, who was getting his feet wet in software engineering, told me that he was using folders to keep different version of his application. I was like, whaaat? Why don't you use Git?

To my surprise, my friend replied, What is that?

It was later that evening that I decided to write a tutorial for my friend. Eventually, that tutorial evolved into a blog post.

## Introduction

This is not a Git tutorial. I do not believe in reinventing the wheel hence, my objective is not to write another Git tutorial but to share some tips and tricks that I find useful in daily use of Git. There are umpteen number of very well explained tutorials on Git that you can follow: here....

### Useful Git Commands

#### Rebase

For pushing local changes to remote without branching an merging you can use the **rebase** command.

```bash
git pull --rebase
```

#### Commit log

To view a nicely formatted commit log

```bash
git log --oneline
```
