---
layout: page
title: Simplifying orders for Holcim’s customers
---


*Project carried out in [Hanzo](https://hanzo.es/) for [Holcim](https://www.holcim.com/) · 2024*<br>

<br>
<a href="/assets/hco-01.jpg" target="_blank"><img src="/assets/hco-01.jpg" alt="Redesigned Holcim customer portal on desktop and mobile" class="inline"/></a>

<br>

# TL;DR
---
- Holcim’s customers avoided the customer portal and kept ordering by phone and email, because ordering and tracking materials in it was too hard.
- Through stakeholder interviews, a current UI analysis and OOUX, I narrowed this down to **four customer problems**: ordering is too complex, it’s hard to find things, reorder goes unnoticed and returning pallets is tedious.
- Every design decision below is tied back to one of those four problems.
- While data is pending, initial feedback indicates customer satisfaction.

<br>

# Context
---
## About Holcim

Holcim is a global leader in supplying cement, aggregates and building materials. It’s present in 70 countries and employs more than 63,000 people.

<br>
<a href="/assets/hco-03.jpg" target="_blank"><img src="/assets/hco-03.jpg" alt="Holcim cement plant" class="inline" style="max-width:420px;display:block;margin:0 auto"/></a>
<br>

## The problem

Customers were struggling to order materials and track orders in Holcim’s customer portal due to unnecessary complexity and a confusing UI. This was leading to:

- Errors
- Additional manual work
- Reluctance to use the portal

## Team and role

**The team:** UX designer (me), visual designer (design system), front-end developer and a product manager from Holcim.

**My responsibilities:**

- Identify customer pain points
- Design a solution that addresses them
- Collaborate with Holcim’s team
- Present designs to stakeholders

<br>

# Discovery
---
## Stakeholder interviews

I interviewed two project managers, a business analyst, the head of engineering and the customer support lead.

I couldn’t speak with customers, so I used the customer support lead as a proxy: they deal with customers’ complaints every day. I defined learning objectives, wrote interview scripts, looked for patterns in my notes and extracted insights.

<br>
<a href="/assets/hco-07.jpg" target="_blank"><img src="/assets/hco-07.jpg" alt="Remote stakeholder interviews" class="inline" style="max-width:420px;display:block;margin:0 auto"/></a>
<br>

## Current UI analysis

I also analyzed the current UI to find what works well, what needs to be improved, and gaps where new functionality could add value.

<br>
<a href="/assets/hco-08.jpg" target="_blank"><img src="/assets/hco-08.jpg" alt="Annotated analysis of the old order status page" class="inline"/></a>
<br>

## Understanding the system

The system was very complex (orders, deliveries, invoices, job sites, contracts, pallets…), so I used [object-oriented UX](https://www.ooux.com/what-is-ooux) to break it down. This helped me map out everything in the system and raise important questions early, which I answered with Holcim’s team.

<br>
<a href="/assets/hco-09.jpg" target="_blank"><img src="/assets/hco-09.jpg" alt="OOUX object map: objects, attributes and actions" class="inline" style="max-width:480px;display:block;margin:0 auto"/></a>
<br>

<br>

# Definition
---
## Business goal

**Increase portal adoption by customers who refuse to use it and place orders by phone or email instead.**

To get there, the portal had to fix the four customer problems below. Each one is shown in the old portal.

<br>

## Problem 1 · Ordering is too complex

The ordering process was complex, time-consuming and prone to errors. Everything happened on one dense form, and customers had to keep jumping between pages and modals.

<br>
<a href="/assets/hco-12.jpg" target="_blank"><img src="/assets/hco-12.jpg" alt="Old order form" class="inline"/></a>
<p><em><center>Old portal: one dense form that starts by asking for a contract number</center></em></p>

<a href="/assets/hco-13.jpg" target="_blank"><img src="/assets/hco-13.jpg" alt="Old job site selection modal" class="inline"/></a>
<p><em><center>Old portal: picking a job site meant filtering a modal by technical fields like Incoterm</center></em></p>

<a href="/assets/hco-14.jpg" target="_blank"><img src="/assets/hco-14.jpg" alt="Old delivery date modal" class="inline"/></a>
<p><em><center>Old portal: delivery dates were entered one row at a time, in yet another modal</center></em></p>

<br>

## Problem 2 · It’s hard to find things

Customers struggled to find things because orders, deliveries and invoices weren’t linked, filters demanded too much precision, and the visual hierarchy was poor.

<br>
<a href="/assets/hco-16.jpg" target="_blank"><img src="/assets/hco-16.jpg" alt="Old invoice detail" class="inline"/></a>
<p><em><center>Old portal: an invoice with no link back to its order or delivery</center></em></p>

<a href="/assets/hco-17.jpg" target="_blank"><img src="/assets/hco-17.jpg" alt="Old deliveries filters" class="inline"/></a>
<p><em><center>Old portal: filters required exact values and date ranges</center></em></p>

<br>

## Problem 3 · Reorder goes unnoticed

Reordering previous purchases was implemented as a “Favourites” feature that most users ignored.

<br>
<a href="/assets/hco-19.jpg" target="_blank"><img src="/assets/hco-19.jpg" alt="Old favourites modal" class="inline"/></a>
<p><em><center>Old portal: reorder was hidden behind a “Favourites” button in the order form</center></em></p>

<br>

## Problem 4 · Returning pallets is tedious

Customers can return pallets and get some money back from their orders. They could request it in the portal, but the process was tedious and didn’t use the data the portal already had about their orders.

<br>
<a href="/assets/hco-21.jpg" target="_blank"><img src="/assets/hco-21.jpg" alt="Old pallets return form" class="inline"/></a>
<p><em><center>Old portal: a blank return form asking for a contract number and materials from scratch</center></em></p>

<br>

# Ideation
---
## User flows

I created user flows and reviewed them with Holcim’s team to align on system requirements. This helped us spot technical challenges early and start designing with more clarity.

<br>
<a href="/assets/hco-24.jpg" target="_blank"><img src="/assets/hco-24.jpg" alt="User flow: new order, cement and aggregates" class="inline"/></a>
<p><em><center>New order (Cement & Aggregates) - Delivery</center></em></p>

<a href="/assets/hco-23.jpg" target="_blank"><img src="/assets/hco-23.jpg" alt="User flows: cement and aggregates and ready-mix" class="inline"/></a>
<p><em><center>Both flows side by side: Cement &amp; Aggregates (top) and Ready-mix (bottom)</center></em></p>

## Low-fi exploration

I explored different paths at very low fidelity before committing to one. This let me discard ideas that didn’t feel right, see all the possible paths side by side, and get feedback early.

<br>
<a href="/assets/hco-26.jpg" target="_blank"><img src="/assets/hco-26.jpg" alt="Low-fidelity sketches of the order detail page" class="inline"/></a>
<p><em><center>Order detail explorations: which layout scales when an order has many materials?</center></em></p>
<br>

<br>

# Design and key decisions
---
Decisions are grouped by the problem they solve. Each design shows desktop and mobile.

<br>

## Solving problem 1 · Ordering is too complex

> *The ordering process is complex, time-consuming and prone to errors. It requires constant back and forth between pages.*

### Splitting the order process into multiple, more focused steps
One long form became a guided flow with one decision per step and a progress bar. Customers always know where they are and what’s left, and fewer things can go wrong at once.

<a href="/assets/hco-29.jpg" target="_blank"><img src="/assets/hco-29.jpg" alt="New order step 1: select job site" class="inline"/></a>

### Bringing delivery info to the front
Scheduling deliveries used to be buried in a per-row modal. Now it’s its own step, with every delivery for every material visible in one table.

<a href="/assets/hco-30.jpg" target="_blank"><img src="/assets/hco-30.jpg" alt="Schedule deliveries step" class="inline"/></a>

### Using smart defaults that save time
Fields are pre-filled wherever the value can be predicted, so customers only change what’s different instead of filling every field by hand.

<a href="/assets/hco-31.jpg" target="_blank"><img src="/assets/hco-31.jpg" alt="Pre-filled delivery dates" class="inline"/></a>

### Letting customers review and edit orders before submission
A summary step shows the whole order, and each section can be edited in place. Errors get caught before the order reaches Holcim, not after.

<a href="/assets/hco-32.jpg" target="_blank"><img src="/assets/hco-32.jpg" alt="Order summary step" class="inline"/></a>

### Optimizing for speed when possible
Shortcuts like “Repeat order” in the list and “Apply to all deliveries” turn repetitive tasks into a single click.

<a href="/assets/hco-33.jpg" target="_blank"><img src="/assets/hco-33.jpg" alt="Repeat order and apply to all deliveries shortcuts" class="inline"/></a>

### Letting users save unfinished orders and finish them later
Orders with several materials and deliveries take time. If customers have to stop halfway, they can save and pick up where they left off instead of starting over.

<a href="/assets/hco-34.jpg" target="_blank"><img src="/assets/hco-34.jpg" alt="Save and resume order dialogs" class="inline"/></a>

### Providing contextual buttons for likely next steps
After key moments, like creating an order or hitting a holiday fee warning, the next likely action is one click away.

<a href="/assets/hco-35.jpg" target="_blank"><img src="/assets/hco-35.jpg" alt="Order created and holiday fee dialogs" class="inline"/></a>

<br>

## Solving problem 2 · It’s hard to find things

> *Customers struggle to find things because orders, deliveries and invoices aren't linked, filters demand too much precision and there's poor visual hierarchy.*

### Bringing all order types under a single “Orders” section
Instead of separate places for each kind of order, there’s one Orders section with tabs for Cement & Aggregates and Ready-mix.

<a href="/assets/hco-37.jpg" target="_blank"><img src="/assets/hco-37.jpg" alt="Unified orders section" class="inline"/></a>

### Providing a global search field
One search field accepts an order number, job site or date, so customers can find an order without setting up filters.

<a href="/assets/hco-38.jpg" target="_blank"><img src="/assets/hco-38.jpg" alt="Global search field" class="inline"/></a>

### Providing more “human” filters
Exact date ranges were replaced with presets like “Last 7 days” or “Year to date”. A custom range is still there when it’s needed.

<a href="/assets/hco-39.jpg" target="_blank"><img src="/assets/hco-39.jpg" alt="Date filter presets" class="inline"/></a>

### Improving the visual hierarchy for better usability and scannability
Clear headings, grouped details and status tags make the important information stand out, so pages can be scanned at a glance.

<a href="/assets/hco-40.jpg" target="_blank"><img src="/assets/hco-40.jpg" alt="Delivery detail with improved hierarchy" class="inline"/></a>

### Always linking orders, deliveries and invoices
Every delivery links to its order and invoice, and the other way round. Matching documents no longer needs manual cross-checking.

<a href="/assets/hco-41.jpg" target="_blank"><img src="/assets/hco-41.jpg" alt="Links between delivery, order and invoice" class="inline"/></a>

### Providing visual indicators of order progress and completion
A progress bar on each material shows how much has been delivered, so customers can track an order without opening every delivery.

<a href="/assets/hco-42.jpg" target="_blank"><img src="/assets/hco-42.jpg" alt="Order progress indicator" class="inline"/></a>

### Adding an orders, deliveries and invoices summary in the dashboard
The dashboard shows how many orders, deliveries and invoices are in each status, with a direct link to see them all.

<a href="/assets/hco-43.jpg" target="_blank"><img src="/assets/hco-43.jpg" alt="Dashboard summary cards" class="inline"/></a>

<br>

## Solving problem 3 · Reorder goes unnoticed

> *Reordering previous purchases was implemented as a “Favorites” feature that most users ignore.*

### Replacing “Favorites” with a clear “Repeat order” button
Reordering now lives where customers already are: on the order they want to repeat, with a label that says exactly what it does.

<a href="/assets/hco-45.jpg" target="_blank"><img src="/assets/hco-45.jpg" alt="Repeat order button in order detail" class="inline"/></a>

### Allowing “Repeat order” from order list
Customers can also repeat an order straight from the list, without opening it.

<a href="/assets/hco-46.jpg" target="_blank"><img src="/assets/hco-46.jpg" alt="Repeat order from order list" class="inline"/></a>

<br>

## Solving problem 4 · Returning pallets is tedious

> *Customers can return the pallets and get some money back from their orders. They can request it in the portal, but the process is tedious and fails to leverage orders data.*

### Allowing customers to initiate a pallet return from an order
The order already knows which pallets were delivered, so a return can start right from it.

<a href="/assets/hco-48.jpg" target="_blank"><img src="/assets/hco-48.jpg" alt="Return pallets from order detail" class="inline"/></a>

<br>
<a href="/assets/hco-49.jpg" target="_blank"><img src="/assets/hco-49.jpg" alt="New return showing returnable pallets per job site" class="inline"/></a>
<p><em><center>The return flow shows how many pallets each job site can return</center></em></p>

### Allowing users to track their pallet returns as if they were orders…
Returns get their own list with the same search, filters and statuses as orders, so there’s nothing new to learn.

<a href="/assets/hco-50.jpg" target="_blank"><img src="/assets/hco-50.jpg" alt="Pallet returns list" class="inline"/></a>

### …and see the detail of each return

<a href="/assets/hco-51.jpg" target="_blank"><img src="/assets/hco-51.jpg" alt="Pallet return detail" class="inline"/></a>

### Nudging users to return pallets right after placing an order
When an order includes returnable pallets, the confirmation screen suggests returning them.

<a href="/assets/hco-52.jpg" target="_blank"><img src="/assets/hco-52.jpg" alt="Return pallets suggestion after ordering" class="inline"/></a>

<br>

Thanks for reading!
