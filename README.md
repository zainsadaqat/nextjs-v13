# NextJS v13

## Routes in NextJS v13
- every route should have a file called page.js/page.jsx
- For Example if you want to go to thee route `/about` then inside the `app` directory you should have a folder called `about` and inside this folder there should be a file named as `page.js`
```jsx
src
|__ app
|____ about
|______ page.js
```

## Nested Dynamic Routes
In order to have nested dynamic routes, use [anything] as a folder name
```jsx
src
|__ app
|____ blog
|______ [slug]
|________ page.js
```

In order to have flexible nested routes, use [...anything] as a folder name
```jsx
src
|__ app
|____ blog
|______ [...slug]
|________ page.js
```
 
 
