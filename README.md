# Legacy domain redirect only

Canonical website: **https://junghan.shin.ai.kr**

Edit homepage content only in **cautiousjh/junghan-homepage**.
This repository retains `neuro.ai.kr` and its HTTPS certificate solely to
redirect old links. Do not restore homepage content here or change its CNAME
to the new domain: that domain belongs to the canonical repository.

GitHub Pages publishes `main` / root as static HTML (`.nojekyll`).
JavaScript redirects preserve paths, query strings and fragments. Meta refresh
and a visible link provide fallback. These are client-side redirects, not HTTP 301.
`cv/index.html` preserves the existing CV route without JavaScript.

Original homepage source and its full history remain in Git, and the main
site repository preserves that history through `a11cccd`.
Migration date: 2026-11-11 (Asia/Seoul).
