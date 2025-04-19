# Form Builder Website

## Description

The **Form Builder Website** allows users to create custom forms and access them via unique URLs. This project enables dynamic form creation and response collection.

## Features

- Users can create forms with various field types using drag and drop funtionality.
- Each form gets a unique URL for easy sharing.
- Responses are stored and can be accessed later.
- Secure user authentication using JSON Web Tokens (JWT) to manage sessions and protect form access.


## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/form-builder.git
   cd form-builder
   ```

2. Install dependencies and run:
   ```sh
   docker-compose up -d
   ```
   ```sh
   cd frontend
   npm install
   npm run dev
   ```
   ```sh
   cd backend
   npm install
   npm run dev
   ```

## Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express, TypeORM
- **Database**: PostgreSQL

## Improvements Required

- **Better UI**: Improve the design with an appropriate color theme for a cleaner and more modern look.
- **Shortened Form URLs**: Implement URL shortening for easier sharing and access.

