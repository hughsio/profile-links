[![Netlify Status](https://api.netlify.com/api/v1/badges/39ad4f9c-f144-41a4-a52a-fa445ee23260/deploy-status)](https://app.netlify.com/sites/hugh-profile-links/deploys)

### Astrolink: Template by [Alam Guardin](https://github.com/alamguardin). I customised it to serve as my defacto landing page, please [view it here](https://go.hughj.dev) to see it in action.


```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── screenshot-app.png
│   │   └── user-profile-image.png
│   ├── components/
│   │   └── icons/
│   │   └── Link.astro
│   │   └── List.astro
│   │   └── Profile.astro
│   │   └── Shadow.astro
│   ├── data/
│   │   └── user.json
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Oh, additionally, you have the entire iconography of [Remixicons](https://remixicon.com/) available. You just need to write the name of the icon within the ```"icon"``` key of each link in the ```user.json``` file.



## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
