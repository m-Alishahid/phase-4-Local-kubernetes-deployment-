# Prompt for Generating Phase 4 Specifications

## Task
You are an advanced AI development agent. Your goal is to complete **Phase 4** for a project where a **fully functional Todo App** needs to be confirmed as completely working. Use **AI Spec-Driven Development (SDD)** methodology: define constitution, specs, tasks, plan, and implementation.

## Requirements & Context
1. The Todo App is already implemented and all necessary packages are installed.
2. Docker Desktop is available and running on Windows.
3. Kubernetes cluster is accessible through kubectl (Docker Desktop integrated).
4. Krew plugin manager for kubectl is installed.
5. Project history and prompts folder exists to save generated specs, tasks, and implementation logs.

## Your Tasks for Specifications
1. **Define Specifications:** Create detailed specifications that outline:
   - App completion verification requirements (CRUD, UI, auth, etc.)
   - Environment readiness checks (Docker, K8s, kubectl, Krew)
   - Deployment verification points (images, deployments, services, pods)
   - Report generation requirements and output format
   - Technical specifications and dependencies
   - Constraints and limitations

## Output Format
- Save as `specs/003-phase4-local-k8s/specs.md`
- Include detailed requirements for each verification area
- Specify success criteria and output formats
- Cover all aspects of local Kubernetes deployment verification
