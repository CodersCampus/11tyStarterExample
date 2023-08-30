# 11ty Starter from Lit's Dev Team, Modified

This project may include a web component created elsewhere, but is primarily an 11ty project.

It was extracted from the lit starter project, by removing everything but the 11ty stuff.

Some other modifications were made to make it a bit more like 11ty default

## Static 11ty Site

This project includes a simple website generated with the [eleventy](https://11ty.dev) static site generator and the templates and pages in `/docs-src`. The site is generated to `/_site` and intended to be deployed to firebase

To build the site, run:

```bash
npm run docs
```

To serve the site locally, run:

```bash
npm run docs:serve
```

## Companion WebCompoment Project

Clone [this project](https://github.com/CodersCampus/WebComponentStarterExampleTypeScript) into a sibling directory, run `npm i` and then `./reDeployToSibling11tyProject.sh`

This will create a file named `my-element.js` in the root of this project, enabling the &lt;my-element&gt; 
Web Component to run on selected pages