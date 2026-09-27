# Steph & Ron — Civil Union Invitation

A single self-contained web invitation (`index.html`) — no build step, no dependencies to install.

## Deploy on GitHub Pages

1. Create a new repository on GitHub (e.g. `steph-and-ron-invite`).
2. Upload `index.html` (and this `README.md`, optional) to the root of the repo.
   - Easiest way: on the repo page, click **Add file → Upload files**, drag `index.html` in, then **Commit changes**.
3. Go to the repo's **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, select `main` (or `master`) and folder `/ (root)`, then **Save**.
6. GitHub will give you a live URL after a minute or two, usually:
   `https://<your-username>.github.io/<repo-name>/`
7. Share that link with your ninong, ninang, and the rest of your guest list.

## Notes

- Everything (HTML, CSS, and JavaScript) lives in the one `index.html` file — nothing else to configure.
- The RSVP buttons open the guest's email app with a message pre-addressed to
  `Stephanniejoycecruz@gmail.com`. This depends on the guest's device having a
  default mail app set up.
- To change any detail (date, venue, names, invitee list, or the RSVP email
  address), open `index.html` in any text editor and search for the relevant
  text — everything is plain, readable HTML.
