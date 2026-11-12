# BIC21203 Lab 4b — JSON and jQuery

This repository contains solutions for the three questions in Lab 4b.

## Files
- `books.json` — the required two-book JSON dataset (Question 1).
- `books.html` — fetches `books.json` and displays its contents (Question 2).
- `jquery-dom.html` — uses jQuery 4.0.0 for text, class, and click-event operations (Question 3).

## Setup and testing
1. Open the folder in **Visual Studio Code**.
2. Install the **Live Server** extension if it is not already installed.
3. Right-click `books.html` and choose **Open with Live Server**. Do not use a `file://` URL: `fetch()` must run from a local server.
4. Check the first book title, second book author, and the two genre lines.
5. Open `jquery-dom.html` in a browser with internet access (needed to load the CDN script). Confirm the text changes, the coral background appears, and the button triggers an alert.
6. Confirm `books.json` is valid JSON using an editor's JSON validation or a JSON validator.

## Required screenshot evidence
- Complete `books.json` file and successful parse/validation.
- `books.html` webpage with all required outputs visible.
- `jquery-dom.html` showing “Modified Text” and coral styled div.
- The “Button clicked!” alert after clicking the button.

## Suggested report contents
- Question 1: screenshot and explanation of JSON structure/data types.
- Question 2: screenshot and explanation of `fetch()`, `response.json()`, `textContent`, `createElement`, and error handling.
- Question 3: screenshots, explanation of `.text()`, `.addClass()`, and `.on()`.
- A short comparison: native JavaScript has no extra library dependency; jQuery remains practical in older existing projects already using it.
- GitHub repository URL: **replace with your URL**.

## GitHub upload
Create a repository on GitHub, upload these files and your screenshots if desired, then copy the repository URL into your PDF report.
