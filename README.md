# Meteor with Vue 2.x boilerplate

A meteor project with commonly used Vue.js npm and atmosphere packages based on the [Vue | Meteor Guide](https://guide.meteor.com/vue.html) generated using this [gist](https://gist.github.com/lnufnu/9ee58771d97424952b0107d636b2dd8f).

[Autopublish](https://atmospherejs.com/meteor/autopublish) and [insecure](https://atmospherejs.com/meteor/insecure) removed by default. `.gitignore` with `.DS_Store`, `.env`, and editor directories included.

Has [akryum:vue-component](https://github.com/Akryum/meteor-vue-component) to use single-file components and [vue-meteor-tracker](https://github.com/meteor-vue/vue-meteor-tracker) to take advantage of Meteor's reactivity.

# Using this repo

```
git clone https://github.com/lnufnu/vue-meteor-boilerplate.git
cd vue-meteor-boilerplate
meteor npm install
```

Change the project name in `package.json`, `package-lock.json` and `/tests/main.js`

Delete the contents of `README.md`

`meteor run`

# Other Vue Meteor Packages

### Routing

Add [akryum:vue-router2](https://github.com/meteor-vue/vue-meteor/tree/master/packages/vue-router2) to use `vue-router`:

    meteor add akryum:vue-router2

### Server-side rendering

Add [akryum:vue-ssr](https://github.com/meteor-vue/vue-meteor/tree/master/packages/vue-ssr#installation) to use server sider rendering.

    meteor add akryum:vue-ssr

### Blaze

Add [meteor-vue:blaze-integration](https://github.com/meteor-vue/blaze-integration) for Blaze integration.

meteor add vuejs:blaze-integration
