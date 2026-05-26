# Learning Project: Not Professional Work

*This reflection note is a personal, educational document created as part of a self directed GRC learning exercise. It does not describe professional experience with any real organisation.*

---

# Reflection Note: AI Shadow IT Risk Assessment Project

**Author:** GRC Portfolio Project (Learning Exercise)

**Date:** 2026

**Project Folder:** AI-Shadow-IT-Risk-Assessment

---

## Introduction

This document is a personal reflection on the process of building the AI Shadow IT Risk Assessment project. The project is entirely fictional. It was designed as a learning exercise to practice the core activities of a junior governance, risk, and compliance role: identifying and articulating risk, drafting a usable policy, and mapping controls to recognised frameworks. This reflection is not a formal report. It is an honest account of what I learned, what I found difficult, what I would do differently with a real organisation, and why this exercise matters for my career transition into GRC.

---

## What I Learned

### Governance, Risk, and Compliance Is a Communication Discipline

The most significant lesson from this project is that GRC is fundamentally about communication, not just technical knowledge. I came into this exercise with an MSc in cyber security. I understand encryption, network segmentation, threat modelling, and security operations. I assumed that building a risk register would be the easy part and writing a policy would be a straightforward administrative task.

I was wrong.

Building the risk register was methodical and structured. I could rely on the frameworks I learned during my degree. The logic chain of asset, threat, vulnerability, likelihood, impact, and control felt familiar. It required discipline to complete every column without skipping steps, but the process was within my comfort zone.

Writing the acceptable use policy was the hardest part of the project by a significant margin. My first draft was technically accurate but completely unusable. I wrote sentences like "Data subjects must ensure that personally identifiable information is not inputted into unsanctioned large language model interfaces due to the absence of a data processing agreement and the resultant regulatory exposure under UK GDPR Article 28." That sentence is correct. It is also impenetrable to a busy nurse, a marketing intern, or a finance officer. They would read the first five words and stop.

I rewrote the policy three times. Each time I removed more jargon and asked myself a simple question: "Would my mother understand this sentence if she worked at MediTech?" The final draft is not perfect, but it is readable. I learned that a policy nobody understands is not a control. It is a document that sits on a SharePoint site and provides nothing except a false sense of compliance. A real control changes behaviour. Behaviour change requires clarity, not complexity.

### Risk Scoring Is Both Structured and Subjective

Assigning a number from one to five to likelihood and impact felt straightforward on paper. In practice, I found myself staring at a risk like "nurse uses AI chatbot during patient triage" and struggling to decide whether the likelihood was a three or a four. I had no historical data. I had no incident reports. I had no access to real employees to ask. I was making an educated guess based on my imagination of what might happen.

This taught me something important. A risk register built by one person working alone is not a finished product. It is a draft. Real risk assessment requires multiple perspectives. A clinician would assess the triage risk differently from an IT security analyst. A data protection officer would see nuance in the patient data scenarios that I missed. A frontline manager would know whether staff are actually using AI tools or whether my scenarios are purely theoretical.

In a real organisation, I would not submit this risk register for approval without first convening a workshop with stakeholders from clinical, legal, IT, and operations. I would present my draft as a starting point and invite challenge. The scoring would be debated, adjusted, and ultimately owned by the group, not by me alone. I understand now why experienced GRC professionals describe risk assessment as a facilitation skill as much as an analytical one.

### Residual Risk Requires Honesty

I caught myself wanting to set residual risk scores very low. After proposing a control, I felt a sense of ownership over it. I wanted it to be effective. I found myself thinking, "I proposed a training course, so the likelihood must drop to one." But that is wishful thinking. Training is notoriously difficult to measure and even more difficult to prove. Employees forget. They get busy. They revert to old habits. A single training module does not eliminate the risk of human error.

I had to consciously check my optimism. For each residual score, I asked myself: "Am I reducing this because the control genuinely addresses the root cause of the vulnerability, or am I reducing it because I want the register to look successful?" In several cases, I revised the residual scores upward after this reflection. This honesty is not a weakness in the register. It is a strength. A risk register that claims all risks are reduced to green after controls is almost certainly inaccurate and provides false assurance to leadership.

