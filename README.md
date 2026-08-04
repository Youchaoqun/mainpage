# Chaoqun You — Academic Homepage

Source code for [chaoqunyou.com](https://chaoqunyou.com), the academic homepage of **Chaoqun You**, Assistant Professor at Fudan University.

The site presents my biography, research interests, news, publications, professional services, and awards. It is built with [Hugo Blox](https://hugoblox.com/) and adapted from [Xingqiu He’s academic homepage](https://github.com/XingqiuHe/xingqiuhe.github.io).

## Update the website

- Edit the homepage sections in `content/_index.md`.
- Edit profile information, links, interests, education, and experience in `data/authors/me.yaml`.
- Replace the profile photograph at `assets/media/authors/me.jpg`.
- Add downloadable papers to `static/data/` and link them from `content/_index.md`.
- Edit navigation in `config/_default/menus.yaml` and site metadata in `config/_default/params.yaml`.

## Preview locally

Install [Hugo Extended](https://gohugo.io/installation/) and Node.js, then run:

```bash
npm install
npm run dev
```

Open the local address printed in the terminal.

## Build

```bash
npm run build
```

The generated site is written to `public/`.

## Deployment

Pushing to the `main` branch triggers the GitHub Actions workflow in `.github/workflows/deploy.yml`. The workflow builds the site and deploys it to GitHub Pages. The custom domain is configured by `static/CNAME` as `chaoqunyou.com`.

In the GitHub repository settings, Pages should use **GitHub Actions** as its source.

## License and attribution

This project is based on the Hugo Blox Academic CV template and the layout customization from [XingqiuHe/xingqiuhe.github.io](https://github.com/XingqiuHe/xingqiuhe.github.io). See [LICENSE.md](LICENSE.md) for the upstream license.
