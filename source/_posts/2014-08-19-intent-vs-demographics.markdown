---
layout: post
title: "Intent Targeting vs Demographic Targeting"
date: 2014-08-19 16:51:55 -0400
comments: true
categories: 
---
Intent Targeting at Local Response.
===================================

Originally I was introduced to the following company idea behind the product: target people that have an intent to purchase something or perform another action of interest ╨ install an app, check-in to the place, etc. Then I was introduced to a bunch of ideas and thought of how Niels sees it on a higher level, in theory. I started working on implementing those ideas in practice and creating a product of intent. Some of the original ideas need to be reconsidered and reformulated along the way, and I think it?s time to define them more precisely.

Here are some aspects of the product I feel I need to bring up.

a) Do we need to target an audience? If yes, we need to define what is audience and model it in terms of signals we can get.
For example, we can formulate a main goal this way: ?Reach a certain crowd that we established are good candidates for a campaign.? 
We have to break this goal apart:
(1) Define this crowd in terms of their online and mobile activity potentially accessible to us.
(2) Decide how we are going to model correspondence between (a) selected audience online activities and (b) campaign targets.
(3) Decide on a way to verify 
a. if we selected the right audience for a campaign based on our criteria of audience selection;
b. if targeting that audience had its contribution toward further action (whether that action can or cannot be measured directly).

It immediately becomes clear that absolutely not all ?potentially reachable? online and mobile activity of people has a direct relation to a product. It?s even harder to establish that relation with respect to an action other then product purchase.

Yes, there are some easy examples in a broad sense of how we understand intent that are relatively easy to model - like ?Travel? category. People look for places to visit online, they monitor vacation deals & packages, hotels and airline tickets, they are being ╥social╙ about their plans ╨ discuss travel plans, share travel pictures and thoughts, write reviews, and easily get influenced by their friends travel. Travel category is unlike any other in this respect, because it is well-defined in online activity and fairly simple.

That will be true for a category of targets that require long planning (expansive purchases) 


Wish lists are direct intent signals. However, this is only related to products and brands, which are the easiest to model, but not in all cases. Here is an example. One can target those who look online for beauty product, for car, or travel, or a certain entertainment sector. But our categories of interest are much more broader then that. Nobody will search for eye drops, or nail polish removal, or toothpaste, or chicken nuggets as well as for retail stores or holiday activities. Majority of our targeting goals lie beyond simple product pages or wish lists. Therefore, we need to build something more complex and advanced to reach our goal.

b) One huge problem is KPI. Although traditionally its all measured in clicks, we have a chance to contribute with much more insightful KPIs, whether measured directly or indirectly. Elaborating on the idea that we reach a crowd with certain interests reflected in online and mobile activities.


So, it looks like we are finding the right audience for a certain campaign. What╒s innovative about that? Many companies do it. Here is what I think is novel: we formulate it in terms of intent that has several levels from informational stage to ready-to-take-action stage and track person╒s intent path. We won╒t only target those people who are ready-to-take-action (that is what wish lists provide), but capture interest or even potential interest to a product reflected I other signals. The conceptual basis is given by an Intent Ontology that provides a unified view to different types of signals and data sources and map campaign targets to select the right audience from signals.

Advance scoring is not possible within this framework ╨ it╒s a scoring on demand. At the moment when campaign goal is formulated in terms of ontology concepts, the audience is obtained, where each user entity has a numeric equivalent of fit to a campaign goal. Currently, we call it an ╥intent score╙ and it╒s simply a score within a topic, mostly based on one signal source (AddThis). 

The industry has no metric that can be estimated directly (too many unknowns in the equation!). Even with a fact of purchase or other action we deal with attribution and incomplete view of the number of actions.

Eventually, we won╒t match signals to topics by configuring keywords but will pick up keywords set from our ontology specific for each signal and match, thus providing a component score from one signal source. 

Other companies also define their audience to target, but do it in a simpler way: by demographic features, by context of pages people visit, combination of both. The difference is they use click as a metric and optimize toward a click, the audience definition is restricted to location or demographic, or content. Our intent model has levels of intent, decay component, sources of data that compliment each other.

Intent targeting: how is it different from demographics.

What they call ?demographics? in advertising is reaching a crowd they think might have intent. So, in a way it is an inferred intent. How is it different from intent?

?Pyramid of intent? ? information is flashed against your eyes; you can ?block? and ?ignore? it immediately as annoying (if you classify this event to the category of annoying events so this event is similar to those other events you hate). Or you can actually allow your brain to remember this.

Example: TV show ad, ?Jennifer falls? in the train. The first time I saw it I thought that it kind of looks interesting. I saw it at least 5 more times until I remembered to write about it here, and the next step is to check it online.

First time I saw this ad it stack to the memory. We can infer intent from this fact alone taking to account al the unknowns! For example, knowing initial values what proportion of people mentally block this kind of info and what do not. We could estimate this from demographics! ? Traditional method of targeting, knowing how many people are in US of a certain age and gender to whom this would be interesting.

So, we won?t target directly Millennial, rather let?s think what kind of clients do we have for millennial and what kind of products do they have then let?s describe those as signals of indirect intent.

Bayes formula:
Prior probability ? what percent of a total crowd is interested in the ad? (we can estimate it in a more complex way, go find gender and age group, estimate those and guess or rely on some study that was performed by somebody, like Nielsen.)

Get posterior probability: how many times this person read about our target category.


Here is another thought: in order to make intent different from demographics, and to make it stronger we have to have direct connection between targets and labels.
