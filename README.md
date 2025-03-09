# Amazigh Quran Translation (ⵜⴰⵙⵓⵖⵍⵜ ⵏ ⵉⵏⵓⵎⴰⴽ ⵏ ⵍⵇⵓⵔⴰⵏ)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Hosted-green.svg)](https://abdelhaqueidali.github.io/Amazigh-Quran-Translation/)

New version v2 : https://abdelhaqueidali.github.io/Amazigh-Quran-Translation/v2/webpagev2.html

This repository contains a digital, interactive version of Jouhadi Lahoussine's Amazigh (Tamazight) translation of the meanings of the Holy Quran.  The project aims to make this valuable translation more accessible and to present it beautifully re-written in the Tifinagh script.

**Live Website:**  https://abdelhaqueidali.github.io/Amazigh-Quran-Translation/

## Features

*   **Parallel Display:** Presents the Amazigh translation alongside the original Arabic text of the Quran.  This allows users to easily compare and understand the intended meanings.
*   **Tifinagh Script:** The Amazigh translation is displayed using the Tifinagh script, preserving the linguistic and cultural heritage of the Amazigh people.  A fallback font (Noto Sans Tifinagh) is included to ensure proper rendering.
*   **Clear Formatting:** Uses distinct fonts (Amiri for Arabic and Noto Sans Tifinagh for Amazigh) and styling for improved readability and visual appeal.
*   **Verse Numbering:**  Clearly indicates verse numbers for both the Arabic and Amazigh text, making navigation and referencing easy.
*   **Highlighting:** Important words or phrases in the Amazigh translation are highlighted (using `**bold text**` in the source file, rendered with a yellow background).
*   **Responsive Design:**  The layout adapts to different screen sizes, making it usable on desktops, tablets, and mobile phones.
*   **Dynamic Loading:** The Quran text is loaded dynamically from text files (`quran.txt` for Amazigh and `quranunicode.txt` for Arabic), making it easy to update and expand the content.  This also improves the initial page load time.
*   **Surah and Verse Structure:**  The code correctly parses the text files to identify and display Surahs (chapters) and Ayahs (verses).
*   **Bismillah Handling:**  The opening phrase ("Bismillah...") is displayed correctly for each Surah.
* **Links to original translation books**:  links to scans of the physical book, so the user can see the authenticity and original source of the translation.

## Project Structure

*   **`index.html`:**  The main HTML file that structures the page and contains the JavaScript code.
*   **`quran.txt`:**  A text file containing the Amazigh translation. The format is:
    *   Surah Number (on a separate line)
    *   Surah Title (enclosed in square brackets `[]`)
    *   Bismillah (if applicable, on the line immediately following the title)
    *   Verses, each starting with the verse number followed by a space and then the verse text.
    *   Bold words are indicated by `**word**`
    *   Empty lines are ignored.
*   **`quranunicode.txt`:** A text file containing the original Arabic text of the Quran, formatted similarly to `quran.txt`.
* **`README.md`:** This file, providing an overview of the project.

## How to Use

1.  **Online:** Simply visit the GitHub Pages link: [https://abdelhaqueidali.github.io/Amazigh-Quran-Translation/](https://abdelhaqueidali.github.io/Amazigh-Quran-Translation/)
2.  **Locally:**
    *   Clone this repository: `git clone https://github.com/AbdelhaqIdali/Amazigh-Quran-Translation.git`
    *   Open `index.html` in your web browser.

## Data Format (quran.txt and quranunicode.txt)

The text files follow a specific format:
Use code with caution.
Markdown
1 <-- Surah Number<br>
[Surah Title] <-- Surah Title<br>
Bismillah... <-- Opening (if applicable)<br>
1 Verse text... <-- Verse 1<br>
2 Verse text... <-- Verse 2<br>
...

2 <-- Next Surah Number<br>
[Next Surah Title]<br>
...

*   Each Surah begins with its number on a new line.
*   The Surah title is enclosed in square brackets.
*   The Bismillah (opening phrase) follows the title, if present.  If the opening spans multiple lines, include all lines before the first numbered verse.
*   Each verse starts with its number, followed by a space, and then the verse text.
*   Empty lines are ignored.

## Important Notes

*   **Translation Purpose:** The translations are provided *solely* for understanding the *meanings* of the Quran.  They are not a replacement for the original Arabic text, which holds the divine revelation.  Always refer to the Arabic Quran for recitation and religious rulings.
*   **Accuracy:** The project strives for accuracy in displaying the translation.  However, there may be minor errors.  Users are encouraged to report any discrepancies.
*   **Ongoing Work:** The re-written version in the Amazigh script is a work in progress. Only some Hizbs are available so far, and the text is still being reviewed for errors.

## Contributing

Contributions are welcome!  If you find any errors, have suggestions for improvement, or want to help complete the Tifinagh transcription, please:

1.  Fork the repository.
2.  Make your changes.
3.  Submit a pull request.

Specific areas for contribution include:

*   **Reviewing and correcting the Amazigh text:** Ensure the accuracy of the Tifinagh transcription.
*   **Adding missing Surahs:**  Complete the transcription of the remaining Surahs.
*   **Improving the code:** Refactor, optimize, or add new features.
*   **Adding CSS styles**: To enhance the looks.

## Credits

*   **Original Translation:** Jouhadi Lahoussine
*   **Original Book Scans Available At:**
    *   [Jouhadi Lahoussine's Website](https://www.jouhadilahoussine.com/publications/%D8%A7%D9%84%D9%82%D8%B1%D8%A2%D9%86-%D8%A7%D9%84%D9%83%D8%B1%D9%8A%D9%85-%D8%AA%D8%B1%D8%AC%D9%85%D8%A9-%D9%85%D8%B9%D8%A7%D9%86%D9%8A%D9%87-%D8%A5%D9%84%D9%89-%D8%A7%D9%84%D9%84%D8%BA%D8%A9-%D8%A7%D9%84%D8%A3%D9%85%D8%A7%D8%B2%D9%8A%D8%BA%D9%8A%D8%A9/8Ias6M02wrtAmU4lZYVd)
    *   [Internet Archive](https://archive.org/details/quran-jouhadi/)
* **Fonts**:
    *   [Amiri](https://fonts.google.com/specimen/Amiri)
    *   [Noto Sans Tifinagh](https://fonts.google.com/noto/specimen/Noto+Sans+Tifinagh)
