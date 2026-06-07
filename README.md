# MBTI Personality Quiz

A modern, responsive, single-page MBTI (Myers-Briggs Type Indicator) personality assessment built with pure HTML, CSS, and JavaScript.

## Overview

This project provides an interactive personality quiz that guides users through 12 carefully crafted questions and determines their MBTI personality type based on their answers. The application features a sleek dark-themed interface, animated transitions, progress tracking, and detailed personality results.

## Features

* ✨ Modern dark UI with animated gradients
* 📱 Fully responsive design
* 📊 Progress tracking during assessment
* 🎯 12 personality-focused questions
* 🧠 Automatic MBTI type inference
* 📈 Personality dimension visualization
* 💪 Personality strengths display
* 📋 One-click result copying
* 🔄 Quiz retake functionality
* ⚡ No frameworks or dependencies required

## MBTI Dimensions Evaluated

The quiz evaluates users across four core MBTI dimensions:

| Dimension  | Options                              |
| ---------- | ------------------------------------ |
| Energy     | Extraversion (E) vs Introversion (I) |
| Perception | Sensing (S) vs Intuition (N)         |
| Judgment   | Thinking (T) vs Feeling (F)          |
| Lifestyle  | Judging (J) vs Perceiving (P)        |

## Supported Personality Types

The application includes profiles for all 16 MBTI personality types:

* INTJ — The Mastermind
* INTP — The Thinker
* ENTJ — The Commander
* ENTP — The Debater
* INFJ — The Counselor
* INFP — The Healer
* ENFJ — The Teacher
* ENFP — The Champion
* ISTJ — The Inspector
* ISFJ — The Protector
* ESTJ — The Executive
* ESFJ — The Provider
* ISTP — The Craftsman
* ISFP — The Composer
* ESTP — The Dynamo
* ESFP — The Performer

## Project Structure

```text
mbti-quiz.html
│
├── HTML Structure
│   ├── Landing Screen
│   ├── Quiz Screen
│   └── Results Screen
│
├── CSS Styling
│   ├── Theme Variables
│   ├── Animations
│   ├── Responsive Layout
│   └── Component Styles
│
└── JavaScript Logic
    ├── Question Management
    ├── Navigation System
    ├── MBTI Calculation
    ├── Result Generation
    └── Clipboard Sharing
```

## Installation

No installation is required.

1. Download the project file.
2. Open `mbti-quiz.html` in any modern web browser.
3. Start the assessment.

## Usage

1. Click **Begin Assessment**.
2. Answer all 12 questions.
3. Navigate through the quiz using the provided controls.
4. View your personality type and detailed results.
5. Copy or share your results.

## Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript (ES6)

## Browser Compatibility

Tested and supported on:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari
* Mobile Browsers

## Customization

### Add New Questions

Edit the `questions` array inside the JavaScript section:

```javascript
{
  dim: "Energy (E/I)",
  q: "Your question here?",
  a: "Option A",
  b: "Option B"
}
```

### Modify Personality Types

Update the `mbti` object to change:

* Type names
* Descriptions
* Strengths
* Color schemes

### Change Theme Colors

Adjust the CSS variables inside `:root`:

```css
:root {
  --accent: #8b5cf6;
  --accent2: #c084fc;
}
```

## Future Improvements

* Save results using Local Storage
* Detailed personality reports
* Social media sharing integration
* Question randomization
* Analytics dashboard
* Multi-language support
* Personality compatibility matching
* Backend database integration

## License

This project is free to use for educational and personal purposes.

## Author: Mubbshra 
