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

## Screenshot
- `books.html` webpage with all required outputs visible.
 <img width="1918" height="985" alt="image" src="https://github.com/user-attachments/assets/ed44c8f3-04e5-46cf-a523-9e22125e1b9b" />
- `jquery-dom.html` showing “Modified Text” and coral styled div.
  <img width="1916" height="909" alt="image" src="https://github.com/user-attachments/assets/28f82e67-fd7e-4914-b923-c890a664bd69" />
- The “Button clicked!” alert after clicking the button.
<img width="1916" height="986" alt="image" src="https://github.com/user-attachments/assets/e47b18d7-7b97-426c-8383-89d1d46fe758" />
## Suggested report contents
- Question 1: screenshot and explanation of JSON structure/data types.
- Question 2: screenshot and explanation of `fetch()`, `response.json()`, `textContent`, `createElement`, and error handling.
- Question 3: screenshots, explanation of `.text()`, `.addClass()`, and `.on()`.
- A short comparison: native JavaScript has no extra library dependency; jQuery remains practical in older existing projects already using it.
- GitHub repository URL: **replace with your URL**.

## GitHub upload
Create a repository on GitHub, upload these files and your screenshots if desired, then copy the repository URL into your PDF report.
