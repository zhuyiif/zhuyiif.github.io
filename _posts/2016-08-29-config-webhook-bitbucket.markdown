---
layout: post
title:  "Bitbucket上配置webhook"
date:   2016-08-29 11:39:12 -0700
categories: ops
---
* make sure your project have already set it up on Jenkins.
go to the Bitbucket of your repo  e.g. https://bitbucket.org/daqri1/melonv2tonetest
go the Settings →Webhooks (if you can not find Settings in your repo, you probably not a admin)  
* click 'Add webhook', and put a name , the url is http://jenkins-la-webhooks.daqri.info/bitbucket-hook/
* go to the Jenkins job page, and go to configure,  
find the Build Triggers , check the build when a change is pushed to Bitbucket
commit a code change onto your current branch, see if Jenkins can build it automatically .

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
