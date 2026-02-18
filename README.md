# SEO SERP Generator GEO for LLM
A standalone React tool designed to generate advanced SEO & Generative Engine Optimization (GEO) prompts. Features multi-language support (EN, DE, FR, ES, IT, PL), dynamic schema markup generation, and SERP snippet customization. Zero dependencies; runs directly in the browser.

# 🚀 Advanced SEO & GEO Prompt Canvas
A single-page React application designed to help SEO specialists and Content Marketers generate high-quality, structured prompts for AI models (ChatGPT, Claude, Gemini).

This tool focuses specifically on **SEO** (Search Engine Optimization) and **GEO** (Generative Engine Optimization), ensuring content is primed for both traditional search engines and AI-driven "Answer Engines."

## ✨ Key Features

- **Multi-Language Support:** Generate prompts instantly in English, German, French, Spanish, Italian, and Polish.
- **GEO Strategy Integration:** Includes specific instructions for "Answer Engine Optimization" to help content appear in AI overviews.
- **Dynamic Customization:**
  - Define Topic, LSI Keywords, and Target Audience.
  - Set custom Brand Tone.
  - Input Competitor data for gap analysis.
- **Toggle-able Modules:**
  - Schema Markup (JSON-LD) requests.
  - Meta Title & Description generation.
  - Featured Snippet (Position Zero) optimization.
- **Zero-Build Architecture:** Built with React, Tailwind CSS, and Babel via CDN. No Node.js or build steps required.
- **Modern UI:** Features a glassmorphism design with real-time prompt preview.

## 🛠️ How It Works

The application uses a "Prompt Engineering" logic to construct a comprehensive instruction block based on your inputs.

1. **Select Language:** Choose the output language for the prompt.
2. **Input Data:** Fill in your topic, keywords, and competitor info.
3. **Configure:** Toggle specific needs like Schema or GEO strategy.
4. **Copy:** The tool constructs a finalized prompt in the preview window, ready to be pasted into your AI tool of choice.

## 📦 Installation & Usage

Because this tool is built as a standalone HTML file using CDNs, there is **no installation** required.

### Option 1: Run Locally
1. Download the [SEO-GEO-Generator.html](SEO-GEO-Generator.html) file from this repository.
2. Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).

### Option 2: Host Static
Upload [SEO-GEO-Generator.html](SEO-GEO-Generator.html) to any static hosting service (GitHub Pages, Netlify, Vercel, or a standard web server).

## 💻 Tech Stack

- **Core:** React 18 (via UMD)
- **Styling:** Tailwind CSS (via CDN)
- **Transpiler:** Babel Standalone (for in-browser JSX compiling)
- **Icons:** FontAwesome

## 🧩 Customization

To add more languages or modify the prompt logic:

1. Open [SEO-GEO-Generator.html](SEO-GEO-Generator.html) in a text editor.
2. Locate the `PROMPT_TEMPLATES` constant to add new language keys.
3. Modify the `buildPrompt()` function to change how the text is assembled.

## 📄 License

[MIT License](LICENSE) — Feel free to modify and use for personal or commercial projects.
