# Software Requirements Specification Document

This serves as a template for each projects' Software Requirements Specification (SRS) document. When filling this out, you will be required to create user stories, use cases, requirements, and a glossary of terms relevant to your project. Each group member must contribute to every section, so it is crucial that your group's GitHub repository shows a commit history that reflects the work of each group member. It is highly recommended that you create separate branches for each member, but since this is one single document, you will need to manually merge the branches together. It is also advisable to have multiple working versions of this document (named separately) so that one person can compile the final SRS document from the multiple working versions. Ultimately, how you go about managing this is up to you, but consistent formatting, clear commit messages, and a thorough commit history with contributions from each group member are required.

Fill the document out following the guidelines listed in each section. Maintain [proper Markdown syntax](https://www.markdownguide.org/basic-syntax/) and be sure that your group has a `main` branch with this document and the entire [template repository codebase](https://github.com/david-gary/onlineStoreTemplate) either forked or downloaded and copied into your group's repository. If you have arranged to use a different codebase as a template, you do not need to have the original template included, but a `main` branch is still required.

## Group Members

* [Ben Jansson](bjansson@uncc.edu)
* [Darwin Peraza](dperaza@uncc.edu)
* [Name](mmailto:email@uncc.edu)
* [Name](mmailto:email@uncc.edu)

## Revisions

When a change is made to the document, a new revision should be created. The revision should be added to the table below with all information filled out.

| Version | Date | Description | Author | Reviewed By |
| --- | --- | --- | --- | --- |
| 1.0 | 03/22/23 | Initial draft | [David Gary](mailto:dgary9@uncc.edu) | [David Gary](mailto:dgary@uncc.edu) |

## Table of Contents

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Constraints](#constraints)
4. [Use Cases](#use-cases)
5. [User Stories](#user-stories)
6. [Glossary](#glossary)

## Introduction

In this section, you should give a brief overview of what your project will be. Describe the software system you are building and what problems it solves. You should also give a short description of the stakeholders (users of the system) and what their needs are. There is no set formatting requirement, but you should maintain a consistent structure across future sections. Not all members must contribute to this section.

## Requirements

Each group member must supply at least three functional requirements for the project. Each requirement should be written in the following format:

Ben Jansson:
* **ID:** REQ-1
  * **Description:** Comment section is a section where customers can leave comments on the website, products etc.
  * **Type:** Functional
  * **Priority:** 4
  * **Rationale:** Websites usually have a comment section so that the customer can get there opion out there
  * **Testing:** Try typing a comment and post it to see if it shows up on the website
* **ID:** REQ-2
  * **Description:** A contact page where a customer can eamil or call with questions or concerns
  * **Type:** Functional
  * **Priority:** 3
  * **Rationale:** This is important if the customer wants to get in contact with the company about the webiste or products
  * **Testing:** Try an actual email or number and see if you can contact it and someone will get the message
* **ID:** REQ-3
  * **Description:** Product images so the customer can see what the product looks like
  * **Type:** Functional
  * **Priority:** 1
  * **Rationale:** This is very important so the customer can scroll through to see different veiws and see what shoes they want to look at and buy
  * **Testing:** Put a random image to see if it shows up and then the actaul picture of the product

## Constraints

Ben Jansson constraints: 1) Using HTML for the website, while using html to create the website using a programming language might be better but would take a lot longer. 2) Another constraint might be to figure out what kind of shoe we want to sell mens, womens, kids, sytle, sports etc.

In this section, you should list any constraints that you have for the project. Each group member must supply at least two constraints. These can be constraints on the project itself, the software system, or the stakeholders. Constraints can be anything that limits the scope of the project. For example, that this project's template code is written using Flask and Python constitutes a constraint on the backend of the project. Constraints can also be things like the required timeline of the project. Be creative.

## Use Cases

In this section, you should list use cases for the project. Use cases are a thorough description of how the system will be used. Each group member must supply at least two use cases. Each use case should be written in the following format:

Ben Jansson:

* **ID:** UC-1
  * **Description:** The user can look through the products that we sell through pictures/decriptions and figure out what shoe they want to buy. 
  * **Actors:** The only actors here would be the customer shopping given that the store is a online website.
  * **Preconditions:** The website must be working for the customer to make a purchase and have a valid credit card to enter into the website to pay.
  * **Postconditions:** The website should get the customers order and the customer must have entered their address for the website to ship the product to.

* **ID:** UC-2
  * **Description:** A comment section can be interacted with by the customer entering in their comment and psoting it to the website for other people to read.
  * **Actors:** An actor would only be a customer, in this case who is commenting on the website.
  * **Preconditions:** The website must ahve a comment section and for the comment entered to be posted on the website.
  * **Postconditions:** The comment entered by the user needs to be posted and be able to be seen on the website.

## User Stories

In this section, you should list user stories for the project. User stories are a short description of how a user will be interacting with the system. Each group member must supply at least two user stories. Each user story should be written in the following format:

Ben Jansson:

US-1:
  * **Type of User:** Customer
  * **Description:** I want to look at pictures of different shoes that I want to buy, I expect to see the multiple different pictures/veiws of the product and buy the product I want

US-2:
  * **Type of User:** Customer
  * **Description:** I have a comment on the product that I bought and would like to leave it on the website for people to see what I think about it, I expect to enter the comment on the wbesite and for the comment to be posted on the websitefor other people to see. 

* **ID:** A unique identifier for the user story. This should be a number that is unique across the entire document (something like US-1, US-2, etc. but be sure to replace the word `ID` with the unique identifier).
  * **Type of User:** The type of user that the user story is for. This should be a single word that describes the type of user. For example, a user story for a customer might be `Customer` and a user story for an administrator might be `Admin`.
  * **Description:** A description of the user story that gives a narrative from that user's perspective. This can be any length, but it must paint the picture of what the user wants to do, how they intend to do it, why they want to, and what they expect to happen.

## Glossary

In this section, you should list any terms that are used in the document that may not be immediately obvious to a naive reader. Each group member must supply at least one term. Each term should be written in the following format:

* **Term:** The term that is being defined. This should be a single word or phrase that is being defined.
  * **Definition:** A definition of the term. This should be a short description of the term that is being defined. This should be a single sentence that describes the term.
