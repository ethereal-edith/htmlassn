# Internet Terminologies — Web Assignment

A multi-page static website covering core Internet and Web technology terms from Topic 1.

**Admission Number:** 220965  
**Unit:** Web Application Development  
**Institution:** Strathmore University

---

## Topics Covered

| Page | Term |
|------|------|
| `index.html` | World Wide Web & HTML |
| `pages/DNS.html` | Domain Name System |
| `pages/HTTP.html` | HyperText Transfer Protocol |
| `pages/FTP.html` | File Transfer Protocol |
| `pages/TCPIP.html` | TCP/IP Protocol Suite |
| `pages/URL.html` | Uniform Resource Locator |
| `pages/intra_extranet.html` | Intranet & Extranet |
| `pages/multitier.html` | Multitier Architecture |
| `pages/request_response.html` | Request-Response Cycle |
| `pages/ServersVSBrowsers.html` | Web Servers vs Web Browsers |
| `pages/web_generation.html` | Web 1.0, 2.0, 3.0 & 4.0 |

## Project Structure

```
htmlassn/
├── index.html
├── style.css
├── README.md
├── images/
│   ├── dns.jpg
│   ├── http.png
│   ├── ftp.png
│   ├── tcpip.png
│   ├── url.png
│   ├── intraextra.png
│   ├── multiter.png
│   ├── reqresp.jpg
│   ├── servervsbrowser.jpg
│   ├── webgen.jpg
│   └── webgen2.jpg
└── pages/
    ├── DNS.html
    ├── HTTP.html
    ├── FTP.html
    ├── TCPIP.html
    ├── URL.html
    ├── intra_extranet.html
    ├── multitier.html
    ├── request_response.html
    ├── ServersVSBrowsers.html
    └── web_generation.html
```

## How to View Locally

Clone the repo and open `index.html` in any browser — no server needed.

```bash
git clone https://github.com/<your-username>/htmlassn.git
cd htmlassn
# Open index.html in your browser
```

## Deploying to GitHub Pages

1. Push all changes to the `main` branch on GitHub.
2. Go to your repository on GitHub.
3. Click **Settings** → **Pages** (in the left sidebar).
4. Under **Source**, select **Deploy from a branch**.
5. Set branch to `main` and folder to `/ (root)`, then click **Save**.
6. Wait ~1 minute, then your site will be live at:

```
https://<your-username>.github.io/htmlassn/
```

## Technologies Used

- HTML5
- CSS3 (custom properties, CSS Grid, Flexbox)
- No JavaScript frameworks — pure HTML/CSS