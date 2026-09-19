# The Civil Media Private Limited — News Portal

A complete browser-based news portal with:
- Public news website
- Breaking-news ticker
- Categories: Nepal, Politics, Business, World, Sports, Entertainment, Technology
- Search
- Responsive mobile design
- Newsletter section
- Contact/footer
- Admin login
- Dashboard counts
- Add/edit/delete/archive news
- Publish/Draft status
- Article search
- Company settings
- Image URL support
- Browser localStorage data storage

## Demo Admin Login
Username: `admin`
Password: `admin123`

## Run
This is a static website. You can open `index.html` directly in a browser.

For a better local development experience, serve the folder with any static server, for example:
- VS Code Live Server
- Python HTTP server: `python -m http.server 8000`

Then open:
`http://localhost:8000/`

## Important
The admin credentials and data storage are intentionally client-side because this version uses browser localStorage. This is suitable for a prototype/demo, not production security.

For production, replace localStorage authentication with a server-side authentication system and database.
