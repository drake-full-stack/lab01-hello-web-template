# 🧪 Lab 1: Hello, Web!

## 🚀 Overview

In this lab, you'll get your development environment set up and publish your first simple website using **HTML**, **GitHub**, **Codespaces**, and **GitHub Pages**.

You'll:

- Accept the GitHub Classroom assignment
- Launch a Codespace and write a basic `index.html` page
- Commit and push your code to GitHub
- Publish your page using GitHub Pages

By the end, your website will be live for the world to see!

---

## ✅ Grading (Total: 4 Points)

| Requirement                                                          | Points |
| -------------------------------------------------------------------- | ------ |
| `index.html` file contains a valid HTML page with at least a heading | 1 pt   |
| At least one meaningful edit (e.g., paragraph, list, image, etc.)    | 1 pt   |
| Git history shows at least one commit with a descriptive message     | 1 pt   |
| GitHub Pages is enabled and the live site displays correctly         | 1 pt   |

> 🔍 I will grade your lab by checking your GitHub repository and your GitHub Pages site.

---

## 📦 What to Submit

Nothing! Just make sure:

- Your `index.html` file is committed to your GitHub repo
- Your GitHub Pages link is working

> You can confirm your site is live by visiting:  
> `https://<your-username>.github.io/<your-repo-name>/`

---

## Step #1 Accept and Open the Assignment

1. Click the GitHub Classroom link provided:
2. Accept the assignmetn and wait for the repo to be created.
3. Click "**Code --> Open in Coespaces**" to launch your environment.
4. When it loads, you should see `index.html` and `README.md`

---

## Step #2: Explore the Terminal

Open the Terminal in Codepaces:

Type in the following commands one by one and notice what happens. Write down in your notes what you think each line of code does.

```bash
pwd
ls
cd ..
mkdir my-test
cd my-test
touch test.html
code .
```

Try This: Edit your new file, the delete it from the terminal:

```bash
rm test.html
```

## Step #3: Build your First Webpage

In `index.html`, write a basic HTML page:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Hello, Web!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
    <p>This is my first web page.</p>
  </body>
</html>
```

Start Live Server:

- right click on `index.html` --> "Open with Live SErver"
- or click **Go Live**

## Step 4: Commit and Push Changes

Open the terminal or use the Source Control tab:

```bash
git status
git add index.html
git commit -m "Add my first web page"
git push
```

## Step #5: Enable Github Pages

1. Go to your GitHub repository in the browser.
2. Click "**Settings--> Pages**" (in the left nav)
3. Under **Branch** select `main` and `/ (root)`.
4. Save. Wait 30-60 seconds.
5. Visit your site at `https://<your-username>.github.io/<repo-name>

## Step #6: Reflection

Answer in your README (or I might provide a Google form, tbd)

- What did you learn about Git, GitHub or Codespaces?
- What felt confusing or new to you?
