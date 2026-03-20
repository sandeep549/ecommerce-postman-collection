# E-Commerce Backend Postman Collection

This repo contains the Postman collection for the deployed e-commerce backend.

## Import

Import `ecommerce.postman_collection.json` into Postman.

## Base URL

Production gateway:

`https://ecommerce-api-gateway-ujbs.onrender.com`

The collection already includes `base_url` set to the production gateway URL.

## Suggested flow

1. `POST /auth/signup`
2. `POST /auth/login`
3. `POST /products`
4. `PUT /stock/{productId}`
5. `POST /orders`
