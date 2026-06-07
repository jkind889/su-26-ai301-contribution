# Contribution [#]: [Issue Title]

**Contribution Number:** [1 / 2 / 3]  
**Student:** [Your Name]  
**Issue:** [GitHub issue link]  
**Status:** [Phase I / Phase II / Phase III / Phase IV] [In Progress / Complete]

---

## Why I Chose This Issue

[1-2 paragraphs explaining why this issue interests you, how it matches your skills/learning goals, what you hope to learn]

 I chose this issue because it has a clearly defined scope and straightforward requirements. The feature involves allowing users to edit account details such as their username and email after account creation, making it an approachable but meaningful contribution. Since the changes will likely involve both backend API updates and frontend form handling, it provides an opportunity to work across multiple parts of the application while still remaining manageable as a first open-source contribution.

This issue aligns well with my learning goals of becoming more familiar with Python backends and Flask-based API development. Web development is one of my primary interests, and I have experience building full-stack applications using React, Node.js, Express, and MongoDB. Through this project, I hope to gain hands-on experience working with an established Python codebase, learn how Flask applications are structured in a real-world environment, and become more comfortable contributing to larger collaborative software projects.

---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]
Theres no button for users to change their fullname or username details even though the logic for it exists in the backend

### Expected Behavior

Users should be able to change their details such as username and full name

### Current Behavior

Button to modify user details doesn't exist

### Affected Components

GrampsjsUsers.js

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]
It's pretty simple to set up the environment as all you have to do is fork the repo and then open the repo in a dev container. It takes a minute to open and theres a lot to download. Since im editing the frontend I had to spin up the backend as well to have live refreshes when editing the front end

### Steps to Reproduce

1. [Step 1]
   Make an owner account
3. [Step 2]
   Go to user details
5. [Observed result]
   Theres no button to change details of username and email

### Reproduction Evidence

- **Commit showing reproduction:** N/A
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]
There's no buttons to change username and full name even though the backend supports it

### Proposed Solution

[High-level description of your fix approach]
Add a button similar to the change email button to implement changing usernames and full names

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem
Add a button to change usernames and full names for users

**Match:** [What similar patterns/solutions exist in the codebase?]
There exists logic to change usernames and fullnames within the API

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]
Modify GrampsjsUsers.js 
**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]
I will implement tests before I ship anything to confirm that a user is able to change their name and username, I can also add tests for the form to implement if a duplicate name doesn't go through but there is logic inside the backend for that as well
---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
