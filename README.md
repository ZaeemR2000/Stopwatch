# Stopwatch Project

This project is a simple stopwatch application built with HTML, CSS, and JavaScript. It allows users to start, stop, and reset the stopwatch, which displays time in hours, minutes, seconds, and milliseconds.

## Features

- **Start**: Begins counting time from zero or resumes from the last stopped time.
- **Stop**: Pauses the stopwatch at the current elapsed time.
- **Reset**: Resets the stopwatch back to zero.

## Project Structure

The project consists of three files:

1. `index.html` – The main structure of the web page.
2. `style.css` – Styling for the layout, buttons, and display.
3. `index.js` – JavaScript logic to handle the stopwatch functionality.

## How to Use

1. Open `index.html` in your web browser.
2. Click the **Start** button to begin timing.
3. Click the **Stop** button to pause the timer.
4. Click the **Reset** button to clear the time and reset it to `00:00:00:00`.

## Files Overview

### HTML (index.html)
This file contains the structure of the web page. It includes the stopwatch display and buttons for controlling the start, stop, and reset functionalities.

### JavaScript (index.js)
The JavaScript file contains the core logic for the stopwatch. It uses `setInterval()` to update the display every 10 milliseconds, converting the elapsed time into hours, minutes, seconds, and milliseconds.

### CSS (style.css)
The CSS file defines the styling for the stopwatch's layout, including button hover effects, text alignment, and the flexbox layout for centering the content.

## Example Usage

1. Upon loading the page, the display shows `00:00:00:00`.
2. Click the **Start** button to begin counting the time.
3. Click the **Stop** button to pause the timer.
4. Click **Reset** to clear the display and reset the time.

## Future Enhancements

- Add a lap time feature to track intermediate times.
- Allow users to save and display lap times.
- Improve mobile responsiveness for smaller screen sizes.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Run

Simply clone the repository or download the files and open `index.html` in any modern web browser. No additional setup or installation is required.

