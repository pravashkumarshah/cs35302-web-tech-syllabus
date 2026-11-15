# CS35302 Web Technology Interactive Syllabus Portal 🌐🎓

> **Official Interactive Syllabus, Notes, 3D Web Core, HTML5 Encyclopedia & AI Tutor Portal**  
> Designed for Quantum School of Technology, Quantum University (Roorkee) B.Tech CSE 5th Semester students.

---

## 🌟 Key Features

### 1. 📚 Complete 5-Unit Official Syllabus (3x–5x Expanded Depth)
- **Unit 1 (7 Hrs):** History of Internet & WWW, HTML Fundamentals & DOM Tree, Protocols (HTTP, SMTP, POP3, MIME, IMAP), DNS Resolution Hierarchy, Web Browsers & Web Servers.
- **Unit 2 (8 Hrs):** HTML Lists, Tables, Images, Forms & Controls, Iframes, CSS Box Model & Selectors, Dynamic HTML (DHTML) with JavaScript, XML Basics, DTD, XML Schema (XSD), DOM vs. SAX XML Processors.
- **Unit 3 (7 Hrs):** Web Services Architecture, Core Stack (UDDI, SOAP, WSDL), Developing & Deploying Services, AJAX (Performance & Asynchronous Programming), CORBA.
- **Unit 4 (7 Hrs):** Web 2.0 (Blogs, Wikis, Social Networks, RSS, Ruby on Rails, Open APIs), Web 3.0 (Semantic Web, RDF, Widgets, Mashups), Web-Based Information Systems, Recommender Systems, Blockchain, Edge Computing, Dark Mode.
- **Unit 5 (7 Hrs):** Web 4.0 (AI-Powered Symbiotic Web, Autonomous Agents, Generative UI), Decentralized Web (DWeb / IPFS / Smart Contracts), Web of Things (IoT / MQTT / Web Bluetooth), WebXR (Spatial AR & VR in Browser), Smart Web, Adaptive Interfaces, Web Automation (Playwright/Puppeteer), Impact of 5G on Web Technologies.

### 2. 🗂️ Interactive 5-Tab Topic Learning Hub
Every topic card opens a full-featured slide-over drawer with 5 dedicated learning tabs:
- **📖 Tab 1: Theory & Use Cases:** Formal Exam Definition, Primary Purpose, Why Needed, Working Mechanism, Key Concepts, Industry Use Cases, Step-by-Step Execution Flow, Common Mistakes vs. Best Practices, and Quick Revision Summary.
- **📊 Tab 2: Flowchart & Visuals:** Visual architecture diagrams, SVG/ASCII flows, and sequential execution stage maps.
- **💻 Tab 3: Code Labs (3 Tiers):** Basic (Beginner), Intermediate (Realistic), and Advanced (Project-level) code examples with expected output cards and line-by-line technical explanations.
- **🎯 Tab 4: Quiz & Flashcards:** Interactive 3-question MCQ quiz with instant answer verification and live score tracking, interactive 3D flip flashcards for active recall, and topic practical coding challenges with collapsible model solutions.
- **💼 Tab 5: Interview & Viva Prep:** Quantum University 2-mark and 7-mark exam questions with complete model answers, plus a "Solve with AI" one-click helper.

### 3. 🏷️ HTML5 Tag Master Encyclopedia
- Dedicated reference guide covering all **34 core HTML tags** with syntax, attributes tables, basic & advanced live examples, practical use cases, browser behavior, and accessibility (a11y) notes.
- Accessible directly from the top sticky navigation bar or from any HTML topic in the syllabus.
- Features real-time search filtering and 8 category filter pills (*Document Structure, Text & Headings, Links & Media, Forms & Controls, Tables & Lists, Semantic Layout, Graphics & Embedded, Interactive*).

### 4. 🤖 OpenRouter AI Doubt Solver with 5-Part Structured Answers
- **Multi-Model Auto-Free Fallback:** Automatic failover across high-speed free models (`nvidia/nemotron-3.5-lightning:free`, `inclusionai/ling-3.2-flash:free`, `cohere/north-mini-code:free`).
- **Strict 5-Part Academic Format:**
  1. **📌 Title / Heading:** Short topic summary.
  2. **📖 Main Explanation:** In-depth explanation with paragraphs, comparison tables, and code snippets.
  3. **💡 Key Points:** Bullet points highlighting critical definitions and distinctions.
  4. **🎯 Action Items & Next Steps:** University exam tips, viva questions, and practical guidance.
  5. **📝 Summary:** Concise 1-sentence wrap-up.
- **Bilingual Support:** Fully understands and responds in natural English or friendly Hinglish.

### 5. 🎙️ Built-in Text-to-Speech (TTS) Engine
- Powered by the native browser **Speech Synthesis API**.
- **Playback Controls:** Play (▶️), Pause (⏸), Resume (🔄), and Stop (⏹).
- **Customizable Speech Settings:**
  - Speed Rate: 0.8x (Slower), 1.0x (Normal), 1.2x (Fast), 1.5x (Speedy).
  - Dynamic Voice & Accent selector populated with all installed system voices.
  - Auto-Speak toggle to automatically read aloud new answers.
- **Smart Markdown Stripper & Sentence Chunker:** Ensures natural speech cadence and prevents browser speech timeouts.

### 6. 🎨 3D Web Core, Theme & Accessibility
- **Three.js 3D Web Core:** Interactive 3D visualization representing internet connectivity and web protocols.
- **Accessibility:** Screen-reader friendly (`role="log"`, `aria-live="polite"`), high-contrast readability, and keyboard shortcuts (`Escape` to close drawers/modals, `Ctrl + /` or `Alt + A` to toggle AI chat).
- **Dark / Light Mode:** Instant theme toggle with local storage persistence.
- **Progress Tracking & Instant Search:** Track completed topics with live percentage progress bar and quick topic search.

---

## 🚀 Deployment & Local Running

This portal is a self-contained, standalone web application. No complex build tools or backend servers are required.

### Local Preview
Simply open `index.html` in any modern web browser, or serve it using any static server:

```bash
# Using Python
python -m http.server 8000

# Using Node / npx
npx serve .
```

### GitHub Pages Deployment
1. Go to repository **Settings** > **Pages**.
2. Select **Source**: Deploy from a branch (`main` / root).
3. The site will be live immediately!

---

## 📄 License
Created for academic and educational purposes for B.Tech CSE students.
