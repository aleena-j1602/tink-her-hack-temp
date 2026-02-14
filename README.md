<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# SkillSync 🎯

## Basic Details

### Team Name: Athena

### Team Members
- Member 1: Aleena Joseph - Jyothi Engineering College
- Member 2: Aghna Vincent - Jyothi Engineering College

### Hosted Project Link

https://drive.google.com/drive/folders/18T4D18EGz8ieO3fSba7hnGNH5DF9OWA_?usp=sharing


### Project Description
A comprehensive career readiness system that compares student skills against role-based requirements, calculates readiness scores, identifies prioritized skill gaps, and generates customized learning paths with curated resources

### The Problem statement
Students struggle to understand the gap between their current skills and industry requirements for placements, leading to unfocused preparation, wasted time on irrelevant topics, and ultimately lower placement success rates. College placement cells lack data-driven insights to identify common skill deficiencies across batches and cannot effectively plan targeted training programs.

### The Solution
SkillSync combines algorithmic skill gap analysis with Google Gemini AI to deliver personalized career readiness insights. The platform analyzes student profiles against industry requirements, calculates readiness scores, and uses Gemini AI to generate intelligent learning recommendations, contextual study guidance, and personalized resource curation. This AI-enhanced approach ensures students receive not just a list of gaps, but actionable, prioritized learning paths with explanations tailored to their unique situation and learning style.

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: Python
- Frameworks used: HTML
- Libraries used: 
- Tools used: Google Gemini, Flask

**For Hardware:**
- Main components: [List main components]
- Specifications: [Technical specifications]
- Tools required: [List tools needed]

---

## Features

List the key features of your project:
- Feature 1: Intelligent Skill Gap Analysis
- Feature 2: Personalized Learning Roadmaps
- Feature 3: Interactive Dashboard with Multi-Tab Analytics
- Feature 4: Batch-Level Institutional Analytics

---

## Implementation

### For Software:

#### Installation
```bash
pip install flask flask
pip install python
```

#### Run
```bash
python3 test_gemini.py
```



## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

https://drive.google.com/drive/folders/1i03lMe0GKllsR7moGq4-izyvmbmKU84p?usp=sharing

Screenshot 1: Home Page
It shows the home page of the actual website

Screenshot2:Student Detail Page
A student can enter the details about their current skillset.

Screenshot3: Analysis Page
SHows the total analysis of the student and their skill gap from the industry; also generates AI insight into the analysis

#### Diagrams

**System Architecture:**

![Architecture Diagram] https://drive.google.com/drive/folders/1_7C5yhYun2LW2oUHo14eQgvlupe3-zpR?usp=sharing
Skill Gap Analyzer Architecture: Flask backend orchestrates user flow—Home→Student form collects profile/skills→Session stores data→Analysis route triggers Gemini AI with role-based skill DB comparison→AI generates JSON readiness score/gaps/roadmap→Jinja2 renders dynamic results page. Tech stack: Flask (routing/session), Google Gemini AI (analysis), HTML/CSS/JS (3-page UI), .env (API security). Data flows unidirectionally: Form POST→Session→AI Prompt→Template render. 

**Application Workflow:**

![Workflow] https://drive.google.com/drive/folders/1fS6g8Sd-Kly0jKTWyxEYTYNpi-T-QRCD?usp=sharing
Student registers with personal details and current skills → Backend analyzes profile against role requirements from database → Algorithm calculates readiness score and identifies prioritized skill gaps → Gemini AI generates personalized learning path with curated resources → Student views comprehensive dashboard with gaps, score, and roadmap → Progress tracked over time → Placement cells access aggregated batch analytics for institutional insights.


---


---



### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python3 test_gemini.py

---

## Project Demo

https://drive.google.com/drive/folders/18T4D18EGz8ieO3fSba7hnGNH5DF9OWA_?usp=sharing

The video demonstrates the working of the website. The home page gets the website analysis started. The second page shows the student details entry where you can enter the the details of your skillset and target role. This gets redirected to the third page where the total analysis of the skill gap is shown along with ai insight into how one can roadmap their learning journey to reach their target goal.


---

## AI Tools Used (Optional - For Transparency Bonus)

ChatGPT, Claude AI

**Tool Used:** Git, GitHub, Flask, Gemini API

**Purpose:**
- Flask was chosen for its lightweight, flexible architecture that allows rapid API development with minimal boilerplate code, making it ideal for building RESTful endpoints for our skill analysis backend.
- Google Gemini AI was integrated to provide intelligent, context-aware learning recommendations and personalized career guidance that adapts to each student's unique skill profile and learning needs.
- GitHub was used for version control, collaborative development, and code management, enabling us to track changes, maintain project history, and facilitate seamless teamwork throughout the development process.

**Key Prompts Used:**
- "Create a GEMINI API endpoint for user authentication"
- "Integrate Flask to develop the backend"

**Percentage of AI-generated code:** [Approximately 65%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- Aghna Vincent: Frontend Development
- Aleena Joseph: Backend development, Added Flask and Google Gemini

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
