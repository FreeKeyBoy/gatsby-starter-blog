---
title: Sprint 5 Wedding-App lab https://joinourbigday.netlify.com/.
date: "2019-05-05T23:46:37.121Z"
---

## Individual Accomplishments

For this sprint, I spent the two weeks adding some badly needed styling and continuity in our web app. I set the margins, border radius, padding, button styling, and what little color palet the app has. I did this for every component in the app, except for the two or three that were specifically called by the other devs. I also made the app responsive to most any size screen, using flex-box styling, and most everything width wise was set to percentages, so very few media queries were needed. We used styled-components for our styling, but there were a few instances where inline styling was needed, since there are a lot of react plug-ins that don’t play nicely with styled components. 

## Detailed Analysis

Pick one of your tickets and provide a detailed analysis of the work you did. This should be approximately ¼ page of text, and include screenshots if appropriate

Any one of my tickets would read much like the others. Since the goal was uniformity across the app, almost every component is styled the same. For screens larger than 700-900 px, width of all the container elements are set to 80%, most very element is separated from the next one down in the column buy a 3% margin, and the border radius is set to 8px. They all use a plain white background with black text for readability. All buttons are set to 30% width, 25% border radius, and have a mat teal color. At cell phone screen widths, the buttons take up less room on the page, and the container widths change to 90%, for readability. The font size also shrinks half an em at cell phone screen sizes as well. 

The custom page components labeled WeddingPage1,2,3 are slightly different, but follow the same theme. The background on the container divs is a light baby blue, and somewhat transparent. I wanted the background to be slightly visible, but not so much, so that it becomes a distraction. The opacity on the story elements is set to .9 on two of the custom backgrounds, because the image was too busy, and it made the text hard to read. So I turned down the opacity, to make the text easier to read, but left it so that the backgrounds harder lines were still barely visible. This allowed me to achieve the effect I was after, without sacrificing useability. One of the tracks to getting this t work was the fact that the font inherited the opacity settings of its parent component. A handy trick to get around that is to give the font a text-shadow of 0. This will make the text appear as though it has no opacity, because the shadow has none, and the 0 setting means it perfectly overlaps the text with 0 blur. 

The remaining custom page, had a simpler background, and the text was still readable with the opacity set to .5, so I left it. The elements that contain the name of the couple, date, and location of the wedding, used larger sized font, and were still plainly readable with the opacity set to .5, so I left them as is. I also set a box shadow on all the elements, because I like the vaguely 3d looking effect that it creates. I know the current design trends use flat elements with sharp angles, but I personally was never a fan of that style trent. It feels aggravating, and emotionless, and that’s the exact opposite of the feel we want from a wedding themed app. 

## Weekly Reflection

Well, as per usual, the hardest part of working with this team, was getting us to work as a team at all. Despite our best efforts we couldn’t get our leader to make a decision on anything. No color palet, no margins, no uniformity, we couldn’t even get him to decide on a font. Every time one of us tried to bring up the necessity of these decisions, we were told to, “wing-it.”  When planning was absolutely needed, we would stage a little mutiny and either organize between ourselves on slack, or on zoom when our leader wasn’t online. That’s why I did 90% of the styling needed. I knew uniformity was needed, and at this point in the project, the only way we would achieve this, is for a single person to make the decisions, and implement them. Thankfully, I am a trained graphic designer, so I took the lead on this aspect. 

Unfortunately, my training is about 12 years old, anf my instinct is to make everything look like a post 90’s angelfire page. I was really hoping for more input from the younger members of our group, to help push past that. Though I think the final result does meld the older, and newer digital design trends nicely. It’s eclectic, but purposefully so, and I think it’s very eye catching. 

The presentation video should be interesting. The person doing it, has been practicing, and I have a lot of faith in him. I don’t think it will be as good as we hoped it would be, coming into this project, but I’m confident it will make the grade. I’m just relieved I’m not the person doing it. 
