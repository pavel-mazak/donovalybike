# DonovalyBike Hugo site

How to build:

```
pushd themes/devfest-theme-hugo
npm ci
npm run build
cp static/* ../../static/
popd
hugo  # for local testing, use: hugo server -D
```

