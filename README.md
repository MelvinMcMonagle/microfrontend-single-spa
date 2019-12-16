# Microfrontend Single-SPA Setup
Base single-spa setup

# Getting started

**1. Clone the repo

```
git clone https://github.com/MelvinMcMonagle/microfrontend-single-spa.git
```

**2. Install dependencies 

```
yarn

#or

npm install

Optional: Install dependencies for your favorite framework

vue -> npm install  single-spa  single-spa-vue vue
react -> npm install single-spa single-spa-vue vue

```

**3. Add your applications

```
<html>
  <head></head>
  <body>
    <div id="navBar"></div>
    <div id="home"></div>
    <div id="vue"></div>
    <div id="react"></div>
    <script src="/dist/single-spa.config.js"></script>
  </body>
</html>
```

# Hands on 

**1 Run 3 coexist vue applications and navigate them over a navbar

**2 Integrate an existing React App into your SingleSpaApplication
