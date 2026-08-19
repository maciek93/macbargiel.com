---
title: "Adding buffer doesn't fix your estimates"
date: 2025-02-11
tags: ["management", "rationality"]
---

We had a project estimated at six weeks. I doubled it, because I have been doing this a while and I know what estimates are. We shipped in fifteen.

The doubling didn't help. That's the part I want to talk about, because I had been doubling estimates for years under the impression that it was a form of wisdom.

Here is what I think is actually going on.

When someone estimates a piece of work, they build a little film of it in their head. First we change the schema, then we backfill, then we flip the flag. The film runs at a sensible pace, everyone in it is working on this and nothing else, and the sequence is the one they just imagined, which is the shortest sequence that works. Then they time the film and tell you six weeks. They are not lying and they are usually not even being optimistic, given the film. The film is accurate. The film is just not a documentary about the next six weeks of your company.

So when I double it, what am I doing? I'm running the same film at half speed. Twelve weeks of the exact same sequence of events, with the same people, doing the same things, in the same order.

But that's not what went wrong. What went wrong was a compliance review nobody had mentioned, a dependency team reshuffling their quarter, and one person being off for two weeks in a way that was entirely reasonable and completely unplanned. None of those are in the film. They can't be, because the film only contains things you thought of, and if you had thought of them you would have put them in the estimate.

Multiplying a number does not add the categories you left out. It just makes the number bigger, and now everyone is annoyed at you for padding, and you are still late.

Kahneman calls this the inside view, and the fix he and Lovallo suggest is embarrassingly simple. Stop looking at the project. Look at the other projects.

Not "how long will this take, given what it involves". Instead: what happened the last six times we did something roughly this size. Not similar in subject matter, similar in shape. Two services, one migration, three or four people, a bit of unfamiliar territory. How long did those actually take, from the day someone first estimated them to the day they were done and nobody was still fixing it.

The reason this works is that all the things you forgot to think about are already baked into the historical numbers. You don't have to enumerate them. You don't have to be clever. Compliance review is in there. So is the reorg, and the person who left, and the fortnight where everyone was firefighting something unrelated. You are not predicting the surprises, you are just noting that there are always surprises and they cost roughly this much.

I started keeping the list about a year ago. It's a spreadsheet, it has maybe twenty rows, and the columns are the project, the original estimate, and what actually happened. It took about an hour to build from calendar archaeology and it is the single most useful management artefact I own.

Our ratio came out at roughly 2.4. Which, fine, that's close to my doubling, so you might reasonably ask what I gained.

What I gained was the spread. The ratio isn't 2.4 every time, it's between 1.1 and about 5, and the shape of that distribution is the actual information. A 1.1 project and a 5x project look identical when someone is describing them to you in a planning meeting. They both sound like six weeks. What separates them, at least for us, is how many teams have to agree on something. One team, it lands near the estimate. Three teams, and you are somewhere in a range so wide that giving a single date is close to dishonest.

So now I mostly don't give a date. I give the range and the thing that would narrow it, which is usually "we'll know more once the platform team confirms whether we can use the new thing".

Two problems with all of this, and I don't have answers to either.

The first is that people hate it. Reference class forecasting feels like it ignores everything they know about the specific work in front of them, because it does. That's the mechanism. You are deliberately throwing away the detail because the detail is what fools you. Telling a senior engineer that their careful bottom-up breakdown is less predictive than a spreadsheet of unrelated projects goes about as well as you would expect. I have not found a way to say it that doesn't sound dismissive, and I'm not sure there is one, because it sort of is.

The second is that it only works if you have a reference class. Genuinely new work has nothing to compare against, and that's exactly the work where estimates matter most and where everyone wants a number. For those I have nothing better than the film, running at half speed, and I say so out loud now, which at least means nobody is surprised later.

The spreadsheet has twenty rows. I add to it after everything ships, usually a month late, when I've mostly stopped caring about that project. That delay is probably a bias of its own, but I haven't worked out which one yet.
