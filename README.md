# e-portfolio
 
Personal e-portfolio built for the **Careers & Management (CAM)** module at N7. 
## Approach
 
**Goal.** Build a clear, easy-to-navigate showcase of who I am, what I study and where I want to go (data / AI / cybersecurity), with a consistent message across my CV, LinkedIn, pitch video and this site.

**Link.** https://clement-cardot-portfolio.vercel.app/

**Structure.** The site follows the six tabs asked for in the course:
 
| Page | Purpose |
|---|---|
| Welcome | Short introduction |
| Engineering course | Studies and technical projects |
| International Mobility | Mobility projects |
| Sustainability & Civic Engagement | CSR / civic engagement |
| Sport & other activities | Activities outside of class |
| Career Development | Career project: CVs, LinkedIn, pitch video, role models |
 
**Technical choices.**
- Use of Vercel, easier than Github pages (didn't work for me)
- Plain HTML and CSS, no framework: the content matters more than the code
- Shared navigation bar and a single stylesheet (`style.css`), so every page looks the same.
- Source code hosted on GitHub, site hosted on Vercel. Each commit on `main` is automatically redeployed.
## Repository layout
 
```
index.html          Welcome
engineering.html    Engineering course
mobility.html       International Mobility
civic.html          Sustainability & Civic Engagement
sport.html          Sport & other activities
career.html         Career Development
style.css           Shared styles
