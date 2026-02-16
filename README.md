Project structure

- assets/
  - css/        # stylesheets (moved `style.css` here)
  - images/     # project images (moved from `image/`)
  - js/         # place JS files here

- index.html
- about.html
- contact.html
- project.html
- services.html

Notes
- HTML files now reference `assets/css/style.css` and images under `assets/images/`.
- Contact forms now submit via FormSubmit.co. Replace the placeholder `your-email@example.com` in the form `action` with your real email and confirm the verification email that FormSubmit sends the first time.
- To preview, open `index.html` in a browser.
