LETTER FROM V — HOW TO PUT THIS ONLINE

You do not need to know coding to publish this version.

OPTION A — GitHub Pages (free)
1. Create a GitHub account at github.com.
2. Create a new public repository named: letterfromv
3. Upload every file from this folder into that repository.
4. Open Settings > Pages.
5. Under Build and deployment, choose "Deploy from a branch".
6. Select branch "main" and folder "/ (root)", then Save.
7. GitHub will give you a temporary public address.

CONNECT letterfromv.com
1. In your GitHub repository, go to Settings > Pages.
2. Under Custom domain, enter: letterfromv.com
3. GitHub will show DNS instructions.
4. Open Porkbun > Domain Management > letterfromv.com > DNS.
5. Add the records GitHub tells you to add.
6. Also add:
   Type: CNAME
   Host: www
   Answer: YOUR-GITHUB-USERNAME.github.io
7. Back in GitHub Pages, enable "Enforce HTTPS" once available.

HOW TO ADD A NEW POST
1. Duplicate letter-new-york.html.
2. Rename it, e.g. letter-seoul-in-october.html.
3. Open it in any plain text editor.
4. Change:
   - page title
   - date/category
   - headline
   - paragraphs
   - image URL
5. Add a new row linking to that file in letters.html.
6. Upload the changed files to GitHub.

IMPORTANT
The three demo photos currently load from Unsplash over the internet.
You can later replace them with your own images by creating an /images folder
and changing the image src values to local files.

CONTACT EMAIL
The site currently links to hello@letterfromv.com. That email will NOT exist
automatically just because you own the domain. Replace it with your actual email
or create a custom email service later.
