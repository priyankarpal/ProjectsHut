# 😎 Contribute your Code to ProjectsHut

## 🧐 Follow these steps to Contribute

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/priyankarpal/ProjectsHut)

1. Fork this repository

![ Fork this repository](/images/fork.png)

2. Click on `Go to file`

![Go to file](/images/gotofile.png)

3. Add following code to end of `src/DB/projects.json`

```json
{
  "gh-username": "YOUR-GITHUB-USERNAME",
  "link": "LINK-TO-GITHUB-OR-DEMO",
  "title": "PROJECT-TITLE",
  "description": "PROJECT-DESCRIPTION",
  "tech": ["some tech 1", "some tech 2", "etc"]
}
```

> ### If you want to run it locally then follow these

4.  Clone it to your computer

```
 git clone https://github.com/[your-username]/ProjectsHut.git
```

5.  Navigate to the project folder

```
cd ProjectsHut
```

6.  install dependencies

```
yarn
```

7.  run in local

```
yarn run dev
```

8.  Create a new branch using your `GitHub Username`

```diff
git checkout -b [name_of_your_new_branch]
```

9. Add your changes.

```diff
git add .
```

10. Add your commits

```diff
git commit -m "Your Changes"
```

11. Set upstream command

```diff
git remote add upstream https://github.com/priyankarpal/ProjectsHut.git
```

12. Push your commits

```diff
git push -u origin [Your-branch-name]
```

13. Create a PR

14. Wait for merge
