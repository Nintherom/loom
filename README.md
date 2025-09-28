# 📖 Loom – Markdown & LaTeX Processor for Jetpack Compose

**Loom** is a Kotlin-based library/app that lets you render **Markdown + LaTeX seamlessly inside Jetpack Compose**.  
It is designed for students, researchers, and developers who need a clean way to display formatted notes and mathematical formulas in Android apps.

---

## 🧩 Problem → Solution → Impact

- **Problem**: Android apps don’t natively support rendering Markdown + LaTeX together, which is essential for students, researchers, and note-taking applications.
- **Solution**: Loom integrates **CommonMark** for Markdown parsing and **MathView** for LaTeX rendering directly into **Jetpack Compose**.
- **Impact**: Makes Android apps more powerful for education, research, and knowledge sharing by supporting rich text + math formulas out of the box.

---

## ✨ Features
- 📑 **Markdown support** → Headings, paragraphs, bold/italic, lists, links
- 🔢 **LaTeX rendering** → Inline (`$E=mc^2$`) and block (`$$\frac{a}{b}$$`) equations
- 🎨 **Jetpack Compose UI** → 100% Kotlin, modern declarative UI
- 🌗 **Dark mode support**
- ⚡ **Real-time preview** (optional: live editing → rendered output)
- 📤 **Export support** (future scope: PDF/Share options)

---

## 🛠️ Tech Stack
- **Language**: [Kotlin](https://kotlinlang.org/)
- **UI Toolkit**: [Jetpack Compose](https://developer.android.com/jetpack/compose)
- **Markdown Parsing**: [CommonMark Java](https://github.com/commonmark/commonmark-java)
- **LaTeX Rendering**: [MathView](https://github.com/garciparedes/MathView) (embedded in Compose with `AndroidView`)

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/loom.git
cd loom
