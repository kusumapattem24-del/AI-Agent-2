# Topic 2 Assessment
## Transitioning from Automation to Agentic Workflows – Build a Semantic Intent Router

### 1. Assessment Overview
This assessment evaluates your ability to design, configure, execute, and validate an AI-powered Semantic Intent Router in n8n. You will build an agentic workflow that classifies customer requests, applies secure system prompt guardrails, enforces structured JSON outputs, and dynamically routes requests based on semantic intent and priority.

### 2. Assessment Objective
Demonstrate the ability to transition from traditional automation to agentic workflows by implementing AI Agent configuration, prompt engineering, structured output parsing, semantic classification, priority-based routing, and prompt-injection resistance.

### 3. Prerequisites
- Review the Requirement Document before starting.
- Review the Implementation Guide.
- Complete Topic 1.
- Have an active n8n workspace with configured LLM credentials.
- Have a GitHub account for source code submission.

### 4. Assessment Tasks
1. **Exercise 1** – Configure a mock customer email input.
2. **Exercise 2** – Configure an AI Agent with Chat Model, Temperature=0.0, Max Tokens=500, Max Iterations=5.
3. **Exercise 3** – Create a secure System Prompt with guardrails.
4. **Exercise 4** – Configure a Structured Output Parser with `category`, `priority`, `urgency_reason`, and `order_id`.
5. **Exercise 5** – Verify semantic classification using multiple customer requests.
6. **Exercise 6** – Implement IF-node routing for High and Normal priority.
7. **Exercise 7** – Validate resistance to prompt injection.
8. **Exercise 8** – Build and execute the complete Semantic Intent Router workflow.

### 5. Practical Assessment Checklist
- [ ] Mock Customer Email Configured
- [ ] AI Agent Configured
- [ ] Chat Model Connected
- [ ] Temperature = 0.0
- [ ] Max Tokens = 500
- [ ] Max Iterations = 5
- [ ] System Prompt Configured
- [ ] Guardrails Implemented
- [ ] Structured Output Parser Added
- [ ] Semantic Classification Verified
- [ ] Priority Routing Working
- [ ] Prompt Injection Test Passed
- [ ] End-to-End Workflow Completed

### 6. Assessment Success Criteria
- Build a complete semantic intent routing workflow.
- Configure AI Agent and Chat Model correctly.
- Implement secure prompt guardrails.
- Generate structured JSON outputs.
- Classify requests accurately.
- Route requests dynamically based on priority.
- Demonstrate prompt injection resistance.
- Submit all required deliverables.

### 7. Required Deliverables
| Deliverable | Requirement |
|---|---|
| Loom/YouTube Demo Video | Mandatory |
| Public GitHub Repository | Mandatory |
| Exported n8n Workflow JSON | Mandatory |
| Documentation (PDF/DOCX) | Recommended |
| Workflow & Execution Screenshots | Mandatory |
| README / Setup Instructions | Mandatory |

### 8. Submission Guidelines
Submit through the LMS:
- Demo video showing workflow creation, AI Agent configuration, structured output parser, semantic classification, routing, prompt injection validation, and execution logs.
- Public GitHub repository containing workflow JSON, documentation, screenshots, README, and supporting files.
- Additional comments describing assumptions, challenges, limitations, or enhancements.

### 9. Final Submission Checklist
- [ ] Completed all assessment exercises
- [ ] Verified workflow execution
- [ ] Pushed latest code to GitHub
- [ ] Verified repository is public
- [ ] Uploaded demo video
- [ ] Reviewed all deliverables

### 10. Important Note
Before submitting, ensure your Loom/YouTube demonstration, public GitHub repository, exported n8n workflow JSON, documentation, screenshots, and README are accessible. Incomplete submissions may not be evaluated.
