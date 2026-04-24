# Resume

This project is my resume and is hosted on [tr0y-gh.github.io](https://tr0y-gh.github.io/?email=hello@example.com&phone=%2B46+700+000+000&git=github.com/tr0y-gh). It is an exercise in minimalist web development and there are no dependencies or build steps. All files can be found in [/docs](/docs) and this is the structure:

```
docs/
├── index.html
├── script.js
└── style.css
```

Even if it is simple it has modern features such as translations, dark and light themes and a (hacky, i know) PDF generator. If you visit the link above you might notice the `email`, `phone` and `git` query parameters. They are there to prevent leaking my contact information to crawlers and they are injected into the DOM.
