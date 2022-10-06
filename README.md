## Personal Website

This platform frontend built with Svelte, Tailwind, & Hugo. 

##  Introduction
All static content is managed with Hugo in the `content` dir. 

### How to Run it

First, install [Hugo Extended](https://gohugo.io/getting-started/installing/) ver `0.101.0` or greater. 

```
git clone <this-repo>
yarn install
yarn start
```

Check it on on `http://localhost:6979/`.


## Commands

- `yarn start`: Main dev server. Runs everything you need. 
- `yarn dev`: Runs components in isolation. Serves `app/index.html` as a playground for components. 
- `yarn hugo`: Only runs static site. 
- `yarn build`: Build for production