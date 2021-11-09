---
layout: post
title: Week7 Presentation
---

This is an example blogpost of our exploration and result as of week 7. 


## Introduction

Last time we conducted data exploration. We run several regressions and found that **there are no relationships between average tax rate and unemployment rates**. But after drawing some graphs, we noticed that they become negative related since 1990s. Hence, we paid attentions to **the welfare reform in 1990s** and focus on **earned income tax credit (EITC)**. You can find more background information here [Welfare Reform and the Work Support System](https://www.brookings.edu/research/welfare-reform-and-the-work-support-system/).



![png](/images/pre-1.png)




# EITC

There are many studies on the influence of federeal EITC but less studies on in-state EITC. With the data in hands, we will inspect on both **federal EITC** and **in-state EITC**. Our research will be on both nation and state levels. Below is a graph showing the present state EITC policies. We've noticed that California and South Carolina have a particularlly high EITC percentage and states in the northeast tend to have in-state EITC.


{% include 2.html %}



# EITC and Unemployment


{% include 3.html %}

It seems that tax and uemployment rates become negative related since 1990s. We draw some graphs on several states to see whether in-state EITC has the same effect on unemployment.


{% include 4.html %}



{% include 5.html %}


We chose two states that gradually increased their EITC and observe **a drop in unemployment rate after EITC rate is raised**. We may do this kind of analysis to more states in the future. We refer to [TAXISM](http://users.nber.org/~taxsim/state-eitc.html) for state EITC rules.

# EITC and Poverty

Running a simple linear regression, we find that there are no storng relationship between U.S. family poverty rate and tax rate, as shown in the graph below.


![png](/images/pre-2.png)


From the graph below we can see that the welfare reform did potentially decrease the family poverty rate.


{% include 7.html %}


A study by CBPP collect data on the number of working families benifited from EITC in each state. We notice that California, Texas, Florida, and New York have the most many families receiving federal ETIC. States in the east tend to have more families receiving EITC.



{% include 8.html %}



From the graph of poverty rate by states, we notice that states in the south tend to have a high proverty level. Looking at the poverty change graph, we notice that the changes are unevenly nationwide and seem to have no relationship with the in-state EITC percentage. If we compare the poverty change to the state EITC rules and the number of families benefited from federal EITC, we cannot see any pattern. It may prove that EITC does not help with decreasing poverty level.

{% include 9.html %}


{% include 10.html %}

# Conclusion and Further Study

In sum, our conclusions are:
- To solve unemployment and poverty, we should focus more on transfer than taxation.
- EITC on both federal and state levels help to the decline in unemployment rate.
- The poverty level in each state does not decrease with more EITC.

Our further study may be focus on how EITC influences children poverty and women participation in workforce.