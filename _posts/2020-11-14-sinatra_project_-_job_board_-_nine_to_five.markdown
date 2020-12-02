---
layout: post
title:      "Sinatra Project - Job Board - Nine_to_Five"
date:       2020-11-14 09:46:41 -0500
permalink:  sinatra_project_-_job_board_-_nine_to_five
---

![](https://pics.filmaffinity.com/Nine_to_Five_9_To_5-364749326-large.jpg)

*Sinatra?*

In looking over the project specifications. I took it one checklist item at a time:

Specifications for the Sinatra Assessment

Specs:

    X Use Sinatra to build the app
        Sinatra, a domain specific language implemented in Ruby that gives access to pre-written methods that turn this app into a Ruby web app. 'sinatra' gem is required in the gemfile, Sinatra controllers in the config.ru file inherit from Sinatra::Base
    X Use ActiveRecord for storing information in a database
        both models inherit from ActiveRecord::Base, 'activerecord' and "sinatra-activerecord' are required in gemfile
    X Include more than one model class (e.g. User, Post, Category) 
        Job, User

    X Include at least one has_many relationship on your User model (e.g. User has_many Posts)
        User has_many jobs

    X Include at least one belongs_to relationship on another model (e.g. Post belongs_to User)
        Job belongs_to User
    X Include user accounts with unique login attribute (username or email)
        username and password on login page and signup page
    X Ensure that the belongs_to resource has routes for Creating, Reading, Updating and Destroying
        Users can create a new job, view all jobs, view a specific job, edit a job, and delete a job
    Ensure that users can't modify content created by other users
    X Include user input validations
        users can't create a new job without a job title and job company
        Signup cannot happen without a username and password
    * BONUS - not required - Display validation failures to user with error message (example form URL e.g. /posts/new)
    
> *Your README.md includes a short description, install instructions, a contributors guide and a link to the license for your code*

Confirm

    X You have a large number of small Git commits
    X Your commit messages are meaningful
    X You made the changes in a commit that relate to the commit message
    X You don't include changes in a commit that aren't related to the commit message 
		
		
What sticks out? 

*The README. *

That is where my story begins. 

# How to get to the bottom of a README?

The most useful resource I found on this topic was submitted via slack by my cohort-mate, Joshua Collins. If you do not know what a readme is or how to make one this is your “go-to”.


Collected from: [https://www.makeareadme.com/](https://www.makeareadme.com/)

**What is it?**

A README is a text file that introduces and explains a project. It contains information that is commonly required to understand what the project is about.

**Why should I make it?**

It's an easy way to answer questions that your audience will likely have regarding how to install and use your project and also how to collaborate with you.

**Who should make it?**

Anyone who is working on a programming project, especially if you want others to use it or contribute.

**When should I make it?**

Definitely before you show a project to other people or make it public. You might want to get into the habit of making it the first file you create in a new project.

**Where should I put it?**

In the top level directory of the project. This is where someone who is new to your project will start out. Code hosting services such as GitHub, Bitbucket, and GitLab will also look for your README and display it along with the list of files and directories in your project.

**How should I make it?**

While READMEs can be written in any text file format, the most common one that is used nowadays is Markdown. It allows you to add some lightweight formatting. You can learn more about it here, which also has a helpful reference guide and an interactive tutorial. Some other formats that you might see are plain text, reStructuredText (common in Python projects), and Textile.
You can use any text editor. There are plugins for many editors (e.g. Atom, Emacs, Sublime Text, Vim, and Visual Studio Code) that allow you to preview Markdown while you are editing it.
You can also use a dedicated Markdown editor like Typora or an online one like StackEdit or Dillinger. You can even use the editable template below. (not shown, check out the website)


Now, that you know the basics, here is my take on the Readme matter. It all boils down to storytelling. Your app, your project, your creation - whatever you are making has to have a purpose. To describe it’s purpose and how to use this new “thing”, words are required. In thinking about many of the most important and popular ideas and creations in existence, you know, Facebook, the Mona Lisa, Pinterest, (well maybe not Pinterest), The Godfather movie, The Oxford English Dictionary, even your own birth certificate, or that song, “Watermelon Sugar” (high!), they all have something in common. 

# They tell a story.

Facebook is a way to connect people (you see their story in a timeline), hey, they even created Instagram “Stories”. The Mona Lisa tells the story of Da Vinci’s lady. What’s behind her cryptic smile? I’ve seen it in person in Paris. It will knock your breath from you, the genius of it. Pinterest - the story of all the things I want to make, collect, come back to, or covet. Look at someone’s saved pins and you get to read an often too revealing story of what they are in to. The Godfather movie, your typical Italian American saga of a family trying to break free of the “life” while constantly being the standard by which all other power is measured. Dictionary? The story of language and what it means. Your birth certificate, is the story of your who, what, when, and where. Your mom and dad are listed. Your time and place of birth. It’s where your story begins. 

Lastly, if you are still with me, that song, “Watermelon Sugar”. Goodness. I can’t get it out of my head. I even set my session_secret to it.



*What story does it tell?*

Albeit perhaps less of a story than the Mona Lisa, but there are all kinds of stories and music just makes you feel. The lyrics below are either Harry Styles completely enamored with someone, the summer, a combination of those, or it could be whatever we decide. The main point is lyrics are the readme of a song. The picture is the readme of the Mona Lisa, Words are the readme of a dictionary, Pins are the readme of Pinterest, and Friends are usually the readme of Facebook. (Or more specifically, a profile). 

> Tastes like strawberries on a summer evenin'
> And it sounds just like a song
> I want more berries and that summer feelin'
> It's so wonderful and warm
> Breathe me in, breathe me out
> I don't know if I could ever go without
> I'm just thinking out loud
> I don't know if I could ever go without
> Watermelon sugar high
> Watermelon sugar high
> Watermelon sugar high
> Watermelon sugar high
> Watermelon sugar
 
I vibe to “Watermelon Sugar” after I get my broken project fixed. Yes, it’s happened more than five times. Such a high, learning development!

What we put in a Readme matters. *It tells the story.*

To learn all about my story for this project and how to use it, check out my repo - START WITH THE README and enjoy the video walkthrough where I tell you why I made Nine_to_Five.


Link to my Video Walkthrough of Nine_to_Five : [https://youtu.be/AYQ23vV1Tsw](https://youtu.be/AYQ23vV1Tsw)

Link to Github repo : [https://github.com/danainjax/nine_to_five](https://github.com/danainjax/nine_to_five)
