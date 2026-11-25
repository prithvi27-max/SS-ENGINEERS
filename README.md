# S S Engineers website: setup steps

## What is in this folder
- index.html: the website
- images/: all photos and the logo
- data/: lists the admin panel edits (work photos, shop photos, customers)
- .pages.yml: settings for the admin panel

## 1. Put the files on GitHub (free)
1. Create an account at github.com (use a business email).
2. Click New repository. Name it ss-engineers-site. Choose Private. Create it.
3. Click "uploading an existing file". Drag in everything from this folder (index.html, .pages.yml, the images and data folders). Click Commit changes.
   Tip: .pages.yml starts with a dot and may be hidden on your computer. If you cannot see it, create it on GitHub with Add file > Create new file, name it .pages.yml, and paste the contents.

## 2. Publish the site on Cloudflare Pages (free)
1. Sign up at dash.cloudflare.com.
2. Workers & Pages > Create > Pages > Connect to Git. Pick the repository.
3. Framework preset: None. Build command: leave empty. Output directory: leave empty (or /). Click Save and Deploy.
4. You get a free address like ss-engineers.pages.dev. Every change saved on GitHub goes live in about a minute.

## 3. Connect the domain (ssengineer.com)
1. Buy the domain from GoDaddy, BigRock or Namecheap (about Rs 800 to 1,200 a year).
2. In Cloudflare Pages open the project > Custom domains > Set up a domain. Follow the DNS steps shown.

## 4. Admin panel for adding and deleting photos
1. Go to app.pagescms.org and sign in with GitHub.
2. Install it on the ss-engineers-site repository when asked.
3. Open "Our work photos", "Inside our shop photos" or "Customers".
4. Add a photo with a caption, delete one, or reorder them. Click Save. The website updates in about a minute.
5. To give the owner his own login, add his GitHub username under the repository Settings > Collaborators.

## 5. Business email (Outlook)
Buy Microsoft 365 Business Basic, add ssengineer.com, then add the MX and TXT records Microsoft shows you in the Cloudflare DNS page. Create rohan-metha@ssengineer.com or any name you like.

## Not editable in the admin panel
Phone number, WhatsApp number, email and address are in index.html. Ask for a change when needed.
