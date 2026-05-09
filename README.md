# SentimentAI — AI-Powered Customer Review Sentiment Analyzer

**Class Project | AI 2010 | Iowa State University**
**Student:** Biswas Khatiwada

> Live Website: [https://biswaskhatiwada.github.io/ai-sentiment-project/](https://biswaskhatiwada.github.io/ai-sentiment-project/)

---

## Project Overview

This is a class project for **AI 2010 at Iowa State University**. The goal of this project is to demonstrate how Artificial Intelligence and Natural Language Processing (NLP) can be applied to solve a real-world business problem — specifically, helping small businesses make sense of customer feedback at scale.

The project analyzes **75 customer reviews** from Google and Yelp for a small restaurant (Bella's Bistro), automatically classifying each review as **Positive**, **Negative**, or **Neutral** using AI tools (ChatGPT / Claude). The results are presented as an interactive web dashboard with charts, trends, and data-driven marketing recommendations.

---

## The Problem

Small business owners receive hundreds of customer reviews every month but don't have time to read them all. Critical feedback about food quality, wait times, pricing, and service gets buried and goes unread — leading to uninformed decisions and unresolved customer pain points.

**Manual review reading is:**
- Slow and time-consuming
- Subjective and inconsistent
- Impossible to scale

---

## The Solution

This project uses an **AI-powered NLP pipeline** to:
1. Automatically classify every review as Positive, Negative, or Neutral
2. Tag each review with a topic category (Food Quality, Service, Wait Time, Pricing, Ambiance, Menu)
3. Visualize all results in an interactive dashboard
4. Generate actionable marketing recommendations based on the data

The result is a complete marketing intelligence tool that requires **zero coding** from the business owner — just raw customer reviews in, clear insights out.

---

## Live Website

The project is deployed as a fully interactive single-page web application.

**Access it here:** [https://biswaskhatiwada.github.io/ai-sentiment-project/](https://biswaskhatiwada.github.io/ai-sentiment-project/)

### Website Sections
| Section | Description |
|---------|-------------|
| **Home** | Key stats at a glance — sentiment breakdown and average rating |
| **Problem** | Research context, problem statement, and the AI solution |
| **Methods** | The 4-step AI pipeline and tools used |
| **Results** | Interactive charts: sentiment distribution, topic breakdown, monthly trends, competitor comparison |
| **Data Table** | Full filterable table of all 75 classified reviews |
| **Recommendations** | 3 data-driven marketing strategies derived from the analysis |
| **About** | Project metadata and course context |

---

## Key Results

From 75 customer reviews analyzed (October 2025 – March 2026):

| Metric | Value |
|--------|-------|
| Positive Reviews | 49% |
| Negative Reviews | 40% |
| Neutral Reviews | 11% |
| Average Star Rating | 3.47 / 5.0 |

### Topic Sentiment Highlights
- **Food Quality** — mostly positive; customers love the pasta and fresh ingredients
- **Wait Time** — highest volume of negative feedback; identified as the #1 pain point
- **Pricing** — mixed; value perception is a key concern for returning customers
- **Service** — split positive/negative; inconsistent staff performance flagged
- **Ambiance** — largely positive; atmosphere is a competitive strength
- **Menu** — neutral to positive; variety appreciated but some gaps noted

---

## AI Pipeline

```
Step 1 — Collect Reviews
    └─ 75 reviews from Google & Yelp (Oct 2025 – Mar 2026)

Step 2 — AI Sentiment Classification
    └─ ChatGPT / Claude NLP → Positive / Negative / Neutral

Step 3 — Topic Extraction
    └─ Food Quality, Pricing, Wait Time, Service, Ambiance, Menu

Step 4 — Visualize & Report
    └─ Interactive dashboard + marketing recommendations
```

---

## Tools & Technologies

| Tool / Platform | Role |
|-----------------|------|
| **ChatGPT / Claude AI** | NLP sentiment classification and topic extraction |
| **Microsoft Excel** | Data organization, storage, and preliminary tallying |
| **HTML / CSS / JavaScript** | Single-page interactive web application |
| **Chart.js** | Interactive charts and data visualizations |
| **Google Reviews** | Primary source of customer review data |
| **Yelp** | Secondary source of customer review data |
| **GitHub Pages** | Free hosting for the live website |

---

## Project Structure

```
ai-sentiment-project/
└── index.html       # Complete single-page web app (HTML + CSS + JS)
```

---

## How to Run Locally

No setup required. Just open the file in any browser:

```bash
git clone https://github.com/biswaskhatiwada/ai-sentiment-project.git
cd ai-sentiment-project
open index.html
```

Or visit the live site directly: [https://biswaskhatiwada.github.io/ai-sentiment-project/](https://biswaskhatiwada.github.io/ai-sentiment-project/)

---

## Course Information

| Field | Detail |
|-------|--------|
| **Course** | AI 2010 — Introduction to Artificial Intelligence |
| **Institution** | Iowa State University |
| **Student** | Biswas Khatiwada |
| **Data Period** | October 2025 – March 2026 |
| **Reviews Analyzed** | 75 (Google + Yelp) |
| **Business Studied** | Bella's Bistro (anonymized local restaurant) |

---

## Key Takeaways

This project demonstrates that:
1. **AI is accessible** — Non-technical business owners can use ChatGPT/Claude to perform professional-grade NLP analysis without writing a single line of code.
2. **Sentiment analysis has real ROI** — Identifying that 40% of reviews are negative, primarily about wait times, gives a business an immediately actionable priority.
3. **Topic tagging multiplies insight** — Knowing not just that customers are unhappy but *what* they are unhappy about (wait times, pricing) is what makes the data useful for marketing strategy.
