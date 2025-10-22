# experimentation-support-public
This is a repo for the Optimizely Experimenation App Support team, which can be used to share handy code snippets, extensions, etc. both internally and externally.


## Instructions for hosting static files (JS/CSS/...) on GitHub and referencing them directly using jsdelivr.com
To get the jsDelivr URLs for GitHub-hosted files, you can use the following format:
https://cdn.jsdelivr.net/gh/:user/:repo@branch/:path

For example, here are the correct jsDelivr CDN links for the "cat" and "dog" files which are used in the Technical Interview for the Experimentation TSE role:
cat.js
https://cdn.jsdelivr.net/gh/optimizely/experimentation-support-public@main/cat-and-dog/cat.js

dog.js
https://cdn.jsdelivr.net/gh/optimizely/experimentation-support-public@main/cat-and-dog/dog.js

These URLs serve the raw content directly from GitHub via jsDelivr’s CDN, which is great for performance and caching.
