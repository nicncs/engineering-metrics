# Engineering Metrics
Monorepo of utilities to gather and measure metrics that matter for building high performing teams

## Background

I've always been interested and fascinated by feedback loop. Earlier on in career, I worked on control systems and understood more than anyone that having a closed-loop system is critical to ensuring learning and improvement to achieve a stable and performant system. 

As I move into engineering management, it became more of an art, as much as we as engineers have tendencies to want order and look at data. Thus over the years I have researched, experimented and accumulated different metrics that could help managers and their software teams achieve continuous improvement.

This method and these metrics are applied at a typical modern product development company, whether startup or scale-up. The teams are structured into 2-pizza scrum teams or feature teams, consisting of cross-functional and specialized roles. Typically there will be combination of mobile devs, frontend devs, backend devs, SRE, and may or may not have QA, Data Engineer etc.

The key is to not overly measure everything and focus more towards leading, as compared to lagging indicators to ensure we are proactive. Focus on the few Tier-1 metrics that really matter and can move the needle. 

## The Metrics

### Tier-1 Metrics 
These are what I call must have and prioritize the visibility into these

#### System Level Objectives (SLO) - The non-negotiables

* API Availability/Uptime 
* API Error Rate
* API Response Time
* App start time (for mobile)
* Crash-free rate (for mobile)
* Page Load Time (for web)
* JS Errors (for web)

#### Software Delivery Performance - The DORA metrics

* Deployment Frequency
* Lead Time for Changes
* Time to Restore Services
* Change Failure Rate

#### People and Culture 

* eNPS
* Westrum Culture Score

#### Information Security - Zero-day prevention

* SAST failure rate
* DAST/Pen Testing failure rate


### Tier-2 Metrics 
Tier-2 metrics are what I will prioritize after we have all the Tier-1 metrics, and are somewhat tied to Tier-1 metrics. These are mainly lagging indicators, to provide additional insights and context to help the teams improve on. And they may/may not be the most important to your organisation.

#### FinOps

* Infrastructure Cost per user

#### Quality

* % test coverage
* Time to discover critical bug
* Test execution failure not due to service defect

#### Innovation Pace

* Number of new innovation in MVP/POC
* New tech from POC into Production


#### Developer Experience

* Number of tech debt paid (each platform)
* Number of reusable assets
* Retirement of legacy service/modules/projects 


### Hiring and Retention

* Hiring vs. Plan
* Attrition rate
* Staff growth/promotion rate


## Inspiration & References
* [Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations](https://www.amazon.com/Accelerate-Software-Performing-Technology-Organizations/dp/1942788339)
* [Building Great Software Engineering Teams: Recruiting, Hiring, and Managing Your Team from Startup to Success](https://www.amazon.com/Building-Great-Software-Engineering-Teams/dp/1484211340/ref=sr_1_3?crid=87YF68MPZAD9&keywords=building+software+team&qid=1652946491&s=books&sprefix=building+software+%2Cstripbooks%2C760&sr=1-3)
* [Site Reliability Engineering: How Google Runs Production Systems](https://sre.google/sre-book/table-of-contents/)
* [Software Engineering at Google: Lessons Learned from Programming Over Time](https://www.amazon.com/Software-Engineering-Google-Lessons-Programming/dp/1492082791)
* [Thoughtworks Technology Radar Framework](https://www.thoughtworks.com/radar)
* [Better Testing - Worse Quality?](https://testobsessed.com/wp-content/uploads/2011/04/btwq.pdf)
* [Chrome User Experience Report (CrUX)](https://developers.google.com/web/tools/chrome-user-experience-report)

