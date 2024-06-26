---
layout: default
title: Trello
parent: Project Management
grand_parent: Operations
nav_order: 2
---

# Trello
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

- TOC
{:toc}

**Purpose**

We use Trello for project management, as it allows unlimited access to boards by partners and clients, encouraging collaboration and transparency.

We use Trello because:
    
 - it allows collaboration with clients on assignments.
 - is simple enough for people to join ad-hoc without training.

[See video version](https://www.youtube.com/watch?v=6X9x4SCLhKs).

**Scope**

This page describes the basics of Trello, then goes more into depth on how we use it at Countable.

## Guidelines for Our Team's Use of Trello

Before progressing to the basics and layout of Trello, we'll outline the key guidelines which help maintain a productive workflow in our team's specific Trello methodology.

1.  "Own" your cards. **If you're assigned to it, you should post updates when there are changes, blockers, or reconfiguration**. If others' tasks rely on yours, directly "@" comment them as needed.
2.  **If it's in a Sprint, it needs to be assigned to exactly one primary team member for accountability**. Don't assign cards to 2 or more people. *Without anyone assigned, cards get lost*. If a card is complex enough
that it needs multiple team members accountable, decompose it into multiple smaller tasks and assign each.
3.  Be pragmatic, not aspirational. **The Sprint column should only contain tasks we expect to finish within that Sprint.**
4.  **Communicate with your team, and include screenshots and clarifying details.** Many cards are created during discussions or collaboration, and we want to capture the valuable information from that moment in the card.

## Trello Basics

We use Trello for project management, as it's simple to set up access to the appropriate boards by partners and clients. 

A Trello board consists of a set of **Cards** (tasks) arranged in **Columns**.

### Trello Cards

A card should contain a clear description of work to be done by one person required to support a given [User Story](/ux/USER_STORIES.md).

During composition, the author of the Trello card should base to assuming that the assigned members are without context of the given task and link to relevant background.

Before assignment, the details and scope of the card should already be finalized to prevent confusion.

A card should typically be between 1 hour and 1 day of work. If it's longer, split it into 2 cards in that column.

#### Composing Trello Cards

When writing titles for Trello cards, use an imperative voice (e.g. "Disable cancel button on page X after doing Y").

Details should include important information depending on what kind of Trello card (e.g. *Feature* or *Bug Fix*) is being created.

##### Feature cards should include:

  - **Current Behavior** (optional) - If an existing feature is proposed to be improved or changed, summarize current behaviour to be enhanced. For front-end related requests, include screenshots, URL of the page if possible, and XD & Google Drive links (if applicable).
    - [Tutorial video for front-end cards](https://www.loom.com/share/3c91d0cf0348471abb3eed20fc63b4ab)
  - **Proposed Behavior** - Key points should be well-defined. For front-end related improvements or changes, if there are any references from other websites, include screenshots or links.
  - **Rationale** - For features that are derived from personal or internal ideas, define why the feature is beneficial. For external requests, include references of discussion threads (e.g. Groove tickets, Slack discussion).
  - **Checklist** - Optional. For small related tasks that will be done together, include a checklist within one card rather than many cards.

##### Bug fix cards should include:

  - **Label** - Card should be labeled as "bug". This may be used for filtering bugs in the Trello board.
  - **Current Behavior** - Specify what is broken. For front-end related requests, include screenshots.
  - **Expected Behavior** - Accurately define the correct behavior.
  - **Steps to Reproduce** - Specify which environment (may be links to our staging or production sites) where the bug was encountered. Write steps in a numbered list.
  - **Potential Cause and Solution** - *Optional*. Share information that may be related to the cause of the bug (e.g. misconfiguration in the project settings, Nginx or Docker).

### Trello Board Columns

#### Ideas

*Optional*. Stuff that's not clear enough to be in backlog yet.

#### Requests

This is the starting point for anyone to add cards, and where cards the client has requested live until the Scrum Master can review and ensure they're actionable and clear. Everyone should generally add cards here.

If they're actionable, move them to Backlog. 

If they're not, write a comment to the client asking for more information in order to make it actionable, and leave it in the feedback or requests column.

If any additional requirements steps such as a mockup are required, mention that in the card. Attach any additional examples and/or specifications to the card.

#### Feedback

*Optional*. On this column, we may store cards that somehow need client or manager review before proceeding further. In practical terms, we use this section whenever we need some client data or feedback to progress with our current task.

#### Backlog

Cards that are **clear** and **actionable**. This is the traditional Scrum backlog list, **ordered by priority** (highest on top), by the Product Owner.

There is only one backlog column, because we need to use the current sprint's lessons to plan future sprints. So, we cannot plan future sprints in advance, we can only set card priority.

#### Sprint

Cards actively being worked on in the current week.

#### Done

Cards that are ready to be tested by the client (and when that's not possible, by the consultant). A test can take the form of a client approval, code review, or automated test written.

### Moving cards between columns

A diagram shows how cards can move from conception to completion [here](https://drive.google.com/open?id=1VrniT1lRqVu9sJr0ZMK1aQLnFwEuFIQD).

As the diagram illustrates, each column corresponds to a specific within the adapted [SCRUM](SCRUM.md) framework.

### Progress Awareness

**It's essential to keep our clients informed about our current progress** on particular tasks, so our professional relationship is strengthened and trust is built.

For this objective, we suggest that you:

1.  Take screenshots of finished progress (when applicable) and post on your trello ticket.
2.  Use checklists for keeping track of what's being done.
3.  Use "Screencastify" chrome extension for recording short screencasts and attaching into your trello ticket

### Labels

Labels can be added to help the team organize cards. Some labels are common across project, such as the `bug` label.

If you find something that's severly broken in any of our websites, please create a Trello card with a red label `bug`, and tell the developer who you've assigned it to. Do this sparingly: only when it's something we're likely to quickly lose customers over such as a service being down completely or a button not working.

For less serious bugs, don't use this label, just make a regular card.

## Boards

We generally have one board per codebase with a client, and one per internal product or project.

## Forwarding Client Emails to Trello

Clients will often email you rather than use Trello. This can be fixed by forwarding their email to the Trello board.

Go to their Trello board, and click settings -\> email-to-board settings, and add that email address as a contact in your email. You can then forward emails directly to your trello board.

However, it does make a bit of a mess since email signature images are copied into the tickets, so please clean them up when you look at them in Trello.
