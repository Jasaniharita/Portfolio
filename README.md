# 🌐 Aditya Bhatt — Cybersecurity Portfolio

Welcome to my personal portfolio website, hosted via GitHub Pages!

This website showcases my professional journey, technical skills, certifications, achievements, major projects, and published articles in the field of **Cybersecurity**, **VAPT**, **Cryptography**, and **Cloud Security**.

> 🔒 Ethical Hacker | Red Team Specialist | TryHackMe Global Top 2% | Published Author

---

## 🚀 Live Website

Visit the portfolio: [https://adityabhatt3010.github.io](https://adityabhatt3010.github.io)

---

## 🛠️ Built With

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Font Awesome**
- **Google Fonts**
- **Responsive Design** with custom dark/light theme toggle
- 💻 Cyberpunk-inspired UI for a hacker aesthetic

---

## 📂 Structure

```
📁 root
    ├── index.html # Main page
    ├── style.css # Styling and themes
    ├── script.js # Interactivity and animations
    ├── assets/ # Images
    └── README.md # You are here
```

---

## 🧠 Sections Included

- 👨‍💻 About Me
- ⚙️ Skills (Security, Programming, Tools)
- 📁 Projects (with GitHub links)
- 🏢 Experience
- 🎓 Education
- 📜 Certifications
- 🏆 Achievements
- 📚 Trainings & Courses
- 📝 Blog Articles
- 📞 Contact Form

---

## 🖥️ Hosting via GitHub Pages

This site is deployed using [GitHub Pages](https://pages.github.com/), a free and reliable method for web hosting directly from your GitHub repository.

---

## 🚀 Deploy to Vercel

### Method 1: Deploy via Vercel Dashboard (Easiest)

1. **Push your code to GitHub**
   - Make sure all your files are committed and pushed to your GitHub repository

2. **Sign up/Login to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Sign up or login (you can use your GitHub account)

3. **Import your project**
   - Click "Add New Project"
   - Import your GitHub repository
   - Vercel will auto-detect it's a static site

4. **Configure and Deploy**
   - Framework Preset: **Other** (or leave as default)
   - Root Directory: `./` (root)
   - Build Command: Leave empty (no build needed for static site)
   - Output Directory: Leave empty (or `./`)
   - Click **Deploy**

5. **Your site is live!**
   - Vercel will provide you with a URL like `your-project.vercel.app`
   - You can add a custom domain later in project settings

### Method 2: Deploy via Vercel CLI

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login
   ```

3. **Deploy**
   ```bash
   vercel
   ```
   - Follow the prompts
   - For production deployment: `vercel --prod`

### Configuration

The project includes a `vercel.json` file for optimal static site configuration.

**Note:** Make sure to update your EmailJS credentials in `script.js` before deploying if you want the contact form to work.

---

## 🌐 Connect Custom Domain (Namecheap)

### Step 1: Add Domain in Vercel

1. **Go to your Vercel project dashboard**
   - Click on your project
   - Go to **Settings** → **Domains**

2. **Add your domain**
   - Enter your domain (e.g., `yourdomain.com` or `www.yourdomain.com`)
   - Click **Add**
   - Vercel will show you DNS configuration instructions

### Step 2: Configure DNS in Namecheap

#### Option A: Using A Record (Root Domain - yourdomain.com)

1. **Login to Namecheap**
   - Go to [namecheap.com](https://www.namecheap.com) and login
   - Go to **Domain List** → Click **Manage** next to your domain

2. **Go to Advanced DNS**
   - Click on the **Advanced DNS** tab

3. **Add A Record**
   - Click **Add New Record**
   - Select **A Record**
   - **Host**: `@` (for root domain) or leave blank
   - **Value**: Use the IP address provided by Vercel (usually `76.76.21.21`)
   - **TTL**: Automatic (or 30 min)
   - Click the checkmark to save

4. **Add CNAME Record for www**
   - Click **Add New Record**
   - Select **CNAME Record**
   - **Host**: `www`
   - **Value**: `cname.vercel-dns.com`
   - **TTL**: Automatic
   - Click the checkmark to save

#### Option B: Using CNAME (Recommended - Easier)

1. **In Namecheap Advanced DNS**
   - Remove any existing A records for `@` (if any)
   - Click **Add New Record**
   - Select **CNAME Record**
   - **Host**: `@`
   - **Value**: `cname.vercel-dns.com`
   - **TTL**: Automatic
   - Click the checkmark to save

2. **Add www subdomain**
   - Click **Add New Record**
   - Select **CNAME Record**
   - **Host**: `www`
   - **Value**: `cname.vercel-dns.com`
   - **TTL**: Automatic
   - Click the checkmark to save

### Step 3: Verify in Vercel

1. **Wait for DNS propagation** (can take 5 minutes to 48 hours, usually within 1 hour)
2. **Check status in Vercel**
   - Go back to Vercel → Settings → Domains
   - You should see "Valid Configuration" when DNS is properly configured
   - Status will change from "Pending" to "Valid"

### Step 4: Enable HTTPS (Automatic)

- Vercel automatically provisions SSL certificates via Let's Encrypt
- Once DNS is configured, HTTPS will be enabled automatically
- This usually takes a few minutes after DNS propagation

### Troubleshooting

**If domain doesn't connect:**
- Wait 24-48 hours for full DNS propagation
- Check DNS records are correct in Namecheap
- Verify domain is added correctly in Vercel
- Use [whatsmydns.net](https://www.whatsmydns.net) to check DNS propagation globally

**Common Issues:**
- **"Invalid Configuration"**: Double-check DNS records match Vercel's requirements
- **"Pending" for too long**: DNS propagation can take time, be patient
- **HTTPS not working**: Wait a few minutes after DNS is valid, SSL is auto-provisioned

---

## 📧 Connect With Me

- 🔗 [Linktree](https://linktr.ee/AdityaBhatt3010)
- 💼 [LinkedIn](https://www.linkedin.com/in/aditya-bhatt-b61868250/)
- 🐙 [GitHub](https://github.com/adityabhatt3010)
- 📝 [Medium](https://medium.com/@info.adityabhatt3010)
- 🛡️ [TryHackMe](https://tryhackme.com/p/info.adityabhatt)
- 🎖️ [Credly](https://www.credly.com/users/aditya-bhatt3010)

---

> Designed & Developed with 💙 by **Aditya Bhatt**
