# How to Start: a national path to open source

*Plant open source, grow it local.*

This is a practical playbook for a government that wants to move from big-tech dependence to open source. Start small, learn fast, and earn the right to move the important systems.

## 1. Start with practitioners, not universities

Pick the first trainers from people who already work in technology every day: system administrators, developers, and IT staff in ministries and local companies.

Don't start with university professors. Professors usually have a set curriculum, have reasons not to change it, and tend to resist change. They're also often not used to teaching working adults. Bring universities in later, once there are local results to show them.

## 2. Set up a national Open Source Program Office

Create a small national Open Source Program Office (OSPO) to own the effort. Its job is to:

- set policy (preferred licenses, how to contribute back, how to buy open-source support)
- train the first group of trainers using the Ziarno courses
- keep a list of which government functions have moved, and what was learned
- connect with the global open-source community

Use the TODO Group (https://todogroup.org), the Linux Foundation community for OSPOs, as the model. It publishes free guides on starting and running an OSPO, and its members can mentor a new office.

### Practice InnerSource first

Before any team works in public, have it practice InnerSource: open-source ways of working, but only inside the ministry. Teams share code in an internal repository, review each other's changes, and write decisions down. Name a Trusted Committer for each shared project (the person who reviews and accepts changes and mentors newcomers) and a few InnerSource Champions who help other teams start. The OSPO sets the rules and decides when an InnerSource project is ready to release in public. Mistakes stay private while people learn. See [curriculum module 6](curriculum/06-innersource/) and [InnerSource Commons](https://innersourcecommons.org/).

## 3. Move a low-importance function first

Choose a function where a mistake is cheap and nobody's safety, money, or rights are at risk, such as an internal wiki, meeting scheduling, a document archive, or an internal help desk.

- Map how the work is done today.
- Use AI tools to help copy those workflows over: documenting steps, converting data and templates, writing scripts, and drafting training material.
- Run the old and new systems side by side until people trust the new one.
- Write down what worked, what didn't, and why.

## 4. Then the next least important function

Repeat with the next function up the ladder. Each move should be a little more important than the last. Reuse the scripts, training, and lessons from the move before.

## 5. Climb toward the important systems

Over time the team learns what works and what doesn't in their own country, with their own people, budgets, and rules. Only then move core and citizen-facing systems such as records, finance, and health.

The order is the strategy:

1. Practitioners trained
2. National OSPO set up
3. Lowest-risk function moved
4. Next function moved, using the lessons
5. Repeat, climbing toward critical systems

## Example ladder

These are examples, not rules. Each country should rank its own functions by risk. Common open-source options are listed for each rung.

| Rung | Risk | Example functions | Example open-source tools |
|---|---|---|---|
| 1 | Lowest | Internal wiki and knowledge base, team chat, meeting scheduling | Wiki.js or BookStack, Mattermost or Matrix (Element), Cal.com |
| 2 | Low | Internal help desk tickets, intranet website, staff surveys | Zammad or osTicket, WordPress or Drupal, LimeSurvey |
| 3 | Low-medium | Office documents and file sharing, video meetings | LibreOffice, Nextcloud, Jitsi or BigBlueButton |
| 4 | Medium | Email and calendar for staff, project tracking | Zimbra or Open-Xchange, OpenProject or Taiga |
| 5 | Medium-high | Public websites for ministries, open data portal, public forms | Drupal, CKAN, Formbricks |
| 6 | High | Procurement, HR, and internal finance | Odoo Community or ERPNext |
| 7 | Highest | Citizen records, health, tax, and identity systems | Proven digital public goods such as OpenMRS, DHIS2, and MOSIP, chosen with the national OSPO |

At every rung:

- Run old and new systems side by side until people trust the new one.
- Keep an exit plan to roll back.
- Record the lessons before moving up.

## Why this order works

- Early wins are cheap and visible.
- Mistakes happen where they don't hurt.
- Local skills grow with every move, so the country depends less on outside vendors, including us.
