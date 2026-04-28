---
title: "What is an ATS? Why Your Resume Keeps Getting Rejected"
meta_description: "Learn what Applicant Tracking Systems are, how they filter resumes, and why understanding ATS technology is crucial for modern job seekers."
slug: what-is-ats
category: ats
date: 2026-01-15
updated: 2026-04-27
author: TMJ Studio
cover_image: /images/blog/what-is-ats.jpg
---

# What is an ATS? Why Your Resume Keeps Getting Rejected

You spent four hours rewriting your resume on a Sunday night. You tailored the summary, mirrored the job title, hit submit, and then nothing. Two weeks pass. No interview, no rejection email, just the quiet hum of your inbox. If that sounds familiar, your resume probably never reached a recruiter at all. The blocker is almost always the same piece of software: the **Applicant Tracking System (ATS)**.

This guide walks through what an ATS actually does, the specific reasons qualified candidates get filtered out, and the small formatting and keyword choices that move you from the rejection pile to the recruiter's screen.

## What an Applicant Tracking System actually is

An Applicant Tracking System is the database and workflow tool that companies use to receive, store, score, and route job applications. When you apply through a careers portal — whether the company runs Workday, Greenhouse, Lever, iCIMS, Taleo, SmartRecruiters, or BambooHR — the form fields and the file you upload all flow into an ATS first.

Recruiters do not read every resume. According to Jobscan's analysis of public hiring data, **over 99% of Fortune 500 companies and roughly 75% of mid-sized US employers** rely on an ATS as the first layer of screening. A single role at a recognizable tech company often pulls in 250 to 1,000 applicants within 72 hours. Without automation, recruiters would burn entire weeks just opening attachments.

The ATS does four things in sequence:

1. **Parses** your resume into structured fields (name, email, work history, education, skills).
2. **Matches** the parsed text against the job description's keywords and requirements.
3. **Scores or ranks** each candidate based on those matches.
4. **Filters** the list so the recruiter only sees the top slice — often the top 10–25 candidates.

If your resume parses badly, the recruiter never sees you. If it parses cleanly but misses the right keywords, you sit at rank 87 out of 600, which is the same as not applying.

## How parsing actually works (and where it breaks)

Parsers do not read resumes the way a person reads a magazine. They walk through the file looking for patterns: a section heading like "Experience," a date range like "2022 – Present," a company name in title case, then a bullet list. When the layout matches what the parser expects, it captures every field correctly. When it doesn't, the parser silently drops content into the wrong bucket — or skips it entirely.

A few real failure modes worth knowing:

- **Two-column layouts** confuse parsers that read left-to-right, top-to-bottom. Your skills column can end up interleaved with your experience column, making both unreadable.
- **Text inside headers and footers** is often skipped, so contact info placed there can disappear.
- **Tables** can be flattened in unpredictable order, scrambling job titles and dates.
- **Images, icons, and text embedded in graphics** are invisible. A skill bar showing "Python: 90%" registers as nothing.
- **Non-standard fonts** sometimes render as garbled characters when the parser cannot resolve the font.

If you want to test this yourself, save your resume as a `.docx`, then copy and paste the text into a plain text editor. Whatever shows up in plain text is roughly what the ATS sees. Anything missing or out of order is a parsing risk.

## Keyword matching: the mechanic that decides your score

Once the resume is parsed, the ATS compares it to the job description. Some systems do simple exact matching. Newer ones use semantic matching — they understand that "PMP" and "Project Management Professional" mean the same thing, or that "JavaScript" includes "JS." But you should never assume the system you're applying through is the smart one.

The reliable rule is: **use the exact phrasing from the job description whenever it accurately describes your experience.** If the JD says "stakeholder management," use that phrase, not "client communication." If it lists "SQL," do not write "relational databases" and hope the parser fills in the gap.

Here is a quick before/after on a single bullet for a Senior Marketing Manager role:

> Before: "Led a small team and worked on customer acquisition projects with cross-functional partners."

> After: "Managed a 4-person performance marketing team to execute paid acquisition campaigns across Google Ads and Meta, partnering with product, analytics, and brand to drive a 38% lift in qualified leads quarter over quarter."

The second version contains the phrases "performance marketing," "paid acquisition," "Google Ads," "Meta," "cross-functional partners," and a quantified result. Each of those is a likely keyword in the JD, and the bullet still reads like a human wrote it.

