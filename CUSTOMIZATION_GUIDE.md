# 🎯 QUICK CUSTOMIZATION CHECKLIST

Complete these steps to personalize your portfolio:

## ✅ STEP 1: Personal Information (5 minutes)

### In `index.html`, find and replace:

- [ ] **Line 7**: Change page title
  ```
  <title>Portfolio - Software Developer | YOUR NAME</title>
  ```

- [ ] **Line 68**: Update your name in hero section
  ```
  <h1 class="hero-title">Hi, I'm <span class="name">YOUR NAME</span></h1>
  ```

- [ ] **Line 69**: Update your professional title
  ```
  <p class="hero-subtitle">YOUR PROFESSIONAL TITLE</p>
  ```

- [ ] **Line 70**: Update introduction
  ```
  <p class="hero-description">YOUR INTRODUCTION HERE</p>
  ```

- [ ] **Lines 76-78**: Update social media links
  ```
  <a href="YOUR_GITHUB_URL" target="_blank" class="social-icon">
  <a href="YOUR_LINKEDIN_URL" target="_blank" class="social-icon">
  <a href="YOUR_TWITTER_URL" target="_blank" class="social-icon">
  ```

## ✅ STEP 2: About Section (5 minutes)

- [ ] **Line 102**: Update about text (first paragraph)
  ```
  <p>YOUR ABOUT TEXT HERE</p>
  ```

- [ ] **Line 103**: Update about text (second paragraph)
  ```
  <p>MORE ABOUT YOU</p>
  ```

- [ ] **Lines 107, 110, 113**: Update stats
  ```
  <h3>YOUR_NUMBER+</h3>
  <p>YOUR_STAT_NAME</p>
  ```

## ✅ STEP 3: Skills Section (5 minutes)

- [ ] Update Frontend skills (line 133)
- [ ] Update Backend skills (line 141)
- [ ] Update Tools & DevOps (line 149)
- [ ] Update Soft Skills (line 157)

Replace skill tags like:
```html
<span class="skill-tag">YOUR_SKILL</span>
```

## ✅ STEP 4: Projects Section (15 minutes)

For each project card, update:
- [ ] Project title
- [ ] Project description
- [ ] Technologies used
- [ ] Live demo link
- [ ] GitHub code link

Example project card starts at line 182.

**To add more projects**: Copy an entire project card and paste it in the projects grid.

## ✅ STEP 5: Contact Information (5 minutes)

- [ ] **Line 315**: Update email
  ```
  <a href="mailto:YOUR_EMAIL@example.com">YOUR_EMAIL@example.com</a>
  ```

- [ ] **Line 322**: Update phone
  ```
  <a href="tel:YOUR_PHONE_NUMBER">+1 (234) 567-890</a>
  ```

- [ ] **Line 328**: Update location
  ```
  <p>YOUR_CITY, YOUR_COUNTRY</p>
  ```

- [ ] **Line 347**: Update copyright year (footer)
  ```
  <p>&copy; 2024 YOUR NAME. All rights reserved.</p>
  ```

## ✅ STEP 6: Color Customization (Optional - 5 minutes)

In `style.css`, find and update the color variables:

```css
:root {
    --primary-color: #6366f1;        /* Change to your brand color */
    --secondary-color: #8b5cf6;      /* Secondary brand color */
    --accent-color: #ec4899;         /* Accent for highlights */
}
```

Popular color combinations:
- **Tech Blue**: `#0080ff`, `#0066cc`, `#0052a3`
- **Professional Purple**: `#7c3aed`, `#6d28d9`, `#5b21b6`
- **Modern Green**: `#10b981`, `#059669`, `#047857`
- **Startup Orange**: `#f97316`, `#ea580c`, `#c2410c`

## ✅ STEP 7: Test & Deploy

- [ ] Open `index.html` in your browser
- [ ] Test all links and buttons
- [ ] Test on mobile devices
- [ ] Verify contact form works
- [ ] Check social media links
- [ ] Deploy to hosting (GitHub Pages, Netlify, etc.)

## 📝 COMMON REPLACEMENTS SUMMARY

| Find | Replace With |
|------|--------------|
| `YOUR NAME` | Your actual name |
| `Your Name` | Your actual name |
| `your.email@example.com` | Your email |
| `+1 (234) 567-890` | Your phone |
| `Your City, Country` | Your location |
| `#` (links) | Actual URLs |
| `Your City` | Your city |

## 🔗 SOCIAL MEDIA URL EXAMPLES

```
GitHub:    https://github.com/yourusername
LinkedIn:  https://linkedin.com/in/yourprofile
Twitter:   https://twitter.com/yourhandle
Portfolio: https://yourportfolio.com
```

## 🎨 ICON CUSTOMIZATION

To change icons in the about/contact sections, find icons at:
https://fontawesome.com/icons

Replace the icon class:
- `<i class="fas fa-envelope"></i>` - Email icon
- `<i class="fas fa-phone"></i>` - Phone icon
- `<i class="fas fa-map-marker-alt"></i>` - Location icon
- `<i class="fas fa-code"></i>` - Code icon
- `<i class="fab fa-github"></i>` - GitHub icon
- `<i class="fab fa-linkedin"></i>` - LinkedIn icon

## ⚡ QUICK TIPS

1. **Add More Projects**: Copy any project-card div and paste below
2. **More Skills**: Add more `<span>` tags in skill categories
3. **Change Font**: Update font-family in `style.css`
4. **Adjust Spacing**: Modify padding/margin values in CSS
5. **Add Custom Sections**: Create new sections following existing pattern

## 🚀 BEFORE YOU DEPLOY

- [ ] Replace ALL placeholder text with your info
- [ ] Update ALL links (GitHub, LinkedIn, email, etc.)
- [ ] Test navigation on mobile
- [ ] Check form functionality
- [ ] Test all project links
- [ ] Verify social media icons work
- [ ] Make sure contact info is correct
- [ ] Review spelling and grammar

## 📚 HELPFUL RESOURCES

- **Colors**: https://colorhunt.co/
- **Icons**: https://fontawesome.com/icons
- **Fonts**: https://fonts.google.com/
- **Inspiration**: https://dribbble.com/

---

**Done! Your portfolio is ready to impress! 🎉**
