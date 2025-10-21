# Team Portfolio Project - G6-Team1

A collaborative portfolio website developed using Git feature-branching workflow for our Software Engineering course.

## 🌐 Live Website
**[View Our Portfolio](https://ashreeef.github.io/team-portfolio-project/)**

## 👥 Team Members

- **Ashref Berbaoui** (Team Leader) - [@Ashreeef](https://github.com/Ashreeef)
- **Hamza Khentache** - [@ebmw](https://github.com/ebmw)
- **Amin Sekkat** - [@SekkatMohamedAmin](https://github.com/SekkatMohamedAmin)
- **Hind Moussaoui** - [@Hindmous](https://github.com/Hindmous)
- **Sihem Sehil** - [@Sihamsehil](https://github.com/Sihamsehil)
- **Aya Hoggas** - [@Aya-Hoggas](https://github.com/Aya-Hoggas)

## Project Overview

This project demonstrates collaborative software development using:
- Git feature-branching workflow
- Pull request reviews
- Merge conflict resolution
- GitHub Pages deployment

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Git & GitHub
- GitHub Pages

## Features

- Responsive team portfolio homepage
- Individual profile pages for each team member
- Professional bio and technical skills showcase
- Direct links to GitHub profiles
- Modern, clean design with smooth animations

## Team Retrospective Analysis

### 1. Most Significant Technical Challenge

The main technical challenge we faced was ensuring that all team members properly followed the Git feature-branching workflow. Since some members may be new to Git, it initially took some time to get everyone comfortable with creating branches, committing changes, and submitting pull requests correctly. However, once the workflow was clearly established, the process became smooth and efficient.

We focused heavily on communication and synchronization between members to avoid potential issues, especially when modifying shared files like `index.html`. By ensuring that each feature was developed in its own branch and merged only through reviewed pull requests, we successfully avoided merge conflicts altogether.

### 2. Merge Conflict Prevention - Our Approach

Unlike many collaborative projects, our team managed to avoid any merge conflicts entirely, thanks to a disciplined Git workflow and consistent communication.

Each member worked on a dedicated **feature branch** named following a clear and consistent convention:  
`feature/implement-[member-name]-profile`  

This structure made it immediately clear who was responsible for which branch and feature. The workflow was as follows:

1. **Branch Creation:** Each member created their branch from the updated `develop` branch before starting their work.  
2. **Independent Development:** Members implemented their personal profile pages without touching shared files unnecessarily.  
3. **Frequent Updates:** Before committing or opening a pull request, each member ran `git pull origin develop` to stay synced with the latest repository state.  
4. **Pull Requests (PRs):** When a feature was ready, the member opened a PR to merge their branch into `develop`.  
5. **Code Review:** Other team members reviewed the PR for structure, content, and consistency before approving it.  
6. **Sequential Merges:** The team leader merged PRs one by one after approval to maintain order and avoid simultaneous edits on shared sections like `index.html`.  

By adhering to this structured workflow, we not only avoided merge conflicts but also gained a real-world understanding of how professional teams manage collaborative development using Git.


### 3. Pull Request and Peer Review Effectiveness


The pull request and peer review process proved to be one of the most beneficial aspects of this project:

**Code Quality Improvements**: Reviews helped catch small issues such as inconsistent indentation, redundant code, and minor HTML/CSS styling errors before merging.  

**Knowledge Sharing**: Team members learned from each other’s approaches and coding styles, reinforcing Git best practices along the way.  

**Consistency**: The review process ensured uniformity across all profile pages and maintained a cohesive look for the entire website.  

**Accountability and Collaboration**: Knowing that code would be reviewed encouraged cleaner, more organized contributions. Discussions in pull requests also strengthened our communication and teamwork skills.  

Overall, the combination of a structured branching strategy, pull request workflow, and effective peer reviews led to a smooth development experience, high code quality, and zero merge conflicts—an outcome that reflects strong collaboration and adherence to professional software engineering practices.

## Development Timeline

- **Phase 1**: Repository setup and branch protection (Oct 17)
- **Phase 2**: Distributed development and PR reviews (Oct 18-21)
- **Phase 3**: Final integration and deployment (Oct 21)

## Learning Outcomes

Through this project, our team gained hands-on experience with:
- ✅ Feature-branching Git workflow
- ✅ Pull request creation and management
- ✅ Code review and constructive feedback
- ✅ Merge conflict resolution
- ✅ Collaborative repository management
- ✅ Static website deployment with GitHub Pages

## License

This project was created for educational purposes as part of our Software Engineering coursework.

---

**Course**: Software Engineering  
**Institution**: ENSIA  
**Semester**: Fall 2025  