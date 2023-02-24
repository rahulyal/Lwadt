---
title: Website 1.0
publish_date: 2023-02-23
---

<!--second post --->
# Website 1.0
It's been a very long journey of thinking of having my own website which I thought would have been an easy all-nighter task, which then turned itself into more of a project that needs continuous development as I pick up more skills on my journey.
Here I am finally giving the [tutorial hell](https://www.wbscodingschool.com/blog/what-is-tutorial-hell-how-to-get-out/) a break and introducing the first version of [my website](https://rahul.page/).

## The beginning
When I first started this journey of getting into the world of computer science, one of coolest things I wanted to do was have my own space on the internet. 
I went ahead and started making [my website](https://yalavarthivr.github.io/), it was as basic as it can get, it was plain old HTML, CSS, and Javascript. After wrapping it up and hosting it using [github pages](https://pages.github.com/). It actually did the job, but I quickly realised that I needed to solve a problem. The porblem of writing posts to my blog. For every blog post I had to write the whole HTML page, and link it as an external page. There was no structure i.e., there was no way to add posts in a structured manner, I needed a data structure to take care of the posts of my blog, that way I can just use it to write new posts. That's when I came across the word [CMS](https://en.wikipedia.org/wiki/Content_management_system): Content Management System. I understood that this was a problem faced by everyone around the world. I then learnt that almost 43% of the whole web is made of [Wordpress](https://en.wikipedia.org/wiki/WordPress), which is the most popular CMS there is. 
This right here pushed me into the world of web development and what's to be popularly known as tutorial hell.

## Tutorial Hell
That's when I started playing around with:
- **Wordpress package** - understood how it was an overkill for what I was trying to do
- **Sass/ TailwindCSS** - understood how CSS was super important but wasn't helpful to give me a solution for my CMS problem

This is where it gets interesting I turned to web dev frameworks, wasn't able to get into any of the million options available out there, got to know a lot of names without knowing anything about them: React, Vue, Angular, Nodejs, Nextjs, then found out how deno was better, had to go out and learn what javascript async/await [meant](https://www.youtube.com/watch?v=cCOL7MC4Pl0), and how the server-side, client-side works. What the Chrome V8 javascript runtime was ? How does the browser render the code ? Just got a very basic idea on how web development worked.

Luckily that's when I realized I wasn't getting anywhere, and started to look for the problem I was trying to solve in the first place. I wanted to come out of the tutorial hell so badly I didn't even want to try out another framework and build an actual portfolio where blogs was a folder, where I could organize my posts. I just wanted to leave everything for the future versions and wanted to get the first version up and running as soon as possible. I came upon two options to choose from for the first version of the blog, [deno_blog](https://deno.land/x/blog@0.5.0) and [jekyll](https://jekyllrb.com/). 

### Why [deno](https://deno.land/) ?
Let me be clear, by no means I should be a judge on this. But as a beginner and newbie in the world of webdev. deno seems like a super great way to start my journey. But why did I choose deno_blog:
- [**deno deploy**](https://deno.com/deploy) - it had github integration and allowed me to host my blog for free, even letting me link my custom domain. Super cool (BTW deno deploy uses edge computing)
- **deno == simple** - I tried out both jekyll and deno blog. But deno just felt so simple in how it's built. deno is just easy, that's the way deno is. From the get go, to writing a blog post, till getting it up on internet. The default deno_blog is just the main page, and blog posts written in markdown (which I picked up after writing a report using it, actually super fun, once you get used to it you start writing documents in markdown, instead of google docs, try [dillinger.io](https://dillinger.io/)).
- **Future prospects** - Ok I'm not against jekyll, it's a super cool static site generator, that is all. That was my problem, I wanted to iterate my website, I wanted to develop a portfolio page which then linked to the blog, and many other things, my projects, hobbies, habits & tracking, content i'm right now on(books, tv shows, games, etc). So all in all, I wanted to try out [fresh](https://fresh.deno.dev/) for the next version of the website, and try to atleast make an about me page to begin with, and make blogs a part of my portfolio, and not my whole website. for the next iteration of my website I'm going to use Fresh, a web framework for deno.

### How does it looks ? 
It obviously looks very similar to the original template of deno_blog. I first found deno_blog when ryan dahl, creator of node and deno used it make his [blog](https://tinyclouds.org/)(tinyclouds.org), to demonstrate edge computing on deno deploy. It's like tiny clouds all around the world hosting the web. Do you see it ? 
<!--In chrome - add front page to readme too-->
#### front page

#### post page

## What's the idea ?
- It's my personal space on the internet. 
- I want to keep learning, and I believe the best way to do that is to try and write about it. 
- I want to pick up the habit of writing: I think it'll help me better understand and organize my thoughts. 
- **Progress** - want to keep track of my learning journey.

## Closing:

My takeaway from all this is that, 
Pick a goal, even if it is a small one, that is achievable, get that done first. Then you can work on improving over it, and make it a second version. Just like writing drafts. **Software Engineering 101** 🤪

### Moving forward:
Now that there is a platform, I need to start working on writing posts. I would like to work on more technologies, and get a basic understanding of the tools by working on projects. I would like to write about them as I go on learning.

This is the first of many posts that are yet to come.

Make it a great day!

### P.S: I guess

#### Courses this quarter:
- **COEN241**-Cloud computing - Notes, AWS(learn by doing), Project (building a cloud based application)
- **COEN283**-Operating Systems - Notes, Research project

#### Ideas for blog posts:
- Content related to courses
- Are we even autonomous at this point (For a course next quater: human computer Interaction: Attention management tools)
- Tutorial hell - it is real

#### Expected next version of the website:
1. Portfolio page : Intro, I'm a (looping text of mechanical engineer, dropout, CS grad student)
2. Blog page: blog posts in folders, maybe categorized
