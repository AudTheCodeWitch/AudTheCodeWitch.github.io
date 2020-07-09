---
layout: post
title: Upgrade Your Flatiron Blog - Part 2
date: 2020-02-20T17:22:35.000-05:00

---
A few months ago, I shared [how to spruce up your Flatiron blog](https://www.codewitch.dev/upgrade_your_basic_flatiron_blog). Since then, I've continued to publish a new blog post each week. Learn.co provides Flatiron students with a built-in blogging platform that is serviceable, if not flashy. Of CodeWitch.dev's 35 blog posts, I wrote and published 30 of them through Learn.co. 

At the beginning of June, a prospective employer asked me what I knew about CMSs, or Content Management Systems. At the time, my answer was, "Honestly? Not much." 

Determined to come up with a better answer for my follow-up email, I did some research. I learned that a CMS is simply a way to handle all the content (pages, blog posts, etc.) for a website. A CMS is especially helpful for team members who aren't as tech-savvy because it wraps the tricky code into a nice, WYSIWYG (what you see is what you get) format. 

As an experiment, I decided to migrate my Flatiron blog to a CMS. Through this process, I figured I would learn a new skill, have a better understanding of what a CMS is actually good for, and maybe -- just maybe -- find a nicer text editor for my blog.

## Choose a CMS

There are countless CMSs out there, but I ultimately settled on Forestry.io for the following reasons:

* The free plan would fit my needs perfectly.
* It integrates cleanly with GitHub Pages and Jekyll, which is how Flatiron initially builds your blog.
* It has a live preview server.
* It is git-based, meaning all posts and edits would be pushed to the GitHub repository first, making it easy to track changes.
* It came [highly recommended](https://bejamas.io/blog/headless-cms/#introduction).

## Sign Up for Forestry.io

If you're ready to make the change, sign up for your [free Forestry.io account](https://app.forestry.io/signup). I chose to sign up through GitHub, but you can use a regular email address and password if you like.

## Import Your Blog

Once you've logged in, importing your blog is simple.

1. Click the green **Add Site** button. 
2. Within the popup, select your static site generator. Again, your Flatiron blog is already built with Jekyll.
3. Select your git provider. Your Flatiron blog is on Github. Make sure the **Quick Setup via OAuth** toggle is on.
4. Choose your git repository (it should look like `YourUsername/BlogName.github.io` and the branch (`master`).

From here, Forestry will import your blog!

## Start Writing

On the left sidebar, Forestry.io will detect the basic components of your blog. They will be broken into **Pages** (your home, about, and any other static pages you created) and **Posts** (your individual blog posts).