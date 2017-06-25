---
layout: post
title: Hacked Myself!
image: /images/icon.png
location: Toronto
---

It's a gorgeous sunday morning and I'm busy working away on a brand new script designed for exposing website vulnerabilities and figured I would begin by testing it now that I think it's working on a website that I am a system admin for. No worries right?

Oh god was I ever wrong...

I begin the attack and overall the responses I'm getting in the console look great. Some false positives I created and some real ones I patched soon after. I was loving the result. Suddenly, out of no where I get a message from the owner of the website. My good buddy Remz. He then proceeds to message me...

![2017-06-25-discord-message](/images/2017-06-25/discord-message.png)

I begin to wonder if it was actually hacked or if somehow I triggered something.

I talk to him for a little bit before I begin to put the peices together. My script found the temporary WIP contact form I was working on and began to hit it over and over to see if it can invoke a response.

Not the desired result of the script but cool nonetheless.

This does mean however that the script is submitting form data when doing it's vulnerability scans. It's not supposed to. The scan is supposed to be checking. Not directly attacking like that. It's something I didnt consider was a possibility.

In the end I apologized for the 150 emails I accidentally sent him in a matter of 5 minutes and went and sent a few patches around. Things on the website should be more secure for the new "Store" coming out on his website soon.

Now... back to fixing that script...
