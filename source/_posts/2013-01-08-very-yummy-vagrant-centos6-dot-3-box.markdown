---
layout: post
title: "Very yummy Vagrant CentOS6.3 box"
date: 2013-01-08 20:15
comments: true
categories: vagrant, centos 
---
Vagrantbox.es is a great resource for finding a base Vagrant box but many are out of date...mainly because the repo is 21 pull requests behind. So you can likely find more up to date box in the pull requests. 

Not to defy convention, but since those pull requests are being ignored, here's a link to a updated minimal CentOS 6.3 x86_64 box. It does not have any VirtualBox Guest Additions installed. I recommend using https://github.com/dotless-de/vagrant-vbguest it will save you a lot of headache and guess work. It doesn't have Chef or Puppet. It does include the necessary packages to fasciliate installing Postgres on CentOS box
    yum install postgresql-devel





