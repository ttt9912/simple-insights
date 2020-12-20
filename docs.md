# UI setup

## Install Vue CLI
https://cli.vuejs.org/

`npm install -g @vue/cli`

`npm i -g @vue/cli-service-global` required for _vue serve_

## Vue serve
`npm run serve` in the directory with the package.json file.
Best. Does hot reloading.

`vue serve` in the directory with the App.vue file

`vue serve -p 8888 -o` serve on port 8888, open browser

## Build, create dist

`npm run build` in the directory with the package.json file 

## Copy resources

#### ui module
`frontend-maven-plugin` to run npm

#### app module
`maven-resources-plugin` to copy dist to resources

## Heroku
`system.properties` for jdk 11

`Procfile` run java -jar

# Vue Scaffolding

### Create Project
`vue create insights-ui`

#### Manually select features
- Typescript