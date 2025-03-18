# How to Push Code to GitHub using Command Line

Follow these simple steps to push your code to GitHub using the command line:

## 1. Initialize Git in Your Project

If you haven't already initialized your project folder with Git, run this command:

```bash
git init
```

# 2. Create a GitHub Repository
Go to GitHub and create a new repository:

## Once the repository is created, you'll get the repository URL. For example:

bash
Copy
```
https://github.com/username/repository-name.git
```
# 3. Link Your Local Project to GitHub
 ## Now, link your local project with the GitHub repository by running this command:

bash
Copy
```
git remote add origin https://github.com/username/repository-name.git
```
# 4. Stage Your Changes
## To prepare your files for commit, run the following command:

bash
Copy
```
git add .
```
## If you only want to add specific files, use their names:

bash
Copy
```
git add filename
```
# 5. Commit Your Changes
 ## After staging your changes, commit them with a message:

bash
Copy
```
git commit -m "Your commit message here"
```
# 6. Push Your Code to GitHub
## Finally, push your code to GitHub with this command:

bash
Copy
```
git push -u origin master
```
## If you're using the main branch (default for new GitHub repositories), run this instead:

bash
Copy
```
git push -u origin main
```
# Note:
## The first time you push, GitHub will ask for your username and password. If you have two-factor authentication (2FA) enabled, you will need to use a personal access token instead of your password.
