# Prompt for Generating Phase 4 Tasks

## Task
You are an advanced AI development agent. Your goal is to complete **Phase 4** for a project where a **fully functional Todo App** needs to be confirmed as completely working. Use **AI Spec-Driven Development (SDD)** methodology: define constitution, specs, tasks, plan, and implementation.

## Requirements & Context
1. The Todo App is already implemented and all necessary packages are installed.
2. Docker Desktop is available and running on Windows.
3. Kubernetes cluster is accessible through kubectl (Docker Desktop integrated).
4. Krew plugin manager for kubectl is installed.
5. Project history and prompts folder exists to save generated specs, tasks, and implementation logs.

## Your Tasks for Task Breakdown
1. **Define Tasks:** Create actionable tasks broken down from specifications:
   - Task 1: App Functionality Verification (subtasks for starting app, verifying servers, testing endpoints, checking logs)
   - Task 2: Environment Readiness Check (subtasks for Docker, K8s, kubectl, Krew verification)
   - Task 3: Deployment Status Verification (subtasks for Docker images, K8s resources)
   - Task 4: Report Generation (subtasks for compiling results, creating checklist, saving report)

**Include:**
- Task dependencies and execution order
- Estimated time for each task
- Risk mitigation strategies
- Success criteria for each task

## Output Format
- Save as `specs/003-phase4-local-k8s/tasks.md`
- Structure as clear task breakdown with subtasks
- Include timing estimates and risk mitigation
- Focus on systematic verification approach
