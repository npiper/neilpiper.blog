---
layout: post
title:  "Continuous Delivery - What I've learned"
date:   2016-06-29 22:36:09 +1000
categories: continuous delivery innovation
---

# What is Continuous Delivery?

>The ability to get changes, whether they be features, configuration, bug fixes or experiments into the hands of your users & customers in a fast, safe & sustainable way.

## Am I doing it?
> Software is always deployable

# Why??

The history of Death march projects and planning for releases, late evenings with multiple people & teams, massive run sheets... is there a better way?

To a 'boring low risk event' - midday.

>Changes to market faster with less cost, effort & to get faster feedback.

Also, increase software quality and stability.

Increases customer & employee satisfaction. 

Rapid smaller changes. (Amazon a change/release - every 11.6 seconds - 50M deploys annually)


# Agile Adoption

'WaterScrumfall..' Agile embedded in a Project management, Portfolio framework. The 'fuzzy front end'.

Weeks, Months..?

Are those iterations going to production...?

Goal: Make the 'last mile' go away.. can we ship to users at end of iteration or faster. 'Shifting left'

# What changes at development time?
 
* Build quality in
* Releaseable to production increments

## A key emphasis

Computers do repetitive tasks, people solve problems & higher value add. (Manual regression tests, Manual steps, .. division of labor)

> Build an engine to build features, always getting better..

## Responsiblity

All of us are responsible for it.. the stability of the system and business level customer outcomes.

## High performing IT Teams - the evidence

> 2x as likely to exceed profitability, market share & productivity goals.

-- 2014 State of Devops Report

![2014 State of Devops](https://img.yumpu.com/39495017/1/358x462/2014-state-of-devops-report.jpg)

## 3 Key metrics (Web services, systems)
* Lead time for changes (commit to deploy)
* Release frequency
* time to restore service

## Lead time for changes

> How long would it take you to deploy a single line of code change?
> Do you do this on a repeatable, reliable basis?

-- Mary & Tom Poppendieck (Lean)

![Mary, Tom Poppiendick](http://booking.agilefaqs.com/images/speakers/MaryPoppendieck.png)

## Time to restore service

> How quickly can I restore systems?
> How quickly can I get a critical fix to users?
> How quickly can I validate whether a features is valuable?

[Heartbleed - SSL bug 2014](https://en.wikipedia.org/wiki/Heartbleed)



## Do we have Requirements?

* NO
* What we have are 'guesses' or 'hypothesis'

* Validate them as quickly as possible 
* An experimental approach to product development
* 2/3 of features we build deliver zero or negative value.. hurts.

## Hypothesis Driven Delivery

> We believe that [Building this feature]
[For these people]
will achieve [this outcome]
We will know we are succesful when we see
[this signal from the market]

-- Jeff Gothelf

## Goals

* Change the economics of software delivery
* Increases both throughput & stability
* Reduce risk & ongoing cost of delivery
** Feedback loops - so we can build quality in
** Create organistaions that adapt to changes, resilience


## References

[Continuous Delivery - Jez Humble](https://www.safaribooksonline.com/library/view/continuous-delivery/9780134389363)

[Ops Metametrics - The currency you use to pay for change](http://www.slideshare.net/jallspaw/ops-metametrics-the-currency-you-pay-for-change-4608108)

[Better product definition with Lean UX and Design - Jeff Gothelf](https://www.infoq.com/presentations/Lean-UX-Design-Thinking)

[Etsy's product development with continuous experimentation](https://www.infoq.com/presentations/Etsy-Deployment)

[State of DevOps report](https://puppet.com/resources/white-paper/2016-state-of-devops-report)