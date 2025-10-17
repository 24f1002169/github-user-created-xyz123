## Overview

This web application allows users to fetch the creation date of a GitHub account by providing a username. It uses the GitHub API to retrieve user information and displays the account creation date in YYYY-MM-DD UTC format. The app is built with Bootstrap for styling and includes a form for submitting the username. It also supports the use of a GitHub API token via the `?token=` query parameter to increase rate limits.

## Setup

1.  Save the provided HTML code as `index.html`.
2.  Open `index.html` in your web browser.

## Usage

1.  Enter a GitHub username in the input field.
2.  Click the "Get Info" button.
3.  The account creation date will be displayed below the form.

   You can optionally provide a GitHub API token via the query parameter `token`.  For example: `index.html?token=YOUR_GITHUB_TOKEN`. Providing a token allows you to make more requests to the GitHub API before being rate limited.