---
layout: page
title: Restaurant reservation flow
---


*Project carried out in [Hanzo](https://hanzo.es/) for [Meliá](https://www.melia.com/)*<br>

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb1.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb1.png" alt="Melia-restaurant-booking" class="inline"/></a>

<br>

# TL;DR
---
- Meliá needed a unified restaurant reservation system to improve operational efficiency and customer experience.
- I identified goals and technical constraints through stakeholder interviews and back-office analysis.
- I created a PRD, user flow, and prototypes to define and align on the solution.
- Guerrilla testing revealed one minor issue and I corrected it using UI copy.
- The solution meets the initial objectives and accounts for multiple use cases. 
<br>

<br>

# Context
---
## About Meliá

Meliá is the third largest hotel chain in Europe, with 350+ hotels in 35 countries. I worked with them on several projects over the course of about a year. 

<br>

## The problem

Meliá restaurants managed table reservations through a variety of methods, mostly phone calls and third parties. The lack of an unified reservation system caused inconsistent customer experience and operational inefficiencies, so they created a in-house reservation management system and asked us to design the user experience.
<br>

<br>

# Discovery
---
## Stakeholder interviews

I created a research project in our research database, wrote down our learning objectives and prepared the interview script. Then I met with Melia's product manager and  engineers.

This helped me to gather initial requirements and understand the business goals:

- Reduce staff manual workload and streamline inventory management.
- Reduce dependency on third parties and associated costs.
- Ensure brand consistency and quality of experience across all touchpoints.

<br>

## Backoffice analysis

Whatever I designed, it had to be consistent with the reservation management system (backoffice), so I explored it and discussed my questions with the Meliá team. 

This helped me to ensure data consistency and identify technical constraints, like:

- Time slots had to be split by service (breakfast, lunch...) and presented at 15 minute intervals. 
- Restaurants could disable automatic confirmation for large groups or people.

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb2.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb2.png" alt="Melia-restaurant-booking" class="inline"/></a>
<br>

<br>

# Definition
---
## Requirements document

With all the info I had from the discovery, I wroted a productd requirements document (PRD) stating problem to solve, goals, KPIs, limits and constrains and initial requirements

I reviewed it with Melia’s team to make sure we were on the same page.

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb3.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb3.png" alt="Melia-restaurant-booking" class="inline"/></a>
<br>
<br>

## User flow

Using the PRD as a foundation, I created a user flow and reviewed it with the team and stakeholders.

This allowed us to map all use cases, connect the user flow with the backend and account for users emails and communications.

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb4.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb4.png" alt="Melia-restaurant-booking" class="inline"/></a>
<br>

<br>

# Prototype
---
## Low-fi exploration

I started exploring with very low fidelity. This helps me visualize many ideas quickly without getting caught up in the details.

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb5.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb5.png" alt="Melia-restaurant-booking" class="inline"/></a>
<br>
<br>

## Wireframe prototype

After some iterations and good feedback, I ended up with a solid proposal. I prototyped each use case so everyone could “feel” and test the experience.

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb6.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb6.png" alt="Melia-restaurant-booking" class="inline"/></a>
<br>

<br>

# Test
---
## Guerrilla testing

User testing wasn’t included in the budget or project plan, so I conducted guerrilla testing instead (I have experience with formal testing, it just wasn't possible this time). 

We discovered that the current day wasn’t obvious to some users, so I added “Today” next to the current date. This served as a reference point, helping users consider upcoming dates with more confidence.

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb7.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb7.png" alt="test" class="inline"/></a>
<br>

<br>

# Final design
---

Below you can see the design for the main use cases. 

<br>
## Normal booking

Key decisions:
- Split the process in logical steps, one per screen. 
- Use smart default values.
- Fix buttons only when enabled.
- Avoid unnecessary placeholders to reduce clutter.

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb8.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb8.png" alt="Melia-restaurant-booking" class="inline"/></a>
<br>
<br>

## Edit booking

Key decisions:
- Allow comparison between the old and new reservation.
- Provide real-time feedback of changes.
- Preserving user data from the first booking.

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb9.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb9.png" alt="Melia-restaurant-booking" class="inline"/></a>
<br>
<br>

## Request table (for reservations with 8+ people)

Some restaurants wanted to manually review reservations for +8 people, so for this case we deactivated the atomatic confirmation and adapted the flow.

Key decisions:
- Place the explanatory message next to the control that triggers it (nº of people).
- Use UI copy to make clear that this is a table request, not a reservation.

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb10.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb10.png" alt="Melia-restaurant-booking" class="inline"/></a>
<br>
<br>

## Cancel reservation 

Key decision:
- Make the feedback about the cancelation reason optional
  
<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb11.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb11.png" alt="Melia-restaurant-booking" class="inline"/></a>
<br>
<br>
<br>
Thanks for reading!

