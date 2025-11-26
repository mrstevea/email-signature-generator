# SpendRule Email Signature Generator

A simple, web-based tool to generate professional email signatures for SpendRule team members. No server required – just open `index.html` in a browser.

![Email Signature Generator Preview](preview.png)

## ✨ Features

- **Live Preview** – See your signature update as you type
- **Permanent Logo** – SpendRule logo is embedded for consistency
- **Hosting Guide** – Built-in instructions for hosting profile photos
- **One-Click Copy** – Copy formatted signature directly to clipboard
- **Download HTML** – Save signature as an HTML file
- **Email Client Compatible** – Works with Gmail, Outlook, Apple Mail, and more
- **No Dependencies** – Pure HTML, CSS, and JavaScript
- **Mobile Responsive** – Works on desktop and mobile devices
- **Outlook VML Support** – Rounded profile photos work in Outlook

## 🚀 Quick Start

### Option 1: Use Online (Recommended)

Visit the live generator: **https://mrstevea.github.io/email-signature-generator/**

### Option 2: Run Locally

1. Download or clone this repository
2. Open `index.html` in any web browser
3. Fill in your details
4. Click "Copy Signature" and paste into your email client

### ⚠️ First-Time Setup (Important!)

After cloning the repo, update the logo URL in `index.html`:

1. Open `index.html` in a text editor
2. Find this line near the top of the `<script>` section:
   ```javascript
   const SPENDRULE_LOGO = "https://raw.githubusercontent.com/YOUR_USERNAME/email-signature-generator/main/assets/spendrule_logo.png";
   ```
3. Replace `YOUR_USERNAME` with your GitHub username (e.g., `spendrule`)
4. Push to GitHub and the logo will be hosted automatically!

## 📧 Installation Guide

### Gmail

1. Generate your signature using the tool
2. Click **"Copy Signature"**
3. Open Gmail → Settings (gear icon) → **See all settings**
4. Scroll to **Signature** section
5. Click **Create new** or edit existing
6. Paste your signature (Ctrl/Cmd + V)
7. Click **Save Changes**

### Outlook (Desktop)

1. Generate your signature using the tool
2. Click **"Copy Signature"**
3. Go to **File → Options → Mail → Signatures**
4. Click **New** to create a new signature
5. Paste your signature (Ctrl/Cmd + V)
6. Click **OK**

### Outlook (Web)

1. Generate your signature using the tool
2. Click **"Copy Signature"**
3. Click Settings (gear icon) → **View all Outlook settings**
4. Go to **Mail → Compose and reply**
5. Paste in the signature editor
6. Click **Save**

### Apple Mail

1. Generate your signature and click **"Download HTML"**
2. Open the downloaded HTML file in Safari
3. Select all (Cmd + A) and copy (Cmd + C)
4. Open Mail → **Preferences → Signatures**
5. Click **+** to add new signature
6. Paste (Cmd + V)

## 🖼️ Image Hosting

For the signature to display correctly, profile photos must be hosted online. The SpendRule logo is permanently embedded.

Recommended hosting options:

| Service | Free Tier | Notes |
|---------|-----------|-------|
| [Cloudinary](https://cloudinary.com) | 25GB | Best for image optimization |
| [Imgur](https://imgur.com) | Unlimited | Simple, no account needed |
| [AWS S3](https://aws.amazon.com/s3/) | 5GB | Professional, requires setup |
| [Google Cloud Storage](https://cloud.google.com/storage) | 5GB | Good for Google Workspace |

### Recommended Image Size

| Image | Display Size | Upload Size (@2x) |
|-------|--------------|-------------------|
| Profile Photo | 68×68 px | 136×136 px |

*Note: The SpendRule logo is permanently embedded and doesn't need to be uploaded.*

## 🎨 Customization

### Changing Brand Colors

Edit the following values in `index.html`:

```css
/* Primary brand color (orange) */
color: #FF4F00;

/* Text colors */
color: #000000;  /* Name */
color: #7F7F7F;  /* Title & contact info */
```

### Modifying Layout

The signature follows these Figma specifications:

- Profile photo: 68×68px with 12px border radius
- Gap between photo and content: 16px
- Name: 16px, -0.35px letter-spacing
- Title: 12px, -0.26px letter-spacing  
- Contact info: 12px, -0.22px letter-spacing, 4px vertical gap
- Logo: 67×14px, aligned bottom-right (permanently embedded)

## 🧪 Testing

Before rolling out to the team:

1. ✅ Send test email to yourself
2. ✅ Verify images load correctly
3. ✅ Test all links (mailto, tel, website)
4. ✅ Forward email to different email service
5. ✅ Check on mobile device

## 📁 Project Structure

```
email-signature-generator/
├── index.html              # Main application (all-in-one)
├── assets/
│   └── spendrule_logo.png  # Company logo (hosted via GitHub raw)
├── README.md               # This file
├── LICENSE                 # MIT License
└── preview.png             # Screenshot for README
```

## 🤝 Contributing

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add new feature'`)
4. Push to branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 License

MIT License – feel free to use and modify for your organization.

## 🔗 Links

- [SpendRule Website](https://spendrule.com)
- [Report an Issue](https://github.com/spendrule/email-signature-generator/issues)

---

Built with ❤️ for the SpendRule team
