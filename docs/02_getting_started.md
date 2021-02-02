## Getting Started With VFA Collaboration
Even if you have used GitHub in the past, we hope this information will provide a baseline understanding of how to use it to build better software!

### What is GitHub?
GitHub is a collaboration platform built on top of a distributed version control system called Git. 

GitHub concentrates on three things:

- Building a technology platform that is like no other, on which developers can create, share and grow the best code possible
- Nurturing a community for developers; a safe and collaborative place that facilitates sharing, amplifies creativity, and supports the principles of open source
- Providing access, opening up a community of opportunity, where new developers can be born and where experienced developers can hone their skills and expand their knowledge

In addition to being a place to host and share your Git projects, GitHub provides a number of features to help you and your team collaborate more effectively. These features include:

- [Issues](https://seanmcilroy29.github.io/training-manual/#/02_getting_started?id=issues)
- [Pull Requests](https://seanmcilroy29.github.io/training-manual/#/02_getting_started?id=pull-requests)
- [Projects](https://seanmcilroy29.github.io/training-manual/#/02_getting_started?id=projects)
- Organizations and Teams

### What is Git?

**Git is:**
- a distributed version control system (DVCS).
- free and open source.
- designed to handle everything from small to very large projects with speed and efficiency.
- easy to learn and has a tiny footprint with lightning fast performance.

Git features cheap local branching, convenient staging areas, and multiple workflows.

#### Snapshots, not Deltas
One of the first ideas you will need understand is that Git does not store your information as series of changes. Instead Git takes a snapshot of your repository at a given point in time. This snapshot is called a commit.

#### Optimized for Local Operations
Git is optimized for local operation. When you clone a copy of a repository to your local machine, you receive a copy of the entire repository and its history. This means you can work on the plane, on the train, or anywhere else your adventures find you!

#### Branches are Lightweight and Cheap
Branches are an essential concept in Git.

When you create a new branch in Git, you are actually just creating a pointer that corresponds to the most recent commit in a line of work. Git keeps the commits for each branch separate until you explicitly tell it to merge those commits into the main line of work.

### Exploring a GitHub Repository
A repository is the most basic element of GitHub. It is easiest to imagine as a project's folder. However, unlike an ordinary folder on your laptop, a GitHub repository offers simple yet powerful tools for collaborating with others.

A repository contains all of the project files (including documentation), and stores each file's revision history. Whether you are just curious or you are a major contributor, knowing your way around a repository is essential!

#### User Accounts
When you signed up for GitHub, you were automatically given a user account. Permissions for a user account are simple, you add people as collaborators to specific repositories to give them full read-write access to the project.

#### Organization Accounts
Organization accounts provide more granular control over repository permissions. In an organization account you create teams of people and then give those teams access to specific repositories. Permissions can be assigned at the team level (e.g, read, write, or admin).

### Glossary Repository Navigation

#### Code
The **Code** tab is where you will find the files included in the repository. These files may contain the project code, documentation, and other important files. We also call this tab the root of the project. Any changes to these files will be tracked via Git version control.

#### Issues
Issues are used to track bugs and feature requests. Issues can be assigned to specific team members and are designed to encourage discussion and collaboration.

#### Pull Requests
A Pull Request represents a change, such as adding, modifying, or deleting files, which the author would like to make to the repository. Pull Requests help you write better software by facilitating code review and showing the status of any automated tests.

#### Projects
Projects allow you to visualize your work with Kanban style boards. Projects can be created at the repository or organization level.

#### Wiki
Wikis in GitHub can be used to communicate project details, display user documentation, or almost anything your heart desires. And of course, GitHub helps you keep track of the edits to your Wiki!

#### README.md
The README.md is a special file that we recommend all repositories contain. GitHub looks for this file and helpfully displays it below the repository. The README should explain the project and point readers to helpful information within the project.

#### CONTRIBUTING.md
The CONTRIBUTING.md is another special file that is used to describe the process for collaborating on the repository. The link to the CONTRIBUTING.md file is shown when a user attempts to create a new issue or pull request.

#### ISSUE_TEMPLATE.md
The ISSUE_TEMPLATE.md (and its twin the pull request template) are used to generate templated starter text for your project issues. Any time someone opens an issue, the content in the template will be pre-populated in the issue body.

### Using GitHub Issues
In GitHub, you will use issues to record and discuss ideas, enhancements, tasks, and bugs. Issues make collaboration easier by:

- Replacing email for project discussions, ensuring everyone on the team has the complete story, both now and in the future.
- Allowing you to cross-link to related issues and pull requests.
- Creating a single, comprehensive record of how and why you made certain decisions.
- Allowing you to easily pull the right people into a conversation with @ mentions and team mentions.

[include](02a_activity_create_github_issue.md ':include')

### Using Markdown
GitHub uses a syntax called **Markdown** to help you add basic text formatting to Issues, Pull Requests, and files with the `.md` extension.

### Commonly Used Markdown Syntax

#### `# Header`
The `#` indicates a Header. `#` = Header 1, `##`  = Header 2, etc.

#### `* List item`
A single `*` or `-` followed by a space will create a bulleted list.

#### `**Bold item**`
Two asterisks `**` on either side of a string will make that text bold.

#### `- [ ] Checklist`
A `-` followed by a space and `[ ]` will create a handy checklist in your issue or pull request.

#### `@mention`
When you @mention someone in an issue, they will receive a notification - even if they are not currently subscribed to the issue or watching the repository.

#### `#975`
A `#` followed by the number of an issue or pull request (without a space) in the same repository will create a cross-link.

#### `:smiley:`
Tone is easily lost in written communication. To help, GitHub allows you to drop emoji into your comments. Simply surround the emoji id with `:`.
