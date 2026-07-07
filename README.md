# Advance Cosmo Care Aesthetic & Wellness Clinic

Welcome to the repository for **Advance Cosmo Care Aesthetic & Wellness Clinic**, a doctor-led clinic providing advanced, non-surgical treatments in skin, laser, hair restoration, and homeopathy wellness based in Modasa, Aravalli, Gujarat.

The website is a fast, highly optimized, and premium responsive single-page web presence designed to deliver a modern, luxury feel while ensuring top-tier SEO and AI optimization (AIO).

---

## 🌟 Clinic Overview

- **Founder & Lead Cosmetologist:** Dr. Ankita Patel (BHMS, Fellowship in Facial Aesthetics, Certified Cosmetologist & Laser Specialist, Trichologist)
- **Location:** 125 First Floor, Shyam Icon, Bypass Road, Sahiyog Chokdi, Malpur Road, Modasa, Gujarat 383315
- **Booking & Contact:**
  - Phone / WhatsApp: +91 96645 27441
  - Email: advancecosmocare258@gmail.com
- **Patient Reviews:** Rated 5 ★ by 195+ patients on Google.

---

## 🛠️ Project Structure

This project is built using semantic HTML5, vanilla CSS, and structured data, prioritizing fast load times and clean structure.

```
advancecosmocare/
├── .agents/
│   └── AGENTS.md          # Workspace rules (SEO and AIO guidelines)
├── assets/                # Visual media (logos, treatment images, graphics)
├── index.html             # Main clinic landing page
├── laser-hair-reduction.html # Specialized treatment landing page
├── style.css              # Custom responsive stylesheet (Cormorant Garamond & Plus Jakarta Sans)
├── llms.txt               # Plaintext structured profile for AI crawlers
├── robots.txt             # Web crawler accessibility rules (explicitly allowing LLM bots)
├── sitemap.xml            # Sitemap index for search engine crawlers
└── README.md              # This file
```

---

## 🚀 Key Features

### 1. Premium Visual Design & Responsiveness
- **Typography:** Uses elegant `Cormorant Garamond` for headings and clean `Plus Jakarta Sans` for body copy.
- **Color Palette:** A cohesive, premium dark green and gold aesthetic reflecting clinical trust and aesthetic luxury.
- **Fully Responsive:** Adapts seamlessly to all screen sizes (mobile, tablet, desktop) using CSS Grid and Flexbox.

### 2. Search Engine Optimization (SEO)
- **Local & Geo SEO:** Meta headers configure precise geographic regions and coordinates (Lat/Long) for Modasa, Gujarat.
- **Semantic Structure:** Follows proper HTML tag hierarchy (`h1` -> `h2` -> `h3`) with clean markup.
- **Rich Snippets (JSON-LD):** Implements organization, clinic branch, and treatment offerings schema using a linked `@graph` structure to help search engines map services accurately.

### 3. Artificial Intelligence Optimization (AIO)
- **Inclusive Crawler Policy:** `robots.txt` explicitly welcomes LLM crawlers like `GPTBot`, `ClaudeBot`, `PerplexityBot`, and `Google-Extended`.
- **`llms.txt` Interface:** Maintained in the root directory as a high-density, machine-readable reference card for LLMs and developer agents.

---

## 💻 Local Development

Since this site is built with vanilla HTML and CSS, you do not need complex build tools.

### Option A: Open Directly
Simply open [index.html](file:///c:/Project/Dev/Clients/advancecosmocare/index.html) in any web browser.

### Option B: Local Server (Recommended)
To prevent CORS or path resolution issues with some assets, serve the project using a simple local server:

**Using Python:**
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

**Using Node.js (`serve` package):**
```bash
npx serve .
```

---

## 📢 SEO & AIO Guidelines (For Developers & Agents)

When adding or updating content (treatments, location details, phone numbers):
1. **Sync Coordinates:** Any change to telephone, address, or hours in [index.html](file:///c:/Project/Dev/Clients/advancecosmocare/index.html) must be updated in [llms.txt](file:///c:/Project/Dev/Clients/advancecosmocare/llms.txt).
2. **Entity Graphing:** Connect new services/procedures to the Organization graph in [index.html](file:///c:/Project/Dev/Clients/advancecosmocare/index.html).
3. **Structured Schema:** Maintain the `FAQPage` schema parallel to any interactive visible FAQ accordions.
4. **Geo SEO tags:** Ensure the `<meta name="geo.position">` and location configurations are intact.
