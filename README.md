# Softdocs Team GitHub Guidelines
> Work in Progess

Version: 1.0.0

Welcome to our team’s GitHub home! This document outlines our shared practices for using GitHub effectively, ensuring smooth collaboration, high-quality code, and a transparent workflow.

📖 Table of Contents

    About This Repository
    Getting Started
    Repository Structure
    GitHub Best Practices
        Branching Strategy
        Commit Messages
        Pull Requests & Code Reviews
        Issues & Project Boards
        CI/CD & Automation
    Team Culture & Communication
    Resources & Links

## About GitHub

## Our goal is to keep it organized, transparent, and collaborative.

## GitHub Best Practices
### Branching Strategy



### Commit Messages
We follow the Conventional Commits specification for clear and consistent commit history:

<type>(<scope>): <short summary>

    type: Indicates the nature of the change. Common types include:
        feat: A new feature
        fix: A bug fix
        docs: Documentation only changes
        chore: Routine tasks, maintenance, or build process changes
        style: Formatting, missing semicolons, etc.; no code change
        refactor: A code change that neither fixes a bug nor adds a feature
        test: Adding missing tests or correcting existing tests
        perf: A code change that improves performance
    scope (optional): The part of the codebase affected by the commit (e.g., auth, ui, database).
    short summary: A concise description of the change, ideally under 72 characters.
    body (optional): Provides additional contextual information about the code changes.
    footer(s) (optional): Can reference issues (e.g., Closes #123), breaking changes, or other metadata.

Pull Requests & Code Reviews

Pull Requests (PRs) are central to our development workflow, enabling code review and collaborative refinement.

    Open PRs against develop: All feature and bugfix branches should be merged into develop first.
    Describe your change: Clearly articulate what was changed, why it was changed, and how it was implemented.
    Link related issues: Reference any associated issues using keywords like Closes #XYZ or Resolves #ABC.
    Request reviews: Always assign appropriate team members as reviewers.
    Address comments: Resolve all comments and suggestions from reviewers before merging.
    Use Squash and Merge: For a clean and readable commit history, prefer the "Squash and merge" option when merging PRs. This condenses all commits from your branch into a single commit on the target branch.

Issues & Project Boards

We use GitHub Issues and Project Boards to track work, manage tasks, and prioritize efforts.

    Create an issue for every piece of work: Whether it's a new feature, a bug, or a minor chore, create an issue to track it.
    Use labels: Leverage labels to categorize and organize issues (e.g., bug, enhancement, documentation, question, good first issue).
    Milestones: Use Milestones to group issues for specific versions, sprints, or release cycles.
    Project Boards: Visualize our workflow with Kanban-style boards, typically with columns like: To Do → In Progress → In Review → Done.

CI/CD & Automation

We leverage GitHub Actions (or your chosen CI/CD tool) to automate our development workflow and ensure code quality.

    Automated Tests: All PRs trigger automated tests to ensure no regressions are introduced.
    Linting & Formatting: Automated checks enforce consistent code style and quality.
    Automated Releases: For some repositories, we automate the tagging and publishing of releases.
    Branch Protection: The main branch is protected, requiring all CI/CD checks to pass and at least one approved code review before a merge.
    Dependency Management: We use tools like Dependabot to automatically keep our project dependencies up-to-date and secure.

Team Culture & Communication

Effective communication is key to a successful team.

    Be respectful and constructive: Provide feedback in comments and reviews that is helpful and actionable.
    Ask questions: Don't hesitate to ask if you're unsure about something. We learn together.
    Document as you go: Small, consistent updates to our docs/ folder help keep everyone informed and reduce knowledge silos.
    Celebrate successes: A simple 👍 reaction or a shoutout for a well-done PR can go a long way!

Resources & Links

