# Kevin Anrico — Portfolio website

All text and images on the site come from `content.json`. You edit that file through Pages CMS (a visual editor), and every save updates the live site automatically.

## One-time setup (about 15 minutes)

### 1. Put the site on GitHub
1. Create a free account at github.com.
2. Click **New repository**, name it `portfolio`, set it to **Public** or **Private** (either works), and create it.
3. On the empty repository page, click **uploading an existing file**.
4. Drag in everything from this folder: `index.html`, `content.json`, `.pages.yml`, `README.md` and the whole `img` folder. Then click **Commit changes**.
   - Mac hides files starting with a dot. If `.pages.yml` doesn't show in Finder, press **Cmd + Shift + .** to show it.

### 2. Connect Netlify to GitHub (auto-deploy)
1. Log in at app.netlify.com → **Add new project** → **Import an existing project** → **GitHub**.
2. Pick the `portfolio` repository.
3. Leave the build command empty and set the publish directory to `/` (the root). Deploy.
4. From now on, every change saved to GitHub goes live within about a minute.
5. Optional: add your own domain under **Domain management**.

### 3. Open the CMS
1. Go to app.pagescms.org and sign in with GitHub.
2. Allow Pages CMS access to the `portfolio` repository.
3. Open the repository. You'll see **Website content** with these sections: Hero, Projects, Unreleased, About, Experience, Capabilities, Approach steps, Clients and Contact.

## Everyday editing
- **Change text:** edit the field, then click **Save**. The site updates in about a minute.
- **Add a project:** in Projects, click **Add an entry**, fill in the fields, upload a cover and gallery images, and save. Give it a unique link name such as `chery-j6`.
- **Reorder projects:** drag the entries. The order on the site follows the list.
- **Category:** decides which filter button (Campaigns & KV, or Brand systems & livery) shows the project.
- **Gallery columns:** use 2 for wide 16:9 images and 3 for 4:5 social posts.

## Image tips
- Export at about 1600px on the long side, as WebP or JPG at around 80% quality. Large files slow the site down.
- 16:9 images work best in Unreleased, and 4:3 or wider for project covers.

## Notes
- The site loads `content.json` when the page opens, so it must be served from a host such as Netlify. Double-clicking `index.html` on your computer will show "Content could not load."
- Keep the `slug` (link name) of an existing project the same if you've already shared links like `yoursite.com/#telfast`.
