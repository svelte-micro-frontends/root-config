# root-config - Svelte Micro-Frontends

This is a simple Micro-Frontends [demo](https://svelte-micro-frontends.surge.sh)
project built with [single-spa](https://single-spa.js.org) using [Svelte](https://svelte.dev)

This website is a single-spa adaptation of the website created by [Cam Jackson](https://twitter.com/thecamjackson)
to demonstrate just one way that micro frontends can be implemented using Svelte.

Micro frontends is an architectural style where independently deliverable frontend applications are
composed into a greater whole. It's useful for breaking up monolithic frontend codebases into smaller,
simpler applications that can be delivered to production by multiple teams independently.

To read more about the technique, including a full explanation of how the code for this demo works,
check out the [long-form article](https://martinfowler.com/articles/micro-frontends.html) that Cam wrote for martinfowler.com.

## Micro-Frontends

- [container](https;//github.com/svelte-micro-frontends/container)
- [order](https;//github.com/svelte-micro-frontends/order)
- [restaurants](https;//github.com/svelte-micro-frontends/restaurants)

## Local Development

### 1. Start the root-config app

```
yarn start
```

### 2. Start the respective micro frontends

For example, for starting the container and restaurants mfes(micro frontends),

container

```
cd container
npm run dev
```

restaurants

```
cd restaurants
npm run dev
```
