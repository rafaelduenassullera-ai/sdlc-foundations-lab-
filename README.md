STUDENT WORKSHEET: SDLC, AGILE, DEVOPS & GIT FOUNDATIONS

Course Code / Subject: Computer Engineering
Student Name: John Rafael D. Sullera
Date: August 29, 2026  	Section: BSIT 3.5

GitHub Repository URL: https://github.com/rafaelduenassullera-ai/sdlc-foundations-lab-

PART 1: GITHUB ONBOARDING & SETUP VERIFICATION 

Part 1: GitHub Account Creation & Onboarding 
Objective: Set up a centralized remote repository environment for future CI/CD and GitFlow collaboration.
Account Registration 
Go to github.com and click Sign Up.
Enter your academic email address, create a strong password, and select a professional username (e.g., j-perminola).
Complete the verification puzzle and enter the launch code sent to your email.
Profile & Security Setup 
Set your display name to your full name and upload a profile picture.
Go to Settings > Password and authentication and enable Two-Factor Authentication (2FA) using an authenticator app or SMS.
Verification Task 
Click the + icon in the top right and select New repository.
Name the repository sdlc-foundations-lab, set visibility to Public, check Add a README file, and click Create repository.
Copy your public repository URL to submit alongside Part 2.

Task Checklist
[✓] Created GitHub account using academic email.
[✓] Enabled Two-Factor Authentication (2FA) in Settings.
[✓] Created public repository named sdlc-foundations-lab with a README.md.
[✓] Pasted public repository link in the header above.




PART 2: REAL-WORLD ENGINEERING SCENARIOS 
Scenario A: SDLC & Framework Selection

Context: A fintech company wants to release a new peer-to-peer payment feature. A government regulatory agency requires complete compliance auditing before release, but competitors are rapidly capturing market share.
Task:
Compare Waterfall vs. Agile (Scrum) for this launch using the criteria below:
Adaptability & Time-to-Market


Regulatory & Compliance Risk Handling


Choose a hybrid or primary framework (e.g., Scrum vs. Waterfall vs. Spiral). Explain your reasoning in 2–3 sentences.

Framework Comparison Table


Criteria
Waterfall 
Agile (Scrum) 
Adaptability & Time-to-Market


Waterfall follows a fixed sequence, making changes difficult and potentially slowing down the release. 
Scrum is flexible and allows the team to quickly adapt to changes while delivering features in smaller increments. 
Regulatory & Compliance Risk Handling


Waterfall provides strong documentation and clear phases, which makes compliance auditing easier. 
Scrum can handle compliance requirements, but the team must continuously include documentation and regulatory checks during each sprint. 


2. Framework Recommendation & Justification:
Which primary or hybrid framework (e.g., Scrum, Waterfall, or Spiral) do you recommend for this fintech regulatory project? Explain your choice in 2–3 sentences.





Answer:
I recommend Agile (Scrum) for this fintech project. Scrum allows the company to develop and release the peer-to-peer payment feature faster while adapting to changes and competing with other companies. They can also adapt to requirements that ensures the standards of the government in every sprint.



Scenario B: DevOps & CI/CD Pipeline Breakdown

Context: A team merges code, but the production app breaks during deployment because testing was done manually on individual laptops rather than in an automated pipeline.
Task:
Identify where the communication and process gap occurred between Dev and Ops.
Map out the automated CI/CD pipeline stages (Plan -> Code -> Build -> Test -> Release -> Deploy ->Operate -> Monitor) and state which stage would catch this bug before it reaches production.

1. Gap Analysis:
Identify where the communication and process breakdown occurred between Dev and Ops.

Answer:
The communication and process gap happened because developers tested the application manually on their individual laptops instead of using a shared automated testing environment. This resulted in the application breaking when it was deployed to production.

2. Pipeline Stage Identification:
Fill in the missing stages of the continuous assembly line and circle/bold the stage that catches local testing bugs before production release:


Plan -> Code -> Build -> Test -> Release -> Deploy -> Operate -> Monitor

Scenario C: Git Lifecycle & Branching Strategy
1. Data Movement Command Mapping

Write the standard Git command used to transfer code between each environment:

Working Directory ->  Staging Area: git add


Staging Area -> Local Repository: git commit


Local Repository -> Remote Repository (GitHub): git push
Remote Repository -> Working Directory: git pull

2. GitFlow Collision Prevention:
Explain how utilizing Feature Branches and a Develop branch prevents two developers from overwriting each other's code on Main. ( 2 to 3 sentences)

Answer:
Feature Branches allow developers to work on separate features without directly changing the Main branch. Developers can safely make changes in their own branches and merge them into the Develop branch for testing and integration before approved code is merged into Main, reducing the risk of overwriting each other's work. 


FINAL SUBMISSION CHECKLIST
[✓] Part 1 checklist completely verified.
[✓] All scenario questions answered clearly.
[✓] Repository set to Public for grading access.
