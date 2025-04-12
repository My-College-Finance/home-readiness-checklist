# My College Finance - Homeownership Readiness Checklist (V2)

[![GitHub Pages Deploy](https://img.shields.io/github/deployments/My-College-Finance/home-readiness-checklist/github-pages?label=Live%20Tool&style=flat-square&logo=github)](https://my-college-finance.github.io/home-readiness-checklist/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT)

An interactive web application by **[My College Finance](https://mycollegefinance.com/)** designed to help users assess their financial preparedness for buying a home through a multi-stage checklist, affordability calculator, and loan quiz.

---

## Live Demo & Access

Assess your homeownership readiness online:

🚀 **[Launch Homeownership Readiness Tool](https://my-college-finance.github.io/home-readiness-checklist/)** 🚀

---

## Features

*   **Multi-Stage Assessment:** Guides users through four key stages:
    1.  **Readiness Checklist:** Evaluates income stability, credit health, savings (down payment, closing costs, emergency fund), cost understanding, and awareness of homebuyer programs. Calculates a readiness score. Includes a live DTI calculation.
    2.  **Affordability Calculator:** Estimates potential mortgage payments (PITI), calculates the resulting back-end DTI based on user inputs (income, debts, home price, rate, etc.), and visualizes the monthly payment breakdown and loan amortization using Chart.js.
    3.  **Loan Type Quiz:** Suggests potentially suitable mortgage types (Conventional, FHA, VA, USDA) based on credit score range, military status, property location, down payment, and need for assistance.
    4.  **Summary Report:** Consolidates the readiness score, affordability analysis, loan recommendation, and provides dynamically generated, actionable next steps.
*   **Informative Tooltips:** Help icons (ⓘ) provide context and definitions for each input field and question.
*   **FAQ & Glossary Panels:** Slide-out side panels offer frequently asked questions and definitions of common mortgage/real estate terms, with search functionality.
*   **Theme Toggle:** Switch between Light and Dark modes for user comfort.
*   **PDF Export (Summary Only):** Download a clean, print-friendly PDF report containing *only* the final Summary page (Stage 4) using the browser's native print-to-PDF functionality. Input fields, buttons, and charts are excluded from the print view.
*   **Progress Tracking:** Visual progress bar and active step indicators show users where they are in the process.
*   **Local State Saving:** User progress and inputs are automatically saved in the browser's `localStorage` for convenience. Includes a manual save button.
*   **Responsive Design:** Adapts for optimal use on desktops, tablets, and mobile devices.

## How to Use

1.  **Online:** Access the tool via the [**Launch Link**](https://my-college-finance.github.io/home-readiness-checklist/) above. Your progress will be saved in *that browser's* localStorage.
2.  **Locally:** Download `Home Readiness Checklist v3.2.htm` and open it in your browser. Progress will be saved locally.
3.  **Embedding:** Use the following iframe code (replace the `src` if your URL differs):

     ```html
    <iframe
        src="https://my-college-finance.github.io/home-readiness-checklist/"
        width="100%"
        height="900" /* Adjust height as needed, tool can be long */
        style="border: 1px solid #ccc;"
        title="Homeownership Readiness Tool"
        allowfullscreen>
    </iframe>
    ```

## Technology Stack

*   HTML5
*   CSS3 (Flexbox, Grid, CSS Variables for Theming)
*   Vanilla JavaScript (ES6+) (DOM Manipulation, Calculations, Event Handling, State Management)
*   Chart.js (for Affordability Visualizations)
*   Browser `localStorage` API (for Saving User Progress)

## Source File

The entire application is contained within the single `Home Readiness Checklist v3.2.htm` file.

## Contributing

Feedback and contributions are welcome!

*   Open an [**Issue**](https://github.com/My-College-Finance/home-readiness-checklist/issues) for bugs or feature ideas.
*   Submit a [**Pull Request**](https://github.com/My-College-Finance/home-readiness-checklist/pulls) with code improvements.

## License

Licensed under the MIT License.

---

Provided by **[My College Finance](https://mycollegefinance.com/)**
