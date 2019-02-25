# nuxt.savepong.com

> My unreal Nuxt.js project

### Build Setup

``` bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn run dev

# build for production and launch server
$ yarn run build
$ yarn start

# generate static project
$ yarn run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).
# nuxt-firebase-hosting

### Deploy to Firebase hosting
Install Firebase tools:
``` bash
npm install -g firebase-tools
```

Sign in to Google:
``` bash
firebase login
```

Initiate your project:
``` bash
firebase init
```

Add your static files to your deploy directory (the default is public)

Deploy your website:
``` bash
firebase use --add
firebase deploy
```

