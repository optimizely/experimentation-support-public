# experimentation-support-public
This is a repo for the Optimizely Experimenation App Support team, which can be used to share handy code snippets, extensions, etc. both internally and externally.


## Instructions for hosting static files (JS/CSS/...) on GitHub and referencing them directly using jsdelivr.com
1. Find your link on GitHub, and click to the "Raw" version.
2. Copy the URL.
3. Change raw.githubusercontent.com to cdn.jsdelivr.net
4. Insert /gh/ before your username.
5. Remove the branch name.
(Optional) Insert the version you want to link to, as @version (if you do not do this, you will get the latest - which may cause long-term caching)

**Example**:

<code>https://raw.githubusercontent.com/optimizely/experimentation-support-public/main/cat-and-dog/cat.js</code>

becomes:

<code>https://cdn.jsdelivr.net/gh/optimizely/experimentation-support-public/cat-and-dog/cat.js</code>

This solution was found on https://stackoverflow.com/a/18049842
