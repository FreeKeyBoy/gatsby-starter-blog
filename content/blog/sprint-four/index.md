---
title: Sprint 4 Wedding-App lab https://joinourbigday.netlify.com/.
date: "2019-04-22T23:46:37.121Z"
---

## Individual Accomplishments

The exercise in futility continues. I know the last thing I want to do is write a blog post while angry. But to be honest, I don’t see myself calming down much until this lab is over, and this needs to be completed. 

All I was able to complete this sprint was adding a countdown timer to the wedding page files, that counts down to the day of the wedding. I used react countdown timer, which is a pretty simple and elegant plug in, i’ll admit. The implementation is simple, and it works exactly as advertised. 

Unfortunately, I could only confirm that it works in a test environment, based on the sample code from its git repository. Upon testing the timer, I noticed that there is a bug in our app that makes it so that the user is incapable of selecting a date other than the current date. Without being able to select a future date, the timer had nothing to countdown to. I put in a trouble ticket for the issue. Regrettably I didn’t have time to fix the bug myself. Or at least I thought I didn’t.

## Detailed Analysis

The primary focus of this last sprint, was getting a feature added that took a design template and turned it into a personal web page for the user. I had no idea how to accomplish this. I’ve been trying to get advice on how to accomplish this feature, and as per usual, asking for help was not a good idea. Well, that’s not fair. It took a couple days, but I did get some helpful advice from my PM. It just took to long to see how her advice could be implemented to this feature. In any case, after asking for advice from the group had backfired a few times, I tried reaching out to an individual developer, and the outcome was much more promising. 

The plan was complicated, but it seemed like it would work. A new table would need to be built on the server, new CRUD routes, and a new helper. And that was just the backend. But it wasn’t that complicated. I asked to take care of the backend portion of the function, since I was confident in my ability to complete that side of it, I was asked to work on the frontend side, insted. 

The frontend required;
1. Create dynamic route for custom site /:userSiteName 
2. Create custom site component
1. state: loading(true) while it gets info
2. Gets info from axios get request
3. Fill state with axis response
4. Render pages with if statements when site info is in state

The arrangement was to pair code as often as possible, so we were both familiar with both sides of the feature, front and back end, and combine efforts in debugging. That and our group really needs to work on our teamwork skills, so I thought the experience would be beneficial. 

Unfortunately, when I logged on Saturday morning, I found a message from my partner saying he already completed the backend, and was logged out of the chatt, so I was unable to pair code with him. He asked me to work on the frontend portion, and I spent most of Saturday on the feature. There were problems getting the props to pass down though. They were not accessing the data table, and I spent most of the day troubleshooting with little success. 

On Sunday, the idea occurred to me, that I could use dynamic rendering to have the template render as a background, and have all the server data render tied to the users ID number. All it would require is adding two columns to the users table, ‘story’ and ‘proposalStory’, then pass them in as props to the wedding page files accordingly. Then I’d have to have the routes of the weddingPage files render dynamically, tied to the user ID. (Thank you, to my PM for passing me literature on how to do this. I wish I saw the connection earlier.) Each page would have a unique URL, and it was a lot less complicated than the original plan. The group was extremely hesitant to the idea before, but I figured if I showed up on monday with a working feature, they’d accept it, and we could move on. 

I was about 75% completed with my idea, when my partner sent me a message saying he finished the feature without me.

## Weekly Reflection

This is the part where I’m supposed to write about my experiences working as a team to complete our objectives. That will be extremely difficult. I wouldn’t call us a team at this point. We’ve had catastrophic communication, organization, and personal interaction problems since about day 2. Now that we’ve officially fallen behind, and the stress is mounting, these problems have only amplified. Everyone is working randomly, and there’s little specific knowledge between developers as to where everyone stands on their tasks. 

Personally, I feel that this lab has had the opposite of the intended effect. I feel I know less now than when we began. One thing I have learned about teamwork in this lab, is what warning signs to look out for in selecting a job.  
