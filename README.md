# The Civil Media Private Limited — Complete News Portal

## Public Website
- Home / latest news
- Nepal News
- Politics
- Business
- International
- Entertainment
- Sports
- Technology
- Video / Photo Gallery
- Breaking-news ticker
- Search
- Fully responsive mobile layout
- About page
- Contact page with browser-stored messages
- Advertisement spaces
- Social-media links
- Individual article pages
- Published date/time
- Author/byline
- English / Nepali UI toggle
- English + Nepali article fields

## Admin CMS
Login defaults:
- Username: `admin`
- Password: `admin123`

Admin modules:
- Dashboard
- Add/edit articles
- Publish/draft/archive/restore
- Article search/filter
- English + Nepali headlines, summaries and content
- Published date/time
- Author/byline
- Featured + breaking flags
- Photo/video gallery management
- Appearance/branding
  - body font
  - heading font
  - primary/accent/background colors
  - card radius
  - content width
  - logo URL
  - default article image
  - homepage hero image
  - advertisement text/display
- Company settings
  - English/Nepali company name
  - about text
  - address/email/phone
  - Facebook/YouTube/Instagram/X/TikTok URLs
- Admin Account
  - change username
  - change password
- Contact message viewer

## Storage
This demo uses browser localStorage/sessionStorage. News, settings, gallery items, subscribers, messages and admin credentials are stored in the browser.

### Production warning
This is a client-side CMS prototype. Anyone with browser access can inspect localStorage and the credentials are not securely protected. For production, use a backend API/database and server-side authentication with hashed passwords, HTTPS, role permissions, validation, image storage and backups.

## Run
Extract the ZIP and open `index.html`, or serve the folder using VS Code Live Server / another static web server.
