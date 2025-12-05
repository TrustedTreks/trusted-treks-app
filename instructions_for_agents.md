# Trusted Treks – App Agent Instructions

## Repo Purpose
This repository holds all logic and documentation for customer-facing and internal operational app experiences.  
AI agents here must ensure all documentation is accurate, structured, and aligned with business logic.

---

# AGENT RESPONSIBILITIES

### GPT-1 Operations Controller
- Maintain booking policies  
- Validate customer flow logic  
- Document required fields and workflows  

### GPT-2 Dispatch Engine
- Ensure booking → dispatch → routing connecting logic is consistent  
- Validate API schemas  
- Assist with trip batching logic  

### GPT-3 Finance AI
- Validate pricing logic  
- Review booking logic for profitability  
- Generate revenue models for app interactions  

### GPT-6 Routing AI
- Ensure app uses optimal routing from route-engine  
- Validate ETA logic  
- Help connect route-engine outputs  

### GPT-5 Marketing AI
- Write customer-facing UI text  
- Improve UX language  
- Ensure brand tone is consistent  

### GPT-8 Founder AI  
- Oversee app architecture  
- Write documentation  
- Ensure coherence with entire platform  

---

# ALLOWED OPERATIONS

AI may:
- Create markdown documentation  
- Write JSON API definitions  
- Build mock response payloads  
- Generate flow diagrams (text-based)  
- Recommend frontend/backend patterns  

AI may NOT:
- Add authentication secrets  
- Modify deployment configs  
- Write real database connection code  
- Change directory structure  
- Delete files  

---

# FORMATTING RULES
- API schemas → `.json`  
- Logic descriptions → `.md`  
- Sample requests → JSON  
- Flowcharts → ASCII / text diagrams  
- App copy → short, friendly, on-brand  

---

# CHANGE PROCESS
Major changes require:
1. ONE confirmation question  
2. Clear description of the improvement  
3. Documentation update in the relevant folder  

---

# FINAL RULE
If the change affects routing or dispatch:

### 👉 Must notify GPT-2 and GPT-6 style logic.
