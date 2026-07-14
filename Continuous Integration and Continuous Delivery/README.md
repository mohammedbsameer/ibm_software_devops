# Continuous Integration and Continuous Delivery (CI/CD) Coursework

This directory contains the hands-on lab manuals, guides, and quizzes for the **Continuous Integration and Continuous Delivery (CI/CD)** course. The labs focus on cloud-native CI/CD automation using **Tekton Pipelines** and **GitHub Actions** to automate software testing, building, and deployment workflows.

---

## 📚 Table of Contents

1. [Lab 1: Building a Tekton Pipeline](#-lab-1-building-a-tekton-pipeline)
2. [Lab 2: Adding a GitHub Trigger](#-lab-2-adding-a-github-trigger)
3. [Lab 3: Using Tekton Catalog Tasks](#-lab-3-using-tekton-catalog-tasks)
4. [Lab 4: Automated Unit Testing](#-lab-4-automated-unit-testing)
5. [Lab 5: Building Container Images with Tekton](#-lab-5-building-container-images-with-tekton)
6. [Lab 6: Deploying to Kubernetes with Tekton](#-lab-6-deploying-to-kubernetes-with-tekton)
7. [Lab 7: Code Coverage Automation](#-lab-7-code-coverage-automation)
8. [Lab 8: Building a GitHub Actions Workflow](#-lab-8-building-a-github-actions-workflow)
9. [📝 Quizzes & Final Exam](#-quizzes--final-exam)

---

## 🛠️ Lab Summaries & Learning Objectives

### 1. Building a Tekton Pipeline
* **File:** [01_base_pipeline.md.html](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/01_base_pipeline.md.html)
* **Objectives:** 
  * Create a base Tekton Pipeline and Task.
  * Apply parameters to tasks and pipelines to make them reusable.
  * Structure Tekton pipeline projects using standard resource specifications (Tasks, Pipelines, PipelineRuns).

### 2. Adding a GitHub Trigger
* **File:** [02_add_github_trigger.md.html](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/02_add_github_trigger.md.html)
* **Objectives:**
  * Configure Tekton Triggers components including `TriggerTemplates`, `TriggerBindings`, and `EventListeners`.
  * Set up webhooks in GitHub to trigger a Tekton pipeline run automatically upon a git push event.

### 3. Using Tekton Catalog Tasks
* **File:** [03_use_tekton_catalog.md.html](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/03_use_tekton_catalog.md.html)
* **Objectives:**
  * Pull and reuse community-defined tasks from the official Tekton Catalog.
  * Implement the community `git-clone` task to fetch repositories into Tekton workspace storage.

### 4. Automated Unit Testing
* **File:** [04_unit_test_automation.md.html](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/04_unit_test_automation.md.html)
* **Objectives:**
  * Create tasks to install software dependencies and execute unit tests (e.g., using `pytest` or `nose`).
  * Automate the validation of code quality during pipeline runs.

### 5. Building Container Images with Tekton
* **File:** [05_build_an_image.md.html](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/05_build_an_image.md.html)
* **Objectives:**
  * Use container image build tools (such as `buildah` or `kaniko`) inside a Tekton task.
  * Build a container image from a Dockerfile and push it to a secure Container Registry.

### 6. Deploying to Kubernetes with Tekton
* **File:** [06_deploy_to_kubernetes.md.html](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/06_deploy_to_kubernetes.md.html)
* **Objectives:**
  * Integrate deployments with the Kubernetes API within a Tekton pipeline.
  * Automate updates to Kubernetes Deployments, Services, and Pods.

### 7. Code Coverage Automation
* **File:** [code_coverage.md.html](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/code_coverage.md.html)
* **Objectives:**
  * Configure testing tasks to generate code coverage reports.
  * Integrate code coverage reporting tools into the continuous integration flow.

### 8. Building a GitHub Actions Workflow
* **File:** [github_actions.md.html](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/github_actions.md.html)
* **Objectives:**
  * Author a GitHub Actions workflow YAML file inside `.github/workflows/`.
  * Set up event triggers, job runners, environment variables, and execution steps.

---

## 📝 Quizzes & Final Exam
* **Module 1 Graded Quiz:** [Module 1 - Graded Quiz.jpg](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/Module%201%20-%20Graded%20Quiz.jpg)
* **Module 2 Graded Quiz:** [Module 2 - Graded Quiz.jpg](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/Module%202%20-%20Graded%20Quiz.jpg)
* **Module 3 Graded Quiz:** [Module 3 - Graded Quiz.jpg](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/Module%203%20-%20Graded%20Quiz.jpg)
* **Final Exam:** [Final Exam.jpg](file:///c:/Users/Mohammed%20Sameer/OneDrive/Desktop/softwaredevops/IBMDEVOPS/Continuous%20Integration%20and%20Continuous%20Delivery/Final%20Exam.jpg)
