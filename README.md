# Moldavite Business Booster — Website

Static marketing site for [moldavitebusinessbooster.com](https://www.moldavitebusinessbooster.com).

```
index.html            Home
about.html            About
services.html         Services (#consultancy, #marketing, #software)
blogs.html            Blogs
career.html           Career
contact.html          Contact
privacy-policy.html   Privacy policy
img/                  Images (webp) + og.jpg social preview
fonts/                Self-hosted Plus Jakarta Sans
vercel.json           Clean URLs, security + cache headers
sitemap.xml, robots.txt
```

## Local preview
```
npx serve .
```

## Deploy
Hosted on Vercel, no build step (Framework preset: **Other**, output dir: root).
Every push to `main` deploys to production; other branches get preview URLs.
