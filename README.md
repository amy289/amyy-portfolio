# Amyy — Developer Portfolio (Lab 1)

A four-page responsive developer portfolio built for Web Technologies Lab 1.

## Pages
- `index.html` — Home and introduction
- `about.html` — Education, profile, skills and learning milestones
- `projects.html` — Student and lab projects
- `contact.html` — Browser-validated demo contact form

## Folder structure
```text
Lab1_Amyy_Developer_Portfolio/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
└── README.md
```

## Run with XAMPP
1. Install and open XAMPP.
2. Start **Apache**.
3. Copy this whole project folder into XAMPP's `htdocs` folder.
4. Open `http://localhost/Lab1_Amyy_Developer_Portfolio/` in Chrome or Edge.
5. Open Developer Tools with `F12`; inspect Elements, Console and Network. In Network, reload the page and confirm `css/style.css` and `js/script.js` load successfully.

You can also open `index.html` with VS Code Live Server for a quick preview, but the lab specifically asks you to demonstrate the project through XAMPP localhost.

## Git practice — at least 3 meaningful commits
From the project folder, open a terminal and run:
```bash
git init
git add README.md
git commit -m "Add portfolio project documentation"
git add index.html about.html projects.html contact.html
git commit -m "Create four portfolio pages"
git add css js images
git commit -m "Add responsive styling and JavaScript interactions"
```
Then create an empty GitHub repository and connect it:
```bash
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```
Replace the URL with your own repository URL. Never share your GitHub password or token.

## Personal information note
The portfolio uses the display name **Amyy**. Phone number and email are intentionally not published on the contact page. Add a public contact address only if you choose to share it.

## Functionality note
The contact form only performs browser-side validation and displays a demo message. It does not send or save messages because this is a front-end portfolio lab. The theme preference is saved in the browser using `localStorage`.
