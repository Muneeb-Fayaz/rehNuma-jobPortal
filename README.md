<div align="center">

🔗 **Live Site:** [https://muneeb-fayaz.github.io/rehNuma-jobPortal/](https://muneeb-fayaz.github.io/rehNuma-jobPortal/)

# 🎯 RehNuma — Job Portal

### Find your dream job and apply instantly via Email

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-2563EB?style=for-the-badge)](https://muneeb-fayaz.github.io/rehNuma-jobPortal/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222?logo=github&logoColor=white)
![Responsive](https://img.shields.io/badge/Design-Responsive-10B981)

**[🔗 Open the live site](https://muneeb-fayaz.github.io/rehNuma-jobPortal/)**

</div>

---

## ✨ About

**RehNuma** (*"guide"* in Urdu/Kashmiri) is a lightweight, single-page job portal built for job
seekers, mainly in India. Browse openings, filter them by city, job type and salary, then
apply in seconds. There is no sign-up and no account to create: fill in the application
form and your email app opens with everything ready to send.

## 🚀 Features

| | Feature | Details |
|:--:|---|---|
| 🔍 | **Keyword search** | Search jobs by title, skill or company |
| 📍 | **Location filter** | Remote, Mumbai, Delhi, Bangalore, Hyderabad, Pune, Chennai, Kashmir |
| 💼 | **Job type filter** | Full-time, Part-time, Contract, Internship, Remote |
| 💰 | **Salary filter** | ₹0–5, ₹5–10, ₹10–20 and ₹20+ LPA |
| ↕️ | **Sorting** | Newest First, Salary High → Low, Salary Low → High |
| 📄 | **Apply modal** | Clean application form that opens inside the page |
| ✉️ | **Apply via Email** | One click sends your details to the employer through your email client |
| 📱 | **Responsive layout** | Works on phones, tablets and desktops |
| ⚡ | **Dynamic loading** | Job listings are loaded on the page, showing a "Loading jobs..." state meanwhile |
| 🔓 | **No login needed** | Browse and apply without creating an account |

## 📝 Application form

When you click a job's apply button, a form appears asking for:

**Required**

- 👤 Full Name
- 📞 Phone
- 📧 Email
- 📍 Location
- 🧭 Experience

**Optional**

- 🔗 LinkedIn profile
- 🐙 GitHub profile
- 💵 Current / Expected CTC
- 💡 Why are you interested?
- 🛠️ Key skills & qualifications
- 📄 Resume / CV (PDF, DOC or DOCX, up to 5 MB)

> 💡 **Tip:** After clicking **✉️ Apply via Email**, attach your resume in your email client
> before sending.

## 🧱 Page layout

```text
┌──────────────────────────────────────────────┐
│  🎯 RehNuma                                  │
│  Find your dream job and apply instantly...  │
│  [ Active Jobs ] [ 500+ Companies ] [ 10K+ ] │
├──────────────────────────────────────────────┤
│  🔍 Search  | Location ▾ | Type ▾ | Salary ▾ │
│                             Sort by ▾        │
├──────────────────────────────────────────────┤
│  ┌─ Job card ─────────────────────────────┐  │
│  │ Title · Company · 📍 City · 💰 Salary  │  │
│  │                         [ Apply ]      │  │
│  └────────────────────────────────────────┘  │
│  ...more job cards...                        │
├──────────────────────────────────────────────┤
│  About · Contact · Privacy Policy · Terms    │
└──────────────────────────────────────────────┘
```

## 🛠️ Tech stack

This is a static front-end site hosted on **GitHub Pages**, so it needs no backend or build
step.

- **HTML5** for structure
- **CSS3** for the card-based, responsive styling
- **JavaScript** for search, filters, sorting, the apply modal and the `mailto:` email flow

## 💻 Run it locally

```bash
# 1. Clone the repository
git clone https://github.com/muneeb-fayaz/rehNuma-jobPortal.git

# 2. Move into the folder
cd rehNuma-jobPortal

# 3. Open index.html in your browser
#    (or use a tiny local server)
python -m http.server 8000
# then visit http://localhost:8000
```

## 📂 Project structure

```text
rehNuma-jobPortal/
├── index.html      # page markup and application modal
├── style.css       # styling (if kept in a separate file)
├── script.js       # search, filter, sort and apply logic (if kept in a separate file)
└── README.md
```

> Adjust this tree to match the actual files in your repository.

## 🌐 Deployment

The site is deployed with **GitHub Pages**:

1. Push the code to the `main` branch.
2. Go to **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site goes live at `https://<username>.github.io/<repository>/`.

## 🗺️ Roadmap

- [ ] Employer dashboard to post and manage jobs
- [ ] Save / bookmark jobs
- [ ] Email job alerts
- [ ] Dark mode
- [ ] Working About, Contact, Privacy Policy and Terms pages
- [ ] Hindi / Urdu language support

## 🤝 Contributing

Suggestions and pull requests are welcome.

1. Fork the repository
2. Create a branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push the branch: `git push origin feature/my-feature`
5. Open a pull request

## 👤 Author

**Muneeb Fayaz**
Designed and created RehNuma.

🔗 [GitHub](https://github.com/muneeb-fayaz)

## 📄 License

© 2026 RehNuma. All rights reserved.

<div align="center">

Made with ❤️ in Kashmir

</div>
