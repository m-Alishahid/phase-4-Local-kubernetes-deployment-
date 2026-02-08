# Prompt for Generating Phase 4 Plan

## Task
You are an advanced AI development agent. Your goal is to complete **Phase 4** for a project where a **fully functional Todo App** needs to be confirmed as completely working. Use **AI Spec-Driven Development (SDD)** methodology: define constitution, specs, tasks, plan, and implementation.

## Requirements & Context
1. The Todo App is already implemented and all necessary packages are installed.
2. Docker Desktop is available and running on Windows.
3. Kubernetes cluster is accessible through kubectl (Docker Desktop integrated).
4. Krew plugin manager for kubectl is installed.
5. Project history and prompts folder exists to save generated specs, tasks, and implementation logs.

## Your Tasks for Plan
1. **Define Plan:** Create a logical execution plan that outlines:
   - Sequential task order with rationale for each phase
   - Execution strategy (evidence-based, fail-fast approach)
   - Risk assessment and contingency plans
   - Timeline estimates for each phase
   - Success metrics and deliverables
   - Risk mitigation strategies

**Structure the plan in phases:**
- Phase 1: Foundation Setup (Environment Verification)
- Phase 2: Core Functionality (App Verification)
- Phase 3: Infrastructure Status (Deployment Verification)
- Phase 4: Synthesis (Report Generation)

## Output Format
- Save as `specs/003-phase4-local-k8s/plan.md`
- Include clear phase breakdown with rationale
- Specify execution strategy and risk management
- Provide realistic timeline estimates
- Focus on systematic verification and reporting
