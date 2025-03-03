# Unit-Converter

A React-based unit conversion tool supporting multiple categories, built with JSX, HTML, and CSS. It features real-time bidirectional conversion, dynamic dropdowns, and a dark mode toggle using React state management.

Features
1. Supported Conversion Types
Length: Meters ⇄ Feet
Weight: Kilograms ⇄ Pounds
Temperature: Celsius ⇄ Fahrenheit
Area: Square Meters ⇄ Square Feet

3. Interactive UI
Dropdown for conversion type: id="conversion-type"
Unit selection dropdowns: id="lhs-unit", id="rhs-unit"
Input fields for real-time conversion: id="lhs-input", id="rhs-input"
Dynamic updates: Input in one field automatically updates the other.

4. State Management & Interactivity
React State (useState) manages dark mode and user input.
Controlled components ensure instant recalculations and updates.
Automatic clearing when conversion type changes.

5. Dark Mode Support
Toggle button to switch themes.
State-based styling.
Tech Stack
Frontend: React.js (JSX), HTML, CSS
State Management: React useState, prevState
Rendering: ReactDOM
