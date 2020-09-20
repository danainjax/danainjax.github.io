---
layout: post
title:      "Command Line Interface "
date:       2020-09-20 09:21:28 -0400
permalink:  command_line_interface_-_airport_codes
---

# Airport Codes

> In order to do anything worthwhile, you have to believe that you can. Be unstoppable!
> 



OK, so the project process. What’s to tell? 

#everything

Mainly, let this post be the one that mentions the most important part of what I assume will be a long line of projects, programs, and/or deliverables. 
What is the most important part? How do I say it? You’ve got to bring YOU. 

Not part of you, not some of you- all the YOU you currently are plus the some of you that is learning to code, PLUS Stack overflow, the cohort, the cohort lead, the  Ed coach, your pair partner, your priest, your workout program, your life circumstances,  slack, zoom, Ruby docs, Youtubes, Learn.co… 

Am I making myself clear? It’s ALL in, or you’re not going to get it done.

How to start


*Brainstorm ideas- * The “think” piece. Thinking is such an abstract thing. So abstract. Probably an excellent place to start for programming.  Just list everything that comes to mind and worry about whether or not it’s valuable or viable at another part of the process. Think about an idea for your project. Vet the ideas- which seem interesting, can you get the data for that idea? How would it work? Eliminate any obvious no’s.

*Write a user story -* I’ve been in the travel industry for almost 25 years. The thing I do a lot of is search availability and lookup airport codes. Codes seemed an easy grab. They must be stored somewhere?

*Model it, baby -* Classes. I had a few main classes in this project: CLI, Scraper, API, and Airport. The CLI class was the brains of the program. The API and Scraper classes provided the data, and the Airport class held my codes/data in airport objects that I could call with their properties of code, and display name.

```
class Airport

    @@all = []

    attr_accessor :code, :display_name

    def initialize(code, display_name)
        @code = code
        @display_name = display_name
        @@all << self
    end
```

*Hook it up. Wire it. Write it. - *(Trial by fire, time.) Doing the actual API get and the actual scraping was hairy, to say the least. There are some great EXAMPLES that I particularly enjoyed.

```
JSON.parse(json)
```

For getting your gem off the ground and figuring out if you can scrape:
[https://youtu.be/KwBMwZ89Hj8](http://)

For a build walk-through:
[https://youtu.be/jxZ4a-3UoEM](http://)


*Break it. Fix it. Test it. REPEAT -* I often didn’t know how to do what I wanted my code to accomplish. I looked it up. I reviewed past lessons, googled, checked Stack Overflow, and reached out to my cohort lead in-office hours and in one-on-ones. After thinking and planning came the actual coding. Comprehending what I was coding and how it was behaving was an action step. I had to write some and test some to see how it behaved and what I wanted to do next. This is where I realized how much more I knew than when I started, but also the infinite amount there is to learn. Spoiler: That was the most exciting moment of my life!

*Believe it.* Getting a project working made me believe I could get a project to work. Learning by doing, really is the best thing.

Link to my Project Video Walkthrough:

[https://youtu.be/6Up9Fay1ea4](http://)



