---
published: 'false'
---

How to move your blog from Wordpress to Github Pages?

I recently needed to have much more control over my blog, so I had two options. One was to upgrade to a much higher plan on wordpress Or have my blog with another CMS. I had heard a lot about Jekyll and how easy and fast it is for creating blogs and websites. In addition to that, Github hosts that for you For FREE, and we all know that github has a massive hosting infrastructure across the world, won't go down, It's extremely fast and reliable.&#x20;

So I decided to move my contents from Wordpress to a blog created by Jekyll. Little I knew, it was harder than I thought. I've decided to write it down for others so that you won't go through all the troubles I did.

## 1. Take control of your domain

first thing you need to do is to be able to take control of your domain. You want to be able to change the DNS settings of it. I'm not sure if Wordpress.Com allows you to do so. What I did was to move the domain out of wordpress.com and transfer it to Google Domains. I had to renew the domain and pay a small fee (about 18$), but Google Domains gives me the freedom I wanted as well as some more features.

Don't start changing your DNS yet. Just make sure you can do it.

## 2.Learn how Jekyll works

Jekyll is a static website builder. It is used to build static pages from dynamic components beforehand such as templates, posts, pages, etc. That means there is no backend or api or database.&#x20;

How it works is you have a directory that contains source files. These files can be textfiles, markdowns, html pages, images, videos, JS script to be included in pages and things like that. When you run `Jekyll server`

that inputs all these files into Jekyll and produces a static website (Only Html, Javascript, Images, Videos).

Then where would you store your blog posts?&#x20;

In files. Stored in a repository. In Github.

## Make sure your url slugs don't change