Version Control Systems (VCS) help developers manage changes in their codebase efficiently. This assignment demonstrates the usage of Subversion (SVN) and Mercurial (Hg) with essential commands, explanations, and screenshots. Additionally, we will create a GitHub repository, upload our report, and host it using GitHub Pages.

1️⃣ Subversion (SVN) Demonstration
📌 Step 1: Install SVN
On Ubuntu, install SVN using:

bash
Copy
Edit
sudo apt update
sudo apt install subversion -y
📌 Step 2: Create an SVN Repository
bash
Copy
Edit
svnadmin create my_svn_repo
This initializes a new SVN repository named my_svn_repo.

📌 Step 3: Checkout Repository
bash
Copy
Edit
svn checkout file:///path/to/my_svn_repo my_project
This clones the repository into my_project.

📌 Step 4: Add a New File
bash
Copy
Edit
cd my_project
echo "Hello SVN" > file1.txt
svn add file1.txt
This adds file1.txt to SVN tracking.

📌 Step 5: Commit Changes
bash
Copy
Edit
svn commit -m "Initial commit"
📌 Step 6: View Repository Status
bash
Copy
Edit
svn status
📌 Step 7: Update Repository
bash
Copy
Edit
svn update
📌 Step 8: View Logs
bash
Copy
Edit
svn log
2️⃣ Mercurial (Hg) Demonstration
📌 Step 1: Install Mercurial
bash
Copy
Edit
sudo apt install mercurial -y
📌 Step 2: Initialize a Mercurial Repository
bash
Copy
Edit
hg init my_hg_repo
cd my_hg_repo
📌 Step 3: Add a File to Mercurial
bash
Copy
Edit
echo "Hello Mercurial" > file1.txt
hg add file1.txt
📌 Step 4: Commit Changes
bash
Copy
Edit
hg commit -m "Initial commit"
📌 Step 5: View Repository Status
bash
Copy
Edit
hg status
📌 Step 6: View Change Log
bash
Copy
Edit
hg log
📌 Step 7: Pull & Update Repository
bash
Copy
Edit
hg pull -u
