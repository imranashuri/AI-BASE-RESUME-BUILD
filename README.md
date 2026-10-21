# ResumeAI – AI-Based Resume Builder

A single-page web application that helps users build a resume: pick a template, enter details, get AI-style suggestions, check an ATS score and export. It is built as a **practice application for Software Testing and Quality Assurance (STQA)**, so it runs without any backend or database.

## Features

- **Template gallery** – 9 resume templates (Modern, Classic, Creative, Minimal, Executive, Elegant, Tech, Bold, Compact) with a readable preview, ATS percentage and Available/Unavailable status.
- **Template search** – search by name, category or template ID; shows a message when nothing matches.
- **Register and Login** – create an account and log in with email/phone and password, with validation and error messages.
- **Resume form** – name, job title, email, phone, education, work experience and skills.
- **Live preview** – the resume updates as you type and takes the style of the selected template.
- **AI suggestions** – generates 3 summary options plus bullet points and keywords; each suggestion can be accepted or rejected.
- **AI unavailable mode** – a "Simulate AI down" switch shows how the app behaves when AI is not available; the user can still write the resume manually.
- **ATS score** – scores the resume out of 100 and lists tips to improve it.
- **Export** – Export PDF / Export Word buttons; export requires login and a non-empty resume.
- **Responsive design** – works on mobile, tablet and desktop, and supports light and dark mode.

- <img width="1331" height="617" alt="one" src="https://github.com/user-attachments/assets/dee38691-e494-48ad-980c-55229fea17c2" />

<img width="1339" height="608" alt="two" src="https://github.com/user-attachments/assets/eb87b094-65a1-4579-ac3b-8fba61ad4c78" />

<img width="1308" height="606" alt="three" src="https://github.com/user-attachments/assets/52a37a98-f35d-40ec-9fcf-abcc2bcc105e" />





## Tech Stack and Tools

| Area | What was used |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (Flexbox, Grid, CSS variables, media queries) |
| Logic | Vanilla JavaScript (no framework, no libraries) |
| Data | In-memory JavaScript objects (no database, no backend) |
| Run / test in | Google Chrome or Microsoft Edge |
| Documentation | Word / Google Docs (lab document), Excel (test scenarios sheet) |
| Built with | Claude (AI assistant by Anthropic) |

## How to Run

1. Download `resumeai.html`.
2. Double-click the file. It opens in Chrome or Edge.
3. No installation or internet connection is needed.

Click **Login → Create account** first to register, then log in. Accounts are kept only in memory and are lost when the page is refreshed.

## Important Notes

- AI suggestions are **simulated** with fixed templates; no real AI model or API is called.
- Export buttons only show a confirmation message; no PDF or Word file is downloaded.
- There is no database, so no data is saved after a page refresh.

## STQA Lab Requirements Covered

| ID | Requirement |
|---|---|
| R1 | Template Search |
| R2 | Login |
| R3 | Invalid Login |
| R4 | Select Template |
| R5 | Unavailable Template (Executive, T005) |
| R6 | AI Suggestions |
| R7 | Empty Resume |
| R8 | Login Before Export |
| R9 | Export Resume |
| R10 | ATS Score |

## Project Structure

```
resumeai.html   # whole application (HTML + CSS + JavaScript)
README.md
```
