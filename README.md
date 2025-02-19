1️⃣ Subversion (SVN) Demonstration
📌 Step 1: Install SVN
On Ubuntu, install SVN using:

sudo apt update
sudo apt install subversion -y
📌 Step 2: Create an SVN Repository

svnadmin create my_svn_repo
This initializes a new SVN repository named my_svn_repo.

📌 Step 3: Checkout Repository

svn checkout file:///path/to/my_svn_repo my_project
This clones the repository into my_project.

📌 Step 4: Add a New File

cd my_project
echo "Hello SVN" > file1.txt
svn add file1.txt
This adds file1.txt to SVN tracking.

📌 Step 5: Commit Changes

svn commit -m "Initial commit"
📌 Step 6: View Repository Status
svn status
📌 Step 7: Update Repository

svn update
📌 Step 8: View Logs
svn log
