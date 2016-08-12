---
layout: post
title: "Fooled by Randomness"
author: ahaldar
categories: articles
excerpt:
tags: [probability, randomness, family size, long queue, pi]
image:
  feature: so-simple-sample-image-3.jpg
  credit:
  creditlink:
comments: true
share: true
---

We're puppets of probability, slaves to statistics. Every last one of us. The gamble of leaving the house without an umbrella on an overcast day.  The despair of picking the slowest moving queue in the supermarket. The risk of grabbing a quick smoke where your mom might just walk in on you.

> Don't be surprised unless you know what you expect.

“Fooled by Randomness” is a book by Nassim Taleb that discusses the fallibility of human knowledge. We humans are quick to dismiss the randomness factor, showing far too much misplaced faith in causality.
In Taleb's words:

> Realism is punishing. Probabilistic skepticism is worse.

We're easily fooled, and I'll prove it to you.

# Family Matters
Consider for a moment that you've been handed the dreary task of carrying out a survey to determine the average number of members of families in your locality. A reasonable way to do the job, one imagines, would be to stand out there and ask everybody you encounter what their family size is. Right? Wrong.
“But I'll make sure the sampling is as random as can be!”, you protest, “How could it possibly go wrong?”. Here's how. Let's say there were a total of 100 families in the locality, and that family sizes can either be 2 or 4 only. If there was equal likelihood of 2 member and 4 member families, your survey should have given you 3 as the estimated family size, yes? Here's the catch. A total of 100 families means 50 families with 2 members, and 50 with 4.
So in your total population of 50 2 + 50 * 4 = 300 individuals, you've got skewed representation. When you sampled randomly, it was twice as likely that you'd pick a person from a family of 4! So right from the start, you're doomed to arrive at something closer to 3.75 as the average family size.

Speaking of family...

# Long Live Grandma
“Just look at my own mother, she's 83 and healthier than I am!”, your least favourite aunt says, firmly cementing her case (or so she believes) that the older generation lived far healthier lives. As she settles into her soliloquy on pesticides and laziness, your mind drifts.
Sure, she's got a point, but the statistics are misleading. Why, there was all manner of disease that caused many of that generation to die young. We just weren't hearing those stories. Besides, it doesn't seem fair to only take the examples of our grandparents. Your grandma is a grandma, ipso facto she couldn't have died at 20! Yet another situation where ill-thought sampling was misleading.

Here's another family-themed trick you can play on gullible friends.

# Oh, Brother
Ask your group of friends to all think of the number of siblings their mothers have. Make them keep a count of the total number of males and females, counting their mother and all her siblings. Pick out the most gullible of the lot. Bet them a large sum of money that no matter who they ask, the probability of there being a female sibling is nonzero. Collect your cash, potentially lose a friend, and live a happy life.
If you're that gullible friend, here's what happened. When that asshat “friend” of yours told everyone to count all their mother's siblings, he was already setting himself up for a win. Mother's siblings. Mother's. Ergo, tally of females would never be 0 for any person, and therefore neither would the probability.

Now that you're rich and friendless, you're going to go shopping. Money can buy happiness, wasn't that the phrase?

# Q
Of course, at the billing counter, you're stuck in the longest queue. You stand there wondering why you are always chosen to face the wrath of the Queue Gods. You realise that the word has no less than 4 superfluous letters, and laugh at the Q Gods. Every other queue now begins to move faster than yours, and you immediately regret antagonising aforementioned Gods.
But ponder this. Aren't you simply more likely to be found in a longer queue? It does have more people in it, after all! If all you poor people weren't in it, would the queue even be the longer queue?

# 3.14159-insert-random-digits-because-who-would-even-know
“Fine, fine, we're all stupid. That's great, but how is probability useful?”, I hear you grumble.
If I had to list all the ways, this would turn into a book. Instead, here's one quick and cute example.

Everyone knows how the value of pi is found. You take a circle of unit radius, find the ratio of its perimeter to its diameter, yada yada. But what if we aren't equipped to measure its perimeter?
Probability to the rescue! Take that circle of radius length 1 unit, and stick it inside a square of side length 2 units. Clearly, the areas of the circle and square are pi * r * r = pi * 1 * 1 sq units and a * a = 2 * 2 sq units respectively. Now have some fun. Find darts, and throw them at the square. There's a fraction of them that will land within the circle, and this ratio gives us an exciting way to figure out an estimate for the value of pi. So we get pi = 4 * M / N with M darts landing within the circle out of the N darts thrown in the square.


Note: I am recounting many of these examples from talks on probability at the recent IISc CSA undergraduate summer school.

