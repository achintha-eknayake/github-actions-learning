# 🚀 GitHub Actions Learning Repository

Welcome to your hands-on learning journey with **GitHub Actions**! This repository is designed for beginners and intermediate developers who want to master CI/CD automation.

## 📚 What You'll Learn

- ✅ GitHub Actions fundamentals (workflows, jobs, steps)
- ✅ Automating builds and tests
- ✅ CI/CD pipeline creation
- ✅ Deploying applications to Azure App Service
- ✅ Working with secrets and environment variables
- ✅ Real-world workflow examples

## 🎯 Target Audience

- Beginners to CI/CD
- Developers wanting to automate their workflows
- Students learning DevOps practices
- Anyone interested in GitHub Actions

## 📋 Prerequisites

Before starting, make sure you have:

- A GitHub account
- Basic Git knowledge
- Node.js installed (v16 or higher) for running sample apps
- (Optional) Azure account for deployment workflows

---

## 🏅 Digital Badges - Earn Them All!

Complete the tasks at each level to earn prestigious digital badges! 

### Level 1: Beginner Badge
![Beginner Badge](images/Beginner.png)

**Requirements:**
- Complete Tasks 1, 2, and 3 from [TASKS.md](TASKS.md#beginner-tasks-)
- Submit proof (screenshots) of:
  - ✅ Task 1: Running the Hello World workflow
  - ✅ Task 2: Workflow triggering on push
  - ✅ Task 3: Local tests passing

**How to Earn:** Submit a [Beginner Submission](#beginner-submission-template) via Pull Request

---

### Level 2: Intermediate Badge
![Intermediate Badge](images/Intermediate.png)

**Requirements:**
- Complete Tasks 4, 5, 6, and 7 from [TASKS.md](TASKS.md#intermediate-tasks-)
- Submit proof of:
  - ✅ Task 4: Custom workflow running
  - ✅ Task 5: Environment variables in logs
  - ✅ Task 6: Secret access (masked in logs)
  - ✅ Task 7: Matrix testing with multiple Node versions

**How to Earn:** Submit an [Intermediate Submission](#intermediate-submission-template) via Pull Request

---

### Level 3: Advanced Badge
![Advanced Badge](images/Advanced.png)

**Requirements:**
- Complete Tasks 8, 9, and 10 from [TASKS.md](TASKS.md#advanced-tasks-)
- Submit proof of:
  - ✅ Task 8: Artifacts uploaded & downloaded
  - ✅ Task 9: Conditional execution working
  - ✅ Task 10: PR created with templates

**How to Earn:** Submit an [Advanced Submission](#advanced-submission-template) via Pull Request

---

## 📝 Submission Process

### How to Submit Your Badges

1. **Complete Tasks**: Finish all tasks at your desired level
2. **Gather Evidence**: Take screenshots of successful workflow runs
3. **Create Pull Request**: Open a PR with your submission (see templates below)
4. **Add Label**: Add `submission` label to your PR
5. **Add Assignee**: Assign `@nisalgunawardhana` for review
6. **Status**: Your submission will be marked as `pending-review`
7. **Earn Badge**: Once approved, your badge is awarded! 🎉

---

## 📋 Submission Templates

### Beginner Submission Template

```markdown
## 🎓 Beginner Level Badge Submission

**Submitted by:** @YOUR-USERNAME
**Date:** [Date]
**Status:** Pending Review

### Tasks Completed

- [ ] Task 1: Run Your First Workflow
- [ ] Task 2: Understand Workflow Triggers  
- [ ] Task 3: Build and Test Locally

### Evidence

#### Task 1: Hello World Workflow Execution
[Attach screenshot of workflow running successfully]

#### Task 2: Push Trigger
[Attach screenshot of workflow triggered by push]

#### Task 3: Local Tests Passing
[Attach screenshot of npm test output]

### Notes
[Any additional notes or challenges faced]

---

**Ready for review!** ✅
```

**To Submit:**
1. Fork this repository
2. Create a new branch: `git checkout -b submission/beginner-badge-yourname`
3. Create a new file: `.github/submissions/beginner-badge-YOURNAME.md`
4. Use the template above and add your evidence
5. Commit and push: `git push origin submission/beginner-badge-yourname`
6. Create a Pull Request
7. Add labels: `submission`, `beginner`, `pending-review`
8. Assign: `@nisalgunawardhana`

---

### Intermediate Submission Template

```markdown
## ⭐ Intermediate Level Badge Submission

**Submitted by:** @YOUR-USERNAME
**Date:** [Date]
**Status:** Pending Review

### Tasks Completed

- [ ] Task 4: Create a Custom Workflow
- [ ] Task 5: Add Environment Variables
- [ ] Task 6: Use GitHub Secrets
- [ ] Task 7: Matrix Testing

### Evidence

#### Task 4: Custom Workflow
[Attach screenshot of custom workflow running on develop branch]

**Workflow file created:** `.github/workflows/custom.yml`

#### Task 5: Environment Variables
[Attach screenshot showing environment variables in logs]

#### Task 6: GitHub Secrets
[Attach screenshot showing secret access (secret will be masked)]

#### Task 7: Matrix Testing
[Attach screenshot showing 3 parallel jobs for different Node versions]

### Workflow Details
- Branches: develop
- Node versions tested: [list versions]
- All tests: PASSING ✅

### Notes
[Any additional implementation details]

---

**Ready for review!** ✅
```

**To Submit:**
1. Fork this repository
2. Create a new branch: `git checkout -b submission/intermediate-badge-yourname`
3. Create a new file: `.github/submissions/intermediate-badge-YOURNAME.md`
4. Use the template above and add your evidence
5. Commit and push: `git push origin submission/intermediate-badge-yourname`
6. Create a Pull Request
7. Add labels: `submission`, `intermediate`, `pending-review`
8. Assign: `@nisalgunawardhana`

---

### Advanced Submission Template

```markdown
## 🏆 Advanced Level Badge Submission

**Submitted by:** @YOUR-USERNAME
**Date:** [Date]
**Status:** Pending Review

### Tasks Completed

- [ ] Task 8: Upload and Download Artifacts
- [ ] Task 9: Conditional Execution
- [ ] Task 10: Create a PR and Use Issue Templates

### Evidence

#### Task 8: Artifacts
[Attach screenshots showing:]
- Artifact uploaded successfully
- Artifact downloaded from Actions UI
- Job dependencies working

#### Task 9: Conditional Execution
[Attach screenshots showing:]
- Deployment step skipped on develop branch
- Deployment step executed on main branch
- Conditions evaluated correctly

#### Task 10: PR with Templates
[Provide links to:]
- Your PR: [URL]
- Your Issue: [URL]
- Templates used correctly

### Advanced Implementation Details

**Artifacts:**
- Upload directory: `[path]`
- Artifact name: `[name]`
- Download successful: ✅

**Conditions:**
- Branch-based conditions: ✅
- Event-based conditions: ✅

**Community Participation:**
- PR created with proper template: ✅
- Issue created using template: ✅

### Notes
[Any additional advanced techniques used]

---

**Ready for review!** ✅
```

**To Submit:**
1. Fork this repository
2. Create a new branch: `git checkout -b submission/advanced-badge-yourname`
3. Create a new file: `.github/submissions/advanced-badge-YOURNAME.md`
4. Use the template above and add your evidence
5. Commit and push: `git push origin submission/advanced-badge-yourname`
6. Create a Pull Request
7. Add labels: `submission`, `advanced`, `pending-review`
8. Assign: `@nisalgunawardhana`

---

## ✅ Review Criteria

Your submissions will be reviewed based on:

| Criteria | Beginner | Intermediate | Advanced |
|----------|----------|--------------|----------|
| **Tasks Completed** | 3/3 | 4/4 | 3/3 |
| **Evidence Quality** | Clear screenshots | Detailed logs | Comprehensive documentation |
| **Understanding** | Concepts understood | Practical implementation | Advanced techniques |
| **Workflow Files** | N/A | Present & working | Present & optimized |
| **Status Labels** | `submission` | `submission` | `submission` |
| **Time to Review** | 2-3 days | 2-3 days | 3-5 days |

---

## 🗂️ Repository Structure

```
github-actions-learning/
├── README.md                          # You are here!
├── TASKS.md                           # All hands-on exercises & task links
├── docs/                              # Learning documentation
│   ├── 01-what-is-github-actions.md
│   ├── 02-workflow-basics.md
│   ├── 03-triggers-and-events.md
│   ├── 04-jobs-and-steps.md
│   ├── 05-secrets-and-env.md
│   ├── 06-build-and-test.md
│   └── 07-deploy-to-azure.md
├── images/                            # Digital badges
│   ├── Beginner.png
│   ├── Intermediate.png
│   └── Advanced.png
├── .github/
│   ├── workflows/                     # Example workflows
│   │   ├── hello-world.yml
│   │   ├── build-test.yml
│   │   └── deploy-azure-app-service.yml
│   ├── submissions/                   # Badge submissions (create this folder)
│   ├── ISSUE_TEMPLATE/                # Issue templates
│   └── PULL_REQUEST_TEMPLATE.md       # PR template
└── sample-app/                        # Sample Node.js application
    ├── src/
    ├── tests/
    ├── package.json
    └── README.md
```

## 🚦 Getting Started

### 1. Clone this Repository

```bash
git clone https://github.com/YOUR-USERNAME/github-actions-learning.git
cd github-actions-learning
```

### 2. Follow the Learning Path

Start with the documentation in order:

1. [What is GitHub Actions?](docs/01-what-is-github-actions.md)
2. [Workflow Basics](docs/02-workflow-basics.md)
3. [Triggers and Events](docs/03-triggers-and-events.md)
4. [Jobs and Steps](docs/04-jobs-and-steps.md)
5. [Secrets and Environment Variables](docs/05-secrets-and-env.md)
6. [Build and Test](docs/06-build-and-test.md)
7. [Deploy to Azure](docs/07-deploy-to-azure.md)

### 3. Try the Sample App

```bash
cd sample-app
npm install
npm start
```

Visit `http://localhost:3000` to see the app running.

### 4. Complete the Tasks & Earn Badges

Check [TASKS.md](TASKS.md) for hands-on exercises and follow the submission process to earn your digital badges!

## 🔧 Example Workflows

This repository includes three practical workflows:

### 1. Hello World Workflow
**File:** [.github/workflows/hello-world.yml](.github/workflows/hello-world.yml)
- Triggers on push
- Prints messages
- Perfect for understanding basics
- **Learn more:** [Task 1 - Run Your First Workflow](TASKS.md#task-1-run-your-first-workflow)
- **Learn more:** [Task 2 - Understand Workflow Triggers](TASKS.md#task-2-understand-workflow-triggers)

### 2. Build & Test Workflow
**File:** [.github/workflows/build-test.yml](.github/workflows/build-test.yml)
- Installs dependencies
- Runs tests
- Checks code quality
- Matrix testing across multiple Node versions
- **Learn more:** [Task 3 - Build and Test Locally](TASKS.md#task-3-build-and-test-locally)
- **Learn more:** [Task 7 - Matrix Testing](TASKS.md#task-7-matrix-testing)

### 3. Deploy to Azure App Service
**File:** [.github/workflows/deploy-azure-app-service.yml](.github/workflows/deploy-azure-app-service.yml)
- Builds the application
- Deploys to Azure App Service
- Uses GitHub Secrets for credentials
- **Learn more:** [Challenge 1 - Deploy to Azure](TASKS.md#challenge-1-deploy-to-azure-optional)

---

## 📚 Complete Learning Path

### 🌟 Beginner Level (Tasks 1-3)
Perfect for getting started with GitHub Actions basics.

| Task | Title | Difficulty | Time | Link |
|------|-------|-----------|------|------|
| 1 | Run Your First Workflow | ⭐ | 5 min | [Task 1](TASKS.md#task-1-run-your-first-workflow) |
| 2 | Understand Workflow Triggers | ⭐ | 10 min | [Task 2](TASKS.md#task-2-understand-workflow-triggers) |
| 3 | Build and Test Locally | ⭐ | 15 min | [Task 3](TASKS.md#task-3-build-and-test-locally) |

**After Completion:** [Submit Beginner Badge](README.md#beginner-submission-template)

---

### ⭐⭐ Intermediate Level (Tasks 4-7)
Dive deeper into practical workflows and configurations.

| Task | Title | Difficulty | Time | Link |
|------|-------|-----------|------|------|
| 4 | Create a Custom Workflow | ⭐⭐ | 15 min | [Task 4](TASKS.md#task-4-create-a-custom-workflow) |
| 5 | Add Environment Variables | ⭐⭐ | 10 min | [Task 5](TASKS.md#task-5-add-environment-variables) |
| 6 | Use GitHub Secrets | ⭐⭐ | 10 min | [Task 6](TASKS.md#task-6-use-github-secrets) |
| 7 | Matrix Testing | ⭐⭐ | 15 min | [Task 7](TASKS.md#task-7-matrix-testing) |

**After Completion:** [Submit Intermediate Badge](README.md#intermediate-submission-template)

---

### ⭐⭐⭐ Advanced Level (Tasks 8-10)
Master complex workflows and CI/CD concepts.

| Task | Title | Difficulty | Time | Link |
|------|-------|-----------|------|------|
| 8 | Upload and Download Artifacts | ⭐⭐⭐ | 20 min | [Task 8](TASKS.md#task-8-upload-and-download-artifacts) |
| 9 | Conditional Execution | ⭐⭐⭐ | 15 min | [Task 9](TASKS.md#task-9-conditional-execution) |
| 10 | Create a PR and Use Issue Templates | ⭐⭐⭐ | 20 min | [Task 10](TASKS.md#task-10-create-a-pr-and-use-issue-templates) |

**After Completion:** [Submit Advanced Badge](README.md#advanced-submission-template)

---

### 🏆 Challenge Tasks (Bonus)

| Challenge | Title | Level | Link |
|-----------|-------|-------|------|
| 1 | Deploy to Azure | Advanced | [Challenge 1](TASKS.md#challenge-1-deploy-to-azure-optional) |
| 2 | Add Code Coverage Reports | Advanced | [Challenge 2](TASKS.md#challenge-2-add-code-coverage-reports) |
| 3 | Create a Custom Action | Expert | [Challenge 3](TASKS.md#challenge-3-create-a-custom-action) |

---

## 🎓 Learning Tips

1. **Start Small:** Begin with the hello-world workflow
2. **Follow Order:** Complete tasks in sequence for better understanding
3. **Experiment:** Modify workflows and see what happens
4. **Read Logs:** GitHub Actions logs are your best friend
5. **Document:** Add comments to your workflow files
6. **Share:** Help others in the community
7. **Earn Badges:** Submit your work to get recognized!

---

## 🤝 Contributing

We welcome contributions! To contribute:

1. Fork this repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Open a Pull Request using our [PR template](.github/PULL_REQUEST_TEMPLATE.md)

---

## 📝 Reporting Issues

Found a bug or have a suggestion? Use our issue templates:

- 🐛 [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md)
- ✨ [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)
- 📚 [Documentation Issue](.github/ISSUE_TEMPLATE/documentation.md)
- ❓ [Question](.github/ISSUE_TEMPLATE/question.md)

---

## 📚 Additional Resources

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)
- [Azure App Service Documentation](https://docs.microsoft.com/en-us/azure/app-service/)
- [YAML Syntax](https://yaml.org/)
- [Shell Scripting Guide](https://www.gnu.org/software/bash/manual/)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🌟 Badge Wall of Fame

Congratulations to our badge earners! 🎉

<!-- Badge winners will be added here -->

---

## 🌟 Show Your Support

If you find this repository helpful, please give it a ⭐️ and share it with others!

---

**Happy Learning! 🎉**

For questions or feedback:
1. Check the [documentation](docs/)
2. Review [TASKS.md](TASKS.md) 
3. Open an [issue](.github/ISSUE_TEMPLATE/question.md) 
4. Contact [@nisalgunawardhana](https://github.com/nisalgunawardhana)


