# About

Notes from the course "Build Your Startup with No Coding (Design, Develop & Ship)", see https://www.udemy.com/course/buildastartup/

- [About](#about)
  - [1 Welcome](#1-welcome)
  - [2 Bubble](#2-bubble)
  - [3 App - Resto](#3-app---resto)
  - [My FAQ](#my-faq)

## 1 Welcome

- Also free lessons, see https://bubble.io/lessons
- in free plan unlimited public, some private

## 2 Bubble

- Editor
  - features two stages: DEV and LIVE=PROD
- Design
  - Visual Elements
  - Containers (div)
  - Input Elements
- Workflows
  - when element is clicked or similar
  - do {navigation, database, email, payment, analytics, element actions, plugins}
- Database
  - data types = table definition (column fields)
  - app data = tables
  - options
    - new entry
    - upload CSV
    - export CSv

## 3 App - Resto

Aim: restaurant directory application, where a user can store, list and search their favorite restaurants

- overview
- frontend
  - uses repeating group design element
- database
  - simply add some data and show it when clicking on `search`

## My FAQ

Can bubble export source code?

- seems like not? see https://forum.bubble.io/t/new-thread-more-context-on-our-changes-to-pricing-faqs-answered/255924/772
  - alternatives: **flutterflow** (flutter = open source app dev toolkit by google), draftbit, noodl

What is flutter?

- primarily a frontend framework
  - https://github.com/flutter/flutter
    - 157k stars ?!?!?!
    - from 2018, similar to fb
  - https://github.com/facebook/react
    - 213k stars
  - https://github.com/vuejs/core
    - 41k stars

What does flutterflow feature?

- similar frontend editor as bubble
- interacts with backend / DB / APIs
- database (services)
  - Firestore (google NoSQL DB)
  - supabase (PostgreSQL DB plus backend with authentication, etc., open source _Firebase_ alternative)
- can setup complex logic flows visually
- add your own code (functions, widgets, actions)
- More features (30-70$ per user per month)
  - download code
  - publish to custom websites
  - publish to google/apple store
  - Swagger imports
  - github integration
  - real-time collaboration
