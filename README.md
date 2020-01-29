# Shopify product selector for Kentico Kontent

[![Stack Overflow](https://img.shields.io/badge/Stack%20Overflow-ASK%20NOW-FE7A16.svg?logo=stackoverflow&logoColor=white)](https://stackoverflow.com/tags/kentico-Kontent)

This repository contains source code of Shopify product selector custom element for Kentico Kontent

## Setup

1. Register a private app with Shopify
    * [See instructions in our documentaton](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-with-e-commerce-shopify#a-step-1-register-a-private-app-within-shopify)
1. Deploy the code to a secure public host
    * See the [deploying section](#deploying) for a really quick option
1. Follow the instructions in the [Kentico Kontent documentation](https://docs.kontent.ai/tutorials/develop-apps/integrate/integrating-your-own-content-editing-features#a-3--displaying-a-custom-element-in-kentico-kontent) to add the element to a content model.
    * The `Hosted code URL` is where you deployed to in step 1
    * Configure the JSON parameters as detailed in the [JSON Parameters section](#json-parameters)

## JSON Parameters

You will also need to provide the following JSON parameters for the custom element to connect to your store. Replace the placeholders with the actual values from the Shopify admin UI:

```json
{
  "storeFrontAccessToken": "<YOUR ACCESS TOKEN>",
  "apiEndpoint": "https://<YOUR STORE NAME>.myshopify.com/api/graphql"
}
```

## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your GitHub account as well.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Kentico/kontent-custom-element-shopify)

![Analytics](https://kentico-ga-beacon.azurewebsites.net/api/UA-69014260-4/Kentico/kontent-custom-element-shopify?pixel)
