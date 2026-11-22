# joyyoursedu-apex-redirect

GitHub Pages site for the bare domain `joyyoursedu.com`. Every page (index.html and 404.html)
immediately redirects to `https://www.joyyoursedu.com` + the same path, query string and hash
(JS `location.replace`, with meta refresh and a link as fallback). `noindex` + canonical to www.

The real site lives at https://www.joyyoursedu.com (Cloudflare Pages). DNS for the apex points
to the GitHub Pages A records (185.199.108-111.153).
