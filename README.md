# Coffee-review
☕ The Great Coffee Rating App Description A fully interactive coffee rating application that allows users to browse a curated list of coffee drinks, vote for their favorites, and manage the collection. Each vote is persisted in a simulated database (localStorage), and the app features beautiful coffee imagery with a clean, responsive design.
<img width="1893" height="977" alt="Screenshot 2026-06-23 200312" src="https://github.com/user-attachments/assets/c9aebf6c-ecbb-4b9e-864a-db370b18b5cc" />
Features
Browse Coffee Collection – View a list of coffee drinks with images, descriptions, and vote counts

Vote System – Click the "Vote +1" button to upvote any coffee, with real-time count updates

Remove Items – Delete any coffee entry from the list using the "Remove" button

Persistent Storage – All votes and items are saved in localStorage, surviving page refreshes

Visual Feedback – Animated vote counter and smooth transitions for an engaging experience

Responsive Design – Works seamlessly on desktop, tablet, and mobile devices

Rich Visuals – High-quality coffee images from Unsplash for each item

Technology Stack
HTML5 – Semantic markup

CSS3 – Custom styling with animations and responsive grid layout

JavaScript (ES6) – Dynamic DOM manipulation, event handling, and data persistence

Font Awesome – Icon library for visual enhancements

LocalStorage – Client-side data persistence simulating a database

How It Works
The app loads coffee data from localStorage or initializes with default items

Each coffee card displays:

A relevant coffee image

Coffee name

Description

Current vote count

"Vote +1" button

"Remove" button

Clicking "Vote +1" increments the vote count, updates the UI, and saves the change to localStorage

Clicking "Remove" deletes the item from both the UI and the database

All data persists across page reloads
