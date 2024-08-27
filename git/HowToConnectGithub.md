#  Connect empty repo with Xcode project

After creating an empty repo on your GitHub account, open your terminal and do these:


Step 1: navigate to your project diectory
```bash
cd /path/to/your/project
```

Step 2: add remote git
```bash
git remote add origin https://github.com/yourusername/repo.git
```

Step 3: push your project to Github
```bash
git push -u origin main
```
4. Open your Xcode (View > Navigators > Show Source Control Navigator). You should have the remote connected to your repository.