### Frameworks Are Not Bureaucracy

Mapping controls to ISO 27001:2022 and NIST Cybersecurity Framework 2.0 felt like an academic checkbox exercise before I started. I had studied these frameworks during my MSc and understood them theoretically. Mapping my own proposed controls to specific clauses and categories changed my perspective.

When I mapped my controls, I could immediately see gaps. My first draft was heavy on technical controls and light on governance. The mapping revealed that I had no controls addressing supplier relationships, even though one of my proposed solutions was to procure an enterprise AI tool. That procurement decision itself introduces a new supplier risk, which I had not considered. I added the supplier relationship control and the data protection impact assessment only after the mapping exercise highlighted the oversight.

I also noticed that my controls were clustered in the NIST CSF Protect function. I had nothing meaningful in Recover. For this particular risk scenario, that may be appropriate. A data leakage to a public AI tool is not something you recover from in the traditional sense. You cannot retrieve the data. But the exercise made me think about whether I was neglecting a whole domain of the framework. In a broader enterprise risk assessment, that blind spot would be a significant finding.

This experience converted me from someone who viewed frameworks as academic abstractions to someone who sees them as practical diagnostic tools. They are not bureaucracy. They are a checklist for thinking systematically.

---

## What I Found Difficult

### The Blank Page Problem

Starting the risk register from absolute zero was harder than I expected. In a real organisation, there are existing assets, known threats, past incidents, and audit findings to draw on. I had none of that. I had to invent a company, imagine its data flows, guess at its employee behaviours, and construct plausible risk scenarios from scratch.

This felt artificial, and it was. But it also forced me to think through the structure of a risk from first principles. I could not rely on copying an existing template or modifying a previous assessment. Every field in every row had to be reasoned out. I believe this was valuable precisely because it was difficult. It built the mental muscle memory for how a risk is constructed.

### Policy Tone and Voice

Finding the right tone for the acceptable use policy was a persistent struggle. My natural writing voice, shaped by academic papers and technical reports, is formal and dense. A policy document needs to be authoritative but not intimidating. It needs to set clear boundaries without sounding punitive. It needs to be precise without being unreadable.

I experimented with different approaches. My first draft read like a legal contract. My second draft read like a friendly blog post and lost all authority. The final draft is an attempt at a middle ground: clear rules stated plainly, with explanations for why the rules exist, and reassurance that honest mistakes will be handled fairly.

I am not fully satisfied with the result. I think a real policy benefits from review by a professional writer or a communications specialist, which is something I would advocate for in a real organisation. I also think a policy document is only one part of a behaviour change strategy. A short, visually engaging summary for the intranet, a three minute video for the learning management system, and a team discussion guide for line managers would all amplify the policy's impact. The written document is necessary but not sufficient.

### Accepting the Limits of a Solo Exercise

The hardest moment in this project was accepting that some of my conclusions might be wrong, and I have no way to know. In a real organisation, my draft risk register would be reviewed by a senior analyst or a risk manager. They would find errors, challenge assumptions, and improve the work. Alone, I can only do my best and acknowledge the limitations.

This is not a comfortable feeling. I want my work to be correct. But I also recognise that the ability to accept feedback and revise your work is a professional skill in itself. I am not presenting this project as a finished, correct product. I am presenting it as evidence that I can think in a structured way about risk, and that I am ready to learn from people who have been doing this longer than I have.

---

## What I Would Do Differently with a Real Organisation

### Start with Discovery, Not Assumption

My risk scenarios are based on what I imagine employees might do with AI tools. They are plausible, but they are guesses. In a real organisation, I would not write a single risk scenario until I had spent time understanding what is actually happening on the ground.

I would conduct a short, anonymous survey asking employees which AI tools they use and for what purpose. I would interview a sample of staff from different departments: clinical, marketing, research, finance, and administration. I would ask IT to provide data on which public AI domains are being accessed from the corporate network, if network monitoring is in place. I would review the last six months of IT service desk tickets for any queries or incidents related to AI tools.

This discovery phase would surface risks I have not imagined and would deprioritise risks I have overestimated. The risk register would be grounded in evidence, not speculation. That is the professional standard I would aim for.

### Involve Stakeholders from the Start

