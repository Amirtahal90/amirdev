# SecureHub

A security-oriented responsive dark website sample for GitHub Pages or any static web server.

## Highlights

- Responsive, mobile-first dark UI
- Zero external dependencies
- Content Security Policy meta policy
- No `eval`, `Function`, or dynamic script loading
- User input rendered through `textContent` / DOM nodes
- Input length validation and a small client-side rate limiter
- No persistent storage for demo input
- Semantic HTML and accessible status messaging

## Run locally

Open `index.html` directly, or serve the directory with any static HTTP server.

## Important

This is a frontend security sample, not a complete security solution. A production application still needs server-side validation and authorization, secure session cookies, CSRF defenses where applicable, security headers at the server/CDN layer, rate limiting, logging/monitoring, dependency management, and appropriate output encoding.

## GitHub Pages

For a project repository, enable GitHub Pages from **Settings → Pages → Deploy from a branch**, then choose the default branch and root folder.

## License

Use and modify this sample for learning and prototyping.
