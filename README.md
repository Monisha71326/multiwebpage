# 🎓 Eduford University Website

A multi-page **College / University Website** built using **HTML**, **CSS**, and **Font Awesome** icons.

## 📸 Screenshots

### 🏠 Home Page
![Home Page](assets/img/screenshots/home.png)

### ℹ️ About Us Page
![About Page](assets/img/screenshots/about.png)

### 📚 Courses Page
![Courses Page](assets/img/screenshots/course.png)

### 📝 Blog Page
![Blog Page](assets/img/screenshots/blog.png)

### 📞 Contact Page
![Contact Page](assets/img/screenshots/contact.png)

---

## 📁 Project Structure

```
project/
│
├── index.html                  # Main entry point
│
├── pages/                      # All inner pages
│   ├── About.html
│   ├── course.html
│   ├── blog.html
│   └── contact.html
│
├── assets/
│   ├── css/
│   │   └── style.css           # Main stylesheet
│   ├── img/                    # All images
│   │   ├── meeting.png
│   │   ├── map.png
│   │   ├── cr.png
│   │   ├── college.png
│   │   ├── logo.png
│   │   └── ...
│   └── img/screenshots/        # 📸 Page screenshots
│       ├── home.png
│       ├── about.png
│       ├── course.png
│       ├── blog.png
│       └── contact.png
```

## 🌐 Pages

| Page | File | Description |
|------|------|-------------|
| 🏠 Home | `index.html` | Landing page with hero section |
| ℹ️ About Us | `pages/About.html` | University intro with image |
| 📚 Courses | `pages/course.html` | Intermediate, Degree, Graduation |
| 📝 Blog | `pages/blog.html` | Certificate & Online Programs 2025 |
| 📞 Contact | `pages/contact.html` | Form, map, address, social links |

## 🚀 Features

- Multi-page website with consistent navigation
- Hero section with background image
- About section with image and description
- Courses section with 3 course cards
- Blog page with certificate programs and post categories
- Contact page with form, map, address and social media icons
- Font Awesome 6.7.2 icons
- Custom CSS styling

## 🛠️ Technologies Used

- HTML5
- CSS
- Font Awesome 6.7.2 (CDN)

## ⚙️ Setup & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/Monisha71326/multiwebpage.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd multiwebpage
   ```

3. **Open in browser**
   ```bash
   open index.html
   ```
   or double-click `index.html`

## 🔗 Navigation Flow

```
index.html  (Home)
    ├── pages/About.html
    ├── pages/course.html
    ├── pages/blog.html
    └── pages/contact.html
```

## 📸 How to Add Screenshots

Screenshots-ஐ எடுத்து சேர்க்க இந்த steps follow பண்ணுங்க:

1. **Folder உருவாக்கவும்:**
   ```bash
   mkdir -p assets/img/screenshots
   ```

2. **ஒவ்வொரு page-ஐயும் browser-ல் open பண்ணி screenshot எடுக்கவும்:**
   - `index.html` → Save as `assets/img/screenshots/home.png`
   - `pages/About.html` → Save as `assets/img/screenshots/about.png`
   - `pages/course.html` → Save as `assets/img/screenshots/course.png`
   - `pages/blog.html` → Save as `assets/img/screenshots/blog.png`
   - `pages/contact.html` → Save as `assets/img/screenshots/contact.png`

3. **Git-ல் push பண்ணவும்:**
   ```bash
   git add assets/img/screenshots/
   git commit -m "Add page screenshots to README"
   git push
   ```

> 💡 **Tip:** Windows-ல் `Win + Shift + S` அல்லது Mac-ல் `Cmd + Shift + 4` use பண்ணி screenshot எடுக்கலாம். Full-page screenshot-க்கு browser DevTools → `Ctrl+Shift+P` → "Capture full size screenshot" use பண்ணுங்க!

## 🚀 GitHub Push Commands

```bash
git init
git add .
git commit -m "Initial commit - Eduford University Website"
git branch -M main
git remote add origin https://github.com/Monisha71326/multiwebpage.git
git push -u origin main
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
