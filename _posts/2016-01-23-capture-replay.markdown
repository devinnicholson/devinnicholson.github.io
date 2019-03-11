---
title: "AWS Capture Replay Tool - Capstone"
layout: post
date: 2018-01-23 22:10
tag: 
image: 
projects: true
hidden: true # don't count this post in blog pagination
description: "Capstone Final Project"
category: project
author: 
externalLink: false
---

## My Capture Replay Tool (MyCRT)
In the Fall of 2017, Amazon proposed a project to our Software Engineering Capstone class. We were split into teams of 7 in order to create several different solutions to creating a tool that captures workloads and metrics on an RDS database. The tool would ultimately allow users to replay workloads on a different database configuration in order to find the best performing database config for business needs. Capstone was split into 3 quarters for a year-long process: Software Requirements, Software Construction, and Software Deployment. During this process, our team created documentation for requirements, built the product using SCRUM as our development process, and focused heavily on QA before deploying the product. To learn more about the product, there is a blog post written [here](https://aws.amazon.com/blogs/database/cal-polys-software-engineering-capstone-class-builds-mysql-capture-and-replay-on-aws/) which goes in depth about the project.

### What is MyCRT?
MyCRT is a Capture & Replay tool for any AWS RDS instance. The tool was designed to attach to an existing AWS setup and monitor the load on a database. After capturing the requests and queries hitting the database, they are stored on an S3 bucket. That saved load can then be replayed onto other RDS instances with different configurations and comapred against the original. This provides a baseline to test all RDS setups against, and that comparison can be performed on all available CloudWatch metrics through our analysis tool. My team was Team Titans, a group of 7 Software Engineers that specialized in different parts of the project. I was specifically on the backend, working on the capture and replay and a sqlite database to support persistence. Overall, my team learned a lot together and it was an amazing experience. It was great to learn how to work with a team on a project proposed by a tech giant, but the friendship my team has will be cherished forever.

### Learn More
Our website for the final project is [here](https://teamtitansaws.github.io/).

---