For a deeper walk-through of the keyword process, see our [ATS optimization guide](/blog/ats-optimization-guide), which breaks down keyword density, synonym handling, and common false positives.

## The five reasons qualified candidates still get rejected

Even strong candidates get filtered. After reviewing thousands of resumes through ATS simulators, the same handful of issues come up again and again.

### 1. The file format is wrong

Most modern ATS platforms parse PDFs reliably, but a few older Taleo and iCIMS deployments still struggle with PDFs that were exported from design tools like Canva or InDesign. When in doubt, upload `.docx`. If the application portal accepts both, choose the format that previews correctly inside the portal — many portals show you a parsed preview before you submit. Read it.

### 2. The formatting fights the parser

Multi-column layouts, tables for skills matrices, text boxes for callouts, custom icons next to phone numbers — these are all features of beautifully designed resumes that wreck parsing. A single-column layout with standard headings ("Experience," "Education," "Skills") parses cleanly across every system. For a side-by-side comparison of formats, see [how to choose the right resume format](/blog/resume-format-guide).

### 3. The keywords are missing or paraphrased

This is the most common silent killer. The job says "Python," your resume says "scripting languages." The job says "Salesforce administration," your resume says "CRM tools." A human recruiter would make the connection. The ATS often does not. Audit every JD for hard-skill nouns and exact tool names, then mirror them in your resume where truthful.

### 4. Section headings are too creative

"Where I've Made an Impact" is not "Experience." "My Toolkit" is not "Skills." Parsers are trained on conventional headings. If yours are clever, the parser may not know which section is which, and your work history can land in the void.

### 5. Critical terms are misspelled or inconsistent

"JavaScript" and "Java Script" are different strings. "Salesforce" and "Sales Force" are different strings. "AWS" without the spelled-out "Amazon Web Services" sometimes fails on systems that only match the long form. Spell-check is not enough. Manually verify every tool, certification, and acronym against the JD.

## A 30-minute ATS audit you can run today

You do not need a paid tool to do a basic ATS audit. Run this checklist on whatever resume you plan to submit next:

1. **Save as `.txt` or copy-paste into Notepad.** Read the result. If section headings, dates, or bullets are out of order, your formatting is breaking the parser.
2. **List every hard-skill noun in the job description.** Tools, languages, certifications, methodologies, named platforms. There should be 8–15 of these. How many appear in your resume verbatim?
3. **Check your section headings against the standard list.** Use "Experience," "Education," "Skills," "Certifications," "Summary." Save the creativity for the content inside those sections.
4. **Read your top three bullets out loud.** Do they include a verb, a quantified result, and at least one keyword from the JD? If not, rewrite them.
5. **Check the file name.** "John_Smith_Resume_2026.pdf" is fine. "Untitled (3) FINAL final v4.pdf" is a small but real signal of carelessness.

If you want this audit done for you against a specific job description, [Tailor](/tailor) runs the parse, scores keyword coverage, and returns a list of missing terms in about 30 seconds. But the manual version above will catch 80% of the issues for free.

## What ATS-friendly does not mean

There is a persistent myth that ATS-friendly resumes have to look like 1998 Word documents. They don't. Modern recruiters still read the resume after it passes screening, and a resume that looks visually careless will lose to one that looks polished, even if both pass parsing.

ATS-friendly means:

- Single-column body
- Standard section headings
- A clean, readable font (Calibri, Arial, Helvetica, Lato, Source Sans)
- Bullets and dates in consistent format
- Contact info in the body, not the header
- Keywords mirrored from the JD

It does not mean ugly. Plenty of resumes pass ATS screening and still look like they were designed by an adult. For a curated set of layouts that parse cleanly and look modern, browse our [resume templates](/resume-templates).

## A worked example: rewriting one bullet for ATS and humans

Take a real-feeling bullet from a project manager resume and walk it through the rewrite.

> Original: "Responsible for managing projects and coordinating with various stakeholders to ensure timely delivery."

That is a fine sentence in English class. It is a terrible sentence on a resume. There is no verb that signals action, no scope, no result, and not a single keyword that would match a JD. After running the JD through a parser, the recurring keywords are: "agile," "cross-functional," "Jira," "stakeholder communication," "release planning," "OKRs."

> Rewrite v1: "Managed agile delivery for a 12-person cross-functional team using Jira, owning sprint planning and stakeholder communication across product, engineering, and design."

