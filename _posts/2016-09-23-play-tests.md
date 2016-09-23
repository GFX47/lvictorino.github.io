---
layout: post
title: How to organize a play test
date: 2016-09-23
meta: Development, game dev, test
summary: Because of the human nature it can be very difficult to get an honnest feedback on the game you're making. Here are few things to know to get the most of your play test sessions.
categories: gamedev production testing
---

You should test your game, at any step of the development. There is no excuse for not doing it.

However, if you're a game developer there are good chances that you end swamped in the production of your game with very few time to perform in-depth testing sessions. And when/if you finally find the time to test the game there are so many reasons for you to let bugs survive in your game. Sometimes, and for your own good, your brain tries to preserve your sanity making you blind to even the most obvious bugs. Also, because we're all different, there are chances that your experience and logic are different from everyone else. Something logical and natural to you may not seem as natural or easy to every one else. Whatever the case, the result is still the same: your game contains bugs that can be seen, understood and catched only by performing a very large number of test sessions.

Finding all the bugs[^1], and understanding what's actually good or wrong in a game often implies to play it thousands of times using a different behaviour each time. It's something impossible to do alone or without a dedicated QA team. Here comes the moment when you need to rely on people not part of the development team to help you making a better game. It's time to let complete stranges play your game.

## The fear behind the test

Not every game developer can afford to pay for a professional QA team. The plan B is then to let people you don't know play your game and give feedbacks. It may be scary to let complete strangers play your un-finished game and find it awful so early in the development. This fear can be reasonnable. But remember that it's better to let someone play a game in development even if they find game breaking bugs than not testing your game and let these game breaking bugs be shipped with it. People, even not from the game industry, can understand that something in development is not bug free or not complete. But players won't. They won't forgive you to let bugs trash out their experience. They won't forgive you to let them pay for a game full of bugs.

If you can do it without spoiling them important information explain to your testers the current step of development you're in. Explain what's missing, or what's not working. Let them know that you know the game is not perfect yet but might become with their help. Be clear about why you need their help.

## Gather the right set of people

Every development team should have a Player0. A Player0 is someone you know, who is not part of the team, but who you trust. Player0 has to be here during the early stage to tell if your prototype is crap, and she has to be here the day before release to tell if your whole game is crap. Player0 will follow [all the development steps](/blog/five-gates-gamedev), and give you honest feedback every time you will ask. But there must be only one Player0.

You can't ask people you know, your friends or family, to test the game and give an honest feedback. It's not possible. Because they know you well, because they probably know how much you're involved into this piece of software, you can't trust their biased feelings. They will always try to find and talk about the positive sides of what they have played, consciously or not. This biased stuff is what we call love[^2].

That's why you need strangers. Strangers don't have any interest in protecting you so they will just tell what they think about the game ignoring what it implies or how many years you have spent crafting it.

The big question that remains: where to find enough strangers to play the game?

### Schools

A lot of people (if not all) are kin on giving thoughts about almost everything (you just have to go on Facebook to prove this statement). However pure random people feedbacks are not interesting for a game. What one developer needs is game feedbacks coming from the larger gamers panel possible. At least large enough to contain the gamer target if there is any.

That's partly why an easy way to find testers is to go to schools. A lot of students usually prefer to play games instead of studying. They usually spend a lot of time playing. They usually have a great gaming experience. And they usually love to play new things that nobody have played before.

A lot of tech, art, game design schools are interested in games in development mainly because organizing a play test session is usually a good way not only to have 30+ testers feedback at the same time but it's also a way to teach these testers a lesson. Students will learn what a game in development really is (far from theory classes or games made in the protected nest that their school can be) and how important play test sessions are. On the way developers will get honest and precious feedback from actual gamers. A win-win situation.

Watch them play. Record the game sessions if you're allowed too. Then you will better see where they were blocked, why they were blocked, when they decided to leave the session, and why they didn't manage to finish the first level. These feedbacks are precious because they will tell you things about the experience that testers won't have even noticed. Watch them, understand them, and use them.

### Internet

The other option is Internet. Clearly not the best option here but it can help. The conditions will not be the same as with a room full of people and the feedbacks will probably need to be treated with more attention but it's an option than can be useful if you can't afford any other. It's important to have a clear build available[^3] before starting any play test session with people on the Internet. While it's easy to warn people in the same room about what's missing in a game it's very different with people online.

Of course, asking people online won't allow you to record them. But you can use special analytics in your game to gather better details about the actual session. In some case you can also add a game recording feature to your game that tester can send right after having played.

## The less they know the better the results will be

As you can't trust someone you know to be honest with you, the same goes with people already knowing what they are about to play. It's very important that testers know as little as possible about the game before they play. One of the worst enemy in game development is the pre-conceived idea that every gamer mentally builds when she hears a game pitch for the first time. It often leads to frustration and disappointement. That's why gamers often comes to hate some games they were waiting for years. It happens when the game does not meet the expectations they had after they knew about it... and as people use to have great expectations it happens a lot these days.

It's important to avoid that situation before a play test. The less testers will know about the game the better the feedbacks will be.

Also, during a play test session the game experience should not be interrupted. Letting players play on their own is the best way to not inconsciously guide them and modify their experience. Do not answer questions during the session and let them play as long as they need[^4] and intervene only in case of game blocking bug. For every other kind of bugs you must just watch and wait to see how players deal with it. You'll then discover that bugs that looks important to you won't even be seen by some of the testers. It will help you to create a bug priority queue.

After the game session you can then collect and gather feedback using a survey.

## Two steps validation

On top of "simply" looking for bugs, there are usually two things you will want to ask to testers: their immediate feeling and their understanding.

### Immediate pleasure

Questions about the immediate gaming experience will help you to know more about the attractivity and potential of the game. With that you'll know the real forces that you can rely on for marketing and communication purpose. You'll also know more about the frustration of some players. Ask them if they enjoyed the game, and most of all, ask them why. Immediately after having played, it's almost always a matter of basic emotions coming from the guts. This kind of immediate feedback, working on emotions, can help you to feel if the "message" or the "story" you want to tell with your game has been understood.

### Understanding

After all the questions implying emotions, feelings and reactions comes the time to question the game mechanics. What did they learn during the test? What do they remember about the game? What is the purpose of the game? Did they notice that shape? Did they understood that specific sign? Did they have hard time with the controls? Knowing the game what do they think about its name? ...

It's important to find what they have understood or not. With that you'll know where to focus your effort to be clearer.

## Keep your testers informed

Organizing play test sessions is a great way to reinforce or start building a community. Don't forget to get testers' contacts (if they accept to share them with you) and send them some updates about the game during the development. They will be among the very first of your players and, with a bit of luck, if they enjoyed what they have discovered during the play testing session, they will be the first to spread the word about your game.

Thanks them. Love them.

---

[^1]: Don't fool yourself believing your game is bug-free, it's not possible. At least not even the game has been released.
[^2]: There are tons of things to say and write about this "love" thing, but I clearly don't have space nor time in this post.
[^3]: Platforms such as [itch.io](http://itch.io) are awesome and can greatly help if you have to use Internet for your play tests.
[^4]: Every play test should be timed. Don't let testers play over time, even those who are very motivated by the game.