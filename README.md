# Backend-First Portfolio

A portfolio website designed specifically for backend engineers, showcasing system design, API architecture, and engineering decisions rather than UI screenshots.

## 🎯 Purpose

This portfolio demonstrates backend engineering competence through:
- **System Architecture** - Visual diagrams and design decisions
- **API Documentation** - Endpoint specifications and contracts
- **Database Design** - Schema design and relationships
- **Engineering Trade-offs** - Scaling considerations and failure handling

## 🚀 Live Demo

[View Portfolio](https://your-portfolio.vercel.app) *(Update after deployment)*

## 📁 Project Structure

```
portfolio/
├── index.html              # Homepage
├── projects.html           # Projects overview
├── projects/
│   ├── oauth-aggregator.html      # OAuth & Analytics Platform
│   ├── varun-travellers.html      # Travel Booking System
│   ├── vendor-marketplace.html    # Multi-Category Marketplace
│   ├── yorder.html                # Quick Commerce Contributions
│   └── lava.html                  # Stock Prediction Contributions
├── assets/
│   └── styles.css          # Clean documentation-style CSS
└── README.md
```

## 🛠️ Technologies

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Custom CSS (documentation-inspired design)
- **Hosting**: Vercel
- **Version Control**: Git/GitHub

## 📦 Deployment

### Deploy to Vercel

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Backend-first portfolio"
   git branch -M main
   git remote add origin https://github.com/MohdAqibChauhan/portfolio.git
   git push -u origin main
   ```

2. **Deploy to Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will auto-detect static site
   - Click "Deploy"

### Local Development

Simply open `index.html` in your browser:

```bash
# Option 1: Direct open
start index.html

# Option 2: Local server (if you have Python)
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📝 Customization

### Update Personal Info

Edit `index.html` and `projects.html`:
- Email address
- GitHub username
- LinkedIn (if added)

### Add New Projects

1. Create new HTML file in `projects/` folder
2. Follow the structure of existing project pages
3. Add project card to `projects.html`

### Modify Styling

Edit `assets/styles.css` to customize:
- Color scheme (CSS variables in `:root`)
- Typography
- Layout spacing

## 🎨 Design Philosophy

**Backend-Focused, Not UI-Focused:**
- Clean, minimal design (like API documentation)
- Content over aesthetics
- Emphasis on technical depth
- Readable code examples and schemas

## 📊 Projects Included

1. **OAuth Aggregator & Analytics Platform** - Multi-platform OAuth integration with data sync
2. **Varun Travellers** - Travel booking platform backend
3. **Vendor Marketplace** - Multi-category service booking system
4. **Yorder** - Quick commerce platform contributions
5. **Lava** - Stock prediction platform contributions

## 📧 Contact

**Mohd Aqib Chauhan**
- Email: chauhanmohdaqib@gmail.com
- GitHub: [@MohdAqibChauhan](https://github.com/MohdAqibChauhan)

## 📄 License

This portfolio template is free to use and modify for your own backend portfolio.

---

**Note:** This portfolio is designed to showcase backend engineering skills to recruiters and interviewers. Each project page demonstrates system-level thinking, not just code.