Better. It has scope (12 people), three keyword nouns, and a verb. But there is no result.

> Rewrite v2: "Managed agile delivery for a 12-person cross-functional team using Jira, owning sprint planning and stakeholder communication across product, engineering, and design — shipped 4 major releases in 2025 and reduced average cycle time from 18 to 11 days."

Now there is a quantified outcome and a second metric. This is the bullet you want. Notice that the keyword density is high but the sentence still reads like a person wrote it on a Tuesday afternoon, not a robot. That is the bar.

## When the ATS is not the problem

Sometimes you pass screening and still get rejected, and that is worth naming too. If your resume is scoring well but you are not getting interviews, the issue is usually one of three things: your experience genuinely does not match the seniority of the role, the recruiter is filtering by location or work authorization, or your resume parses fine but reads as generic to the human reader. The first two are out of your control. The third is fixable, and most of the techniques in our [2026 resume tips](/blog/resume-tips-2026) and [AI resume optimization guide](/blog/ai-resume-optimization-guide) address exactly that gap.

It is also worth checking whether you are applying through the right channel at all. Cold applications through a careers portal go through the full ATS funnel. Referrals usually skip the keyword scoring stage and land directly in the recruiter's queue. If three referred candidates and 600 cold applicants are competing for the same role, the cold applicants need to be in the top 5% just to draw level. That is one reason people who get interviews from referrals often have weaker resumes than cold applicants who never hear back. The funnel they entered through was different.

## The takeaway

The ATS is not your enemy. It is a filter, and like any filter, it has rules. Once you know the rules — clean parsing, mirrored keywords, conventional structure, quantified bullets — you stop losing applications to formatting accidents and start competing on actual qualifications. That is where you want to be.

Tailoring each application is unavoidable. A generic resume submitted to 50 jobs will outperform no resume at all, but it will lose every time to a focused resume submitted to 10. The trade is worth it.

## Frequently Asked Questions

### What does ATS stand for in job applications?

ATS stands for Applicant Tracking System. It is the software that companies use to collect, parse, score, and filter resumes submitted through their careers page. Over 99% of Fortune 500 employers run an ATS, and most mid-sized companies do too, so almost every online application passes through one before a recruiter sees it.

### How do I know if my resume is ATS-friendly?

The fastest test is to copy and paste your resume into a plain text editor. If section headings, job titles, dates, and bullets all appear in the right order with no missing pieces, your formatting parses cleanly. If anything is scrambled or missing, the ATS is likely seeing the same broken version. You can also run it through a free ATS simulator for a more detailed report.

### Should I submit my resume as a PDF or Word document?

Most modern ATS platforms parse both formats well, but Word (.docx) is the safer default if the job posting does not specify. PDFs exported from design tools like Canva or InDesign sometimes parse poorly on older systems. If the application portal shows a parsed preview after upload, always read it before submitting.

### How many keywords should my resume have to pass an ATS?

There is no fixed number, but a useful rule is to mirror 70–80% of the hard-skill nouns from the job description, naturally integrated where they truthfully describe your work. Stuffing every keyword from the JD will trigger penalties on smarter systems and will read as obvious to the recruiter who eventually opens the file.

### Do small companies use ATS software too?

Yes, more than people expect. Tools like Greenhouse, Lever, BambooHR, and Workable are inexpensive and widely adopted by startups and companies with 50–500 employees. Roughly half of mid-sized employers in the US run an ATS, and nearly all venture-backed startups use one to manage their hiring pipeline.

### Can an ATS read images, icons, or skill bars on my resume?

No. ATS parsers extract text, not visuals. An icon next to your phone number, a skill bar showing 'Python: 90%,' or a logo in the header are all invisible to the parser. If a piece of information matters, write it as plain text inside the document body.

### Why does my resume keep getting rejected when I am qualified?

The most common causes are missing keywords, multi-column or table-based layouts that confuse the parser, creative section headings the system does not recognize, and small spelling inconsistencies in tool or certification names. Run a side-by-side comparison of your resume and the job description, and rewrite bullets to include the exact phrasing the JD uses.

### How long does an ATS take to screen a resume?

The parsing and scoring run in milliseconds. The bottleneck is the recruiter, who typically reviews the top-ranked 10–25 candidates a day or two after the posting closes. If your resume scored in the top tier, you usually hear back within one to two weeks. Silence beyond three weeks almost always means you were filtered out before review.
