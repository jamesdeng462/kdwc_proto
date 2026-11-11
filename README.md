Kuza Elimu: Clickable Prototype

Education that ends in work, with proof employers can verify in 30 seconds.

A clickable, mobile-first prototype of Kuza Elimu's core journey: a refugee or host-community youth in Kakuma learns a digital skill, proves it through a real project, earns a partner-co-signed credential, and an employer verifies it in a public registry.

Built for the VIS Skills Immersion programme at African Leadership University (ALU), Kuza Elimu track. First pilot: Kakuma Digital Work Connect (KDWC).

Author: James Giir Deng, BSc Software Engineering, ALU

Live demo: https://claude.ai/artifact/2fPUs77WSErczXELznprBj

What problem does this show a solution to?

Youth in Kakuma can learn, but cannot prove what they know. 82% of East African employers struggle to verify candidates from camps (World Bank, 2022), and Kenya has no framework that recognises camp-issued credentials. Stakeholder research showed the barrier is trust, not skills. This prototype shows how an evidence-backed, externally anchored credential closes that gap.

What the prototype includes

Seven screens, one per step of the journey. Use the numbered buttons above the phone to jump to any screen.

#	Screen	What you can do	Insight behind it
1	Join	Start with a phone number only	Zawadi's deal-breakers: no national ID, no upfront payment
2	Pathway	View the skill, rubric and recognition anchor before enrolling	Employers want graded results, not "completed the course"
3	Learn	Save a 38 KB lesson; switch on "Simulate no signal"	Camp hub operator: outages are the daily norm
4	Project	Attach work and submit a real task instead of taking a quiz	Public skill demonstrations replace self-reported completion
5	Review	Step through assessor scoring and partner co-sign	NGOs cannot prove outcomes; every decision leaves a record
6	Credential	See a credential with ID, status and QR code	Zawadi had "no certificate an employer would trust"
7	Employer	Run the 30-second verification check	82% of employers cannot verify camp-based candidates

The panel beside the phone explains each screen and the stakeholder insight it answers.

How to try it
Open the live demo, or open Kuza Elimu_ Clickable Prototype.html in any modern browser.
Click Continue on screen 1 and follow the journey.
On screen 3, click Simulate no signal to see that learning still works offline.
On screen 4, click Attach your work before Submit for review becomes available.
On screen 5, click the simulate buttons twice: first for the assessor review, then for the co-sign.
On screen 7, click Run the 30-second check to watch the four verification steps complete.
Click Restart prototype to reset.
Design principles
Evidence before badge. A credential is issued only after observable work is reviewed against a published rubric.
External trust anchor. A partner or published skill standard co-signs. No endorsement is implied before a formal agreement.
Fast verification. An employer checks issuer, evidence and status without calling anyone.
Offline-first. Lessons are small and progress is kept on the phone.
No barriers to entry. No national ID and no upfront fee.
Technical notes
A single HTML file with inline CSS and JavaScript. No frameworks, libraries or build step.
Works in light and dark mode and adapts to desktop and mobile screens.
All data is sample data. Partner names appear as [partner or standard] placeholders until a formal agreement exists.
Limitations

This is a demonstration, not a working product.

Offline mode is simulated by a toggle. There is no service worker or real sync.
There is no backend. Nothing is saved, and no assessor, partner or registry exists yet.
The QR code is a sample pattern and cannot be scanned.
The credential ID and project data are illustrative.
Payments, mentorship, language options and scam reporting are not yet built. Testing flagged these as priorities.
Evidence and testing
Reality check (6.3): employer trust in the credential is the riskiest step in the user journey, which the co-signed, verifiable credential is designed to address.
Prototype testing (Deliverable 8.1): 20 young people in Kakuma reviewed the KDWC prototype and 18 (90%) recommended it for further development. Risks flagged: data costs and connectivity, payment clarity, scams, language, and beginner support.
Discovery research: one real interview (Zawadi, a composite persona's source interview) and four simulated interviews, treated as hypotheses until replaced with real ones.
Next steps
Run five more real stakeholder interviews.
Secure an employer letter of intent to serve as the first co-signing partner.
Add payment guidance, scam reporting and language options.
Build a real offline-sync layer and a working registry.
Run a 12-week pilot with 200 learners.
Project documents

Mission Research Report · Stakeholder Needs Analysis · Problem Definition Interview Kit · Ideation Log · Strategic Wireframe · Reality Check Testing Log · Prototype Testing Report · SRS v1.0

Sources

UNHCR Kenya (2024); ILO World Employment and Social Outlook (2023); World Bank Kenya Jobs Diagnostic (2022); UNHCR Global Trends (2023); Danish Refugee Council and Mercy Corps (2022); IRC (2022).