In a real organisation, I would not write the risk register alone and present it as a finished document. I would draft an initial version and then convene a working group with representatives from IT security, legal, data protection, clinical governance, human resources, and a department head or two. I would walk through each risk and ask for challenge.

This approach has multiple benefits. It improves the quality of the assessment by incorporating diverse expertise. It builds shared ownership of the risks and controls, which makes implementation far more likely. It signals to the organisation that GRC is not a gatekeeping function that imposes rules from a distance, but a collaborative function that works with the business to manage risk proportionately.

### Design for Behaviour Change, Not Just Documentation

A policy document is not a control. The control is the changed behaviour that results from the policy. Too many organisations confuse publishing a policy with implementing a control. I do not want to carry that assumption into my GRC career.

In a real organisation, I would complement the policy document with a communication plan, a training module with real world scenarios and a short assessment, a set of frequently asked questions co developed with frontline staff, a simple decision aid like a one page flowchart for the question "Can I use AI for this task?", and a scheduled review six months after implementation to measure whether AI related incidents have decreased and whether staff can correctly identify what is and is not permitted.

I would also advocate for making it easy to do the right thing. If the approved enterprise AI tool is slower, harder to access, or less capable than the public tool, people will use the public tool regardless of the policy. The user experience of the approved tool is a security control. If the control is frustrating, it will be bypassed. This is a human factor that technical security people sometimes overlook, and I want to be the kind of GRC professional who does not overlook it.

### Connect the Risk Register to the Organisation's Real Appetite

In this exercise, I defined risk appetite implicitly through my scoring thresholds. A score above 15 was red and required treatment. I chose that threshold arbitrarily. In a real organisation, risk appetite is set by the board or senior leadership. It reflects the organisation's strategy, its regulatory environment, and its tolerance for different types of harm.

A risk that is red on my register might be accepted by a real board because the cost of the control exceeds the expected loss, or because the activity driving the risk is strategically critical. Alternatively, a risk I scored as medium might be unacceptable to a board in a heavily regulated sector. Without knowing the organisation's actual risk appetite, the entire colour coding system is just my personal judgement.

This is not a flaw in the exercise. It is a recognition that a risk register is not a standalone artefact. It exists within a governance structure that defines what "acceptable" means. I would approach any real risk assessment by first understanding that structure.

---

## Why This Matters for My GRC Development

I completed this project during a career transition. I am 36 years old. I have a recently completed MSc in Cyber Security from the University of Portsmouth. I have 1.5 years of prior experience in technical support and service coordination from my time in Bangladesh. I do not yet have direct GRC experience, and I am open about that.

This project confirmed something important for me. I want to work in GRC. I enjoyed the process of building the risk register. I found the policy drafting frustrating but deeply satisfying when a sentence finally landed clearly. The control mapping gave me a sense of rigour that I value. Writing this reflection has helped me clarify what kind of professional I want to be: someone who is technically informed but human centred, rigorous but collaborative, and honest about the limits of their own analysis.

I am not entering this field with a decade of direct experience. I am entering it with a structured way of thinking, a willingness to learn, and the humility to know that good risk assessment is never a solo activity. I believe I can add value to a GRC team from day one by contributing to risk registers, drafting policy language, mapping controls, and supporting stakeholder engagement. I also believe I have significant room to grow, and I am actively looking for a role where that growth is supported.

If you are reading this as a recruiter or a hiring manager, I hope this reflection gives you a sense of how I think. I am ready to do this work for real, and I am ready to learn from people who have been doing it longer than I have.

---

## Next Steps in My Learning

This project is the first in a planned series of GRC portfolio exercises. The topics I intend to cover next include the following.

Third party vendor risk assessment, where I will practice analysing a sample SOC 2 report and drafting a vendor due diligence summary. Data classification and retention scheduling, where I will build a data flow diagram and a retention schedule aligned to UK GDPR principles. A mock internal audit finding and management response, to practice the remediation tracking lifecycle.

Each project will follow the same structure: a fictional scenario, a set of deliverables, and an honest reflection on what I learned.

---

*End of Reflection Note*

*This document is fictional and was created as part of a self directed GRC learning portfolio. It does not describe professional experience with any real organisation.*