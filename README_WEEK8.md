# Skillora — Week 8 Advanced Final Project

Week 8 combines and polishes the Week 1–7 Skillora freelancing marketplace. No unrelated project was introduced.

## Complete Flow
User Registration/Login → Profile → Marketplace → Search & Filters → Service/Job Details → Proposal → Orders/Projects → Messaging → Notifications → Project Completion → Review & Rating → Client/Freelancer Dashboard.

## Week 8 Advanced Improvements
- Unified responsive UX layer across all existing pages.
- Login + registration demo with persistent localStorage session and client/freelancer role.
- Session-aware account menu, dashboard/profile/message shortcuts and notification count.
- Global accessibility improvements: skip link, visible focus states, keyboard-friendly controls and reduced-motion support.
- Loading/progress treatment, form validation feedback, save-state feedback and back-to-top control.
- Consistent final footer on pages that did not already have one.
- Dedicated `reviews.html` for ratings, review submission, verified-feedback presentation and persistent demo reviews.
- Existing Week 7 marketplace keeps multi-filter search, sorting, favorites, loading/empty/reset states and responsive filter drawer.
- Existing advanced dashboard keeps client/freelancer role switching and project pipeline.
- Existing project workflow keeps milestones, delivery, change requests, completion and review flow.
- Existing messages page keeps conversations + notifications.

## Main Pages
`index.html`, `marketplace.html`, `find-jobs.html`, `service-details.html`, `freelancer-profile.html`, `profile.html`, `edit-profile.html`, `create-service.html`, `my-services.html`, `post-job.html`, `job-details.html`, `submit-proposal.html`, `my-proposals.html`, `orders.html`, `project-details.html`, `messages.html`, `reviews.html`, `advanced-dashboard.html`.

## Technologies
HTML5, CSS3, Vanilla JavaScript, localStorage, Font Awesome, Google Fonts. No build step required.

## Run
Extract the ZIP and open `index.html` in a modern browser. Internet access is only needed for remote fonts/icons/demo imagery.

## Demo Data
All major interactions are frontend demos and persist in browser localStorage. Use Login/Register to create a demo session, then explore Marketplace → Details → Projects → Messages → Reviews → Dashboard.
