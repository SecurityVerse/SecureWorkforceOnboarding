# Secure Workforce Onboarding - Cybersecurity Training

## Description

This repository contains the source code and assets for a bilingual (Spanish/English) cybersecurity onboarding presentation designed for new employees. The goal of this training is to provide foundational knowledge on cybersecurity, common threats, best practices, and incident response to help create a more secure workforce.

The presentation is a single HTML file that functions as an interactive slideshow, including:
* Coverage of key cybersecurity concepts (CIA Triad).
* Information on applicable (generic) data protection principles.
* Overview of common threat actors and their methodologies (MITRE ATT&CK).
* Examples of prevalent threats like phishing, vishing, malware, and ransomware.
* Actionable advice on secure passwords, Multi-Factor Authentication (MFA), VPN usage, Zero Trust principles, and recognizing social engineering.
* Clear "Do Nots" in cybersecurity.
* Guidelines for incident response.
* Language toggle functionality (English/Spanish).
* Per-slide timer.
* Fullscreen mode.

## Features

* **Bilingual Content:** Supports English and Spanish, with a toggle button to switch languages. Spanish version includes common English technical terms.
* **Interactive Slideshow:** Built as a single HTML page with JavaScript for navigation, slide transitions, and language switching.
* **Timed Sections:** Includes a timer for each slide to help manage presentation pacing (times are configurable in the script).
* **Fullscreen Mode:** Allows for an immersive presentation experience.
* **Modern Design:** Styled with CSS for a professional and engaging visual appearance.
* **Image Integration:** Designed to incorporate relevant images for each section to enhance learning.

## File Structure

* `index.html` (o `cybersecurity_onboarding.html`): The main presentation file.
* `/images/`: This directory should contain all the image files used in the presentation (e.g., `1.png`, `2.png`, ..., `21.png`, `CIA.jpg`).

## How to Use

1.  **Clone or Download the Repository:**
    ```bash
    git clone [https://github.com/SecurityVerse/SecureWorkforceOnboarding.git](https://github.com/SecurityVerse/SecureWorkforceOnboarding.git)
    cd SecureWorkforceOnboarding
    ```
    Or download the ZIP and extract it.

2.  **Prepare Images:**
    * Ensure you have all the necessary images (21 images, named `1.png` through `21.png` or your preferred format, plus `CIA.jpg` or your chosen image for the CIA Triad).
    * Place them inside a folder named `images` in the root of the project directory.

3.  **Open the HTML File:**
    * Open the main HTML file (e.g., `index.html` or `cybersecurity_onboarding.html`) in any modern web browser (like Chrome, Firefox, Edge, Safari).

4.  **Navigate the Presentation:**
    * Use the "Next" and "Previous" buttons.
    * Use the navigation dots on the right side.
    * Use keyboard arrow keys (Right/Left) or Spacebar.
    * Use number keys (1-9) to jump to a specific slide (up to slide 9).

5.  **Switch Language:**
    * Use the "Switch to English" / "Cambiar a Español" button located at the bottom/top right of the screen.

6.  **Toggle Fullscreen:**
    * Use the "Fullscreen" / "Completa" button.

## Customization

* **Content:** Edit the text directly within the `<span>` tags with classes `lang-es` and `lang-en` in the HTML file for each slide.
* **Images:** Replace images in the `/images/` folder. Ensure the paths in the HTML file match your image names and locations. The current setup assumes images are named `1.png` to `21.png` and `CIA.jpg`.
* **Slide Timings:** Adjust the `slideTimes` array in the `<script>` section at the bottom of the HTML file. Times are in seconds.
* **Styling:** Modify the CSS within the `<style>` tags in the `<head>` section of the HTML file.

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details. (You would add a LICENSE file if you choose this, GitHub can help generate one).

Or, if you chose no license initially:

This project is provided as-is. All rights are reserved by the owner unless otherwise specified.

## Contributions

Contributions, issues, and feature requests are welcome. Please open an issue to discuss what you would like to change or add.

---

*This README provides a general guide. You can customize it further to suit your specific needs and how you intend for others to use this project.*
