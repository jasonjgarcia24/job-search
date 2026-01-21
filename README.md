# Job Search Workspace

AI-assisted job search workspace leveraging Claude AI to create ATS-optimized application materials.

## Table of Contents

- [About This Repository](#about-this-repository)
- [Repository Structure](#repository-structure)
- [Core Templates](#core-templates)
  - [Resume Template](#resume-template)
  - [Cover Letter Template](#cover-letter-template)
- [Common Claude Project Interaction](#common-claude-project-interaction)
  - [Example Resume and Cover Letter Tailoring](#example-resume-and-cover-letter-tailoring)
  - [Example Claude Analysis Output](#example-claude-analysis-output)
- [Application Workflow](#application-workflow)
  - [1. Research & Targeting](#1-research--targeting)
  - [2. Tailor Application Materials](#2-tailor-application-materials)
  - [3. Apply & Track](#3-apply--track)
  - [4. Follow Up](#4-follow-up)
- [Git Ignored Files](#git-ignored-files)
- [Claude AI Integration](#claude-ai-integration)
- [Professional Profile](#professional-profile)

## About This Repository

This repository contains templates and tools for managing a targeted job search.

## Repository Structure

```
job-search/
├── README.md                              # This file
├── Claude_Instructions.md                 # Detailed AI assistance guidelines
├── Jason_J_Garcia-_RESUME.md             # Master resume template (markdown)
├── Jason_J_Garcia-COVERLETTER.md         # Master cover letter template
└── EXAMPLE-List of Target Companies.docx # Company tracking template
```

## Core Templates

### Resume Template
[Jason_J_Garcia-_RESUME.md](Jason_J_Garcia-_RESUME.md) - Customizable, ATS-optimized resume template and baseline experience.

**Key Features:**
- Formatted for LinkedIn Parsing System (LPS) compatibility
- Quantifiable metrics and achievements
- Consistent professional styling

### Cover Letter Template
[Jason_J_Garcia-COVERLETTER.md](Jason_J_Garcia-COVERLETTER.md) - Customizable cover letter template with guidance for personalization.

**Usage Guidelines:**
- Create Claude project for job searching
- Paste `Claude_Instructions.md` content into the created project's instructions 
- Add template documents to Claude project
- Use the `EXAMPLE-List of Target Companies.docx` to create a `List of Target Companies.docx`
- Add `List of Target Companies.docx` document to Claude project

## Common Claude Project Interaction

### Example Resume and Cover Letter Tailoring Input:
> Using the pasted job role, create a tailored resume and cover letter for my application.

### Example Claude Analysis Output

> I'll create tailored application materials for this Anduril Senior Technical Program Manager role. Let me start by reading the relevant skill documentation to ensure the best quality output.
>> Reading the docx skill to create a high-quality resume document
>
> Now I'll analyze the job description and create tailored materials. Let me break down the key requirements and how your experience maps to them:
>
> **Key Job Requirements Analysis:**
> - Identifies technical requirements and maps them to your experience
> - Highlights required skills (e.g., TPM experience, cross-functional leadership)
> - Verifies alignment with preferred qualifications
> - Notes any clearance or certification requirements
>
> **Strong Alignment Points:**
>
> Claude identifies specific areas where your background directly matches the role:
> 1. **Domain-Specific Experience**: Maps your current and past roles to job requirements (e.g., edge compute systems, defense sector work, hardware/software integration)
> 2. **Quantifiable Achievements**: Highlights metrics from your background (budget scope, team size, cross-functional coordination scale)
> 3. **Technical Breadth**: Shows how your SW/HW/Test experience meets multi-disciplinary requirements
> 4. **Field Experience**: Connects deployment and travel experience to role requirements
>
> **ATS Optimization Strategy:**
> - **Keyword Integration**: Incorporates essential terms from job posting (e.g., "cross-functional," "agile methodology," "customer-facing," "prototype deployment")
> - **Skills Matching**: Explicitly aligns your years of experience with requirements
> - **Achievement Quantification**: Emphasizes metrics like budget size, team count, scope of coordination
>
>
> Now I'll create both documents with ATS optimization in mind.Hide stepsInstalling docx package for creating Word documentsbashnpm install -g docxOutput
changed 22 packages in 6s
>> Creating tailored resume for Anduril Senior TPM role with ATS optimization
>>
>> Generating the tailored resume
>>
>> Creating tailored cover letter for Anduril Senior TPM
>>
>> Generating the cover letter document
>>
>> OutputCover letter created successfully
>>
>> Moving final documents to outputs directory
>>
>> Presented 2 files
>
> **Gap Identification:**
>
> Claude identifies potential gaps (e.g., specific clearance levels, preferred certifications) and suggests how to address them in interviews or applications.
>
> **Salary & Fit Analysis:**
>
> Compares posted salary range with your target, evaluates alignment with career goals (e.g., senior level, mission-driven work, growth company trajectory).
>
>> Jason garcia anduril resume
>>
>> Jason garcia anduril coverletter

## Application Workflow

### 1. Research & Targeting
- Identify companies with strong growth trajectory and stability
- Research company culture, AI tool usage, and remote work policies
- Verify alignment with target industries and role types

### 2. Tailor Application Materials
- Analyze job description for required vs. preferred qualifications
- Extract ATS keywords and integrate into resume
- Customize cover letter with company-specific research
- Highlight relevant achievements using quantifiable metrics

### 3. Apply & Track
- Submit application through preferred channels
- Update tracking document with application date and status
- Document networking contacts and referrals

### 4. Follow Up
- Send follow-up email 1 week after application
- Prepare company-specific interview questions
- Practice STAR method responses for behavioral questions

## Git Ignored Files

Application-specific materials are excluded from version control for privacy:

- `*-RESUME-*.doc` and `*-RESUME-*.pdf` - Company-tailored resumes
- `*-COVERLETTER-*.doc` and `*-COVERLETTER-*.pdf` - Customized cover letters
- `List of Target Companies.doc*` - Personal application tracking

## Claude AI Integration

This workspace leverages Claude AI for comprehensive job search support:

**Resume & Cover Letter Optimization:**
- ATS keyword optimization
- Metric-driven achievement highlighting
- Industry-specific tailoring
- LPS compatibility verification

**Job Search Strategy:**
- Company research and culture analysis
- Role alignment assessment
- Skill gap identification
- Networking message drafting

**Interview Preparation:**
- Practice question generation
- STAR method response crafting
- Company-specific question suggestions

See [Claude_Instructions.md](Claude_Instructions.md) for detailed AI assistance guidelines and communication preferences.

## Professional Profile

**Jason J. Garcia**
Technical Program Manager | 10+ Years Experience in Systems Engineering & Program Management

- **Email:** jason.garcia24@gmail.com
- **LinkedIn:** [linkedin.com/in/24-jason-j-garcia](https://www.linkedin.com/in/24-jason-j-garcia/)
- **Location:** Seattle, WA
- **Current Role:** Technical Program Manager @ Meta (AR/VR Research Technologies)

**Core Competencies:** Cross-functional coordination, camera/sensor development, vendor contract management, budget planning, annotations & data labeling, people management, SW lifecycle management
