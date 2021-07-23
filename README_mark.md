### ```File```
```
ts_demo/

├─ images.d.ts      //will tell TypeScript that certain types of image files can be import-ed, which create-react-app supports.
├─ node_modules/
├─ public/
├─ src/
│  └─ ...
├─ .gitignore
├─ package.json     
//contains our dependencies, as well as some shortcuts for commands we'd like to run for testing, previewing, and deploying our app.
//public contains static assets like the HTML page we're planning to deploy to, or images. You can delete any file in this folder apart from index.html.
//src contains our TypeScript and CSS code. index.tsx is the entry-point for our file, and is mandatory.
├─ tsconfig.json    //contains TypeScript-specific options for our project.
├─ tsconfig.prod.json //We also have a tsconfig.prod.json and a tsconfig.test.json
├─ tsconfig.test.json //in case we want to make any tweaks to our production builds, or our test builds.
└─ tslint.json      //stores the settings that our linter, TSLint, will use.
```
