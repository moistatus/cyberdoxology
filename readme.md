# Introduction to the Exocore

## What is the Exocore?
The Exocore is an easily navigable personal hypertext database for text and images— a personal wiki which, over time, forms in increasingly faithful digital representation of your brain. Read a more detailed explanation of the Exocore's present and future functionality [[exocore|here.]]

## Features
**Smart syntax rendering:** To read more about how you can use hyperlinks, embedded code, footnotes and more, see [[syntax|this article]] about Exocore syntax.

## How to Begin
Follow the instructions [[installation-instructions|here]] to learn how to install your Exocore locally, set up publishing with Netlify, and view your site offline before publishing.

## Using your Exocore

### Creating new posts 

Use keyboard command `Ctrl + Shift + P` to summon the command panel. From here you can access a variety of functions by beginning to type their names. Start typing 'create new note from template' to find the options for creating new posts. 

- **Daily Notes** are designed as a quick access scratch pad, and are perfect for low-specificity research dumps and fleeting notes that will inform your notes in future. These are automatically titled by date. One is created each day automatically, and opened when you open VSCode.
- **Wiki Notes** are designed for single atomic data points, and are automatically titled with a hexadecimal color code. This code is turned into a correspondingly colored badge in the index of the published site.
- **Journal Entries** are for your thoughts, and are not automatically titled.
- **Articles** are for longer write-ups on a particular topic.

You may have noticed that these notes together create a pipeline for systematising knowledge over time from the general to the particular, and for capturing a bank of scattered reference material and developing it into a polished final product. You might choose to cite a research dump in the subsequent post that it turned into as a bibliography/further reading section, such as appears at the bottom of [[predictive-processing|this wiki note]] 

### Using Metadata

If you followed the above instructions to create a new post, you will notice that it spawned with a YAML metadata section at the top. This metadata does not appear in the text of the post, but affects how the post will be treated when your Exocore is rendered into a website. The metadata of the post you are currently reading looks like this:

```
---
layout: article
category: article
subtitle:
topic: meta
date: 2022-04-13
tags: meta computers exocore
---
```

If you're using a browser to read this, you won't see this information at the top of the post, but the Exocore has incorporated it already into the way it treats the post. It has dated the post, sorted it into the 'Articles' section of the site, and given it tags which appear in the left sidebar. You can add to the topic and tags sections, backdate your post, or add a subtitle if you wish. 



[//begin]: # "Autogenerated link references for markdown compatibility"
[exocore|here.]: _articles/exocore "The Exocore Package"
[syntax|this article]: _articles/syntax "Exocore Syntax Examples"
[installation-instructions|here]: _articles/installation-instructions "Exocore Installation Instructions"
[predictive-processing|this wiki note]: _journal/predictive-processing "Predictive Processing and the Free Energy Principle"
[//end]: # "Autogenerated link references"