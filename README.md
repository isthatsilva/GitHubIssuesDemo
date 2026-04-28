# GitHub Issues Demo
![Github licence](http://img.shields.io/badge/license-MIT-blue.svg)

## Overview
This repository demonstrates how **GitHub Issues** can be used for bug tracking, task management, feature requests, and team collaboration in software development projects.

GitHub Issues allows developers and project teams to:
- Report and track bugs
- Request new features
- Assign tasks to team members
- Label and prioritize work
- Discuss and resolve problems collaboratively
- Link issues to commits and pull requests

---

## Objectives
This demo shows how to use GitHub Issues for:

- Creating bug reports
- Managing feature requests
- Assigning issues
- Using labels and milestones
- Tracking issue progress
- Closing issues through commits or pull requests

---

## Features Demonstrated

### 1. Creating an Issue
Navigate to the **Issues** tab and click **New Issue**.

Example bug report:

**Title:** Login button does not respond

**Description:**
- Click login button
- Nothing happens
- Console shows JavaScript error

**Label:** bug

**Assignee:** Developer Name

---

## 2. Issue Labels
Labels help categorize and prioritize issues.

Examples:

| Label | Purpose |
|-------|---------|
| bug | Defect or error |
| enhancement | Feature improvement |
| documentation | Documentation updates |
| help wanted | Needs contributors |
| priority-high | Urgent issue |

---

## 3. Issue Templates
This repository includes templates for standardized reporting:

### Bug Report Template
Captures:
- Description
- Steps to reproduce
- Expected behavior
- Actual behavior
- Screenshots

### Feature Request Template
Captures:
- Problem statement
- Proposed solution
- Additional context

---

## 4. Assigning Issues
Issues can be assigned to contributors for ownership.

Example:

Issue #12 → Assigned to @developer

---

## 6. Linking Issues to Pull Requests
Use keywords in commits or PRs:

```bash
Fixes #10
Closes #14
Resolves #7
```

GitHub automatically closes the issue when merged.

---

## Example Workflow

1. User reports a bug
2. Create GitHub Issue
3. Add labels and assign developer
4. Discuss solution in issue comments
5. Create branch and fix bug
6. Submit Pull Request
7. Merge PR using:

```bash
Fixes #15
```

8. Issue automatically closes

---

## Sample Issues Included

| Issue | Type | Status |
|------|------|--------|
| #1 Login bug | Bug | Closed |
| #2 Dark mode feature | Enhancement | Open |
| #3 Update README | Documentation | In Progress |

---

## Screenshots (Optional)
Add screenshots in `/docs/screenshots/`

Example:

```md
![Create Issue](docs/screenshots/create-issue.png)
![Issue Labels](docs/screenshots/labels.png)
![Milestones](docs/screenshots/milestones.png)
```

---

## Benefits of GitHub Issues
- Built into GitHub
- Easy collaboration
- Integrates with GitHub Projects
- Supports Agile/Scrum workflows
- Tracks bugs and enhancements in one place

---

## How to Try This Demo

Clone repository:

```bash
git clone https://github.com/yourusername/github-issues-demo.git
cd github-issues-demo
```

Then:
- Open the **Issues** tab
- Create a sample issue
- Apply labels
- Assign collaborators
- Link issue to a pull request

---

## Technologies Used
- GitHub Issues
- GitHub Projects
- Markdown
- Git / GitHub Workflow

