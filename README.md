# Simple Vue App

This guide will help you set up a simple Vue app using Vue CLI (a globally installed npm package that provides the vue command in your terminal.)

### Install Vue CLI Globally
```sh
npm install -g @vue/cli
```

For Mac users:
```sh
sudo npm install -g @vue/cli
```

### Check Vue CLI Version
```sh
vue --version
```

### Create a New Vue Project
```sh
vue create simple-vue-app
```

### Select the Default Option
When prompted, select the default preset:

```
Vue CLI v5.0.8
? Please pick a preset: (Use arrow keys)
❯ Default ([Vue 3] babel, eslint)
```

### Navigate to the Project Directory
```sh
cd simple-vue-app
```

### Run the Development Server
```sh
npm run serve
```

Open your browser and navigate to the provided localhost port. If everything is set up correctly, you will see the default Vue.js welcome page.

### Update Files
Update the following files to customize your app:

- `public/index.html`
- `src/main.js`
- `src/App.vue`

Save the updates and refresh the page to see the changes.

### Note: Stopping the Server
To stop the server, use:

```sh
Control + C
```
