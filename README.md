# 👋 Hi, I'm Sheila Hernandez
**Creative Operations & Workflow Automation Specialist**  
*Promotional Products Industry • 20+ Years • Remote*

<p align="center">
  <strong>I find the manual, repetitive, expensive bottleneck & eliminate it.</strong>
</p>

<p align="center">
  <a href="https://shernandez520.github.io"><img src="https://img.shields.io/badge/Portfolio-shernandez520.github.io-222222?style=flat-square&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/sheila-aiworkflow/"><img src="https://img.shields.io/badge/LinkedIn-Sheila%20Hernandez-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.artcheck.app"><img src="https://img.shields.io/badge/Live%20App-artcheck.app-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="ArtCheck"></a>
</p>

I build practical automation for creative, operations and production teams. I've spent 20+ years in promotional products, on both the supplier and distributor side, so I don't just understand the technology. I understand the workflows it has to survive in.

My sweet spot: **I know the production process cold, I spec the workflow logic, and I build it with AI-assisted development**, so the tool actually fits how the work gets done.

---

## ⭐ Featured Projects

### 🎨 [ArtCheck](https://github.com/Shernandez520/artcheck): instant art file screening *(live)*

[![Live App](https://img.shields.io/badge/Live%20App-artcheck.app-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://www.artcheck.app)
[![Repo](https://img.shields.io/badge/GitHub-artcheck-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Shernandez520/artcheck)
[![Deployed](https://img.shields.io/badge/deployed-Railway-blueviolet?style=flat-square)]()

I designed and built this SaaS tool on my own time. It comes from 20 years of watching sales and CS reps interrupt art departments with the same questions: *"What Pantone is this?" "Will this embroider?" "This file won't open."*

Upload a vector, embroidery or image file and get:
- **Instant previews:** AI, EPS, PDF, SVG, CorelDRAW, embroidery (DST, PES and more) and raster files
- **Real color analysis:** Pantone names, CMYK and K% are read from the file's internal structure, not guessed from pixels
- **Decoration method check:** a plain verdict for screen print, embroidery, DTF, DTG, sublimation and more
- **Font check and vector PDF conversion:** with a ready-to-send request when fonts aren't outlined
- **ArtBot:** an AI production assistant (Claude) that gives reps the exact words to use with customers and vendors

**No expensive software. No art department interruption. Just answers.**

`Python` · `Streamlit` · `PyMuPDF` · `Ghostscript` · `Anthropic Claude API` · `Docker` · `GitHub Actions` · `Railway`

---

### 🎯 [Batch Color Swap](https://github.com/Shernandez520/illustrator-batch-color-swap): find and replace any color across hundreds of Illustrator files

[![Repo](https://img.shields.io/badge/GitHub-illustrator--batch--color--swap-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Shernandez520/illustrator-batch-color-swap)
[![Platform](https://img.shields.io/badge/Adobe%20Illustrator-ExtendScript-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=white)]()

Brand colors change all the time, and opening files one by one doesn't scale. This Illustrator script finds any fill or stroke color in a whole folder of PDF, AI or EPS files and replaces it with any other color:
- **Match colors** by CMYK, RGB or grayscale build, or by Pantone/spot name
- **Replace with any color:** process, spot or none, with original tints preserved
- **Brand presets** you can save and share
- **Reference swatch file** to bring in official Pantone definitions
- **Safe to run:** backups, CSV logs, dry runs and resumable batches

`Adobe ExtendScript (JSX)` · `ScriptUI` · `Node.js test harness`

---

### ⚙️ [FINALIZER Batch Suite](https://github.com/Shernandez520/finalizer-batch-suite): production file automation

[![Repo](https://img.shields.io/badge/GitHub-finalizer--batch--suite-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Shernandez520/finalizer-batch-suite)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey?style=flat-square)]()
[![Status](https://img.shields.io/badge/status-production--ready-brightgreen?style=flat-square)]()

This replaced the manual post-approval step in a logo registration workflow. After a proof was approved, the Graphics team used to do all of this by hand for every job: duplicate folders, open each PDF in Illustrator, export PNGs, toggle background layers, save, close, ZIP and log. **FINALIZER does all of it from a single right-click Send-To action.**

`Windows Batch` · `Adobe ExtendScript (JSX)` · `PowerShell`, coordinated through a flag-file handshake so it runs safely in Dropbox.

> ⚠️ It's built around one internal workflow's folder and naming conventions. I include it as an example of cross-technology orchestration, not as a plug-and-play utility.

---

## 🛠️ More Tools

| Project | What it does | Stack |
|---|---|---|
| [Image Sorting Tool](https://github.com/Shernandez520/image-sorting-tool) · [case study](https://github.com/Shernandez520/promo-artwork-automation-case-study) | Sorts 150–200-image webstore batches by orientation and logs every move. Turned a multi-hour weekly task into minutes | PowerShell |
| [Illustrator PNG Export](https://github.com/Shernandez520/Illustrator-png-export-script) | Exports open PDFs to 72 PPI PNGs on white backgrounds for web, mockups and proofs | JSX |
| [Illustrator Size & Center Action](https://github.com/Shernandez520/Illustrator-size-center-action) | Sizes and centers logos on a production template for consistent output | Illustrator Action |
| [Photoshop Thumbnail Action](https://github.com/Shernandez520/Photoshop-thumbnail-action) | Batch-processes e-commerce product thumbnails with consistent formatting | Photoshop Action |
| [Batch File Renamer](https://github.com/Shernandez520/batch-file-renamer) | Renames large file sets to a naming convention, with a log for auditing | PowerShell |
| [AI Task Intake](https://github.com/Shernandez520/zapier-ai-task-intake) | Spots actionable emails and logs them to a structured Google Sheet, built on the free tier | Zapier |

---

## 🔧 Currently Building

- **FINALIZER Extended:** a follow-on automation that closes out the whole logo registration lifecycle after FINALIZER runs. It pulls colors from the output files, delivers files to the order and logo-registration systems, updates status in both, and routes complex files to a person through Teams. The architecture proposal is done.
- **Learning:** Power Automate and Power BI, to bring the same approach to Microsoft 365 workflows.

---

## 🧰 Tech & Tools

**Scripting & Automation**  
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ExtendScript](https://img.shields.io/badge/ExtendScript%20JSX-FF0000?style=flat-square&logo=adobe&logoColor=white)
![Batch](https://img.shields.io/badge/Windows%20Batch-4D4D4D?style=flat-square&logo=windows&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4F00?style=flat-square&logo=zapier&logoColor=white)
![Make.com](https://img.shields.io/badge/Make.com-4C27E8?style=flat-square&logo=make&logoColor=white)

**AI & Development**  
![Claude](https://img.shields.io/badge/Anthropic%20Claude-222222?style=flat-square)
![Copilot](https://img.shields.io/badge/GitHub%20Copilot-000000?style=flat-square&logo=github&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Creative Production**  
![Illustrator](https://img.shields.io/badge/Adobe%20Illustrator-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=white)
![Photoshop](https://img.shields.io/badge/Adobe%20Photoshop-31A8FF?style=flat-square&logo=adobephotoshop&logoColor=white)

**Project & Operations**  
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-D83B01?style=flat-square&logo=microsoftoffice&logoColor=white)

**Learning**  
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=flat-square&logo=microsoftpowerautomate&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

---

## 🤝 How I Work

I care about clarity, clean logic and real-world impact, not complexity for its own sake. I work closely with designers, CX, marketing and ops teams to build tools that are:

✔ simple enough to actually be used  
✔ scalable when the need grows  
✔ well documented for the next person  
✔ designed around real constraints, not ideal conditions  

---

## 🔍 What I'm Open To

- Remote full-time or contract roles in **workflow automation, creative operations, business process analysis or implementation**
- Freelance automation projects for creative and production teams
- Teams that value domain expertise and technical execution together

---

## 📬 Let's Connect

I'm always happy to trade automation notes, talk creative ops, or see whether we're a good fit for something.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sheila%20Hernandez-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sheila-aiworkflow/)
[![Portfolio](https://img.shields.io/badge/Portfolio%20%26%20Resume-shernandez520.github.io-222222?style=flat-square&logo=githubpages&logoColor=white)](https://shernandez520.github.io)
