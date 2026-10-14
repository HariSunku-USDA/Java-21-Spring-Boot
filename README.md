<div align="center">

# 🎲 Soc Ops

### Turn “nice to meet you” into a game.

**Social Bingo for in-person mixers, classrooms, and team events.**
Find people who match the prompts, mark your squares, and be the first to get five in a row.

<p>
  <a href="#-quick-start">Quick start</a> ·
  <a href="#-how-it-works">How it works</a> ·
  <a href="workshop/GUIDE.md">Lab guide</a>
</p>

🌐 [Português (BR)](README.pt_BR.md) · [Español](README.es.md)

![Java 21](https://img.shields.io/badge/Java-21-ED8B00?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.4-6DB33F?logo=springboot&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue)

</div>

---

## ✨ Why Soc Ops?

The best icebreakers get people moving. Soc Ops replaces awkward introductions with a simple shared mission: **talk to someone, discover a match, and complete your board**.

- 🧩 **Low friction** — a fresh 5×5 board is ready in one click.
- 🤝 **Built for conversation** — every square is a reason to meet someone new.
- 🏆 **Instant feedback** — mark matches and get a celebratory BINGO moment.
- 💾 **Pick up where you left off** — the current board is restored in your browser.
- 📱 **Works where the people are** — a responsive, touch-friendly interface for phones and laptops.

## 🎯 How it works

1. **Start a game** to generate a board of conversation prompts.
2. **Find a match** by talking to people in the room.
3. **Tap a square** when someone fits its prompt.
4. **Complete a line** of five squares horizontally, vertically, or diagonally.
5. **Celebrate the BINGO!** 🎉

## 🚀 Quick start

### Prerequisites

- [Java 21 JDK](https://adoptium.net/) or newer
- [Apache Maven 3.9+](https://maven.apache.org/) — or use the included Maven Wrapper

### Run locally

```bash
git clone https://github.com/HariSunku-USDA/Java-21-Spring-Boot.git
cd Java-21-Spring-Boot/socops
./mvnw spring-boot:run
```

Open [http://localhost:8080](http://localhost:8080), press **Start Game**, and let the introductions begin.

### Build and test

```bash
./mvnw clean package
./mvnw test
```

## 🧰 Built with

| Layer | Technology |
| --- | --- |
| Application | Java 21 + Spring Boot 3.4 |
| Web layer | Spring MVC + Thymeleaf |
| UI | HTML, CSS utility classes, and vanilla JavaScript |
| State | Browser `localStorage` for in-progress games |
| Delivery | GitHub Actions + GitHub Pages for the workshop guide |

## 📚 Learn by building it

Soc Ops is also a hands-on lab for modern, design-first development with coding agents. Follow the guided path from idea to finished game:

| Part | Focus |
| --- | --- |
| [00](workshop/00-overview.md) | Overview and checklist |
| [01](workshop/01-setup.md) | Setup and context engineering |
| [02](workshop/02-design.md) | Design-first frontend |
| [03](workshop/03-quiz-master.md) | Custom quiz master |
| [04](workshop/04-multi-agent.md) | Multi-agent development |
| [05](workshop/05-complete.md) | Complete implementation |

> Prefer a single starting point? **[Open the complete lab guide →](workshop/GUIDE.md)**

## 🤝 Contributing

Have a great prompt for a mixer? Found a way to make the game more welcoming? Read [CONTRIBUTING.md](CONTRIBUTING.md) and help make the next conversation easier to start.

## 📄 License

Soc Ops is available under the [MIT License](LICENSE).
