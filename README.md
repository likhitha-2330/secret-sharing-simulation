# Secret Sharing Simulation

Secret Sharing Simulation is an interactive web-based educational application that visually demonstrates the core concepts of **Rational Secret Sharing** and **Multiparty Computation**. Through animated simulations and interactive canvases, users can explore threshold secret sharing, coalition attacks, randomized protocols, deviation behavior, information checking, and robustness conditions.

The project is inspired by the research paper **"Distributed Computing Meets Game Theory: Robust Mechanisms for Rational Secret Sharing and Multiparty Computation"** and is designed to simplify complex distributed computing concepts through visualization.

---

# Features

- Interactive threshold secret sharing simulation
- Coalition attack visualization
- Alpha (α) protocol round simulation
- Deviation analysis with dishonest participants
- Information Checking Protocol (ICP) demonstration
- (k, t)-Robustness visualization
- Light/Dark mode support
- Mobile touch support
- Fully client-side application
- No installation or backend required

---

# Tech Stack

### Frontend

- HTML5
- CSS3
- JavaScript

### Graphics

- HTML5 Canvas API

### Runtime

- Modern Web Browser

---

# Project Structure

```
secret-sharing-simulation/
│
├── index.html
├── README.md
├── .gitignore
└── Distributed Computing Meets Game Theory - Robust Mechanisms for Rational Secret Sharing and Multiparty Computation.pdf
```

---

# Simulation Modules

The application consists of six interactive simulations.

## 1. Threshold Secret Sharing

Demonstrates how a secret is divided into multiple shares.

Users can:

- Select random shares
- Attempt reconstruction
- Observe threshold requirements

Concept:

A secret can only be reconstructed when the minimum required number of shares is available.

---

## 2. Coalition Attack

Illustrates how colluding participants attempt to recover the secret.

Users can:

- Form coalitions
- Launch attacks
- Observe successful and failed reconstructions

Concept:

Shows why threshold values are important for protecting secrets.

---

## 3. Alpha (α) Protocol

Simulates randomized protocol rounds.

Users can:

- Advance protocol rounds
- Observe mediator behavior
- Study probabilistic secret revelation

Concept:

The α-protocol uses randomized decisions to encourage honest behavior among rational participants.

---

## 4. Deviation Analysis

Demonstrates what happens when a participant sends incorrect information.

Users can:

- Trigger deviations
- Observe protocol behavior
- Compare honest and dishonest execution

Concept:

Analyzes the impact of malicious or rational deviations during protocol execution.

---

## 5. Information Checking Protocol (ICP)

Shows how verification tags help detect dishonest participants.

Users can:

- Send fake shares
- Verify messages
- Detect lies

Concept:

ICP ensures integrity by attaching verification information to secret shares.

---

## 6. (k, t)-Robustness

Visualizes robustness conditions for distributed protocols.

Users can:

- Adjust faulty participants
- Adjust colluding participants
- Verify robustness conditions

Concept:

Demonstrates when a protocol remains secure under faulty and colluding participants.

---

# Installation

## Clone Repository

```bash
git clone https://github.com/likhitha-2330/secret-sharing-simulation.git

cd secret-sharing-simulation
```

---

# Run the Project

Since the project is completely client-side, no installation is required.

Simply open:

```
index.html
```

using any modern web browser.

---

## Alternatively

Run a local server:

```bash
python -m http.server 8000
```

Open:

```
http://localhost:8000
```

---

# User Interface

The application includes:

- Six interactive simulation tabs
- Animated canvas visualizations
- Interactive buttons
- Status information panel
- Theme switcher
- Mobile touch support

---

# Customization

All application logic is implemented inside:

```
index.html
```

Developers can modify simulation parameters such as:

### Threshold Sharing

```javascript
const N = 5;
const M = 3;
```

---

### Coalition Attack

```javascript
const N = 6;
const M = 3;
```

---

### Alpha Protocol

```javascript
const ALPHA = 0.3;
```

---

### Deviation Analysis

```javascript
const N = 5;
const M = 3;
```

---

### Information Checking Protocol

Detection probability is based on:

```javascript
1 - (1 / 2089)
```

---

### (k, t)-Robustness

```javascript
const N = 10;
const M = 4;
```

---

# Educational Objectives

This project helps learners understand:

- Secret Sharing
- Threshold Cryptography
- Multiparty Computation
- Rational Players
- Coalition Formation
- Information Checking
- Distributed Computing
- Fault Tolerance
- Protocol Robustness
- Game Theory

---

# Technologies Used

- HTML5
- CSS3
- JavaScript
- HTML5 Canvas API

---

# Future Improvements

- Separate CSS and JavaScript into dedicated files
- Responsive layout improvements
- Adjustable simulation parameters using UI controls
- Cryptographically accurate Shamir Secret Sharing implementation
- Export simulation results
- GitHub Pages deployment
- Accessibility improvements
- Keyboard navigation
- Animation speed controls
- Unit testing

---

# How It Works

Each simulation represents a different distributed computing protocol using animated participants, messages, and visual feedback.

The application illustrates protocol behavior instead of implementing production-ready cryptographic algorithms, making it ideal for teaching and demonstrations.

---

# References

This project is based on concepts presented in:

**Distributed Computing Meets Game Theory: Robust Mechanisms for Rational Secret Sharing and Multiparty Computation**

The reference research paper is included in this repository.

---

# Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

Suggestions include:

- Improving visualizations
- Adding new protocol simulations
- Enhancing accessibility
- Optimizing animations
- Improving educational content

---

# License

This repository currently does not include a license.

For open-source distribution, adding the **MIT License** is recommended.

---

# Author

**Likhitha Pogaku**

Computer Science Engineering Student

Passionate about Distributed Computing, Cryptography, Artificial Intelligence, and Interactive Educational Applications.

---

# Acknowledgements

- Distributed Computing Research Community
- Rational Secret Sharing Research
- HTML5 Canvas API
- JavaScript
- Open Source Community
