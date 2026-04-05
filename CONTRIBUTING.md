# Contributing to Public APIs Curated

Thank you for your interest in contributing to this repository! 🎉 This project is a curated adaptation of the [Public APIs](https://github.com/public-apis/public-apis) list, maintained to help developers discover free, public APIs for their projects.

Whether you're fixing a typo, adding a new API, or improving documentation, every contribution helps make this resource better for everyone.

---

## 🚀 Quick Start

1. **Fork** this repository
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/mohd-ali10/public-apis-curated.git
   cd public-apis-curated
   ```
3. **Create a branch** for your changes:
   ```bash
   git checkout -b add-my-api
   ```
4. **Make your changes** following the guidelines below
5. **Commit & push**:
   ```bash
   git add README.md
   git commit -m "Add [API Name] to [Category]"
   git push origin add-my-api
   ```
6. **Open a Pull Request** against this repository

---

## ➕ Adding a New API

### ✅ Eligibility Criteria
Before submitting, ensure the API:
- [ ] Has **free access** or a **generous free tier** (no credit card required for basic usage)
- [ ] Does **not require purchasing hardware/devices** to use
- [ ] Has **public, accessible documentation**
- [ ] Is **not a duplicate** of an existing entry
- [ ] Is **actively maintained** (no 404s, deprecated endpoints, or abandoned projects)

### 📝 Entry Format
Each API entry must follow this markdown table format:

```markdown
| [API Name](https://docs-url) | Short description (<100 chars) | Auth | HTTPS | CORS |
```

#### Field Guidelines:
| Column | Accepted Values | Example |
|--------|----------------|---------|
| **API Name** | `[Name](https://docs-link)` — link to official docs, not homepage | `[NASA](https://api.nasa.gov)` |
| **Description** | Clear, concise, **≤100 characters** | `NASA data, including imagery` |
| **Auth** | `No`, `apiKey`, `OAuth`, `X-Mashape-Key`, `User-Agent` | `apiKey` |
| **HTTPS** | `Yes` or `No` | `Yes` |
| **CORS** | `Yes`, `No`, or `Unknown` | `Yes` |

#### Example Entry:
```markdown
| [NASA](https://api.nasa.gov) | NASA data, including imagery | No | Yes | Yes |
```

> ⚠️ **CORS Note**: If an API doesn't support CORS, it can only be used server-side. Please test or verify before marking `Yes`.

### 🗂️ Category Placement
- Place the API in the **most relevant category** (see [Index](#index))
- If it fits multiple categories, choose the **primary use case**
- Keep entries in **alphabetical order** within each section

---

## 🛠️ Other Ways to Contribute

### 🔧 Fixing Issues
- Broken links, outdated info, or formatting errors? Open an [Issue](https://github.com/YOUR_USERNAME/YOUR_REPO/issues) or submit a PR.
- Always verify links before reporting them as broken.

### 📚 Improving Documentation
- Suggest clearer descriptions, better categorization, or additional metadata.
- Propose new sections if a meaningful category is missing.

### 🧹 Maintenance
- Help deprecate APIs that are no longer free, maintained, or accessible.
- Update authentication/CORS/HTTPS fields when you discover changes.

---

## 📋 Pull Request Guidelines

### Before Submitting
- [ ] Search existing [Issues](https://github.com/YOUR_USERNAME/YOUR_REPO/issues) and [PRs](https://github.com/YOUR_USERNAME/YOUR_REPO/pulls) to avoid duplicates
- [ ] Ensure your branch is up-to-date with `main`
- [ ] Test all links and API endpoints you're adding/modifying
- [ ] Follow the formatting rules above

### PR Requirements
- **One API per PR** (unless fixing multiple related issues)
- **Title format**: `Add [API Name] to [Category]`  
  Example: `Add OpenWeatherMap to Weather`
- **Commit message**: Short and descriptive  
  Example: `Add OpenWeatherMap API with free tier`
- **Target branch**: `main` of this repository
- **Squash commits** if you have multiple small fixes

### After Submission
- A maintainer will review your PR within a few days
- You may be asked to make small adjustments — just push additional commits to the same branch
- Once approved, your PR will be merged! 🎉

---

## 🧭 Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/). By participating, you agree to uphold a welcoming, inclusive, and respectful community.

Report any concerns to the maintainers via [Issues](https://github.com/YOUR_USERNAME/YOUR_REPO/issues) or direct message.

---

## 📜 License & Attribution

This repository is licensed under the [MIT License](LICENSE). By contributing, you agree that your contributions will be licensed under the same terms.

> This project is adapted from [public-apis/public-apis](https://github.com/public-apis/public-apis). All original APIs remain the property of their respective creators. This list does not host, operate, or endorse any third-party services.

---

## ❓ Questions?

- 💬 Join our community discussions in [Issues](https://github.com/YOUR_USERNAME/YOUR_REPO/issues)
- 📖 Review the [README](README.md) for project overview
- 🔍 Check existing entries for formatting examples

Thank you for helping build a better resource for developers worldwide! 🌍✨

---

> 💡 **Pro Tip**: Use a tool like [Markdown Table Generator](https://www.tablesgenerator.com/markdown_tables) to format entries quickly and avoid spacing errors.
