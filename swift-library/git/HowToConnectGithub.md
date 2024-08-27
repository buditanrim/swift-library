#  Connect empty repo with Xcode project

After creating an empty repo on your GitHub account, open your terminal and do these:

```bash
// 1. navigate to your project diectory
cd /path/to/your/project

// 2. add remote git
git remote add origin https://github.com/yourusername/repo.git

// 3. push your project to Github
git push -u origin main

// 4. Open your Xcode (View > Navigators > Show Source Control Navigator)
// you should have the remote connected to your repository
```
