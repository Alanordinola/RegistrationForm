[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Alanordinola/RegistrationForm">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  
<h3 align="center">Registration Form</h3>

<p aling="center">
A sleek, accessible form with dark/light mode toggle and smooth animations

<a href="https://github.com/Alanordinola/RegistrationForm"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Alanordinola/RegistrationForm">View Demo</a>
    &middot;
    <a href="https://github.com/Alanordinola/RegistrationForm/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/Alanordinola/RegistrationForm/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)


This **Interactive Registration Form** transforms the traditional sign-up process into an engaging user experience. Originally developed as a FreeCodeCamp project, I've enhanced it with:

- Dynamic Dark/Light Mode - Users can toggle themes with system preference detection
- Custom Styling - Elegant form controls with smooth animations
- Built-in Validation - HTML5 validation with visual feedback

**Key Features:**

- Dynamic Theme Switching - Toggle between light/dark mode.
- Form Validation - Built-in HTML5 validation with custom patterns
- Smooth Animations - Pleasant hover and focus effects
- Persistent Preferences	Remembers user's theme choice via localStorage


This project demonstrates how to apply progressive improvement principles in common projects



<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![HTML5][HTML5-shield]][HTML5-url]
* [![CSS3][CSS3-shield]][CSS3-url]
* [![JavaScript][JavaScript-shield]][JavaScript-url]
* [![Poppins][Poppins-shield]][Poppins-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

Launch Registration Form in minutes! Follow these simple steps to set up the project locally.

### Prerequisites

- Any modern browser (Chrome, Firefox, Edge)
- Git (optional, for version control)
- Code editor (VS Code recommended)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/RegistrationForm.git
   ```

2. **Navigate to project folder:**
```sh
cd RegistrationForm
```

3. **Open in browser:**

Double-click index.html or run
```bash

start index.html # Windows
open index.html # macOS
xdg-open index.html # Linux
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Explore the registration form's interactive features:


1. **Theme Switching**  
   Toogle between light/dark mode using the button in the top-right corner. Your preference is automatically saved for future visits.

2. **Form Navigation**  
  - Fields are organized into logical sections (Basic Info, Account Type, Additional Info)
  - Required fields are marked with HTML5 validation

3. **Interactive Elements**
  

  - **Radio buttons:** Select account type (Personal/Business)
  - **File upload:** Click to add a profile picture
  - **Dropdown menu:** Choose how you heard about us
  - **Textarea:** Share your bio with character counter

4. **Form Validation**
   ``` html 
   <input pattern="[a-z0-5]{8,}" required>  <!-- Password requirements -->
   <input type="email" required>           <!-- Email format -->
   <input type="number" min="13" max="120"> <!-- Age restrictions -->
    ```


5. **Customize the guide.**
   Modify the theme colors in ` styles.css:`
   ```css
   :root {
   --primary: #6c5ce7; /* Main brand color */
   --bg: #f5f6fa;     /* Light mode background */
   }
   .dark-mode {
   --primary: #a29bfe; 
   --bg: #2d3436;     /* Dark mode background */
   }
   ```

6. **Submission.**
    Click the animated Submit → button to send your data to the demo endpoint.
    
    Try submitting with invalid fields to see the validation messages!
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ]  **UI/UX Enhancements**
  - [x]  Light/dark theme toggle (implemented)
  - [ ]  Additional theme presets (high contrast, midnight)
  - [ ]  Field transition animations
  - [ ]  Micro-interactions for form controls
- [ ]  **Core Functionality**
  - [x]  Basic HTML5 form validation
  - [ ]  Real-time validation with visual feedback
  - [x]  Fully responsive layout (completed)
  - [ ]  Progressive form autosave
- [ ]  **User Experience**
  - [ ]  Multi-step progress indicator
  - [ ]  Context-aware error messages
  - [ ]  Smart field suggestions
  - [x]  Keyboard navigation support
- [ ]  **Technical Improvements**
  - [x]  User preference persistence (localStorage)
  - [ ]  Backend API integration
  - [ ]  Jest unit test suite
  - [ ]  Performance benchmarking


See the [open issues](https://github.com/Alanordinola/RegistrationForm/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

####  Reporting Issues
Open an [issue](https://github.com/AlanOrdinola/RegistrationForm/issues) with:
- `bug` for unexpected behavior
- `enhancement` for feature requests
- `design` for UI/UX improvements

####  Code Contributions
1. Fork the Repository
2. Clone your Fork (`git clone https://github.com/your-username/RegistrationForm.git`)

3. Create your Feature Branch (`git checkout -b feature/your-feature`)

4. Commit your Changes (`git commit -m "feat: Add cold brew section"`)

5. Push to your Branch (`git push origin feature/your-feature`)

6. Open a Pull Request

### Top contributors:

<a href="https://github.com/Alanordinola/RegistrationForm/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Alanordinola/RegistrationForm" alt="contrib.rocks image" />
</a>

<!-- LICENSE -->
## License

Distributed under the project_license. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Alan Ordinola - [Linkedin](https://www.linkedin.com/in/alan-ordinola-10026a196/)

Project Link: [https://github.com/Alanordinola/RegistrationForm](https://github.com/Alanordinola/RegistrationForm)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Hecho con ❤️ para el [curso de freeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/)  
[![FCC](https://img.shields.io/badge/🚀_Estudiando_en_FCC-0A0A23)](https://www.freecodecamp.org/)

[Best-README-Template](https://github.com/othneildrew/Best-README-Template) - Por la estructura base de este README

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Alanordinola/RegistrationForm.svg?style=for-the-badge&color=green
[contributors-url]: https://github.com/Alanordinola/RegistrationForm/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Alanordinola/RegistrationForm.svg?style=for-the-badge&color=blue
[forks-url]: https://github.com/Alanordinola/RegistrationForm/network/members
[stars-shield]: https://img.shields.io/github/stars/Alanordinola/RegistrationForm.svg?style=for-the-badge&color=yellow
[stars-url]: https://github.com/Alanordinola/RegistrationForm/stargazers
[issues-shield]: https://img.shields.io/github/issues/Alanordinola/RegistrationForm.svg?style=for-the-badge&color=red
[issues-url]: https://github.com/Alanordinola/RegistrationForm/issues
[license-shield]: https://img.shields.io/github/license/Alanordinola/RegistrationForm.svg?style=for-the-badge&color=green
[license-url]: https://github.com/Alanordinola/RegistrationForm/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=0A66C2
[linkedin-url]: https://www.linkedin.com/in/alan-ordinola-10026a196/
[product-screenshot]: images/screenshot.png
[HTML5-shield]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[HTML5-url]: https://developer.mozilla.org/en-US/docs/Web/HTML
[CSS3-shield]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
[CSS3-url]: https://developer.mozilla.org/en-US/docs/Web/CSS
[JavaScript-shield]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[JavaScript-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[Poppins-shield]: https://img.shields.io/badge/Poppins-FF6B6B?style=for-the-badge&logo=google-fonts&logoColor=white
[Poppins-url]: https://fonts.google.com/specimen/Poppins
