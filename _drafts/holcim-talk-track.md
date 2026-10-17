# Holcim · Portfolio review · RevenueCat — talk track

Target: ~15 minutes. Each section is also in the presenter notes of the matching Figma slide.

**The thread:** the portal spoke Holcim's language (contracts, pallet lines, record numbers); customers speak their own (job sites, trucks, "what arrived this week?"). Four problems, one root cause, one principle applied four times.

---

## 1 · Cover (0:00)
This is a B2B ordering portal I redesigned at Hanzo for Holcim, one of the biggest building-materials companies in the world. It's a complex product problem: lots of objects, lots of edge cases, and a customer I couldn't talk to directly. I'll take about 15 minutes.

## 2 · Agenda (0:20)
I'll follow what you asked for: the problem, my role, the decisions I made for each customer problem, the interaction details, what happened after launch, and what I'd do differently.

## 3 · Context (0:35)
Holcim sells cement, aggregates and ready-mix concrete in 70 countries. Its customers are businesses ordering materials for their job sites, so every order has a site, materials, quantities and delivery slots attached.

## 4 · The problem: a chain (0:55)
The core issue was a chain. The portal was hard to use, so orders went wrong. Calling felt faster and safer, so customers went back to phone and email, and adoption stayed low. And every one of those orders was manual work for Holcim. The business goal was adoption, but the real lever was the first link: the portal itself.

## 5 · My role (1:30)
Small team: me as UX designer, a visual designer owning the design system, a front-end developer, and a PM on Holcim's side. I owned UX end to end: research, problem definition, flows, low-fi, hi-fi prototypes for desktop and mobile, and presenting to stakeholders.

## 6 · Discovery (2:00)
Biggest constraint: no access to customers. So I triangulated: five stakeholder interviews, including the support lead as a proxy because they hear every complaint; a review of the current UI; and an OOUX object map of contracts, orders, deliveries, materials and invoices. That map is where the insight came from.

## 7 · The insight (2:40)
This is where it clicked. When I mapped the objects, I saw that every screen mirrored Holcim's back office: contracts, positions, Incoterms, sales orders. Customers don't think in those terms. They think in job sites, trucks arriving, and "what arrived this week?". The portal was making them translate.

## 8 · Four symptoms (3:20)
Once you see that, the four problems I found stop looking like four separate issues. They're the same root cause showing up in four places. I'll walk through each one, and then what I did about it.

## 9 · Before pixels (3:40)
Before designing screens I mapped the flows for each order type and reviewed them with the developer and Holcim. That surfaced technical constraints early. Then I sketched on paper, for example to decide which order detail layout scales when an order has many materials.

## 10 · Problem 1 · Ordering (4:10)
To order 200 pallets of one cement: contract number first, then a job-site modal filtered by Incoterm, then the quantity split into 12 lines, each with a date and a time window. 36 fields for one material. Every one is a chance for an error, so calling Holcim was simply easier. The design had to start from what customers know and let the portal do the repetitive work.

## 11 · Start from the job site (5:00)
So the job site comes first, because that's what customers know best, picked with a plain search. One decision per step, with a progress bar.

## 12 · Plan deliveries, not pallet lines (5:20)
Deliveries become rows per truck or load, the way they actually arrive at the site. Dates and slots are prefilled, and "Apply to all deliveries" copies a slot in one click. The 36 fields are gone.

## 13 · Review before sending (5:45)
And a summary with inline edit, so mistakes are caught before the order reaches Holcim, not in a phone call afterwards.

## 14 · Problem 2 · Documents didn't talk (6:00)
An invoice showed the delivery note number as plain text. To check the delivery behind it, customers copied the number, went to deliveries and filtered until it showed up. For Holcim these are separate records. For a customer they're one story: what I ordered, what arrived, what I'm paying for.

## 15 · Problem 2 · Search by record numbers (6:35)
And search was built on record numbers: 8 filters named after system fields. A simple question like "what arrived this week?" meant an exact date range and a long table. So the design had to connect the documents, and let customers search with their own questions.

## 16 · Search with their questions (7:00)
One search for order number, job site or date, and filters like "Last 7 days". Every order type lives in one Orders section.

## 17 · Documents as one story (7:20)
Every delivery links to its order and its invoice, both ways. Checking an invoice against what arrived is one click.

## 18 · Progress without digging (7:40)
And progress is visible without digging: each material shows how much has been delivered, and the dashboard sums everything up by status.

## 19 · Problem 3 · Reordering (8:00)
Reordering existed, but as "Favourites", a template list opened from inside the new-order form. Customers think "same as last time", about an order they can already see, so most never found it.

## 20 · Repeat order (8:30)
So "Repeat order" sits on every order and in the list. It copies the order and jumps straight to scheduling deliveries.

## 21 · Problem 4 · Pallet returns (8:50)
Customers get money back for returned pallets, but the request started from a blank form asking for a contract number and every material, data the portal already had.

## 22 · Start a return from the order (9:15)
So a return starts from the order: "Return pallets" sits next to each material.

## 23 · Show what can be returned (9:30)
And the flow shows how many pallets each job site can return, so nobody has to look it up. Returns are then tracked in their own list, like orders, and customers get a nudge to return pallets after ordering.

## 24 · One principle, applied four times (9:55)
Same principle every time: start from what the customer knows, and let the portal handle Holcim's records. That's the thread through the whole project.

## 25 · Mobile (10:25)
On interaction details: every flow was designed for mobile too. Tables turn into cards, secondary details use progressive disclosure, and some advanced features stay on desktop.

## 26 · Small interactions (10:55)
And small interactions that prevent dead ends: the next likely step after ordering, a holiday-fee warning before it surprises anyone, and orders that can be saved and finished later.

## 27 · After launch (11:25)
Honestly: early feedback indicated customers were satisfied with the new ordering experience, but hard adoption data was still pending, so I won't claim a number. If I were judging success, I'd look at these four signals: portal share vs phone and email, corrected orders, support contacts, and returns started from an order.
> Before the review: replace or confirm with real feedback or numbers.

## 28 · What I'd do differently (12:20)
Three things. Push harder for even a few customer calls. Agree success metrics and a baseline before designing, so the launch is measurable. And test with real customers before handoff, because stakeholders know the system too well.

## 29 · Thanks (13:20)
That leaves time for questions. Happy to go deeper into any of the decisions, the OOUX work, or how I worked with the developer.
