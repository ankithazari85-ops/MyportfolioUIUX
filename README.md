# Ankit Hazari — UI/UX & Product Designer Portfolio

> A dynamic, stylish personal portfolio website built with pure HTML, CSS, and JavaScript — showcasing UI/UX design projects, skills, certifications, and work experience.

---

## 👤 About

**Designer:** Ankit Hazari  
**Role:** UI/UX Designer & Product Designer  
**Email:** Ankithazari06@gmail.com  
**Phone:** +91 9165446685  
**Location:** Damoh, Madhya Pradesh, India  

---

## 🗂️ Project Structure

```
ankit_hazari_portfolio/
├── index.html       # Main HTML — all sections and content
├── style.css        # All styling, animations, responsive design
└── script.js        # Interactivity — cursor, filters, counters, form
```

---

## ✨ Features

- **Custom animated cursor** — smooth follower effect on desktop
- **Animated hero section** — staggered text reveals, floating skill cards, rotating ring avatar
- **Scroll reveal animations** — elements fade up as you scroll
- **Animated stat counters** — numbers count up when visible
- **Project filter tabs** — filter by All / Matrimony / Jobs / E-Commerce
- **Working contact form** — with success feedback animation
- **Active nav highlight** — current section highlighted in navbar
- **Fully responsive** — mobile, tablet, and desktop layouts
- **Noise texture overlay** — for a premium tactile feel
- **No dependencies** — zero frameworks, zero libraries

---

## 🎨 Design System

| Property | Value |
|---|---|
| Background | `#0a0a0f` (deep black) |
| Surface | `#111118`, `#1a1a24` |
| Foreground | `#f0ede8` |
| Accent | `#e8b84b` (gold) |
| Accent Light | `#f0c96e` |
| Display Font | Syne (Google Fonts) |
| Body Font | DM Sans (Google Fonts) |
| Border Radius | 16px (cards), 10px (small), 50px (pills) |

---

## 📁 Sections

### 1. Hero
- Name, title, availability badge
- CTA buttons (View Work / Get In Touch)
- Animated stats: 1+ Year Experience, 10+ Projects, 20% Engagement Increase
- Floating skill cards: UI Design, UX Research, Prototyping
- Avatar with rotating dashed ring

### 2. About
- Professional summary from resume
- Work experience at Jain Shadi Milan (Aug 2024 – Present)
- Education: B.Sc. Computer Application, Maharaja Chhatarshal Bundelkhand University (2017–2020)
- Roles & responsibilities breakdown
- Profile badges (degree, location, availability)

### 3. Skills
Six skill cards covering:
- Design Tools: Figma, Adobe XD, Sketch, Canva
- Prototyping: High-Fidelity, Low-Fidelity, Interactive Flows
- UX Research: A/B Testing, Usability Testing, User Research
- Manual Testing: Functional, Regression, Bug Reporting
- Collaboration: Jira, Trello, Slack
- Web Technologies: HTML, CSS, JavaScript (Basic)

### 4. Projects (10 total)

#### Matrimony Category
| Project | Type |
|---|---|
| Jain Shadi Milan | Website |
| Jain Shadi Milan | Android User App |
| Jain Shadi Milan | Admin Panel / CRM |
| Hindu Connect Shadi | Website |
| Hindu Connect Shadi | Android User App |
| Hindu Connect Shadi | Admin Panel |

#### Jobs Category
| Project | Type |
|---|---|
| CityJobsIndia | Job Portal Website |

#### E-Commerce Category
| Project | Type |
|---|---|
| TechioHisab | E-Commerce Website |
| TechioHisab | Android User App |
| TechioHisab | Admin Panel |

### 5. Certifications
- UI/UX Design Certification — Infosys Springboard
- UI/UX for Chatbot & Voice Interface AI — Infosys Springboard
- UX/UI Designing with Color Theory — Infosys Springboard
- Manual Testing Training — Udemy
- Career Edge – Young Professional (Excellent Marks) — TCS
- Communication Skills Certification — TCS
- CPCT Typing Certification — Madhya Pradesh Government

### 6. Accomplishments
- Redesigned landing page → 25% increase in conversions
- Redesigned user app → increased users and experience
- Designed CRM connecting management to employees
- Improved usability testing → reduced errors in final products

### 7. Contact
- Email, Phone, Location, Availability info cards
- Contact form with name, email, subject, message fields

---

## 🚀 How to Run

1. Download and unzip `ankit_hazari_portfolio.zip`
2. Open `index.html` in any modern browser
3. No server, no build step, no installation required

```bash
# Optional: serve locally with Python
python -m http.server 8000
# Then open http://localhost:8000
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| `> 1024px` | Full 2-col / 3-col grids, side-by-side hero |
| `≤ 1024px` | 2-col grids, stacked hero |
| `≤ 768px` | Single column, hamburger menu |
| `≤ 480px` | Compact stats, single-col certs |

---

## 🔧 Customization Guide

### Change accent color
In `style.css`, update the `--accent` variable:
```css
:root {
  --accent: #e8b84b; /* Change this to any color */
}
```

### Add a new project
In `index.html`, copy any `.project-card` block inside `#projectGrid` and update:
- `data-cat` attribute (`matrimony` / `jobs` / `ecommerce`)
- Background gradient in `style` attribute
- Project title, description, tools, and metrics

### Update contact details
Search `index.html` for `Ankithazari06@gmail.com` and `+91 9165446685` and replace with your details.

### Replace avatar initials
Search for `AH` inside the `.avatar-initials` span and update.

---

## 🛠️ Built With

- **HTML5** — semantic structure
- **CSS3** — custom properties, Grid, Flexbox, keyframe animations
- **Vanilla JavaScript** — IntersectionObserver, custom cursor, counter animation
- **Google Fonts** — Syne (display) + DM Sans (body)

---

## 📄 License

This portfolio is personal work created for **Ankit Hazari**. All project descriptions and personal information belong to Ankit Hazari. Free to use as a personal portfolio template with attribution.

---

*Designed & developed for Ankit Hazari · UI/UX & Product Designer · Damoh, M.P., India*
