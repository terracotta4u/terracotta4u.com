# terracotta4u.com

Source code for [terracotta4u.com](http://terracotta4u.com/).

## Develop

This site uses [Hugo](https://gohugo.io/).

Some useful commands:

```bash
# Preview site
hugo server

# Build site
hugo --minify
```

## Deploy

Deployments are managed through AWS Amplify. Any pushes to `main` are detected by AWS and automatically trigger a new build. 