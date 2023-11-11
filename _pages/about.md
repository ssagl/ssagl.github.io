---
layout: about
title: about
permalink: /
subtitle: Ph.D. Candidate, Department of Economics, The Pennsylvania State University

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  address: >
    <p>420 Kern Graduate Bldg</p>
    <p>University Park, PA 16802</p>
    <p>United States</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---
<br />
I am a Ph.D. candidate in economics at [Penn State](https://econ.la.psu.edu). My research interests are in industrial organization and applied microeconomics. Recently, I have worked on research on the estimation of discrete choice demand models and applications relating to the US automobile market. If you want to, you can view my CV here [<i class="fa-regular fa-file-pdf fa-lg" style="color: #b509ac;"></i>](files/cv.pdf).

<br />
I am on the job market for the 2023--24 academic year. Check out the latest version of my job market paper below!
<br />
<br />
  
#### Current Research
<br />
[<b>Dispersion, Discrimination, and the Price of Your Pickup</b>](https://ssagl.github.io/papers/jmp_sagl.pdf), November 2023. (<b>Job Market Paper</b> [<i class="fa-solid fa-truck-pickup" style="color: #b509ac;"></i>](https://ssagl.github.io/papers/jmp_sagl.pdf))
* Price discrimination is a pervasive, yet controversial feature of the automobile market. Using repeat purchase data on pickup trucks, fully controlling for product heterogeneity, I establish that the same consumers pay persistently high or persistently low prices across vehicle purchases. This result suggests that dealers can learn persistent consumer preferences beyond coarse demographics through direct interactions with consumers and use them for pricing. Using a novel discrete choice model of supply and demand, I study the role of consumer information available to firms in the welfare effects of price discrimination. To do so, I overcome a common problem in settings with transaction data: consumer-specific prices of non-chosen alternatives are unobservable. I solve this problem by recovering unobserved consumer-specific prices and consumer-specific price sensitivity from the observed transaction price via firms' first-order conditions. I simulate two counterfactuals: uniform pricing and price discrimination based on coarse demographic groups -- gender, race, and income. Compared to uniform pricing, price discrimination with consumer-specific prices increases profits and total welfare but, on average, harms consumers. On the other hand, compared to uniform pricing, price discrimination based only on demographics is not profitable. This suggests that information beyond demographic groups drives the profitability of price discrimination.

<br />
[<b>Conformant and Efficient Estimation of Discrete Choice Demand Models</b>](https://ssagl.github.io/papers/like-blp.pdf), May 2023.  
with Paul Grieco, Charles Murry, and Joris Pinkse  
<b>Revisions requested at _Econometrica_</b> 
* We propose a likelihood-based estimator with exogeneity restrictions
for BLP-type demand models combining microdata, product shares, and prices.  
* Our estimator is implemented in the easy-to-use companion Julia package [Grumps.jl](https://nittanylion.github.io/Grumps.jl/dev/). Install it by typing `using Pkg; Pkg.add("Grumps")` in the Julia REPL.