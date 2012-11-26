---
layout: post
title: Migrating to Jekyll from Wordpress
date: November 17, 2012
--- 

Always on the lookout for ways to improve my websites and workflow I stumbled upon a ruby based framework called Jekyll. What is Jeckyll?

`Jekyll is a simple, blog aware, static site generator. It takes a template directory (representing the raw form of a website), runs it through Textile or Markdown and Liquid converters, and spits out a complete, static website suitable for serving with Apache or your favorite web server. This is also the engine behind GitHub Pages, which you can use to host your project’s page or blog right here from GitHub.`

Why is this so appealing? First of all it runs fast on any server because it's only html that is compiled and deployed. Also without the need for any database it is very secure, so you have to love the simplistic beauty of that. Jekyll supports markdown, a very easy to read and write text to html conversion tool for web writers/developers like myself. I just started writing this way and I love it. It's fast and natural to write, and all I have to do when I want to write an article is create a .markdown file in the _post folder, name it appropriately, add a yaml header. Then simply run the command jeckyll in the terminal and it outputs all the necessary html pages, and links to a folder called _site. 

So far during my migration I have been completely involved in perfecting my workflow with Jeckyl, Sass, and Git. So far I have been successful in my quest to have two different computers that I can update my site from via a github repo. Once I update the site with Jekyll all I have to do it push changes to the git repo and it deploys my website to the production server via a git hook. Before I started to use Jekyll I was developing a way to work on a local copy of wordpress and deploy both the site and database via git. Though I will likely still pursue this solution for other clients sites, the static approach of my current workflow makes my life a lot easier for my personal site needs. That's all for now, next comes a new responsive design.</li>


