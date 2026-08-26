# 🔐 PassCheck — Password Security Analyzer

A client-side password strength analyzer that evaluates password security and gives users actionable feedback to make better password choices.

## 🎯 Objective

Help users understand how strong (or weak) their passwords are, and why — based on real security factors used by attackers and cracking tools.

## ✨ Features

- **Real-time analysis** as you type
- **Multi-factor evaluation**:
  - Length
  - Character variety (uppercase, lowercase, digits, symbols)
  - Estimated entropy (bits)
  - Common/leaked password detection
  - Sequential patterns (e.g. `abc`, `321`)
  - Keyboard-walk patterns (e.g. `qwerty`, `asdf`)
  - Repeated character runs
- **Clear strength verdict** (Weak → Strong) with a visual score
- **Tailored recommendations** for improving weak passwords
- **Built-in test cases** to try instantly
- **Show/Hide toggle** for the password field
- **Privacy-first**: nothing is stored, logged, or sent over the network — all analysis runs locally in the browser

## 🛠️ Tech Stack

- Vanilla JavaScript
- HTML5 / CSS3
- No external libraries or dependencies for the analysis logic

## 🚀 Running Locally
## 🔗 Live Demo
[Try PassCheck here](paste-your-stackblitz-url-here)

```bash
npm install
npm run dev
