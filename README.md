# E-portfolio

Personal e-portfolio built for the **Careers & Management (CAM)** module at N7 (ENSEEIHT, Toulouse INP).

**Link:** https://clement-cardot-portfolio.vercel.app/

## Approach

**Goal.** Build a clear, easy-to-navigate showcase of who I am, what I study and where I want to go (data and the ethics of its use), with a consistent message across my CV, LinkedIn, pitch video and this site.

**Structure.** The site follows the six tabs asked for in the course, plus a CV page:

| Page | Purpose |
|---|---|
| Welcome | Introduction, selected projects, quick links |
| Engineering course | Studies, skills and detailed technical projects |
| International Mobility | Three mobility plans, with the role models that inspired them |
| Sustainability & Civic Engagement | Student life, associations and sustainability |
| Sport & other activities | Activities outside of class |
| Career Development | CVs, LinkedIn, role models, pitch video |
| CV | CV in French and English, to download |

**Content.** Each mobility plan (double degree with Sciences Po and Hertie School, Universidad Politécnica de Madrid, Politecnico di Milano) is linked to a role model on the Career Development page.

## Technical choices

- **Plain HTML and CSS, no framework:** the content matters more than the code.
- **One shared stylesheet** (`style.css`) and the same navigation bar on every page, so the site looks consistent.
- **Cards** for projects, activities and role models, in a responsive layout that adapts to phones.
- **Flags** are small images loaded from flagcdn.com.
- **Vercel** for hosting: GitHub Pages deployments were blocked for me, and Vercel redeploys automatically on every commit on `main`.

## A project in itself

Before this site, I had never written HTML or CSS. I built it while learning, and I used an AI assistant to explain concepts and suggest code, which I adapted and tested myself. The content, the structure and the choices are mine.

## Repository layout

```
index.html          Welcome
engineering.html    Engineering course
mobility.html       International Mobility
civic.html          Sustainability & Civic Engagement
sport.html          Sport & other activities
career.html         Career Development
cv.html             CV page
style.css           Shared styles
images/             Project images (GIF, screenshots)
*.pdf               CVs in French and English
```

## Run locally

No build step is needed. Clone the repository and open `index.html` in a browser.

## Updating the site

1. Edit or add files in this repository.
2. Commit to `main`.
3. Vercel redeploys the site within about a minute.
