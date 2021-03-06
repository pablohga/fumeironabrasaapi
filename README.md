# Fumeiro na Brasa Delivery - API

[API Documentation](https://documenter.getpostman.com/view/7189884/SWECXvVh?version=latest)



## What it does?

This application allows the creation of products of different categories and order management, which can be done by the administrator on the web. The customer, using the app can view the products, add to cart and place a order. It also allows image upload.

## Integration

This AdonisJS API is consumed by an [mobile app](https://github.com/pablohga/fumeiroapp), for customers, and an [web app](https://github.com/pablohga/fumeiroweb) for managing. Both were built with React, check them out.

## :arrow_down: Installing

**Cloning the repo**

```shell
git clone https://github.com/pablohga/fumeiroapi.git

cd fumeiroapi
```

**Installing dependencies**

```shell
npm install
```

## :wrench: Setting up

**Set the environment variables in a _.env_ file as exemplified in the _.env.example_**

**Run the migrations to create the database**

```shell
npx adonis migration:run
```

**Run the seeds to populate the database**

```shell
npx adonis seed
```

## :runner: Running

**Just start the server**

```shell
npm run start
```
