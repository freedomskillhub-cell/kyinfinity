KYNFINITY CONSULTING - HOSTING GUIDE
====================================

IMPORTANT
---------
Upload the CONTENTS of this folder, not the ZIP file itself and not the
folder containing these files.

HOSTINGER
---------
1. Open Hostinger hPanel -> Websites -> Manage -> File Manager.
2. Open the domain's public_html folder.
3. Remove the default index.html (only if it is the Hostinger placeholder).
4. Upload all files and folders from this package directly into public_html.
   The final layout must look like this:

   public_html/index.html
   public_html/.htaccess
   public_html/assets/...
   public_html/media/...
   public_html/services/...

5. If Hostinger uploaded a ZIP, right-click it -> Extract, then move the
   extracted CONTENTS into public_html. Do not leave an extra outer folder.
6. Open the domain in a private/incognito browser window and hard-refresh.

GITHUB
------
For a normal GitHub repository, upload/commit the CONTENTS of this package.
For GitHub Pages:
- Use the repository root (or a username.github.io repository/custom domain).
- Enable Settings -> Pages -> Deploy from branch -> main -> /(root).
- The .htaccess file is for Apache/Hostinger and is ignored by GitHub Pages.
- The .nojekyll file prevents GitHub from filtering static files.

CONTACT LINKS
-------------
The compiled site already contains its WhatsApp, Gmail, Instagram, LinkedIn,
and YouTube links. No server-side PHP is required for this static package.

IF THE SITE SHOWS A BLANK PAGE
------------------------------
Check that index.html, assets/, and media/ are directly inside public_html.
The most common mistake is public_html/KYNFINITY-.../index.html instead of
public_html/index.html.
