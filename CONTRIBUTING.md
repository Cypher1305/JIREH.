# JIREH.

Create a digital space for donations and acquisitions of charity items

---

### Table of Contents

- [How We Work](#-how-we-work)
- [Main Branches](#️-main-branches)
- [Branch Nomenclature](#-branch-nomenclature)
- [Contribution Step](#-contribution-steps)

---

## 🤝 How we work

- **Tasks are created as issues** (by the scrum master [Cypher1305](https://github.com/Cypher1305))
- Each Contributor **assigns or receives an issue** ou en reçoit une
- A branch is **created from `dev`** for each issue (Always from dev branch)
- Commit messages must reference the issue ID
- A **pull request** (PR) is made to `dev`
- 1 branche = 1 fonctionnalité = 1 PR
- Once the PR has been accepted, **the branch is deleted**

---

## 🗂️ Main branches

| Branche | Usage |
|---------|-------|
| `main` | Stable version, ready for production |
| `dev` | Development base (all functionalities converge here) |

---

## 🌱 Branch nomenclature

```bash
Type/XX/#num-title-in-kebab-case
```
| Prefix     | When to use it                   |
| ----------- | ----------------------------------- |
| `Feature/`  | New feature             |
| `Hotfix/`   | Bug fix                   |
| `Refactor/` | Code cleanup or reorganization |

- XX = contributor's initials
- #num = GitHub issue number

Examples :

    Feature/BY/#12-addition-form-orientation

    Hotfix/KY/#16-fix-bug-scroll

    Refactor/GY/#20-clean-user-model
---

#### 🛠 Contribution steps

1. Fork the project

- Click on **"Fork"** at the top right of the repository's GitHub page.
- This creates a **copy of the project on your own GitHub account**.

2. Clone your fork
```bash
git clone https://github.com/Cypher1305/JIREH..git
cd JIREH.
```
3. Add remote origin to official repository
```bash
git remote add upstream https://github.com/Cypher1305/JIREH..git
git remote -v # to verify
git fetch upstream # to fetch remote branches
```
3. Create a branch from issue
```bash
git checkout dev
git pull upstream dev
git checkout -b Feature/BY/#12-add-orientation-form
```
_Bring your contribution on your branch_
4. Commit your work
```bash
git add .
git commit -m "#12 Add-orientation-form"
```
5. Push the branch
```bash
git push -u origin Feature/BY/#12-add-orientation-form
```
_Proceed to a pull request (Add a clear description and link the issue with #12)_

6. Delete branch locally
```bash
git branch -d Feature/BY/#12-add-orientation-form
git push origin --delete Feature/BY/#12-add-orientation-form
```


