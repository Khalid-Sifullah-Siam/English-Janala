# English Janala

<p align="center">
  <img src="./assets/logo.png" alt="English Janala Logo" width="90" />
</p>

## Overview

English Janala is a responsive vocabulary learning web application built with HTML, Tailwind CSS, DaisyUI, and vanilla JavaScript. The project helps learners explore English lessons, search vocabulary, listen to pronunciations, and view detailed word information through a clean and interactive interface.

## Live Demo

- Live Site: [English Janala](https://khalid-sifullah-siam.github.io/English-Janala)
- Repository: [Khalid-Sifullah-Siam/English-Janala](https://github.com/Khalid-Sifullah-Siam/English-Janala)

## Features

- Dynamic lesson buttons loaded from the API
- Vocabulary cards filtered by lesson
- Search functionality across all available words
- Word details modal with meaning, pronunciation, example, and synonyms
- Text-to-speech pronunciation using the Web Speech API
- Loading spinner while vocabulary data is being fetched
- Empty-state handling for lessons with no vocabulary
- Active lesson highlighting for better navigation
- Responsive layout for desktop and mobile devices
- FAQ accordion section for a polished user experience

## Tech Stack

- HTML5
- Tailwind CSS
- DaisyUI
- Vanilla JavaScript (ES6+)
- Web Speech API
- Programming Hero Open API

## API Reference

| Purpose | Endpoint |
| --- | --- |
| Get all levels | `https://openapi.programming-hero.com/api/levels/all` |
| Get words by level | `https://openapi.programming-hero.com/api/level/{levelNo}` |
| Get word details | `https://openapi.programming-hero.com/api/word/{id}` |
| Get all words | `https://openapi.programming-hero.com/api/words/all` |

## Project Structure

```text
English-Janala/
|-- assets/
|   |-- Images/
|-- script/
|   `-- script.js
|-- style/
|   `-- style.css
|-- English-Janala.fig
|-- index.html
`-- README.md
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Khalid-Sifullah-Siam/English-Janala.git
```

2. Move into the project folder:

```bash
cd English-Janala
```

3. Run the project with a static server such as VS Code Live Server.

## Environment Variables

This project does not require any environment variables for local setup because it is a frontend-only static application.

## How It Works

- The app fetches lesson data and renders lesson buttons dynamically.
- Clicking a lesson loads the related vocabulary cards from the API.
- Users can search vocabulary globally using the search box.
- Each card supports pronunciation playback and a details modal.
- The modal displays additional information including example usage and synonyms.

## Design Resource

- Figma source included in the project: `English-Janala.fig`

## Challenges Faced

- Managing asynchronous API requests while keeping the interface responsive
- Handling empty vocabulary results and missing data without breaking the UI
- Keeping lesson filtering, word details, pronunciation, and search behavior organized in vanilla JavaScript

## Lessons Learned

- How to build a dynamic data-driven interface using `fetch()` and DOM manipulation
- How to improve user experience with loading states, modal details, and active button states
- How to use the Web Speech API to add pronunciation support in a practical way

## Future Improvements

- Add a saved words or favorite vocabulary feature
- Add better search behavior such as instant filtering or debounced search
- Improve error handling for failed API requests
- Add user progress tracking and lesson completion features

## Author

- Khalid Sifullah Siam
- GitHub: [Khalid-Sifullah-Siam](https://github.com/Khalid-Sifullah-Siam)

## License

This project currently does not include a `LICENSE` file. If you plan to reuse or distribute it, adding a clear license would be a good next step.

## Project Photos

Below are the latest project photos from the `assets/Images` folder, arranged serially.

**1. Project Photo 1**

<img src="./assets/Images/Screenshot (74).png" alt="Project Photo 1" width="800" />

**2. Project Photo 2**

<img src="./assets/Images/Screenshot (75).png" alt="Project Photo 2" width="800" />

**3. Project Photo 3**

<img src="./assets/Images/Screenshot (76).png" alt="Project Photo 3" width="800" />

**4. Project Photo 4**

<img src="./assets/Images/Screenshot (77).png" alt="Project Photo 4" width="800" />

**5. Project Photo 5**

<img src="./assets/Images/Screenshot (78).png" alt="Project Photo 5" width="800" />

**6. Project Photo 6**

<img src="./assets/Images/Screenshot (79).png" alt="Project Photo 6" width="800" />

**7. Project Photo 7**

<img src="./assets/Images/Screenshot (80).png" alt="Project Photo 7" width="800" />
