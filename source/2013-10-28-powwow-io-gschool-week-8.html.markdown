---
title: Powwow.io - gSchool Week 7
date: 2013-10-28 15:25 UTC
tags: retrospective, ideabox, sinatra, pusher
---

> “I do the very best I know how, the very best I can, and I mean to keep on doing so until the end.” ― *Abraham Lincoln*

This past week we officially finished [IdeaBox](http://bit.ly/16Uyusn).

*It was a definite learning process for me.*

I strived to stay true to my thoughts from my last blog post, regarding working
on the things that challenge me vs the things that I already know how to do.

And though I *did* spend some time making the project look presentable... I only
spent a few hours doing so (vs spending hours upon hours making sure everything
was well designed and pixel perfect).

My project, overall, turned out pretty good. You can find it here:
(Powwow.io)[http://github.com/thewatts/powwow.io], and a gem to interface with
it (Powwow)[http://github.com/thewatts/powwow].

The purpose of the gem was to be able to interface with the server and
create/list ideas through an API built on top of Powwow. 

It was a definite learning experience, and - ha - it doesn't work unless you're
running the server locally. It still needs actual user authentication, and some
other factors.

I've found that though I can now write ruby programs, I have a hard time knowing
which direction to move sometimes. How things should work, be structured, etc.
More than anything, I think I just need more experience writing programs - even
if they aren't the best programs in the world - it's still more experience.

One of the other pieces of the project that was fun to implement, was
[Pusher](http://pusher.com). When someone from the group creates an idea, the /activity page auto updates
without a page refresh. It's not the best execution - but it works!

So, some things I learned:

- I'm feeling fairly confident in building *basic* web applications. There's so
  much more that goes into building confident apps... authentication, production
  vs development implementations, security, etc. My tendency is to stress about
  what I *don't* know, as opposed to standing firm in what I've learned - so
  I'll be working to take this all in stride and trust that it will come with
  time.

- Testing is hard, but worth it. I was able to use a TDD approach nearly the
  entire project. Though, crunch time the night before I stopped testing
  altogether. And because of that - I carried a nervous tension while presenting
  the project to my classmates. I didn't know if any of my changes were going to
  break last minute, etc. All in all - testing is crucial, and my hope is that
  I never find myself in that place again - lacking confidence in my application
  because of a lack of tests.

- Evaluating how the project ended, and what I would do differently next time...
  I would definitely fight to be more stringent about my schedule. I feel like
  I found myself stressing towards the end of the project for lack of time. *The
  only person responsible for my schedule, is me* - so, I need to do a better
  job to not find myself in that place again.

All in all, I loved this project - in fact, I want to keep working on Powwow.io
and its gem (though I'm not sure how plausible that will be as we continue into
the next projects).

Regardless, I'm still incredibly thankful for the opportunity to build things
and share this experience with others!


