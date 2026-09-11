# russia.solutions

Static landing page for the `russia.solutions` domain, served by GitHub Pages.

One HTML file, no build step, no dependencies, bilingual (EN/RU).
Inquiries: `sale@russia.solutions`.

Analytics: Google Analytics 4 and Yandex Metrica, both loaded directly from the
page. Session recording, scroll maps and form-field capture are switched off.

`.github/workflows/healthcheck.yml` checks every five minutes that the page is
up and still serves its own content; a failure e-mails the repository owner.

Source of truth for the page is `landing/index.html` in the private working
repository; changes are copied here.
