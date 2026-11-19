# dosh8212.github.io

Root of the dosh8212 GitHub Pages domain. It exists for one file:
`.well-known/apple-app-site-association`, which tells iPhones that TripWright
(team H69ZF54MVC, bundle com.tripwright.app) opens share links under
`/tripwright-site/app/trip/`, `/collab/` and `/shared/`. Apple only reads this file
at the root of a domain, so it can't live in the tripwright-site repository.

`.nojekyll` makes GitHub Pages serve the `.well-known` folder. `index.html` sends
visitors to the TripWright site.

Source of truth: `site/user-site/` in the app repository.
