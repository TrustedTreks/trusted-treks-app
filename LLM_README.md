# Trusted Treks – App Repository

## Purpose
This repository contains all application logic for the Trusted Treks shuttle and charter system, including:

- The customer-facing app experience
- Internal driver/owner-facing app modules
- Trip creation + booking flows
- API endpoints for dispatch, routing, and scheduling
- Backend logic for pricing, ride requests, and notifications
- Integration with route-engine outputs
- Communication with GPT Suite for smart automation

This is the core application layer that powers the Trusted Treks service.

---

## Folder Breakdown

### /frontend
User interfaces, mockups, HTML/JS components, UI flows, layouts.

### /backend
Application logic, server endpoints, dispatch functions, auth logic.

### /api
REST API definitions, endpoints, request/response schemas.

### /booking
Booking engine logic.

#### /booking/logic
Pricing, eligibility rules, scheduling logic, trip validation.

### Metadata
- `LLM_README.md`
- `instructions_for_agents.md`

---

## AI Agents Allowed to Access This Repo
- GPT-1 Operations Controller  
- GPT-2 Dispatch Engine  
- GPT-3 Finance AI  
- GPT-6 Routing AI  
- GPT-5 Marketing AI (limited: UI copy only)  
- GPT-8 Founder AI  

---

## What AI is Allowed To Do
- Write or improve app documentation  
- Generate UX/UI copy  
- Create REST API schemas  
- Document booking logic  
- Suggest backend structure  
- Build mock JSON payloads  
- Create customer journey flows  

---

## What AI is NOT Allowed To Do
- Write production server code without user confirmation  
- Add authentication/credential code  
- Delete or rename directories  
- Modify API secrets  
- Deploy scripts  
- Invent undocumented app interactions  

---

## Purpose Summary
The Trusted Treks App repository holds all app-facing logic and is the bridge between:

- Customers  
- Dispatch  
- Vehicles  
- AI agents  
- Routing systems  
- Admin console  

It must remain clean, structured, documented, and consistent with business-core and route-engine logic.
