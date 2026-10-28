<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=450A0A,DC2626,F87171&height=220&section=header&text=Blackjack%20Simulation%20%28Java%20OOP%29&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=Polymorphic%20Card%20Suits%2C%20Blackjack%20Logic%2C%20and%20Game%20Loops&descSize=16&descAlignY=62&descAlign=50" width="100%" alt="Blackjack Simulation (Java OOP) Header Banner"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/> <img src="https://img.shields.io/badge/Design-Polymorphism%20%26%20Inheritance-red?style=for-the-badge" alt="Inheritance"/>
</p>


## 📌 Table of Contents
- [📖 Executive Summary](#-executive-summary)
- [✨ Key Features & Capabilities](#-key-features--capabilities)
- [🏗️ System Architecture & Workflow](#️-system-architecture--workflow)
- [🛠️ Tech Stack Breakdown](#️-tech-stack-breakdown)
- [⚙️ Reproducible Quickstart & Setup](#️-reproducible-quickstart--setup)
- [📂 Project Directory Layout](#-project-directory-layout)
- [👩‍💻 Author & Contributions](#-author--contributions)

---

## 📖 Executive Summary
### Problem Statement
Implementing traditional casino card games requires modeling card hierarchies and suit-specific behavior through clean object-oriented inheritance.

### Motivation & Solution Overview
A Java simulation of Blackjack implementing an inheritance hierarchy with specialized card classes (`HeartCard`, `SpadeCard`, `ClubCard`, `DiamondCard`) extending a base `Card` class.

---

## ✨ Key Features & Capabilities
- **Class Inheritance:** Subclassed suits extending base `Card` entities.
- **Game State Logic:** Hand evaluation, bust detection, and dealer turn resolution.
- **Clean Java Console Interface:** Interactive game loop.

---

## 🏗️ System Architecture & Workflow
```mermaid
classDiagram
    class Card {
        #int value
        #String name
        +getValue()
    }
    class HeartCard {
    }
    class SpadeCard {
    }
    class ClubCard {
    }
    class DiamondCard {
    }
    Card <|-- HeartCard
    Card <|-- SpadeCard
    Card <|-- ClubCard
    Card <|-- DiamondCard
```

---

## 🛠️ Tech Stack Breakdown
| Category | Technologies |
|---|---|
| **Language** | Java |
| **Concepts** | Inheritance, Polymorphism, Encapsulation, Console Game Loop |

---

## ⚙️ Reproducible Quickstart & Setup
```bash
git clone https://github.com/Bhumikaravi/Bhumika_BlackJack.git
cd Bhumika_BlackJack
javac *.java
java Main
```

---

## 📂 Project Directory Layout
```text
Bhumika_BlackJack/
├── Card.java
├── ClubCard.java
├── DiamondCard.java
├── HeartCard.java
├── SpadeCard.java
├── Main.java
└── README.md
```

---

## 👩‍💻 Author & Contributions
Developed by **Bhumika Ravi** ([@Bhumikaravi](https://github.com/Bhumikaravi)), Bachelor of Computer Applications (BCA) at **Alliance University, Bengaluru**.

- 💻 **GitHub Profile:** [github.com/Bhumikaravi](https://github.com/Bhumikaravi)
- 🔗 **LinkedIn:** [linkedin.com/in/bhumika-ravi-b5a01b326](https://www.linkedin.com/in/bhumika-ravi-b5a01b326/)
- 📬 **Email Contact:** [bhumikaravi2006@gmail.com](mailto:bhumikaravi2006@gmail.com)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=450A0A,DC2626,F87171&height=100&section=footer" width="100%" alt="Footer Banner"/>
</p>
