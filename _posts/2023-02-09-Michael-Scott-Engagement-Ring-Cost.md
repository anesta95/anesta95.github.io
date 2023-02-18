---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: 
title: "So How Much Did Michael Scott's Engagement Ring Really Cost?"

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
#author: ""
# multiple category is not supported
category: economics
# multiple tag entries are possible
tags: [wages]
# thumbnail image for post
img: ":michael-scott-three-years-salary.jpg"
# disable comments on this page
comments_disable: true

# publish date
date: 2023-02-18 17:22:00 -0500

# seo
# if not specified, date will be used.
#meta_modify_date: 2021-08-10 11:32:53 +0900
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false
---

Last week, as I trudged back to my work desk from the bathroom, my eyes caught my co-worker's computer screen as I passed from behind his seat. He was online shopping for what looked like some fairly expensive engagement ring. Oddly enough my first thought after seeing the glittering assortment of diamond-laden bands — aside from how much privacy is lost in this post-pandemic push back into the office, especially ones with open-air plans — is one of my [favorite scenes](https://www.nbc.com/the-office/video/a-decent-proposal/3847248) from the US version of The Office. In the 19th episode of season 7, office manager Michael Scott is planning to propose to his then-girlfriend Holly Flax and his employees Jim, Ryan, Oscar, and Pam — who stops Michael's first fiery proposal attempt — are giving him some advice about how to make the ordeal as elaborate as possible. 

In the proposal brainstroming session Michael exhibits the engagement ring he's purchased for Holly. The rock is so massive it prompts Pam incredulously question the authenticity of the ring. Micheal responds with a non-shalant "Yeah. They say three year's salary." Of course only Michael could inadvertantly inflate the actual conventional wisdom of spending three **month's** salary on an engagement ring by 36 times.

![Pam Beesly reaction to Michael Scott Engagement Ring](/assets/img/posts/pam_beesly_reaction.png){:data-align="center"}

Aside from the comedy of the situation, the scene really activates the side of my brain that's frequently curious about the actual economics of situations. How much, canonically, _did_ Michael spend on Holly's engagement ring? Luckily, the US Bureau of Labor Statistics actually publishes some extremely specific data that can give us the closest answer to this question. 

The BLS has a program called the [Occupational Employment and Wage Statistics](https://www.bls.gov/oes/) that produces extremely detailed estimates of US workers wages across a variety of [NAICS](https://www.census.gov/naics/) industries and [SOC](https://www.bls.gov/soc/) occupations for the nation as a whole, for individual states, and for metropolitan and nonmetropolitan areas. This data, which is released annually in May, provides one of the most in depth look at both employment levels and wages for workers across the US economy and is employed by economists and policy makers for assistance in [administering the H1-B visa program and improving the calculation of Medicare reimbursement rates](https://www.bls.gov/oes/oes_ques.htm), among other uses. However for my equally-as-important needs OEWS data can also give me the best estimate of an answer to the question: "How much money did the average paper company sales manager in Scranton, Pennslyvania make in [2011](https://en.wikipedia.org/wiki/Garage_Sale_(The_Office))?"

After looking in the BLS [OWES database](https://download.bls.gov/pub/time.series/oe/) I found that any data for metropolitan areas — including the Scranton—Wilkes-Barre—Hazleton metropolitan statistical area I'm interested in — will have median wages for different occupations but not across different industries for each occupation. As such, the closest figure I could find in the regular program OWES data was an annual median wage of [$105,820](https://www.bls.gov/oes/special-requests/oesm11ma.zip) for all sales managers in the Scranton MSA in 2011. Notably, as of 2021 annual median wages for these works have actually _declined_ to an estimated [$99,510](https://beta.bls.gov/dataViewer/view/timeseries/OEUM004254000000011202213). Here's hoping Michael Scott had a better retirement plan than he did for these [children's college educations](https://www.youtube.com/watch?v=x0N2ZxQJYTw).

However, aside from their main database the OEWS also publishes annual [research estimates](https://www.bls.gov/oes/current/oes_research_estimates.htm) of employment and wage data that does have figures for median earnings for workers across major occupations _and_ industries. Unfortunately, the data is only available statewide level and were first produced in _2012_ so it's again not precisely what is needed. That said, if you inflation-adjust the estimate from May 2012 to March 2011 sales managers in the [paper and paper product merchant wholesalers industry](https://www.naics.com/naics-code-description/?code=4241) in Pennsylvania made around [$105,548](https://www.bls.gov/oes/special.requests/oes_research_2012_sec_42-44-45.xlsx) a year.    

The fact that these two estimates are so close gives me a reasonable amount of confidence that Michael Scott was probably pulling in around $105,000 annually in 2011. Which means if his statement that he paid three years of his salary on Holly's engagement ring is true it would have cost a whopping $315,000. But if that wasn't an eye-popping enough sum, that figure is in 2011 dollars as I confirmed with the BLS that all of the OEWS wage estimates are in [nominal](https://www.investopedia.com/terms/n/nominalvalue.asp) and not real values. Using the [Consumer Price Index](https://www.bls.gov/data/inflation_calculator.htm) to adjust $315,000 in March 2011 dollars to current dollars you would have an engagment ring that cost about **$421,711**! A ring that expensive would put the cost of Holly's ring somewhere between the ones that Kate Middleton and Meghan Markle [reportedly recieved](https://www.whowhatwear.com/celebrity-engagement-rings-expensive) from their respective princes. I guess if you want to feel like royalty find someone whose memory of engagement shopping adages are as hazy as Michael Scott's. Knowing him, he probably picked out one like this at [Costco](https://www.delish.com/just-for-fun/a27684180/costco-engagement-ring/):


![Costco $400,000 engagement ring](/assets/img/posts/costco_diamond_ring.jpg){:data-align="center"}




