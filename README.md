# Shopify product selector for Kentico Cloud

[![Stack Overflow](https://img.shields.io/badge/Stack%20Overflow-ASK%20NOW-FE7A16.svg?logo=stackoverflow&logoColor=white)](https://stackoverflow.com/tags/kentico-cloud) [![Netlify Status](https://api.netlify.com/api/v1/badges/c36f1f37-7186-48ba-bc0b-ec33f1d4f9bd/deploy-status)](https://app.netlify.com/sites/kontent-shopify-product-selector-demo/deploys)

This repository contains source code of Shopify product selector custom element for Kentico Cloud

## Quick testing

If you're interested in trying this out without deploying it yourself, you can use <https://kontent-shopify-product-selector-demo.netlify.com/>. This is the deployed version of the master branch in this repo. **This should only be used for quick testing as it is subject to change**

You will also need to provide the following JSON parameters for the custom element to connect to your store. Replace the placeholders with the actual values from the Shopify admin UI:

```
{
  "storeFrontAccessToken": "<YOUR ACCESS TOKEN>",
  "apiEndpoint": "https://<YOUR STORE NAME>.myshopify.com/api/graphql"
}
```


## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your GitHub account as well.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Kentico/cloud-custom-element-sample-shopify)

## Live site implementation sample

If you want to see live site example of Shopify product displayed on the live site, browse to a [deployed sample site](https://kentico-cloud-sample-app-react-shopify.surge.sh/en-us/articles/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5).

See source code of the sample site implementation [here](https://github.com/Kentico/cloud-sample-app-react/commit/b93be362f8c6b854e98324fb9d68bc4a97c9cd79).

![Analytics](https://kentico-ga-beacon.azurewebsites.net/api/UA-69014260-4/Kentico/cloud-custom-element-sample-shopify?pixel)
