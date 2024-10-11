---
layout: default
title: research
permalink: /research/
nav: true
nav_order: 2


#profile:
#  align: right
#  image: prof_pic.jpg
#  image_circular: true # crops the image to make it circular
#  address: >
#    <p>1309 E Tenth Street</p>
#    <p>Hodge Hall 3080</p>
#    <p>Bloomington, IN 47405</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---
  
### Working Papers
<br />
[<b>Dispersion, Discrimination, and the Price of Your Pickup</b>](../papers/jmp_sagl.pdf), 2024.
* <b>Abstract:</b> Using repeat purchase data on pickup trucks, I establish that the same consumers pay persistently high or persistently low prices across vehicle purchases. Less than 1% of this persistence can be explained by demographics. This result suggests that dealers use consumer information beyond coarse demographics to personalize prices. Using a novel discrete choice model with personalized pricing, I study the role of consumer information firms use for pricing in the welfare effects of price discrimination. To do so, I overcome a common problem in settings with transaction data: personalized prices of non-chosen alternatives are unobservable. I solve this problem by recovering unobserved personalized prices and consumer-specific price sensitivity from the observed transaction price via firms’ first-order conditions. I simulate two counterfactuals: uniform pricing and price discrimination based on coarse demographic groups. Compared to uniform pricing, personalized pricing increases profits and total welfare but, on average, harms consumers. On the other hand, compared to uniform pricing, price discrimination based only on demographics is not profitable. This highlights the importance of the amount of consumer information firms can use for pricing in the welfare effects of price discrimination.

<br />
[<b>Conformant and Efficient Estimation of Discrete Choice Demand Models</b>](../papers/like-blp.pdf), 2023.  
with Paul Grieco, Charles Murry, and Joris Pinkse  
<b>Revisions requested at _Econometrica_</b> 
* We propose a likelihood-based estimator with exogeneity restrictions
for BLP-type demand models combining microdata, product shares, and prices.  
* Our estimator is implemented in the easy-to-use companion Julia package [Grumps.jl](https://nittanylion.github.io/Grumps.jl/dev/). Install it by typing `using Pkg; Pkg.add("Grumps")` in the Julia REPL.