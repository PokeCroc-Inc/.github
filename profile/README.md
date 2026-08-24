# 🐊 PokeCroc Inc.

<p align="center">
  <strong>Building the world of PokeCroc.</strong>
  <br>
  <sub>Server • Client • Content • Web • Infrastructure</sub>
</p>

<p align="center">
  <a href="https://github.com/PokeCroc-Inc">Organization</a>
  •
  <a href="https://github.com/PokeCroc-Inc?tab=repositories">Repositories</a>
  •
  <a href="https://github.com/PokeCroc-Inc/issues">Issues</a>
</p>

---

## 🐊 About PokeCroc

**PokeCroc** is a PokéTibia project focused on building a complete and evolving Pokémon MMORPG experience.

This organization brings together the code, tools, content and infrastructure required to develop and operate the project.

Our goal is simple:

> **Build something we would want to play ourselves.**

From the game server and client to maps, systems, websites, tools and deployment infrastructure, everything is developed with long-term maintainability and scalability in mind.

---

## ⚙️ Our Ecosystem

The PokeCroc ecosystem is organized around several core areas:

| Area                  | Responsibility                                       |
| --------------------- | ---------------------------------------------------- |
| 🧠 **Server**         | Core game logic, systems and networking              |
| 🎮 **Client**         | Game client and player experience                    |
| 🗺️ **Content**       | Pokémon, maps, quests, NPCs, items and world content |
| 🌐 **Web**            | Website, account systems and web services            |
| 🚀 **Infrastructure** | Hosting, deployment, containers and automation       |
| 🛠️ **Tools**         | Internal tools and development utilities             |
| 🧪 **QA**             | Testing, validation and quality assurance            |
| 📚 **Documentation**  | Technical and project documentation                  |

---

## 🏗️ Development

PokeCroc follows a collaborative development workflow.

```text
                 ┌───────────────┐
                 │    Feature    │
                 │     Branch    │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │ Pull Request  │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │ CI / Checks   │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │ Code Review   │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │    Merge      │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │    Release    │
                 └───────────────┘
```

We prefer small, focused changes over large and difficult-to-review pull requests.

### Branches

Typical development branches:

```text
main
develop
feature/*
fix/*
hotfix/*
refactor/*
```

`main` represents production-ready code.

---

## 🧩 Repository Philosophy

Each repository should have a clear responsibility.

Avoid creating repositories simply because a component is convenient to separate.

Before creating a new repository, ask:

* Does this component have an independent lifecycle?
* Does it require different permissions?
* Does it have a different deployment process?
* Would separating it make development easier?
* Can its purpose be clearly explained in one sentence?

If the answer is no, it probably belongs in an existing repository.

---

## 🔐 Security

Security is everyone's responsibility.

Never commit:

```text
API keys
Passwords
Database credentials
Private keys
Access tokens
Production secrets
.env files containing secrets
```

Use GitHub Secrets, environment variables or the appropriate secret-management system.

If you discover a security vulnerability, **do not create a public issue containing sensitive information**.

Report it privately to the project maintainers.

---

## 🤝 Contributions

Contributions are welcome from people who want to help improve PokeCroc.

Before opening a pull request:

1. Make sure you understand the repository's contribution guidelines.
2. Keep changes focused.
3. Test your changes locally.
4. Update documentation when necessary.
5. Do not include unrelated changes.
6. Provide enough context for reviewers to understand the change.

Good pull request:

```text
feat: add Pokémon breeding system
```

Less useful pull request:

```text
updates
```

Clear commits and pull requests make the project's history significantly easier to maintain.

---

## 🐛 Issues

Use GitHub Issues for actionable problems and tasks.

Examples:

```text
Bug
Feature
Improvement
Refactor
Documentation
Infrastructure
```

When reporting a bug, provide enough information to reproduce it whenever possible.

A useful bug report should answer:

* What happened?
* What was expected?
* How can it be reproduced?
* Which version was being used?
* Are there relevant logs or screenshots?

---

## 💡 Discussions & Ideas

Not every idea needs to become an issue.

Use discussions for:

* Architecture decisions
* New system ideas
* Gameplay proposals
* Development questions
* Community discussion
* Technical decisions

The objective is to keep the issue tracker focused on work that can actually be executed.

---

## 🧑‍💻 Development Principles

### Keep it maintainable

Code written today may need to be maintained years from now.

### Prefer clarity

Readable code is usually better than clever code.

### Automate repetitive work

If developers repeatedly perform the same manual operation, consider automating it.

### Document important decisions

If something is non-obvious, document the reasoning — not only the implementation.

### Review before merging

Code review is not about finding someone to blame.

It's about improving the project.

---

## 📦 Releases

Production releases should be identifiable and reproducible.

We use semantic versioning where appropriate:

```text
MAJOR.MINOR.PATCH
```

Example:

```text
v1.4.0
v1.4.1
v2.0.0
```

Every production release should provide enough information to understand what changed.

---

## 🛠️ Organization Structure

The organization is divided into teams according to responsibility.

```text
PokeCroc Inc.
│
├── 🧠 Core
│   ├── Server
│   └── Database
│
├── 🗺️ Content
│   ├── Pokémon
│   ├── Maps
│   ├── Quests
│   └── Gameplay
│
├── 🎮 Client
│   ├── Client
│   └── Launcher
│
├── 🌐 Web
│   └── Website
│
├── 🚀 DevOps
│   ├── Infrastructure
│   ├── CI/CD
│   └── Deployment
│
└── 🧪 QA
    ├── Testing
    └── Quality
```

Access to repositories should be granted according to responsibility rather than automatically giving everyone access to everything.

---

## 📚 Documentation

Technical documentation should live as close as possible to the code it describes.

Repository-specific documentation belongs in the repository.

Cross-project documentation belongs in the organization's documentation resources.

When something is important enough to be remembered, document it.

---

## 🐊 PokeCroc

This organization is more than a collection of repositories.

It's the foundation of the PokeCroc project.

```text
        CODE
         │
         ▼
      SYSTEMS
         │
         ▼
      CONTENT
         │
         ▼
      PLAYERS
         │
         ▼
     POKECROC
```

**Build. Test. Improve. Ship.**

<br>

<p align="center">
  <strong>🐊 PokeCroc Inc.</strong>
  <br>
  <sub>Creating our own Pokémon world, one commit at a time.</sub>
</p>
