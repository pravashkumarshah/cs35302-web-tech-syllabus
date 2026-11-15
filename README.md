# CS35302 Web Technology Interactive Syllabus Portal 🌐🎓

> **Official Interactive Syllabus, Notes, 3D Core & AI Tutor Portal**  
> Designed for Quantum School of Technology, Quantum University (Roorkee) B.Tech CSE 5th Semester students.

---

## 🌟 Key Features

### 1. 📚 Complete 5-Unit Official Syllabus
- **Unit 1 (7 Hrs):** History of Internet, WWW, HTML, Protocols (HTTP, SMTP, POP3, MIME, IMAP), DNS, Web Browsers & Servers.
- **Unit 2 (8 Hrs):** HTML Lists/Tables/Forms/Frames, CSS, DHTML with JavaScript, XML, DTD, XSD, XML DOM & SAX Processors.
- **Unit 3 (7 Hrs):** Web Services Architecture, UDDI, SOAP, WSDL, AJAX (Performance & Programming), CORBA.
- **Unit 4 (7 Hrs):** Web 2.0 (Blogs, Wikis, Social, AJAX, RSS, Ruby on Rails), Web 3.0 (Semantic Web, RDF, Widgets, Mashups), Blockchain, Edge Computing, Dark Mode.
- **Unit 5 (7 Hrs):** Web 4.0 (AI-Powered Web, Autonomous Agents), Decentralized Web (DWeb), IoT in Web Development, AR/VR, Smart Web, 5G Impact.

### 2. 🤖 OpenRouter AI Doubt Solver with 5-Part Structured Answers
- **Multi-Model Auto-Free Fallback:** Automatic failover across high-speed free models (`nvidia/nemotron-3.5-lightning:free`, `inclusionai/ling-3.2-flash:free`, `cohere/north-mini-code:free`).
- **Strict 5-Part Academic Format:**
  1. **📌 Title / Heading:** Short topic summary.
  2. **📖 Main Explanation:** In-depth explanation with paragraphs, comparison tables, and code snippets.
  3. **💡 Key Points:** Bullet points highlighting critical definitions and distinctions.
  4. **🎯 Action Items & Next Steps:** University exam tips, viva questions, and practical guidance.
  5. **📝 Summary:** Concise 1-sentence wrap-up.
- **Bilingual Tutor:** Explains complex concepts in clear English or natural Hinglish.

### 3. 🎙️ Built-in Text-to-Speech (TTS) Engine
- Powered by the native browser **Speech Synthesis API**.
- **Playback Controls:** Play (▶️), Pause (⏸), Resume (🔄), and Stop (⏹).
- **Customizable Speech Settings:**
  - Speed Rate: 0.8x (Slower), 1.0x (Normal), 1.2x (Fast), 1.5x (Speedy).
  - Dynamic Voice & Accent selector populated with all installed system voices.
  - Auto-Speak toggle to automatically read aloud new answers.
- **Smart Markdown Stripper & Sentence Chunker:** Ensures natural speech cadence and prevents browser speech timeouts.

### 4. 🎨 Visual Experience & Accessibility
- **Three.js 3D Web Core:** Interactive 3D visualization representing internet connectivity and web protocols.
- **Accessibility:** Screen-reader friendly (`role="log"`, `aria-live="polite"`), high-contrast readability, and keyboard shortcuts (`Escape` to close drawers, `Ctrl + /` or `Alt + A` to toggle AI chat).
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
