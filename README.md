# The Odin Project — Homepage Clone

A 7-day frontend development challenge where students recreate the homepage of **The Odin Project** using HTML and CSS.

The primary objective is not only to build a responsive website, but also to practice a professional **GitHub-based development workflow** involving Issues, branches, commits, Pull Requests, reviews, and merges.

##  Project Objective

Recreate the visual structure and responsive behavior of the current [The Odin Project](https://www.theodinproject.com/) homepage.

The original website contains major sections including:

* Navigation
* Hero section
* How It Works
* Curriculum / What You'll Explore
* Success Stories
* Support section
* Footer

Students will progressively implement these sections over **7 days**.

---

## Technologies

* HTML5
* CSS3
* Git
* GitHub

### JavaScript

JavaScript is **not required** for the core assignment.

If required for small UI interactions such as a mobile navigation menu, students may use basic JavaScript only after completing the required HTML/CSS implementation.

---

# Initial Project Structure

The project should begin with:

```text
odin-project-clone/
│
├── index.html
├── css/
│   └── style.css
├── images/
├── fonts/
└── README.md
```

Students may introduce additional files/folders when required.

---

# Repository Structure

The instructor will maintain the main repository.

Each student will have a dedicated branch.

Example:

```text
main
│
├── student-01
├── student-02
├── student-03
├── student-04
└── ...
```

Students will work on their assigned branch through their own fork.

---

# GitHub Workflow

This project is completed through **GitHub Issues**.

Each day has one Issue containing the tasks that must be completed.

### Daily Process

```text
GitHub Issue
     ↓
Pull latest approved code
     ↓
Implement today's task
     ↓
Make meaningful commits
     ↓
Push to fork
     ↓
Create Pull Request
     ↓
Instructor Review
     ↓
Changes if required
     ↓
Approval
     ↓
Merge into student branch
     ↓
Best implementation → main
     ↓
Pull latest approved design
     ↓
Next day's Issue
```

---

# Student Rules

### 1. Read the Issue

Read the complete Issue before starting the day's work.

### 2. Pull Before Starting

Always make sure you are working from the latest approved version.

```bash
git pull
```

### 3. Make Meaningful Commits

Avoid commits such as:

```text
update
changes
done
final
test
```

Instead use:

```text
feat: create project structure
feat: implement navigation
feat: add hero section
style: improve hero typography
style: make curriculum cards responsive
fix: resolve mobile overflow
```

### 4. Create a Pull Request

Every day's completed work must be submitted through a Pull Request targeting the student's assigned branch.

### 5. Respond to Review Comments

If changes are requested:

1. Make the corrections.
2. Commit the changes.
3. Push again.
4. Continue using the same Pull Request.

Do not create unnecessary duplicate PRs.

---

# 7-Day Roadmap

| Day       | Milestone                     | Main Focus                                    |
| --------- | ----------------------------- | --------------------------------------------- |
| **Day 1** | Project Setup + Header + Hero | HTML structure, navigation, hero              |
| **Day 2** | How It Works                  | Feature cards and responsive layout           |
| **Day 3** | Curriculum Section            | Course/topic cards and grid layout            |
| **Day 4** | Success Stories               | Testimonial cards and responsive layout       |
| **Day 5** | Support + Footer              | CTA, footer and complete page structure       |
| **Day 6** | Responsive Design + Polish    | Mobile, tablet, desktop optimization          |
| **Day 7** | Final Review + Completion     | Bug fixes, accessibility and final submission |

---

# Design Requirements

The goal is to reproduce the **layout, spacing, hierarchy, typography, and responsive behavior** of The Odin Project homepage as closely as reasonably possible.

Students should pay attention to:

* Navigation spacing
* Typography
* Section spacing
* Content hierarchy
* Card layouts
* Buttons
* Images
* Responsive breakpoints
* Mobile navigation
* Footer structure

Do not simply copy the original site's source code.

---

# Responsive Requirements

The website must work properly across:

* Large desktop
* Desktop
* Tablet
* Mobile

The layout should adapt rather than simply shrinking.

Students should test at different viewport widths and ensure:

* No horizontal scrolling
* No overlapping content
* Images scale correctly
* Text remains readable
* Cards stack appropriately
* Navigation adapts for mobile
* Buttons remain usable

---

# Commit Convention

Use meaningful commit messages.

| Prefix     | Purpose                   | Example                          |
| ---------- | ------------------------- | -------------------------------- |
| `feat`     | New functionality/section | `feat: add hero section`         |
| `style`    | Styling changes           | `style: improve hero spacing`    |
| `fix`      | Bug fixes                 | `fix: resolve mobile overflow`   |
| `refactor` | Code restructuring        | `refactor: organize card styles` |
| `docs`     | Documentation             | `docs: update readme`            |

---

# Pull Request Requirements

Every Pull Request should include:

### Clear title

Example:

```text
feat: implement how it works section
```

### Description

Explain:

* What was implemented
* What was changed
* Any important decisions
* Any known issues

### Issue Reference

Reference the corresponding GitHub Issue.

Example:

```text
Relates #3
```

### Screenshots

Add screenshots when appropriate, especially for major UI changes.

---

# Daily Submission Checklist

Before creating a Pull Request:

* [ ] I read the day's Issue.
* [ ] I pulled the latest approved code.
* [ ] I completed all assigned tasks.
* [ ] I tested the implementation.
* [ ] I checked desktop layout.
* [ ] I checked mobile layout.
* [ ] I used meaningful commit messages.
* [ ] I pushed my changes.
* [ ] I created a Pull Request.
* [ ] The PR targets my assigned branch.
* [ ] I referenced the corresponding Issue.
* [ ] I added screenshots where appropriate.
* [ ] I did not modify unrelated files.

---

# Evaluation

| Category                     |   Weight |
| ---------------------------- | -------: |
| GitHub Workflow              |      20% |
| HTML Structure               |      10% |
| CSS Quality                  |      15% |
| Visual Accuracy              |      20% |
| Responsive Design            |      20% |
| Accessibility & Code Quality |      10% |
| Final Polish                 |       5% |
| **Total**                    | **100%** |

---

# Final Goal

By the end of this project, students should have:

* A complete responsive homepage inspired by The Odin Project.
* Experience working with GitHub Issues.
* Experience working with forks and branches.
* Experience writing meaningful commits.
* Experience creating Pull Requests.
* Experience receiving and responding to code reviews.
* Experience synchronizing their branch with an upstream repository.
* Experience continuing development from an approved shared design.

---

## The Main Learning Cycle

```text
PLAN
  ↓
ISSUE
  ↓
CODE
  ↓
COMMIT
  ↓
PUSH
  ↓
PULL REQUEST
  ↓
CODE REVIEW
  ↓
FIX
  ↓
APPROVE
  ↓
MERGE
  ↓
SYNC
  ↓
NEXT ISSUE
```

### Build → Commit → Push → PR → Review → Improve → Merge → Repeat
