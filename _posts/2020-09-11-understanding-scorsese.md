---
layout: post
title: Understanding Scorsese
---

Martin Scorsese is a great director. Yet in recent years his films seem to be getting longer and longer. His most recent release, *The Irishman*, was his longest by far, to the point that watching it in the cinema became a badge of pride for many. Perhaps somewhat surprisingly, despite his fame and critical plaudits, Scorsese claimed he couldn't get the money to make *The Irishman* with a traditional study and hence turned to Netflix.

Studios might have been turned off by the ever-expanding runtime of Scorsese's films. They might have worried that people would be put off heading out to see a three and half hour one - a worry that could have been exacerbated by the costs (and risk) of the de-ageing makeup.

These concerns could have been misplaced, though. The critical response to *The Irishman* was overwhelmingly positive and its limited theatrical run brought people out to cinemas.

Let's look at Scorsese's filmography and see whether the data support the studios' fears and anxieties.

I'm going to combine data from [TMDb](https://www.themoviedb.org/), [IMDb](http://www.imdb.com/) and [OMDb](http://www.omdbapi.com/) to explore how Martin Scorsese's output has evolved and how audiences have responded to it.

Let's start with a high-level take on Scorsese's films: how long each one was and what its budget was. (Budget, adjusted for inflation, will be encoded by the area of the circles.)

Note: figures below are interactive. Hover over data points for more details.

{% include scorsese/runtime-v-year.html %}  
<p></p>

Scorsese's films have tended to get longer and cost more to make over time. Some of that cost will certainly be associated with duration, but his reputation also attracts (and makes) bigger stars who demand bigger salaries.

We can look at those aspects separately. First, how budget has changed in time:

{% include scorsese/budget-v-year.html %}  
<p></p>

Second, how budget might depend on runtime:

{% include scorsese/budget-v-runtime.html %}
<p></p>

OK, so the films are getting longer and costing more. Without more data on the breakdown of budgets, we can't really understand with any more depth what the key drivers are here.

Still, if you're going to invest all that money in making a really long Scorsese film, you want to know if audiences are going to appreciate it. We can look at the relationship between both budget and runtime and critical reception. We'll use Rotten Tomatoes for that, because not all the films have Metacritic scores.

{% include scorsese/rt_score-v-budget.html %}
<p></p>

Generally speaking, it seems that critical reception isn't that affected by how much is invested in making the picture. At least, when you're pretty consistently batting above 70 on Rotten Tomatoes, you're doing fine.

Let's look at length:

{% include scorsese/rt_score-v-runtime.html %}
<p></p>

Similarly, people don't have much of a higher opinion just because of the length.

Critically, then, Scorsese is putting out high-quality product regardless of budget or duration. What matters for most studios, though, is that people are turning up to see them. Let's look at how revenues are changing.

{% include scorsese/revenue-v-year.html %}
<p></p>

His revenues are pretty healthy. He even produced one of the highest grossing (and possibly longest) comedies of all time in *The Wolf of Wall Street*. *The Irishman* is any outlier here: as a *Netflix* production, it only had a limited theatrical release.

{% include scorsese/revenue-v-runtime.html %}
<p></p>

People aren't necessarily put off by the blossoming length of Scorsese's films. When above two hours, there's a lot of high-earning pictures. His films about Christianity (*The Last Temptation of Christ* and *Silence*) are the outliers among the longest runtimes.

Critical reception might tell a different story.

{% include scorsese/revenue-v-rt_score.html %}
<p></p>

The highest-grossing pictures aren't the most critically well-received. Show's what the critics know.

Given how expensive some of these pictures are, it's important to know how likely Scorsese is to turn a profit, if we are looking for a monetary return on our investment in him. Let's compare budgets with revenues.

{% include scorsese/budget-v-revenue.html %}
<p></p>

That's a pretty good success rate.

Finally, Scorsese is known for often working with the same actors. In particular, he's made a lot of films with Robert De Niro and, more recently, Leonardo DiCaprio. We can look and see whether these actors are an important factor in the success of Scorsese's films.

{% include scorsese/revenue-v-budget-deniro-or-leo.html %}
{% include scorsese/revenue-v-rt_score-deniro-or-leo.html %}
<p></p>

DiCaprio seems to bring more popular appeal but less critical acclaim.

To conclude, Scorsese more often than not makes a profit, and these days it's frequently a solid one. If you throw Leo in, it's even more likely to be so, but if it's accolades you're after then better opt for Bob.
