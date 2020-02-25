---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

## Data Analytics Project
---

[Humana-Mays Health Analytics Case 2019 Competition - A Predictive Analysis Using Python](/Humana_May_Case_Competition.html)
<img src="images/humana-mays.png"/>
We predicted probability of long-term opioid use for 13,997 patients based on four-year medical records utilizing Python by conducting exploratory data analysis, data cleaning, feature engineering, and predictive modelling to enable Humana identify patients at risk for opioid overdoses and initiate intervention procedures, reaching prediction accuracy 87% and ranking in the 90th percentile of participants.

---
[Kiwi Bubble VS Mango - Casual Analysis on Consumer Choice Data using Multilogit Choice Model](/pdf/PricingAnalyticsPJ2.pdf)
<img src="images/PricingAnalyticsPJ2.png?raw=true"/>
My team conducted casual analysis on customer choice data by using multilogit choice model, and then we use k-mean clustering to segment customers and detect the nash equilibrium of Kiwi company and Mango company. Check our analytics process using R.

---
[Estimating Car Demand - Casual Analysis on Sales Data](/pdf/PricingAnalyticsPJ1.pdf)
<img src="images/PriceAnalyticsPJ1.jpeg?raw=true"/>
My team conducted casual analysis, including linear regression with fixed effect, linear regression with instrumental variable, to exploit the demand of car models. Check our analytics process using R.

---
[Twitter Airline Customer Sentiment Analysis - Natural Language Processing Using Python NLTK Package](/pdf/Twitter%20-%20Natural%20Language%20Processing.pdf)
<img src="images/twitter.png?raw=true"/>
I predicted customer sentiment from Tweets by conducting natural language processing, including word-tokenization and TFIDF modelling, and leveraging machine learning algorithm, such as Naïve Bayes Classifier and Support Vector Machine, reaching 80% prediction precision. Check my python notebook.

---

[911 Emergency Call - A Data Visualization Project Using Python](/911_descrptive_analysis.html)
<img src="images/911 Projct.png?raw=true"/>

---

## Data-driven Business Case Study
[Toy Horse Conjoint Experiment - Conjoint Analysis using R & Tableau](/pdf/ToyHorseCase.pdf)
<img src="images/Toy Horse Case.png?raw=true"/>
In this case study, my team serves as analysts/modelers in a consulting company. We are in charge of analyzing a conjoint analysis conducted for a relatively small toy company to help them determine which new features should they launch.

---

[Yogurt Flavor - TURF Analysis using R & Tableau](/pdf/YogurtCase.pdf)
<img src="images/Yogurt Case.png?raw=true"/>
In this case study, my team utilize R to conduct TURF analysis for a particular greek yogurt brand to determine which flavor should they launch next and then we use tableau to visualize our data.

---

[Wine Retailer Case - Casual Effect Analysis using R & Tableau](/pdf/WineRetailerCase.pdf)
<img src="images/Wine Case.png?raw=true"/>
In this case study, my team utilize R to conduct linear regression, casual forest to determine which customer should we target for a email promotion campaign.

---

[Beer Case - NPV & Demand Analysis](/pdf/BeerCase.pdf)
<img src="images/Beer Case.png?raw=true"/>
In this case study, my team analyze a certain brand of beer's potential of opening new market by utilizing NPV and demand analysis.


{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
