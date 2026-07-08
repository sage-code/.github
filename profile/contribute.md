# Sage-Code Contribution Protocol

We operate a tier-based contribution model. We maintain zero central databases; identity and access are federated through our community channels.

## 1. Access Tiers & Roles

*   **Guests:** Unrestricted access to fundamental modules (Software Engineering, Programming Languages) via the homepage. No registration required.
*   **Students:** Granted access to staging rooms, scheduled sessions, and extra resources. Can submit Pull Requests (PRs) via repository forks.
*   **Developers:** Requires active Discord presence and an interview. Granted direct access to specific private repositories and development branches. 
*   **Mentors (Core Team):** Professional code maintainers and moderators. Granted direct commit access to main branches and all protected repositories (including `/vip`). 

## 2. The Network

Role assignments and GitHub invitations are managed strictly through our community nodes:
*   [Discord](https://discord.gg/fAEHfw8T) (Primary operations and role claims)
*   [Google Group](https://groups.google.com/g/sagecode)
*   [Reddit](https://www.reddit.com/r/sagecode/)

## 3. Repository Architecture

Do not clone the `.github` repository unless updating global discussions or the main README. Clone specific project repositories as needed. 

```text
~/sagecode
 ├── .github/    # Central discussions and global README
 ├── cse/        # Computer Science & Engineering (Core tutorials)
 │   ├── images/ # Global shared images
 │   └── [lang]/ # Language-specific subfolders
 └── vip/        # Protected access (Mentors only)
