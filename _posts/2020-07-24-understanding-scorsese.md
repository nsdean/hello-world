---
layout: post
title: Understanding Scorsese
---
Something wrong?

Martin Scorsese is a great director. But lately his films seem to be getting longer and longer. *The Irishman* was amazingly long, to the point that watching it in the cinema became a badge of pride for many.

So have his films actually been getting any longer as his career develops? And does additional length bring any kind of bonuses? Let's try and find out.

I'm going to combine data from [TMDb](https://www.themoviedb.org/), [IMDb](http://www.imdb.com/) and [OMDb](http://www.omdbapi.com/) to explore how Martin Scorsese's filmography has evolved.

Let's start with a high-level take on Scorsese's films: how long each one was and how its budget compared. (Budget, adjusted for inflation, will be encoded by the area of the circles.)

{% include scorsese/runtime-v-year.html %}  
<p></p>

So, Scorsese's films have tended to get longer and cost more to make over time. We can look at those aspects separately. First, how has budget changed in time:

{% include scorsese/budget-v-year.html %}  
<p></p>

And does the budget have any dependence on the run time?

{% include scorsese/budget-v-runtime.html %}
<p></p>

OK, so the films are getting longer and costing more. Do people appreciate that more? We can look at how critical reception is potentially influenced by these two factors. We'll use Rotten Tomatoes for that, because not all the films have Metacritic scores.

{% include scorsese/rt_score-v-budget.html %}
<p></p>

Generally speaking, it seems that critical reception isn't that effected by how much is invested in making the picture.

{% include scorsese/rt_score-v-runtime.html %}
<p></p>

Similarly, people don't have much of a higher opinion just because of the length. And when you're pretty consistently batting above 70 on Rotten Tomatoes, you're doing fine.

Scorsese is putting out high-quality product, but are people turning up to see it? Let's look at how revenues are changing.

{% include scorsese/revenue-v-year.html %}
<p></p>

His revenues are clearly going up. He's become more of a household name over time, producing one of the highest grossing comedies of all time in *The Wolf of Wall Street*. *The Irishman* is any outlier here: as a *Netflix* production, it only had a limited theatrical release.

{% include scorsese/revenue-v-runtime.html %}
<p></p>

Looking at the impact of run time now, it's clear that people aren't put off by the blossoming length of Scorsese's films. But what about the critical reception?

{% include scorsese/revenue-v-rt_score.html %}
<p></p>

The highest-grossing pictures aren't the best received. Show's what the critics know.

Given how expensive some of these pictures are, it's important to know who likely Scorsese is to turn a profit, if we are looking for a monetary return on our investment in him. Let's compare budgets with revenues.

{% include scorsese/revenue-v-budget-deniro-or-leo.html %}
<p></p>

Scorsese doesn't always turn a profit but more often than not you'll make your money back. And if you throw Leo in, you're even more likely to do so.
