[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/u5GZ8gGl)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19669974)
# CYSE 411 - Security Requirements

## 🧪 Objective

This lab gives students hands-on experience eliciting **user stories**, **evil user stories**, and **security stories** from a real-world scenario involving a disaster response system ("Argus Crisis").

Students will read a provided **problem statement**, analyze the system, and write:

- User Stories (task-oriented)
- Evil User Stories (from attacker perspective)
- Security Stories (countermeasures)

All stories must follow the appropriate format and include acceptance criteria (when required).

#### The autograde does not check the semantic of the stories, only the syntax.

---

## 📘 Instructions

1. Read the `Problem_Statement.pdf` provided in this repo.
2. Complete the three files below using the specified formats:
   - `user_stories.txt`
   - `evil_user_stories.txt`
   - `security_stories.txt`
3. Use the templates for each story type as shown below.

---

## ✍️ Template Formats

### 1. User Story
```
As a <type of user>,
I want <some goal>,
So that <some reason>.
```

### 2. Evil User Story (with acceptance criteria)
```
As a malicious actor,
I want to <exploit a weakness>,
So that <achieve a malicious goal>.

Acceptance Criteria:
- <criteria 1>
- <criteria 2>
```

### 3. Security Story (with acceptance criteria)
```
As a security engineer,
I want to <protect against a threat>,
So that <ensure system security>.

Acceptance Criteria:
- <criteria 1>
- <criteria 2>
```

---

## ✅ Autograding

Autograding will check:
- Each file includes correctly formatted stories.
- Specific keywords are used for each role (`As a malicious actor`, `As a security engineer`, etc.).
- Presence of “Acceptance Criteria” for Evil/Security stories.

Run the tests locally:
```bash
python3 test_user_stories.py
```

---

## 📁 Files to Submit

Please fill out:
- `user_stories.txt`
- `evil_user_stories.txt`
- `security_stories.txt`

Push your changes to GitHub to submit your assignment.
