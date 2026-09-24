# Petfolio

Petfolio is a mobile pet health and financial management application developed as my **eight-month Software Development capstone project at SAIT**.

The project was built collaboratively by a software development team and combined mobile UI development, authenticated REST APIs, financial tracking, analytics, validation, testing, and iterative product development.

## Project Overview

Petfolio was designed to give pet owners one place to manage both pet information and recurring financial activity.

Core areas of the application included:

- Pet profiles
- Expense tracking
- Monthly budgets
- Financial analytics
- Monthly reporting
- Authenticated user workflows
- Multi-pet data
- Mobile charts and visualizations
- REST API integration

## Tech Stack

- React Native
- Expo
- JavaScript / TypeScript
- REST APIs
- Authentication
- Mobile UI development
- Git / GitHub
- Team-based software development

## My Contribution

My primary contribution focused on frontend mobile development and integration with backend services.

I worked on:

- Pet profile interfaces
- Budget and expense workflows
- Monthly financial reporting
- Chart-based analytics
- Authenticated API integration
- Form and data validation
- Loading and error states
- Financial calculations
- Multi-pet budgeting logic
- Responsive mobile interfaces
- Debugging and edge-case handling

## Application Architecture

```mermaid
flowchart LR
    A[React Native / Expo Mobile App]
    B[Authentication]
    C[REST API]
    D[Application Data]
    E[Pet Profiles]
    F[Expenses & Budgets]
    G[Analytics & Reports]

    A --> B
    A --> C
    C --> D
    D --> E
    D --> F
    D --> G
