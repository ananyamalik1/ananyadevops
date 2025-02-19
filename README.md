1️⃣ What is Version Control?

A Version Control System (VCS) is a tool that tracks changes to files, enabling developers to work together on projects efficiently.

🔹 Types of VCS

Type	Description	Example
Centralized VCS (CVCS)	A single central repository is used to store project history.	Subversion (SVN)

Distributed VCS (DVCS)	Every developer has a full copy of the repository, allowing offline work.	Git, Mercurial (Hg)

🔹 Why Use Version Control?

✔ Collaboration: Multiple developers can work on the same project.

✔ Tracking Changes: Every modification is recorded.

✔ Rollback: Easily revert to previous versions.

✔ Branching & Merging: Work on new features without affecting the main code.

2️⃣ Subversion (SVN) - Centralized Version Control

STEP 1📌 Install SVN on Ubuntu

sudo apt update

sudo apt install subversion -y

STEP 2📌 Create an SVN Repository

svnadmin create my_svn_repo

STEP 3📌 Checkout the Repository

svn checkout file:///path/to/my_svn_repo my_project

STEP 4📌 Add and Commit Changes

cd my_project

echo "Hello SVN" > file1.txt

svn add file1.txt

svn commit -m "Initial commit"

STEP 5📌 View Repository History

svn log
## 🌐 Mercurial (HG)

Mercurial (**Hg**) is a **distributed version control system (DVCS)** designed for speed, efficiency, and ease of use. It enables developers to track changes in source code and collaborate effectively.

---

## **🔹 Key Features of Mercurial**

1. **Distributed Architecture**
   - Every developer has a complete copy of the repository.
   - No central server is required, but one can be used for collaboration.

2. **Fast Performance**
   - Optimized for handling large codebases efficiently.

3. **Simple and Intuitive Commands**
   - Commands are user-friendly and similar to Git.

4. **Atomic Commits**
   - Ensures that commits are completed successfully or not at all.

5. **Branching & Merging**
   - Supports easy branching and merging, preserving history.

6. **Scalability**
   - Handles projects of all sizes, from small teams to enterprise applications.

---

## **🔹 How Mercurial Works?**

### **1️⃣ Distributed Repositories**
Each user has a complete copy of the repository, enabling offline work.

### **2️⃣ Committing Changes**
- Developers **edit files locally**.
- They **commit changes**, creating a new revision in their local repository.

### **3️⃣ Pull & Push**
- Developers **pull** changes from others.
- They **push** their changes to a shared repository when ready.

### **4️⃣ Merging & Conflict Resolution**
- Mercurial provides tools to merge changes from multiple sources.

---
📌 Install Mercurial on Ubuntu

sudo apt install mercurial -

📌 Initialize a Repository

hg init my_hg_repo

cd my_hg_repo

📌 Add and Commit Files

echo "Hello Mercurial" > file1.txt

hg add file1.txt

hg commit -m "Initial commit"

📌 Check Repository Status

hg status

📌 View Repository History

hg log
