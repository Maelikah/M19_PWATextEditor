# PWA Text Editor

</br>

![Github License](https://img.shields.io/badge/license-MIT-blue.svg)

</br>

---

##   📝 Description


---

</br>

The purpose of this repository is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline. To build this text editor, I started with an existing application and the idea is to implement methods for getting and storing data to an IndexedDB database. A package called idb will be used, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla. This app will be deployed in Heroku

</br>

---


##   ⌨️ Programming Languages & Technologies
---

</br>

<div style="display: inline_block">

[![JavaScript](./assets/javascript.svg)](https://devdocs.io/javascript/)
&nbsp;&nbsp;
[![NodeJS](./assets/nodejs.svg)](https://nodejs.org/en/docs)
&nbsp;&nbsp;
[![ExpressJS](./assets/expressjs.svg)](https://expressjs.com/en/4x/api.html)
&nbsp;&nbsp;
[![WebPack](./assets/webpack.svg)](https://webpack.js.org/)
&nbsp;&nbsp;
[![Heroku](./assets/heroku.svg)](https://devcenter.heroku.com/categories/reference)
&nbsp;&nbsp;
[IndexedDB](https://web.dev/indexeddb/)
&nbsp;&nbsp;
[IDB](https://www.npmjs.com/package/idb)
&nbsp;&nbsp;


</div>

</br>


---

## 📑 Table of Contents

---

</br>

- [Installation](#💿-installation)
- [Usage](#💻-usage)
- [License](#🔏-license)
- [Credits](#🖋️-credits)
- [Tests](#🧪-tests)
- [User Story](#✍️-user-story)
- [Acceptance Criteria](#👏-acceptance-criteria)


</br>


---

##  💿 [Installation](#📑-table-of-contents)

---

</br>

1. Fork and clone repository to local machine 
2. Run `npm i` to install dependencies in local project directory



</br>


---

##   💻 [Usage](#📑-table-of-contents)

---

</br>

1. Open integrated terminal
2. Run `npm run build` to create the dist folder with the app
3. Run `npm run start:dev` to initiate the app
4. Click on the generated local port link
5. For offline usage, click on the `install` button
6. Alternatively, you can visit the deployed app in [Heroku](https://devdocs.io/javascript/)


</br>

The github URL containing the code for this project is located at:

https://github.com/Maelikah/M19_PWATextEditor

</br>


Heroku Page:

https://.herokuapp.com/


</br>


---

##  🔏 [License](#📑-table-of-contents)

---

</br>


 This project is licensed under the terms of the `MIT` license. 


</br>


---

## 🖋️ [Credits](#📑-table-of-contents)

---

</br>


- https://shields.io/category/license
- https://github.com/devicons/devicon/tree/master/icons
- https://nodejs.org/en/docs
- https://web.dev/indexeddb/
- https://www.npmjs.com/package/idb


</br>


---

##   🧪 [Tests](#📑-table-of-contents)

---

</br>



NA


</br>


---

## ✍️ [User Story](#📑-table-of-contents)

---

</br>

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```


</br>

---

## 👏 [Acceptance Criteria](#📑-table-of-contents)

---

</br>


```md
GIVEN a text editor web application
- WHEN I open my application in my editor
    - THEN I should see a client server folder structure
- WHEN I run npm run start from the root directory
    - THEN I find that my application should start up the backend and serve the client
- WHEN I run the text editor application from my terminal
    - THEN I find that my JavaScript files have been bundled using webpack
- WHEN I run my webpack plugins
    - THEN I find that I have a generated HTML file, service worker, and a manifest file
- WHEN I use next-gen JavaScript in my application
    - THEN I find that the text editor still functions in the browser without errors
- WHEN I open the text editor
    - THEN I find that IndexedDB has immediately created a database storage
- WHEN I enter content and subsequently click off of the DOM window
    - THEN I find that the content in the text editor has been saved with IndexedDB
- WHEN I reopen the text editor after closing it
    - THEN I find that the content in the text editor has been retrieved from our IndexedDB
- WHEN I click on the Install button
    - THEN I download my web application as an icon on my desktop
- WHEN I load my web application
    - THEN I should have a registered service worker using workbox
- WHEN I register a service worker
    - THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
- WHEN I deploy to Heroku
    - THEN I should have proper build scripts for a webpack application
```

</br>


---

[Back to Top](#pwa-text-editor)

