# AlexMedvedev.pro

This is my personal website/blog...

## Structure

```bash
/
├── public/
│   ├── pagefind/ # auto-generated when build
│   ├── favicon.svg
│   └── cloud-k8s.png
├── src/
│   ├── assets/
│   │   ├── icons/
│   │   └── images/
│   ├── components/
│   ├── data/
│   │   └── blog/
│   │       └── some-blog-posts.md
│   ├── layouts/
│   ├── pages/
│   ├── scripts/
│   ├── styles/
│   ├── utils/
│   ├── config.ts
│   ├── constants.ts
│   ├── content.config.ts
│   ├── env.d.ts
│   └── remark-collapse.d.ts
└── astro.config.ts
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Any static assets, like images, can be placed in the `public/` directory.

All blog posts are stored in `src/data/blog` directory.

---

This site built with [Astro](https://astro.build/) and based on the excellent **[AstroPaper](https://github.com/satnaing/astro-paper)** theme created and designed by **[Sat Naing](https://satnaing.dev)**.
