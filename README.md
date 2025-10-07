# 🧩 Bookmarklet Collection

A curated suite of browser bookmarklets for language learning, OSINT, and productivity.  
Each tool runs directly in the browser — no installation, no extensions, no external setup.

> 💡 **How to use:** Drag any colored button from the page into your bookmarks bar.  
> Then click it while viewing any web page to activate its functionality.

---

## 🚀 Quick Start

1. **Open the HTML page** (`bookmarklets.html`) in your browser.  
2. **Drag** the colored links (e.g., “Oxford 1000 Highlighter”) to your bookmarks bar.  
3. **Click** a bookmarklet while viewing a web page to run its tool.  
4. Some bookmarklets will load external JavaScript libraries hosted on GitHub Pages.

> 🧱 **Tip:** If a bookmarklet doesn’t seem to activate, try running it on a simple page like  
> [example.com](https://example.com) — some corporate or secure sites block inline scripts.

---

## 📚 Included Bookmarklets

### 🟩 **Oxford 1000 Highlighter**
Highlights all Oxford 1000 core English words on any webpage.  
Useful for ESL learners or instructors checking text difficulty.

**Features**
- Highlights all Oxford 1000 words in bright yellow.  
- Counts total words found and displays an alert summary.  
- Loads the word list dynamically from GitHub Pages.

---

### 🟢 **NGSL / NAWL Multi-Set Highlighter**
Advanced academic vocabulary visualization tool based on the  
**New General Service List (NGSL)** and **New Academic Word List (NAWL)**.

**Features**
- Supports 7 sets (NGSL 1-3000 + NAWL).  
- Interactive floating legend to toggle each set.  
- Highlights in distinct colors (yellow, blue, pink, etc.).  
- Detects “off-list” words not found in any of the sets.  
- Click “Clear All” to remove all highlights instantly.

---

### 🔵 **Aramco Service List Highlighter**
Custom internal vocabulary list highlighter for company-specific terminology.

**Features**
- Loads multiple 250-word service list sets (ASL 1-1100).  
- Highlights all matching service terms on a webpage.  
- Includes draggable floating legend for toggling sets.  
- Ideal for professional training or document analysis.

---

### 🟣 **OSINT Quick Tool**
An **Open Source Intelligence (OSINT)** data extraction and investigation panel.  
Instantly detects and organizes intelligence artifacts on any webpage.

**Features**
- Extracts: Emails, domains, URLs, IPv4/IPv6, phone numbers, crypto wallets, usernames.  
- Displays data in a modern floating panel with categorized sections.  
- Each result includes actionable links for:
  - Google / Bing / DuckDuckGo / Yandex searches  
  - WHOIS / crt.sh / VirusTotal / Shodan / Censys / Wayback  
  - LinkedIn, Twitter/X, and GitHub site searches  
- Built-in **Dork Builder** for generating Google and Bing search dorks.  
- Copy data in **JSON format** for analysis tools.

---

### 🟠 **Google Power Search**
A visual panel for building complex Google search queries with ease.

**Features**
- Opens a lightweight floating search builder.  
- Insert search operators such as `site:`, `filetype:`, `inurl:`, `intitle:`, `OR`, `AND`, etc.  
- Automatically opens the built search in a new tab.  
- Designed for digital investigators, educators, and researchers.  
- Click again to close the panel.

---

### ⚫ **Image Resolution Tooltip**
Shows the pixel resolution (width × height) of any image when hovering.

**Features**
- Displays a floating tooltip above images on hover.  
- Automatically hides when you move the mouse away.  
- Ideal for designers, educators, or OSINT analysts.

---

### 💜 **Aramco Colors**
Interactive **Aramco Brand Color Picker** tool for quick reference and copy.

**Features**
- Displays internal and external brand palettes.  
- Preview swatches with HEX values.  
- “Select All”, “Clear All”, and “Copy Selected” buttons.  
- Click **Close** to remove the palette.  
- Works as a floating, draggable color reference.

---

## 🧠 Technical Notes

- All bookmarklets are **pure client-side JavaScript** (no server dependencies).  
- External scripts (e.g., NGSL/NAWL, Oxford 1000 lists) are loaded via HTTPS from:
  - `https://msdt463657.github.io/`
- Works on all modern Chromium, Firefox, and Safari browsers.
- For corporate environments: bookmarklets may be blocked by CSP (Content Security Policy).  
  Run on non-restricted domains for testing.

---

## 🧰 File Structure
