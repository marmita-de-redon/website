# marmita-de-redon.github.io/website

This repository has the code for the public website (this is really the source).

# Using

1. [Install Hugo](https://gohugo.io/overview/installing/)
2. Clone this repository
```bash
git clone https://github.com/Marmita-de-Redon/website.git marmita-website
cd marmita-website
```
3. Run Hugo and access http://localhost:1313/
```bash
hugo server 
```
4. Eposides should be published inside `/content/post`:
- `/content/post/s01e01.md` with the first episode of Season 1
- `/content/post/s01e02.md` with the sedond episode of Season 1
5. Media content (images, audio, videos, etc...) should **NOT** be hosted here (except for website logos).  
Host those files somewhere else, and link them here.

# Publishing to production (making it live)

Every push to the `main` branch gets automatically deployed to production (in a couple of minutes).  
This uses [Github Actions](https://docs.github.com/actions) to host the website using [Github Pages](https://pages.github.com/) to do it.
