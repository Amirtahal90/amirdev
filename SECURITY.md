# Security Notes

## Threat model

This sample assumes an attacker can fully control the text entered into the demo form.

## Defenses demonstrated

1. A restrictive Content Security Policy limits executable and embedded content.
2. User-controlled strings are inserted with `textContent`, never `innerHTML`.
3. Input lengths are bounded before rendering.
4. A basic client-side submission limiter reduces accidental abuse in the demo.
5. No remote scripts, fonts, analytics, or runtime dependencies are loaded.

## Production requirements

Client-side checks are bypassable. A real application must repeat validation and authorization on the server, protect session tokens with secure cookie settings, implement appropriate CSRF protection, apply response security headers at the HTTP layer, rate-limit requests server-side, keep dependencies patched, and monitor security-relevant events.

To report a vulnerability in a deployed derivative, use the repository owner's preferred private disclosure process rather than publishing exploit details in an issue.
