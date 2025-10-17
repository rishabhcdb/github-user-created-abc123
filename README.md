# GitHub Account Creation Date Display

## Overview

This project publishes a simple Bootstrap webpage that allows users to input a GitHub username and retrieve the account's creation date. It leverages the GitHub API to fetch user data and displays the creation date in a user-friendly format (YYYY-MM-DD UTC). The page is designed to be easily deployable and customizable.

## Features

*   Fetches GitHub user data using the GitHub API.
*   Displays the account creation date in YYYY-MM-DD UTC format.
*   Uses Bootstrap for a responsive and visually appealing design.
*   Supports optional authentication via a `token` query parameter.
*   Includes a form with the ID `github-user-abc123`.
*   Displays the creation date within an element with the ID `github-created-at`.

## How to Use

1.  Open the webpage in your browser (e.g., after deploying to GitHub Pages).
2.  Enter a GitHub username in the input field.
3.  Optionally, add `?token=[YOUR_GITHUB_TOKEN]` to the URL to increase the API rate limit. Replace `[YOUR_GITHUB_TOKEN]` with your personal access token.
4.  The account creation date will be displayed below the input field.

## Technology Stack

*   HTML
*   CSS (Bootstrap)
*   JavaScript
*   GitHub API

## Project Structure

```
github-user-created-abc123/
├── index.html
└── README.md
```

## Local Development

1.  Clone the repository: `git clone https://github.com/YOUR_USERNAME/github-user-created-abc123.git` (Replace `YOUR_USERNAME` with your GitHub username)
2.  Open `index.html` in your browser.

## License

This project is licensed under the MIT License.

---

## Round 2 Enhancement
**Updated:** 2025-10-17

### New Feature
Show an aria-live alert #github-status that reports when a lookup starts, succeeds, or fails.

### Implementation
- Updated with new functionality
- All Round 1 features remain intact
