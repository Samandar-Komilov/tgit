
# Turin Git (tgit) - A Git-like Version Control System

## Overview

**[Your VCS Name]** is a lightweight version control system (VCS) built from scratch in Python. Inspired by Git, it aims to provide a hands-on understanding of VCS concepts while progressing through increasingly advanced features. The project will be released in multiple stages, from basic functionality to more complex features. The main priority is to learn, practice and get experience with university coursemates.

## Features

### Planned Versions
We will develop the project step-by-step, adding features incrementally:

1. **Version 0.1: Core Initialization**
   - Create and initialize a repository (`init`).
   - Track files and calculate file hashes.
   - Save file snapshots locally.

2. **Version 0.2: Basic Commit System**
   - Add and commit changes (`add`, `commit`).
   - Maintain a history of commits.
   - Implement `log` to view commit history.

3. **Version 0.3: Networking Basics**
   - Introduce server-client communication using sockets.
   - Enable basic repository synchronization (`push`, `pull`).

4. **Version 0.4: Branching and Merging**
   - Create and switch branches.
   - Merge branches and handle basic conflicts.

5. **Version 0.5: Enhanced Storage and Efficiency**
   - Use a database-like structure for object storage.
   - Optimize data transfer between client and server.

6. **Version 1.0: Advanced Features**
   - Add user authentication for secure operations.
   - Implement tags and release management.
   - Support large file storage efficiently.

## Getting Started

### Prerequisites
- Python 3.10 or above
- Basic understanding of version control systems
- `socket` library (default in Python)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-vcs.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-vcs
   ```
3. Run the setup script (if applicable):
   ```bash
   python setup.py install
   ```

## Contribution Guidelines

We welcome contributions to help make **Turin Git** better! Here's how you can contribute:

1. Check the [Issues](#) and [Project Roadmap](#) for open tasks.
2. Fork the repository and create a feature branch.
3. Submit a pull request with detailed explanations of your changes.

### Current Tasks
- [ ] Implement repository initialization (`init`).
- [ ] Design the file tracking mechanism.
- [ ] Define the commit object structure.
