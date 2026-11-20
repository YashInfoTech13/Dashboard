YASH INFOTECH COMMAND CENTRE — DASHBOARD
=========================================
Live address after setup:  https://yashinfotech13.github.io/Dashboard/
Team/admin page:           https://yashinfotech13.github.io/Dashboard/admin.html

WHAT'S INSIDE
  index.html            Front dashboard (metro board, live status, search, QR share, services, partners)
  admin.html            Team page to add / edit / delete partners and platforms (no coding)
  data/platforms.json   The platform links (Academic, Admission, Excellence 360, SNBP, Yash website)
  data/partners.json    Tie-ups, clients and service partners (with logos)
  data/services.json    The four service lines
  logos/  img/          Logos and images

1) UPLOAD TO GITHUB (one time)
  a. Open https://github.com/YashInfoTech13/Dashboard
  b. Click "Add file" -> "Upload files".
  c. Unzip this file on your computer, open the folder, select EVERYTHING inside it
     (index.html, admin.html, README.txt and the data, img, logos folders) and drag it in.
     Important: upload the contents, not the outer folder.
  d. Click "Commit changes".

2) TURN ON THE WEBSITE (one time)
  a. In the repository: Settings -> Pages.
  b. Source: "Deploy from a branch". Branch: main, folder: / (root). Save.
  c. Wait 1-2 minutes, then open https://yashinfotech13.github.io/Dashboard/

3) CREATE THE ADMIN TOKEN (one time, for whoever will add partners)
  a. GitHub -> your photo -> Settings -> Developer settings -> Personal access tokens
     -> Fine-grained tokens -> Generate new token.
  b. Name: dashboard-admin.  Expiration: 1 year (set a reminder to renew).
  c. Repository access: Only select repositories -> YashInfoTech13/Dashboard.
  d. Permissions -> Repository permissions -> Contents: Read and write.
  e. Generate and copy the token (starts with github_pat_). Keep it private.

4) ADD A NEW TIE-UP / CLIENT / PLATFORM
  a. Open .../Dashboard/admin.html (also linked as "Team login" at the bottom of the dashboard).
  b. Paste the token, click Connect.
  c. "+ Add new" -> name, Tie-up / Client / Service partner, city, website, description, logo.
  d. "Save & publish". It shows on the dashboard in about 1 minute.
  Platforms tab: add new portal links the same way. Each gets its own share link.

DIRECT LINKS FOR EACH PLATFORM (share these on WhatsApp)
  https://yashinfotech13.github.io/Dashboard/?go=academic
  https://yashinfotech13.github.io/Dashboard/?go=admission
  https://yashinfotech13.github.io/Dashboard/?go=excellence360
  https://yashinfotech13.github.io/Dashboard/?go=snbp
  https://yashinfotech13.github.io/Dashboard/?go=yash
  These open the platform straight away. If a platform address changes later, edit it in admin
  and the old shared links keep working.

SHORTCUTS ON THE DASHBOARD
  Ctrl+K or /   Search and jump to any platform, service or partner
  1 - 9         Open platform number 1-9 on the board

NOTE: Admission and SNBP sites are on free Render hosting. After a quiet period they take
about 30 seconds to wake up; the board shows them in amber ("Waking up") during that time.
