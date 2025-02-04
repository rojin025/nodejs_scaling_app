# Nodejs Scaling App

Scaling Applications with Node.js

# Advanced Node.js: Scaling Applications

## Overview

This course covers techniques to scale Node.js applications efficiently by leveraging process forking, clustering, database partitioning, and microservices.

## Prerequisites

Before starting, ensure you have:

- Familiarity with **modern JavaScript (ES6+)**, including:
  - Arrow functions (`() => {}`)
  - Destructuring (objects & arrays)
  - `let` and `const` declarations
- Basic knowledge of **core Node.js modules**, such as:
  - HTTP
  - NPM
  - Express.js
- **Node.js installed** (latest version from [Nodejs.org](https://nodejs.org))

## Scaling Techniques Covered

- **Cloning (X-Axis Scaling)**: Forking multiple Node.js processes to handle increased traffic.
- **Horizontal Partitioning (Y-Axis Scaling)**: Distributing data across multiple databases.
- **Microservices (Z-Axis Scaling)**: Breaking applications into smaller, independent services.

## Exercise Files

- Download the exercise files to follow along.
- Folder structure:
  - Each **chapter** has its own directory.
  - Each **video lesson** has a **subfolder**:
    - **`start/`** → Initial files for the lesson.
    - **`finished/`** → Completed version after modifications.
- If a **`package.json`** exists in the `start/` folder, install dependencies:
  ```sh
  npm install
  ```
