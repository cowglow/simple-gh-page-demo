# simple-gh-page-demo
https://cowglow.github.io/simple-gh-page-demo/

No matter where you are at with your project, you can add the `gh-pages` dependency, add the script to your package scripts and publish your site.

Things to keep in mind. You can not have server side rendering. so everything should be static. In this example you have one directory with one html file. That is in essence what we are publishing.

## Step 1
Add dependency 
```
npm install --save-dev gh-pages
```


## Step 2
Add package script
```
 "scripts": {
    ....
    "deploy": "gh-pages -d build"
  }
```

## Step 3
Publish, but first, make sure your target directory, in this example `build`, only contains static content. No SSR is available. This means you'll probably run a "pre-deploy" script if necessary. 
```
npm run deploy
```

---

### About me

I'm American living and working in Germany.

- [@cowglow](https://twitter.com/cowglow) - Say 'hi' on twitter!
- [YouTube](https://youtube.com/c/cowglow) - I'm a filmmaker
- [GitHub](https://github.com/cowglow) - but I know how to code

### Todos

- Fork it
- Code it!
- Do it on your own!

## License

MIT
