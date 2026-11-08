# Diwali Wishes

Create a personalised Diwali wish with anyone's name and share it as a link. Each wish ends with "With love, Dhanwani Sagar".

## How it works
- Open the site, type a name, tap **Create link**.
- The link looks like `https://<username>.github.io/<repo>/#happy-diwali-rahul`.
- The receiver opens it, taps the diya, and sees their name light up with fireworks.

## Publish on GitHub Pages
1. Create a new repository (for example `diwali-wishes`) and upload `index.html` and this README.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. After a minute your site is live at `https://<username>.github.io/diwali-wishes/`.

## Change the sender name
Edit `var SENDER = "Dhanwani Sagar";` in `index.html`, and the "With love" line in the reveal section.
