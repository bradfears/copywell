# Copywell: GitHub Pages edition

Upload index.html, app.js, marked.js, purify.js, and .nojekyll to the published folder. Keep the license files in your repository. Enable Enforce HTTPS in Pages settings. No build, secrets, or API keys are required.

Dependencies: DOMPurify 3.4.17; Marked 18.1.2. Retrieved from the npm registry with tarball integrity verification. Script integrity hashes are pinned in index.html; regenerate the SHA-384 integrity attribute whenever any script changes, or the browser will refuse to load it.

Security: strict HTML element/attribute allowlist; HTTP(S) and mailto links only; no images or embedded resources; no-referrer policy; no outbound fetch connections; no inline scripts or eval; script integrity checks. Inline styles remain enabled to preserve Office clipboard formatting. The downloaded HTML also has a restrictive CSP. The preview preserves links: clicking one intentionally visits that destination.

Content is processed locally in the tab and is not uploaded or persisted by this app. Hosting providers still receive normal page requests. Browser extensions, clipboard history, and enhanced browser spellchecking are outside the app's control. Input is limited to 200,000 characters and imported files to 1 MB.

GitHub Pages does not offer repository-configured arbitrary response headers. A meta CSP cannot enforce frame-ancestors, so this package does not claim protection against other sites framing the page. A host or proxy supporting response headers can add frame-ancestors 'none', X-Content-Type-Options: nosniff, and Permissions-Policy restrictions.

Maintenance: check upstream security advisories periodically. Vendored JS is not automatically upgraded by Dependabot without a dependency workflow. Do not commit private documents or credentials. This is defense in depth, not a formal security audit.
