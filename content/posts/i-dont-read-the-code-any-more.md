---
title: "I don't read the code any more"
date: 2024-10-06
tags: ["management"]
---

About four months in I approved a pull request I did not understand.

Not dramatically. It was a change to retry behaviour in a service I used to own, sixty lines or so. I read the whole thing. I recognised every word in it. I could not have told you whether it was correct.

I approved it because the person who wrote it is careful, the tests passed, and I had a 1:1 starting in four minutes.

That was the moment, if there was one. Not a decision, just something I noticed afterwards on the walk to get coffee.

The thing nobody warns you about is that you don't lose the ability to read code. That would be obvious and you would do something about it. You lose the ability to read *this* code, the version of it that exists now, with the six months of context that went into the bits that look strange. The strange bits are the whole point. That's where the decisions are. And I wasn't in the room for any of them, because I was in a different room, talking about headcount.

What actually goes is the feedback loop.

When I was writing code I knew whether I'd had a good day by about four in the afternoon. The thing worked or it didn't. If it didn't, that was information, and I'd have more information in twenty minutes. Some days the answer was no, but at least there was an answer, and it arrived while I still remembered the question.

Management feedback arrives in quarters. Sometimes it doesn't arrive at all, it just stops being relevant. You make a call about who owns what, and you find out whether it was right in March, by which point four other things have changed and you can't isolate the variable anyway. Nobody comes and tells you. The team either works or it slowly doesn't, and the signal is buried in noise that includes the roadmap, the reorg, and whether two people happen to like each other.

So you go looking for substitutes, and most of them are bad.

The obvious bad one is reading the code anyway. I did this for a while. I'd open the diff and leave a comment about a variable name, because the variable name was the only part I could still evaluate. This is worse than useless. It's a tax on the person who wrote it and it tells them exactly how much attention you were able to give, which is not much. I stopped after someone politely implemented my suggestion and the naming got worse.

The other bad one is metrics. Not because metrics are bad, but because the ones available on a weekly cadence are mostly measuring whether people are busy. Busy is not the thing. I have had teams that were extremely busy and produced almost nothing anyone wanted, and the dashboard looked great the entire time.

What I've landed on, and I don't think it's finished, is that the signal is in how people describe their own work.

If someone can tell me what they're doing and why it matters in about a minute, without hedging, the work is probably fine. If it takes five minutes and there's a lot of "well, it depends what you mean by", something upstream is broken. Usually it's that nobody decided something and everyone is politely routing around the gap. That's a real signal and it's available immediately, which is the part I actually missed.

It's not as good as tests passing. It's slower and it depends on me being able to tell the difference between someone who is confused and someone who is just quiet. I get that wrong regularly.

There's a version of this post that ends with me making peace with it. I'm not going to write that one, because I check the repo most Fridays and read through what landed that week, knowing full well I'm not going to catch anything. It's about twenty minutes and it doesn't help anybody.

I keep doing it anyway.
