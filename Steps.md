Table of Contents
---

- [Setup from those modules](#setup-from-those-modules)
- [Module 69: Deploy to Heroku and Practice Problem](#module-69-deploy-to-heroku-and-practice-problem)
  - [`heroku login`](#heroku-login)
  - [`heroku create`](#heroku-create)
  - [`git push heroku main`](#git-push-heroku-main)
- [Module 69: Deploy to Heroku and Practice Problem](#module-69-deploy-to-heroku-and-practice-problem-1)
  - [`Documentation Links for Module 69`](#documentation-links-for-module-69)
- [Reveal Config Vars](#reveal-config-vars)
  - [`Setup Config Variables in heroku from .env`](#setup-config-variables-in-heroku-from-env)
- [Deploy client side project to firebase with server side url](#deploy-client-side-project-to-firebase-with-server-side-url)
  - [`UPDATE SERVER with new changes`](#update-server-with-new-changes)
  - [`Connect Server with Client and Deploy Client`](#connect-server-with-client-and-deploy-client)

# Setup from those modules

- [Module 67: Pagination and Load Data by filter](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone08/module48-simple-react-SPA-with-simple-E-commerce/02ema-john-simple.md#module-67-pagination-and-load-data-by-filter "from 02ema-john-simple.md")
  - [67.1 (Conceptual) Node vs Express, Set simple ema-john server](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone08/module48-simple-react-SPA-with-simple-E-commerce/02ema-john-simple.md#671-conceptual-node-vs-express-set-simple-ema-john-server "from 02ema-john-simple.md")
  - [67.9 Module Summary > Final & Full modified Code > index.js](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone08/module48-simple-react-SPA-with-simple-E-commerce/02ema-john-simple.md#indexjs-1 "index.js - from 02ema-john-simple.md")
- [Module 66: Genius Car Node Mongo CRUD Recap](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone10/module60-responsive-react-website-and-react-recap/00module-overview-and-react-review.md#module-66-genius-car-node-mongo-crud-recap)
- [Module 68: (Advanced) Secure API using JWT](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone10/module60-responsive-react-website-and-react-recap/00module-overview-and-react-review.md#module-68-advanced-secure-api-using-jwt)
- [Module 69: Deploy to Heroku and Practice Problem](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone11/module69-deploy-to-heroku-and-practice-problem/00deploy-to-heroku.md#module-69-deploy-to-heroku-and-practice-problem)

**[🔼Back to Top](#table-of-contents)**

# Module 69: Deploy to Heroku and Practice Problem

## `heroku login`

``` JavaScript
// Step-01
heroku login
```

``` JavaScript
// check that you have the prerequisites installed properly

node --version
npm --version
git --version

npm run start-dev
```

**[🔼Back to Top](#table-of-contents)**

## `heroku create`

``` JavaScript
// Step-02
heroku create
```

``` JavaScript
C:\Users\cresc\Documents\Projects\projectsHero Server\03ema-john-server>heroku create
 »   Warning: heroku update available from 7.53.0 to 7.63.4.
Creating app... done, ⬢ sleepy-sea-74931
https://sleepy-sea-74931.herokuapp.com/ | https://git.heroku.com/sleepy-sea-74931.git
```

**[🔼Back to Top](#table-of-contents)**

## `git push heroku main`

``` JavaScript
// Step-03
git push heroku main
```

``` JavaScript
C:\Users\cresc\Documents\Projects\projectsHero Server\03ema-john-server>git push heroku main
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (11/11), 12.63 KiB | 1.58 MiB/s, done.
Total 11 (delta 0), reused 3 (delta 0), pack-reused 0
remote: Compressing source files... done.
remote: Building source:
remote:
remote: -----> Building on the Heroku-22 stack
remote: -----> Determining which buildpack to use for this app
remote: -----> Node.js app detected
remote:
remote: -----> Creating runtime environment
remote:
remote:        NPM_CONFIG_LOGLEVEL=error
remote:        NODE_VERBOSE=false
remote:        NODE_ENV=production
remote:        NODE_MODULES_CACHE=true
remote:
remote: -----> Installing binaries
remote:        engines.node (package.json):  unspecified
remote:        engines.npm (package.json):   unspecified (use default)
remote:
remote:        Resolving node version 16.x...
remote:        Downloading and installing node 16.17.1...
remote:        Using default npm version: 8.15.0
remote:
remote: -----> Installing dependencies
remote:        Installing node modules
remote:
remote:        added 80 packages, and audited 81 packages in 1s
remote:
remote:        10 packages are looking for funding
remote:          run `npm fund` for details
remote:
remote:        found 0 vulnerabilities
remote:
remote: -----> Build
remote:
remote: -----> Caching build
remote:        - npm cache
remote:
remote: -----> Pruning devDependencies
remote:
remote:        up to date, audited 81 packages in 432ms
remote:
remote:        10 packages are looking for funding
remote:          run `npm fund` for details
remote:
remote:        found 0 vulnerabilities
remote:
remote: -----> Build succeeded!
remote: -----> Discovering process types
remote:        Procfile declares types     -> (none)
remote:        Default types for buildpack -> web
remote:
remote: -----> Compressing...
remote:        Done: 34.9M
remote: -----> Launching...
remote:        Released v3
remote:        https://sleepy-sea-74931.herokuapp.com/ deployed to Heroku
remote:
remote: Starting November 28th, 2022, free Heroku Dynos, free Heroku Postgres, and free Heroku Data for Redis® will no longer be available.
remote:
remote: If you have apps using any of these resources, you must upgrade to paid plans by this date to ensure your apps continue to run and to retain your data. For students, we will announce a new program by the end of September. Learn more at https://blog.heroku.com/next-chapter
remote:
remote: Verifying deploy... done.
To https://git.heroku.com/sleepy-sea-74931.git
 * [new branch]      main -> main
```

- [https://sleepy-sea-74931.herokuapp.com/](https://sleepy-sea-74931.herokuapp.com/)

**[🔼Back to Top](#table-of-contents)**

<br /><br />

# Module 69: Deploy to Heroku and Practice Problem

## `Documentation Links for Module 69`

- [Module 69: Deploy to Heroku and Practice Problem](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone11/module69-deploy-to-heroku-and-practice-problem/00deploy-to-heroku.md "Module 69: Documentation")
- [03ema-john-server/Steps.md](https://github.com/crescentpartha/03ema-john-server/blob/main/Steps.md "Only 69.1M Documentation from Module 69")
- [03ema-john-server](https://github.com/crescentpartha/03ema-john-server "03ema-john-server Repository Link (newer-version) | Deploy in Heroku")
- [Original Client-Side Documentation File for 01ema-john-simple](https://github.com/crescentpartha/projectsHero/blob/main/milestone-module/milestone08/module48-simple-react-SPA-with-simple-E-commerce/02ema-john-simple.md "02ema-john-simple.md - Documentation of Modules 48-49-52-59-67")
- [01ema-john-simple folder](https://github.com/crescentpartha/projectsHero/tree/main/milestone-module/milestone08/module48-simple-react-SPA-with-simple-E-commerce "01ema-john-simple for client-side - 03ema-john-server for server-side (older-version)")

**[🔼Back to Top](#table-of-contents)**

# Reveal Config Vars

## `Setup Config Variables in heroku from .env`

1. Go to Heroku ___Dashboard___ > Current Project (___sleepy-sea-74931___) > ___Settings___ > ___Reveal Config Vars___
2. Copy Paste ___config vars___ from your `.env` file

``` JavaScript
// Reveal Config Vars > Config Vars

// KEY VALUE Add
DB_USER dbJohn1
DB_PASS To9RpxEiy4wR2jdO
```

> `Notes:` After setup `config variables`, `product data` and `productCount data` load from MongoDB database. <br /> `https://sleepy-sea-74931.herokuapp.com/product` <br /> & <br /> `https://sleepy-sea-74931.herokuapp.com/productCount`

**[🔼Back to Top](#table-of-contents)**

# Deploy client side project to firebase with server side url

## `UPDATE SERVER with new changes`

1. Make changes
2. Make sure everything is ___updated___ like `git add .` `git commit` `git push`
3. `git push heroku main` 

**[🔼Back to Top](#table-of-contents)**

## `Connect Server with Client and Deploy Client`

1. Replace localhost by heroku link
   - `http://localhost:5000/` by `https://sleepy-sea-74931.herokuapp.com/` in Client-side (useCart.js - Shop.js - useProducts.js)
2. `npm run build`
3. `firebase deploy`
   - [https://ema-john-simple-447ad.web.app/](https://ema-john-simple-447ad.web.app/) check everything is ok or not.

**[🔼Back to Top](#table-of-contents)**





