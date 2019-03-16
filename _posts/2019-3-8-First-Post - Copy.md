---
layout: default
author: Bashar
categories: Test
tags: [pfSense, ESXi]
title: First Post
---


I always wanted to start a blog but never made it a priority. After finishing my masters degree, I decided it is time to start blogging and contributing back to the community. I have been attending many conferences and always find new ideas to research and experiment but never really dedicated the time.

I try to attend different conferences every year to see what everyone is working on. I always meet very smart people who are working on really cool projects. I always wanted to start a project of my own but never committed to it. So hopefully, this blog will help me stay on track to contribute back to the generous InfoSec community.

So this is how this blog was born; to document my very first project: The Purple Team Lab.

# The Purple Team Lab

{:center: style="text-align: center;"}
![Lab Diagam](/assets/images/pa.png)
{: center}

## Background

​	Many people approach me asking; How do I get into this industry and how do I land my first job? There are a lot of smart talented individuals out there who are trying to break into the information security field but are really struggling to figure out where to start. It is the infamous chicken and egg problem; How do you land your first InfoSec gig if every single employer is looking for someone with experience? How do you demonstrate experience without having a job in the field? I always refer people struggling in defining their plan to this great post from Daniel Miessler [How to Build a Successful Career in Information Security / Cybersecurity](https://danielmiessler.com/blog/build-successful-infosec-career) and the detailed video from John Strand [5 Year Plan into InfoSec Part 2](https://youtu.be/iB_xCLsgQZI)

​	But after a while, I started realizing that while these guides are spot on and a really good start, many were struggling transforming these ideas into technical concepts. So I started thinking why don't I utilize my technical background to build a lab that can cover many areas these great resources are focusing on. 

​	Since my professional career has been focused around the defensive side of the house, I also wanted to build a playground for the Blue Team. I want to build a lab where I can mimic an enterprise network setup as much as possible without breaking the bank. But what if I take this opportunity to also present some of the concepts and skills needed to start an InfoSec career ? Why don't we start building a hypothetical enterprise network from the ground up and make this network our ultimate lab for both red and blue teams' projects as well as a place to grow our SysAdmins skills (Which are arguably one of the most important skills in this field)?

## The Requirements

​	I started researching what it would take to build the ultimate InfoSec Lab, one lab to rule them all! While we all know such lab will never exist, I still wanted to take a shot at it. 

​	So what would it take to build this lab? What kind of systems, servers, networks and all the other fun stuff do we need to accomplish this goal? Well, let's see:

- **Virtualization:** Minimize costs and get a warm feeling of the "cloud".
- **Active Directory:** A must have for most decent size enterprises.
- **Firewalls:** Critical for any organization today.
- **Network Segregation or VLANs:** Helps understand the concept of pivoting and dual homed networks.









The answer is simple; *Build a portfolio*. A portfolio where you can showcase your work and your understanding of security topics and methodologies. 

There are tons of blogs, webinars and YouTube videos discussing how to build a lab for Pentesting. The standard build includes a Desktop/Laptop with some type of virtualization software to host a Kali machine along with a handful vulnerable machines. This approach is great or people starting out or for someone on a low budget. We can easily spin up new VMs as long as we are not limited by the host resources.

## The Architecture

## ESXi FTW



So we will breakdown the LAB into different segments:

- Virtualization using ESXi
- Network Setup
- Architecture 
- Unifi
- Automation







