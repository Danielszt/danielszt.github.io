---
layout: page
title: Restaurant booking process
---


*Project carried out in [Hanzo](https://hanzo.es/) for [Meliá](https://www.melia.com/)*<br>

<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb1.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb1.png" alt="Melia-restaurant-booking" class="inline"/></a>

<br>

## Context
---
### About Meliá

Meliá is the third largest hotel chain in Europe, with 350+ hotels in 35 countries. I worked with them on several projects over the course of about a year. 
<br>
<br>

### The problem

Meliá restaurants managed table reservations through a variety of methods, mostly phone calls and third parties. The **lack of an unified reservation system** caused inconsistent customer experience and operational inefficiencies.

<br>

### Role and team

The team consisted of:

- UX designer (me)
- Visual designer
- Front-end developer
- Project manager

<br>

### Design process

1. **Discovery**: understand the problem, user needs and business goals
2. **Definition**: agree on what criteria the solution should meet
3. **Prototype**: explore and communicate design ideas
4. **Test**: identify gaps in the solution and reduce risk
5. **Final design**: develop a polished design ready for implementation



## Discovery
---
### Stakeholder interviews

I outlined our learning objectives and prepared the interview script.

Next, I met with the Product Manager and Channel Manager responsible for restaurant booking.

This helped me to gather initial requirements and understand **business goals**:
- **Increase efficiency**: Streamline the reservation process to reduce staff worload and improve inventary management.
- **Reduce dependency on third parties**: Minimise reliance on third-party reservation systems and reduce associated costs.
- **Improve brand experience**: Ensure consistent quality and brand experience across all touchpoints, reinforcing brand reliability.

<br>

### Backoffice analysis
<br>
<a href="{{ https://danielszt.github.io/ }}/assets/mb2.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb2.png" alt="Melia-restaurant-booking" class="inline"/></a>
<br>

I explored the backoffice and discussed my questions with the Meliá team. This helped me to ensure data consistency and identify **technical constraints**:  

- **Can’t modify reservations**: the system couldn't handle reservation changes, just delete them and create new ones.
- **Can’t show availability at calendar level**: the booking engine couldn’t show availability at calendar level due to performance reasons.
- **Time slots must be service-based**: time slots had to be split by service (breakfast, lunch...) and be presented at 15 minute intervals.
-  **Not all reservations are auto-confirmed**: restaurants could disable automatic confirmation for large groups or people.

<br>

## Definition
---
### Requirements document
<br>
With all the info I had, I wroted a PRD stating:

- Problem to solve
- Goals
- KPIs
- Limit and constrains
- Requirements

I reviewed it with Melia’s team to make sure we were on the same page.

<a href="{{ https://danielszt.github.io/ }}/assets/mb3.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb3.png" alt="Melia-restaurant-booking" class="inline"/></a>

<br>

### User flow
<br>

Using the PRD as a foundation, I created a user flow and reviewed it with stakeholders.

This allowed us to:

- Map all use cases
- Connect user flow with backend system
- Account for user communications

<br>

<a href="{{ https://danielszt.github.io/ }}/assets/mb4.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb4.png" alt="Melia-restaurant-booking" class="inline"/></a>

<br>

## Prototype
---
### Low-fi exploration

I started exploring with very low fidelity.

This helps me visualise many ideas quickly and weigh the pros and cons.

<br>

<a href="{{ https://danielszt.github.io/ }}/assets/mb5.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb5.png" alt="Melia-restaurant-booking" class="inline"/></a>

<br>

### Wireframe prototype

<br>

After some iterations and good feedback, I ended up with a solid proposal.

I prototyped each use case so everyone could “feel” and test the experience.

<br>

<a href="{{ https://danielszt.github.io/ }}/assets/mb6.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb6.png" alt="Melia-restaurant-booking" class="inline"/></a>

<br>

## Test
---
### Guerrilla testing

User testing wasn't in the budget or project plan, so instead I did some guerrilla testing.

No problems were reported, which gave me mixed feelings.

<br>

## Final design
---
### Normal booking

<a href="{{ https://danielszt.github.io/ }}/assets/mb8.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb8.png" alt="Melia-restaurant-booking" class="inline"/></a>

<br>

### Edit booking

<a href="{{ https://danielszt.github.io/ }}/assets/mb9.png" target="_blank"><img src="{{ https://danielszt.github.io/ }}/assets/mb9.png" alt="Melia-restaurant-booking" class="inline"/></a>

