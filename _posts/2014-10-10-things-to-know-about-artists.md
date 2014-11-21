---
layout: post
title: Things you should know about artists
date: 2014-10-10 12:12:12
meta: How to communicate with game artists
summary: Game artists are different. They can create beauty and transform an ugly piece of code into something visually subtle. However working with them require some knowledge about their habits and work that game programmers should know.
categories: artist communication
---

*The following content is about my personal experience after almost 10 years spent working with different teams of artists. I don't mean to imply that all artists are the same. I just try to expose common patterns shared by artists I know.*

Of all the people needed to make a video game the most intriguing ones are, without a doubt, game artists. They come in different flavors, from mockup artists to 3D artists. Without them, games would have a different visual aspect, but also a different soul. 

Programmers and artists are not compiled on the same platform. We are people of logic, trying to make round things fit into squared holes while they are people of art and sensuousness. We do not work on same levels and maybe that's why we do not know how to talk to each other.

Almost every unexperienced game programmer sees artists as nothing more than people knowing how to color inside the lines. With that in mind, being an artist does not seem to be a difficult activity. Young coders often imagine that having The Gimp installed on their computer means that they can easily create sprites, textures and 3D meshes. However art is more than putting colors on a blank page.

On the other hand programmers with a bit of experience know how hard the work of graphic designers can be. Even more because of the artistic aspect of their job. Making things beautiful is not the only thing designers have to deal with, their job is to make people understand what they have to do in the game; their job is to make things coherent and immersive; their job is finally to transform all our dirty code into something simple and elegant.

Because we come from different planets it's very difficult for us to communicate.

## Art is eternal

An important thing to realize about game artists is that they do not work on the same time scale. I don't know if it's a matter of pride, or if it's because they are actual artists, but game artists often don't want to show their work if they are not 99%[^1] happy with the result. Even if they know that nobody will ever judge them or the overall quality of their work they simply don't want to show if it's not ready to be contemplated. 

Having a bunch of perfectionist in your team is actually not a problem… except when you are making a game. Game programmers are used to try and trash because it's how things are done. We live in a world of iteration where we start low in order to aim high later. A good idea is often only good on paper, once put in the game it can be necessary to trash it all. Even when neat Agile techniques are used, trashing things happen. 

Sometimes, because of this "no-no-no-it's-not-ready-yet" complex, game artists spend too much time working on something that will end up trashed. The majority of those I know have real troubles with the idea of seeing their 10 hours work unused and put aside. That's understandable. What is not is the fact they have spent 10 hours working on something that everybody knew could be trashed.

It is very important to be clear about the needs. Everybody in the team has to make an effort to remember that it's all about iterating. We, programmers, have to show them how iterating can save a lot of work to everybody. Placeholders are placeholders: they need to be awful. A pink ugly squared sprite with the right dimensions can be enough. When the game will start looking like a game, when features will be a bit more stable, there will be time to change that ugly pink sprite into a shiny knight full of beautiful colors.

Nothing, except frustration, can result of too many hours spent working on something that won't be used.

## Being more pragmatic

<blockquote class="twitter-tweet" lang="en" align="center">
<p>Developers: age will teach you that it&#39;s more important to create useful things than &#39;perfectly crafted&#39; things. No tech ages well.</p>&mdash; Steve Streeting (@stevestreeting) <a href="https://twitter.com/stevestreeting/status/519590617014222849">October 7, 2014</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

One of the important thing about the relation between artists and their softwares is that it's not because they know what the tools do that they actually care about how they do it. A lot of artists know what a branch in Subversion is, but they don't see the point in the fine and subtle beauty of a Git branch[^3]. For them a branch is a branch be it in SVN or in Git. Silly right?

There is something to learn here. Artists care about productivity not efficiency. Learning and typing Git commands is a long and hard process when they are just a right click away from a Perforce update. If it apparently does the same thing but one is easier to do, why bothering with the hard method? It's really not about the software itself, it's more about how to use it. I don't say that artists are superficial, I'm just saying that sometimes they are way more pragmatic than programmers.

It all make sense when you know that game programmers often have to build tools for the team, especially for artists. When you have to design such tools it's important to keep in mind that accessibility is sometimes more important than the effectiveness or the code poetry that are hidden under the hood.

## Don't wait for approval

Artists can't really appreciate the complexity or the beauty behind code architecture or optimization. Programmers can't really appreciate the work behind a photorealistic mesh with an extremely low poly count. That's a point, even if we can have a lot of respect for the other field, we can't grasp every subtility of it. 

Programmers and artists (but mainly programmers) often need to hear that what they have done is awesome. Waiting approval from someone who doesn't really care about all the weird technical acronym you use can be very frustrating. The next time you'll be proud of your work, remember not to wait for others to care about, consider what you have done a personal achievement instead.

## In the end

We come from different worlds, that is a fact. However our common passion, and a little bit of effort, can help us all to work together in the best possible conditions. Next time you will have to deal with a shiny artist, remember that with a common effort, you should be able to achieve big things.

---

[^1]: I never met an artist 100% happy about her work. The famous _twisted artist_ syndrom.
[^2]: You will say "Git GUI has buttons" and I will say "Commit + Push when you just need Commit in SVN and Perforce can seem as unatural as writing commands".
[^3]: I know GUIs exist for Git (and I suggest you to give a try to [SourceTree][1] by [Steve Streeting][2]). But due to its nature, where Perforce requires a simple action (commit) Git asks for two (commit+push) to do the same. Seen from outside it's one action more than needed. Even if it's biased.

[1]: http://www.sourcetreeapp.com/
[2]: https://twitter.com/stevestreeting
