# Software Requirements Specification Document

This serves as a template for each projects' Software Requirements Specification (SRS) document. When filling this out, you will be required to create user stories, use cases, requirements, and a glossary of terms relevant to your project. Each group member must contribute to every section, so it is crucial that your group's GitHub repository shows a commit history that reflects the work of each group member. It is highly recommended that you create separate branches for each member, but since this is one single document, you will need to manually merge the branches together. It is also advisable to have multiple working versions of this document (named separately) so that one person can compile the final SRS document from the multiple working versions. Ultimately, how you go about managing this is up to you, but consistent formatting, clear commit messages, and a thorough commit history with contributions from each group member are required.

Fill the document out following the guidelines listed in each section. Maintain [proper Markdown syntax](https://www.markdownguide.org/basic-syntax/) and be sure that your group has a `main` branch with this document and the entire [template repository codebase](https://github.com/david-gary/onlineStoreTemplate) either forked or downloaded and copied into your group's repository. If you have arranged to use a different codebase as a template, you do not need to have the original template included, but a `main` branch is still required.

## Group Members

<<<<<<< HEAD
* [Monish Soundar Raj](mailto:msoundar@uncc.edu)
* [Ben Jansson](bjansson@uncc.edu)
* [Darwin Peraza](dperaza@uncc.edu)
>>>>>>> 405b2c7ecc0df75ab1d25207b5ce3cfe35d32a2e
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

Group 6, we will be building a online store for selling shoes. We are planning to use HTML, CSS, and JavaScript for the Front-end. And for the back-end for now we are planning on using Flask for handling all the API requests from the Front-end.  Users using our store will be able to look up different brand shoes, provide review on shoes, add and remove shoes from cart, will be able to search for a specific brand of shoes, and finally will be able to provide us with there shipping details.

## Requirements

<<<<<<< HEAD
* **ID:** REQ-2. 
  * **Description:** A product siplay page to show the products in a enlarged view, and to display all the product description, price, and quality selection. 
  * **Type:** Functional.
  * **Priority:** 2
  * **Rationale:** It allows users to view the products enlarged images, description -> to learn about the product, and to add no of quality. 
  * **Testing:** By displaying and checking the products details in this page at each building stage of the site. 

  * **ID:** REQ-3. 
  * **Description:**  A review section for each product.
  * **Type:** Functional.
  * **Priority:** 3
  * **Rationale:** It allows users to decided which product to buy based on the review from the previous users of the same product.
  * **Testing:** By populating the review section of the products with fake reviews and by asking some real people to post the fake reviews for some products.
=======
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
>>>>>>> 405b2c7ecc0df75ab1d25207b5ce3cfe35d32a2e

## Constraints

In this section, you should list any constraints that you have for the project. Each group member must supply at least two constraints. These can be constraints on the project itself, the software system, or the stakeholders. Constraints can be anything that limits the scope of the project. For example, that this project's template code is written using Flask and Python constitutes a constraint on the backend of the project. Constraints can also be things like the required timeline of the project. Be creative.

Member - Monish Soundar Raj

constraints: 
1) Time available to complete the project is minor.
2) As the template code is written in Flask, it might be time consuming to learn about it first before working on the project.

## Use Cases

In this section, you should list use cases for the project. Use cases are a thorough description of how the system will be used. Each group member must supply at least two use cases. Each use case should be written in the following format:

Member - Monish Soundar Raj

* **ID:** UC-1
  * **Description:** Searching for shoes by brand.
  * **Actors:** User, Online Shoe store.
  * **Preconditions:** The user clicks on the search bar located in the nav-bar to make it active and searches to find shoes of a specific brand.
  * **Postconditions:** The user is presented with a page displaying the shoes of the brand the user searched for.

  * **ID:** UC-2
  * **Description:** Viewing product details to make a purchase.
  * **Actors:** User, Online Shoe store.
  * **Preconditions:** The user clicks on the product that they wanted to learn more about. 
  * **Postconditions:** The user is displayed with a product display page, which shows the user the selected product desciption, price, let's users select the quantity, let's users select the size and let's user to add the product to cart or buy it with one click.

## User Stories

In this section, you should list user stories for the project. User stories are a short description of how a user will be interacting with the system. Each group member must supply at least two user stories. Each user story should be written in the following format:

Member - Monish Soundar Raj

* **ID:** US-1
  * **Type of User:**  Customer
  * **Description:**  As an online shoe shopper, I should be able to read reviews written by others who previously brought the same product, so that I can make my decision on whether to purchase a product or not. And also, I need to be able to leave a review on a product I purchase, to help the future customer choose a product.

  * **ID:** US-2
  * **Type of User:**  Customer
  * **Description:**  As an online shoe shopper, I should be able to search for specific brand shoes, I donot want to look at all the brand shoes without having a interest to purchase them. So, having a search bar allows me look up products fast and complete the purchase soon. 

## Glossary

In this section, you should list any terms that are used in the document that may not be immediately obvious to a naive reader. Each group member must supply at least one term. Each term should be written in the following format:

* **Term:** The term that is being defined. This should be a single word or phrase that is being defined.
  * **Definition:** A definition of the term. This should be a short description of the term that is being defined. This should be a single sentence that describes the term.
