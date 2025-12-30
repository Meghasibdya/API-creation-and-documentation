# DT Internship Assignment – Node.js APIs

## Overview
This project implements REST APIs for managing Events and Nudges using Node.js and MongoDB. The focus is on clean API design, pagination, and schema-less flexibility.

## Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose

## Features
- CRUD APIs for Events
- Pagination support
- Nudge creation linked to events
- Schema-less MongoDB design

## API Endpoints

### Events
- GET /api/v3/app/events
- GET /api/v3/app/events/:id
- POST /api/v3/app/events
- PUT /api/v3/app/events/:id
- DELETE /api/v3/app/events/:id

### Nudges
- POST /api/v3/app/nudges
- GET /api/v3/app/nudges
- GET /api/v3/app/nudges/:id
- PUT /api/v3/app/nudges/:id
- DELETE /api/v3/app/nudges/:id

## Notes
MongoDB was chosen for its flexibility and ease of handling dynamic event data.

