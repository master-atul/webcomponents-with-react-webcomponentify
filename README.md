# Webcomponents Library with react-webcomponentify + React

This repo showcases how you can build webcomponents using react without much bundlesize overhead.

Go ahead and test it out here: <a href="https://master-atul.github.io/webcomponents-with-react-webcomponentify" alt="components library link" > Webcomponent library with react webcomponentify with low bundlesize overhead </a>

# How much overhead does react-webcomponentify add?

**TLDR: 2.1kb**

- With react-webcomponentify and components : 9.1kb after gzip
- Without react-webcomponentify and only components: 7kb after gzip
- Overhead caused by react-webcomponentify: 2.1kb after gzip for entire component library

**Hence with react-webcomponentify + preact you can build a web component libarary with bundle size as small as 9kb**

> components include button component and input component

# Why I am using Preact in the examples ?

Well I you look closely at package.json and webpack config, you will realise I am using preact here. You can go ahead and use React aswell. Everything will work as expected. Only downside is that React is a bit heavy as compared to Preact. Hence it will add to your bundle size. The example here will work 100% with React as Preact has extremely good compatibility with react.