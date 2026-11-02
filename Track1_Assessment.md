Track 1 — Engineering Issue Investigation

Problem statement
Find one original, non-duplicate, technically meaningful issue in UnvibeCode by using it on a real repository. Investigate its cause or boundaries, gather reproducible evidence, and submit it as a well-structured GitHub issue.

You can investigate incorrect code relationships, missing or misleading workflow links, unsupported claims in risk findings, inaccurate or missing context, runtime failures, platform-specific problems, or a specific engineering usability defect.

Depth matters more than issue count. One thoroughly investigated, reproducible, high-impact issue can make a stronger case for internship selection or a cash prize than several superficial reports. Finding a genuine defect is not the same as merely requesting a new feature.

Before you file
Search open and closed UnvibeCode issues and check whether the same underlying problem has already been reported. Do not submit duplicate issues with slightly different wording.
Verify expected behavior against the repository's actual source code or reliable product behavior.
Re-run the case where possible. Differentiate a repeatable defect from a hypothesis or misunderstanding.
Pick one well-scoped issue; do not bundle unrelated bugs together.
Remove private repository content, credentials, tokens, customer data, and other secrets from evidence.
Required GitHub issue format
Create your issue at UnvibeCode Issues → New issue using this template:

Title: [Bug] <component> — <specific observable failure>

## 1. Problem summary
What is wrong, and why does it matter to a developer?

## 2. Test environment
- UnvibeCode version:
- Operating system / Python version:
- Public repository URL and commit or release:
- Relevant command:

## 3. Steps to reproduce
1. <Exact preparation step>
2. <Exact command or user action>
3. <Where to inspect the result>

## 4. Expected behavior
What should happen? Point to supporting source code or an explicit product expectation.

## 5. Actual behavior
What happened instead? Include the exact error or incorrectly generated result.

## 6. Evidence
- Relevant file/function names and line numbers:
- Small sanitized log excerpt, output excerpt, or screenshot:
- Source-code comparison supporting the finding:

## 7. Impact and scope
Who is affected? Is this a wrong answer, missing context, crash, or usability problem?
Does it occur on one repository or multiple tested cases?

## 8. Suspected cause / suggested fix (if known)
Explain your hypothesis and how an engineer could validate it.
If not known, write "Not yet identified" rather than guessing.

## 9. Duplicate check
Links to the closest existing issues checked, and why this is distinct.
Reproduction quality: Another engineer should be able to follow the steps, observe the same outcome, and understand the expected-versus-actual difference without asking you to explain the report. If your finding is non-deterministic, say how often it occurs and under which conditions.

Track 1 deliverable: Submit one non-duplicate GitHub issue and paste its URL, the analyzed repository URL, and a short summary into the Google form. Do not submit a pull request for this challenge.

Track 1 judging — 100 points
Criterion	Points
Technical depth, root-cause investigation, and reasoning	35
Reproducibility and strength of evidence	30
Real developer impact and usefulness	20
Originality / verified non-duplicate scope	10
Clarity of issue report	5
