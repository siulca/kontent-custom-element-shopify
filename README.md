# Shopify product selector for Kentico Cloud

[![Stack Overflow](https://img.shields.io/badge/Stack%20Overflow-ASK%20NOW-FE7A16.svg?logo=stackoverflow&logoColor=white)](https://stackoverflow.com/tags/kentico-cloud)

This repository contains source code of Shopify product selector custom element for Kentico Cloud

# Use

If you want to use Shopify product selector in your project in Kentico Cloud, follow these steps:

* In Kentico Cloud open Content models tab
* Open / create a content model to which you want to add Shopify selector
* Add **Custom element** content element
* Open configuration of the content element
* Use following URL as Hosted code URL (HTTPS): https://kentico.github.io/custom-element-samples/Shopify/product-selector.html
* Provide the following JSON parameters for the custom element to connect it to your store, replace the macros with the actual values from Shopify admin UI

```
{
  "storeFrontAccessToken": "<YOUR ACCESS TOKEN>",
  "apiEndpoint": "https://<YOUR STORE NAME>.myshopify.com/api/graphql"
}
```

# Installation

If you want to adjust the implementation, first download [Kentico Cloud Custom Elements Devkit](https://github.com/kentico/custom-element-devkit). This repository should be positioned within `/client/custom-elements` folder. For further instructions on devkit implementation, please refer to [Custom Element Devkit README](https://github.com/Kentico/custom-element-devkit/blob/master/readme.md).

## Get started

Prerequisites:
* Node.js
* git

```
git clone https://github.com/Kentico/custom-element-devkit.git
cd custom-element-devkit
git clone https://github.com/Kentico/cloud-custom-element-sample-shopify.git ./client/custom-elements/cloud-custom-element-sample-shopify
npm install --save jquery
npm start -- -hw
```
Browse: https://localhost:3000/custom-elements/cloud-custom-element-sample-shopify/wrap

# Live site implementation sample

If you want to see live site example of Shopify product displayed on the live site, browse to a [deployed sample site](https://kentico-cloud-sample-app-react-shopify.surge.sh/en-us/articles/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5).

See source code of the sample site implementation [here](https://github.com/Kentico/cloud-sample-app-react/commit/b93be362f8c6b854e98324fb9d68bc4a97c9cd79).

![Analytics](https://kentico-ga-beacon.azurewebsites.net/api/UA-69014260-4/Kentico/cloud-custom-element-sample-shopify?pixel)
