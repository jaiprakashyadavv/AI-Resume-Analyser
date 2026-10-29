# ResumeAI - SaaS AI Resume & ATS Compatibility Analyzer

> **Beat the ATS. Land the Interview.**  
> A modern, responsive, corporate-grade single-page React application built with Tailwind CSS, Lucide icons, and intelligent ATS simulation algorithms.

---

## 🌟 Key Features & Architecture

### 1. Header / Navigation
- **Branding**: Clean `ResumeAI` logo with glowing gradient icon and `ATS v4.2` engine badge.
- **Navigation Links**: Interactive triggers for "How it Works", "Pricing", and "Sign In" with sleek modals.
- **Mobile Responsive**: Adaptive drawer menu for smartphones and tablets.
- **Interactive Quick-Demo**: 1-click sample data preloader to instantly try the product.

### 2. Hero Section
- **Headline**: *"Beat the ATS. Land the Interview."*
- **Subheadline**: *"Upload your resume and the target job description. Our AI analyzes keyword match, formatting, and impact to give you an instant ATS compatibility score."*
- **Social Proof**: Trust badges showing compatibility with **Workday**, **Greenhouse**, and **Lever**, plus 240,000+ resumes optimized.

### 3. Interactive Input Section (Two Distinct Cards)
- **Card 1 (Resume Upload)**:
  - Drag-and-drop zone with animated dashed border, upload icon, and hover states.
  - File picker supporting PDF, Word (.docx), and TXT.
  - Document preview card displaying file name, size, page count, and status badge with delete/replace options.
- **Card 2 (Job Description)**:
  - Resizable textarea for pasting target job requirements.
  - Real-time character count and "Insert Demo Job Spec" action.
- **Primary CTA**: Prominent "Analyze Resume" button with magic wand icon and hover lift effect.
- **Multi-Step Loading State**: Progress bar (0% -> 100%) showing realistic AI scan phases (*extracting keywords, cross-referencing Workday/Taleo algorithms, synthesizing bullet scores*).

### 4. Results Dashboard
- **Circular Match Score Gauge**: SVG animated circular indicator displaying the **82% Match** with high-match emerald badge, plus sub-scores for Skills (88%), Format (95%), and Impact (72%).
- **Executive Fit Summary**: Comprehensive candidate alignment paragraph highlighting strong areas and key gaps needed to cross 90%.
- **Three-Column Metrics Grid**:
  - **Strengths (Card 1)**: Matched skills (React, TypeScript, Tailwind CSS, Redux, Next.js, Jest, REST/GraphQL) with green checkmarks.
  - **Missing Keywords (Card 2)**: Missing requirements (Docker, AWS S3/CloudFront, Micro-frontends, Cypress) with red X-marks and priority badges.
  - **Formatting Audit (Card 3)**: 6 core ATS checks (*Standard headings, No tables, Single-column hierarchy, Standard typography, UTF-8 encoding*).
- **Feedback & Bullet Point Rewriter**:
  - 3 high-impact suggestions showing original low-impact bullets vs. AI-optimized rewrites with quantified metrics (+8 pts).
  - 1-click "Copy to Clipboard" with instant toast feedback.
- **Export & Print**: Printable ATS audit PDF preview modal.

### 5. Corporate Footer
- Clean SaaS footer with copyright notice, product links, supported ATS systems, and legal/privacy links.

---

## 🚀 How to Run the Application

You have two easy ways to experience the application:

### Option 1: Instant Run (Zero Installation Required)
You can directly double-click `index.html` in file explorer or run:
```bash
python serve.py
```
*(or double-click `start.bat`)*

This starts a local HTTP server at `http://localhost:3000` and automatically opens your default browser.

### Option 2: Run via Node.js / Vite
If you have Node.js installed and wish to run the standard Vite development environment:
```bash
npm install
npm run dev
```

---

## 🎨 Design System
- **Theme**: Clean, corporate yet modern (inspired by Stripe and Vercel).
- **Primary Color**: Trustworthy deep slate (`#0f172a` / `slate-900`) with vibrant scores (emerald `#10b981`, amber `#f59e0b`, rose `#ef4444`).
- **Typography**: Inter (Google Fonts), crisp letter spacing, clean mono snippets for bullet comparisons.
