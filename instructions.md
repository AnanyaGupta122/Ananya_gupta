# WEB-001: PixelVault

## Online Gaming Website

**Category:** Web Development

---

# Context

PixelVault is a browser-based indie game discovery and publishing platform. Users can discover games, browse curated content, create collections, submit ratings and reviews, and access developer-created content through a responsive web application.

The project focuses on delivering a frontend application that works on desktop and mobile browsers.

---

# Project Information

| Field | Details |
|---------|---------|
| Project ID | WEB-001 |
| Category | Web Development |
| Project Type | Online Gaming Website |
| Platform | Responsive Web Application |
| Primary Goal | Build a browser-based indie game discovery platform |

---

# Main Goal

Build a responsive web application containing:

1. Homepage
2. Game Library
3. Game Detail Pages
4. User Authentication
5. User Profiles
6. Collections
7. Ratings and Reviews
8. Developer Dashboard
9. Game Submission
10. Developer Analytics
11. Administrative Moderation

---

# Requirements

## Homepage

The homepage must contain:

- Navigation Bar
- Hero Section
- Featured Games Section
- Trending Games Section
- Game of the Week Section
- Genre Browsing Section
- Footer

The navigation bar must provide routes to:

- Homepage
- Game Library
- User Profile
- Developer Dashboard

**Reference:**

`data/homepage_layout.png`

---

## Game Library

The Game Library must contain:

- Search Functionality
- Genre Filter
- Sorting Controls
- Game Card Grid

Each game card must display:

- Cover Image
- Game Title
- Genre
- Rating

**Reference:**

`data/game_library_layout.png`

---

## Game Detail Page

Each game detail page must contain:

- Banner Image
- Game Information
- Developer Information
- Minimum 4 Screenshots
- Ratings Section
- Reviews Section
- Play Game Button

**Reference:**

`data/game_detail_layout.png`

---

## User Features

Users must be able to:

- Register
- Login
- View Profile
- Create Collections
- Save Games
- Remove Games from Collections
- Submit Ratings
- Submit Reviews

**Reference:**

`data/user_profile_layout.png`

---

## Developer Features

### Dashboard Overview

Must display:

- Total Games
- Published Games
- Draft Games
- Total Views

### My Games

Must display:

- Game Title
- Status
- Last Updated Date

### Analytics Section

Must contain:

- One Line Chart
- One Activity Summary Table

### Recent Activity

Must display developer activity records.

### Game Submission Form

Must contain:

- Game Title
- Description
- Genre
- Cover Image
- Screenshot Gallery
- Play URL

**Reference:**

`data/developer_dashboard_layout.png`

---

## Administrative Features

Administrative moderation must support:

- Approve Game
- Reject Game
- Remove Review
- Mark Game as Featured
- Remove Featured Status

---

# Visual Requirements

**Reference:**

`data/branding_moodboard.png`

## Colors

| Purpose | Color |
|----------|----------|
| Primary | #6C63FF |
| Secondary | #00C2A8 |
| Accent | #FFB800 |
| Background | #111827 |
| Surface | #1F2937 |
| Text | #F9FAFB |

## Typography

- Inter Bold
- Inter SemiBold
- Inter Regular

---

# Technical Requirements

## Frontend

- React
- TypeScript
- Tailwind CSS
- React Router

## Data

- JSON Data Files
- Local Storage

## Responsive Support

| Device | Width |
|----------|----------|
| Mobile | 320px–767px |
| Tablet | 768px–1023px |
| Desktop | 1024px+ |

## Browser Support

- Chrome
- Edge
- Firefox
- Safari

## Not Allowed

- Backend Services
- Database Systems
- Payment Systems
- Multiplayer Features
- Live Chat
- Streaming Features

---

# Reference Materials

Provided files:

- data/branding_moodboard.png
- data/homepage_layout.png
- data/game_library_layout.png
- data/game_detail_layout.png
- data/user_profile_layout.png
- data/developer_dashboard_layout.png
- data/navigation_structure.png

Use `data/branding_moodboard.png` for color palette, typography style, spacing, and visual direction.

Use `data/homepage_layout.png` for homepage section ordering and content hierarchy.

Use `data/game_library_layout.png` for game card layout, filtering controls, search placement, and grid structure.

Use `data/game_detail_layout.png` for screenshot gallery placement, game information layout, and review section organization.

Use `data/user_profile_layout.png` for profile information layout, collection display, and activity history presentation.

Use `data/developer_dashboard_layout.png` for dashboard card arrangement, analytics placement, and game management structure.

Use `data/navigation_structure.png` for navigation hierarchy and route organization.

Do not reproduce reference assets exactly. Use them only as structural and visual guidance.

---

# Deliverables

The final submission must include:

1. Complete React project using React, TypeScript, Tailwind CSS, and React Router.
2. Complete source code for all required pages and features.
3. README.md containing project overview, installation instructions, local setup instructions, and build instructions.
4. Dockerfile capable of running the application locally.
5. package.json with project dependencies.
6. JSON data files used by the application.

---

# File Naming

Required filenames:

- README.md
- Dockerfile
- package.json

All other files may use the developer's preferred naming convention.

---

# Folder Structure

```text
PixelVault/
├── public/
├── src/
├── README.md
├── package.json
├── Dockerfile
└── .env.example
```

---

# Scope Boundaries

## In Scope

- Homepage
- Game Library
- Game Detail Pages
- User Authentication
- User Profiles
- Collections
- Ratings and Reviews
- Developer Dashboard
- Game Submission
- Developer Analytics
- Administrative Moderation

## Out of Scope

- Backend APIs
- Database Integration
- Payment Processing
- Subscription Systems
- Multiplayer Functionality
- Live Chat
- Streaming Services
- Native Desktop Applications

---

# Delivery Terms

This task is evaluated as a single delivery.

No revision rounds are expected.

The submission will be evaluated against the Acceptance Criteria and Evaluation Criteria sections of this document.

---

# Acceptance Criteria

Delivery is complete only if:

- Homepage is implemented.
- Game Library is implemented.
- Game Detail Pages are implemented.
- Authentication pages are implemented.
- User Profiles are implemented.
- Collections functionality is implemented.
- Ratings functionality is implemented.
- Reviews functionality is implemented.
- Developer Dashboard is implemented.
- Game Submission workflow is implemented.
- Developer Analytics is implemented.
- Administrative Moderation is implemented.
- Responsive requirements are satisfied.
- README.md is included.
- Dockerfile is included.
- package.json is included.

---

# Evaluation Criteria

The project will be evaluated on:

- Feature Completion
- Functional Correctness
- Responsive Behavior
- Alignment with Reference Assets
- Documentation Completeness
- Submission Completeness

---

# Final Goal

The completed project should allow users to discover browser-based games, browse curated content, manage collections, submit reviews, and access developer content through a responsive web application.
