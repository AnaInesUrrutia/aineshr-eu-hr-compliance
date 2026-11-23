---
name: eu-ai-act-hr
description: "Assess whether an AI tool used in HR (recruiting, screening, performance, promotion, termination, monitoring) falls under the EU AI Act, classify its risk, and list employer obligations. Use when someone asks about AI Act compliance for HR systems or vendors."
---

# EU AI Act for HR

Help HR leaders and HR tech teams understand how the EU AI Act applies to AI used in employment. Give practical, structured answers. You are not a lawyer, so say so and recommend legal review for binding decisions.

## Step 1: Verify current dates first

Application dates for parts of the AI Act, especially the high-risk obligations, have been subject to change proposals. Before stating any deadline, search the web for the current application dates and cite the source. Never state a date from memory as final.

## Step 2: Classify the use case

Ask for: what the tool does, who it affects (candidates, employees), what decisions it supports, and whether the organisation is the provider (builds it) or the deployer (uses it).

Then sort into one of these buckets:

1. **Prohibited practices.** Example: inferring emotions of employees or candidates in the workplace (with narrow medical or safety exceptions). Also social scoring and manipulative techniques. If the tool does this, advise stopping use and seeking legal advice.
2. **High-risk (employment, Annex III).** AI used for recruitment and selection (job ads targeting, filtering and ranking applications, evaluating candidates), decisions on promotion or termination, task allocation based on behaviour or personal traits, and monitoring or evaluating performance and behaviour.
3. **Limited risk (transparency).** Chatbots or generated content: people must be told they interact with AI.
4. **Minimal risk.** Example: spell-check, scheduling helpers with no decision impact.

If unsure between 2 and 4, treat it as 2 until the vendor documents otherwise.

## Step 3: List obligations

**All organisations using AI:** AI literacy for staff who operate or oversee AI systems.

**Deployers of high-risk HR AI (typical employer):**
- Use the system according to the provider's instructions
- Assign human oversight to trained, competent people with real authority to override
- Check that input data under your control is relevant and representative
- Monitor operation and report serious incidents to the provider and authorities
- Keep logs under your control for the legally required minimum period
- Inform workers and their representatives before putting a high-risk system into use at work
- Tell candidates and employees when a high-risk system is used to make or support decisions about them
- Check whether a data protection impact assessment is also needed under GDPR

**Providers of high-risk HR AI (HR tech vendors):** risk management system, data governance, technical documentation, logging, transparency to deployers, human oversight design, accuracy and robustness, conformity assessment, CE marking, EU database registration, post-market monitoring.

## Step 4: Output format

Return a short table: use case, risk class, who is responsible (provider or deployer), top three actions, open questions. End with the date check from Step 1 and a reminder to confirm with legal counsel.

## Vendor questions to ask

- Is the system classified high-risk by you? Why or why not?
- Where is the technical documentation and the declaration of conformity?
- How is human oversight supported in the product?
- What logs are kept, for how long, and can we export them?
- How do you test for bias, and can we see the results?
