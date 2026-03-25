# Prompt 07 — Bug Report Generator

## Prompt Text

You are a quality assurance assistant at a company operating in a [industry] sector, responsible for documenting software bugs.

Using the bug description provided below, generate a structured bug report that includes:

1. Bug title  
2. Description of the issue  
3. Steps to reproduce the issue 
4. Expected behaviour  
5. Actual behaviour  
6. Possible severity level (Low / Medium / High)

Present the report in a clear format suitable for development teams.

Bug description:
[Insert bug description here]

---

## Intended Workflow / Task

This prompt is used during product development or testing to convert informal bug descriptions into structured bug reports that can be shared with developers.

---

## Problem Being Solved

Bug descriptions reported by testers or users are often incomplete or inconsistent. Developers may spend additional time clarifying the issue before they can begin fixing it. This prompt also clarifies the steps to reproduce the issue which helps the developers to understand exactly where the bug is seated.

---

## Automation Potential

This prompt helps standardise bug reporting by converting raw descriptions into structured reports, improving communication between testers and developers.

---

## Risks and Limitations

AI-generated bug reports rely on the clarity and completeness of the original bug description. Potential limitations include:

- Incorrect reproduction steps if the original report lacks sufficient technical detail.

- Misinterpretation of system behaviour, particularly in complex software environments.

- Inaccurate severity assessment, since AI does not have full knowledge of system impact or dependencies.

The generated report should therefore be treated as a structured draft intended to improve documentation clarity. Quality assurance engineers or developers should verify the details before submitting the issue to the development tracking system.
