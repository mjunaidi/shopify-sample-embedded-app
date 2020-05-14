# Shopify

## Build a Shopify App with Node and React

_Reference_
https://shopify.dev/tutorials/build-a-shopify-app-with-node-and-react/set-up-your-app

### Requirement

    node -v

> should be 8.1.0 or higher

### How is this being created?

1. Run script

```
mkdir sample-embedded-app
cd sample-embedded-app
yarn init -y
yarn add react react-dom next
```

2. Create new folder `pages`

3. Create new file `pages/index.js`

```
const Index = () => (
  <div>
    <p>Sample app using React and Next.js</p>
  </div>
);

export default Index;
```

4. Update `package.json`

> Add "scripts"

```
{
  ...
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "next",
    "build": "next build",
    "start": "next start"
  }
}
```

5. Run `yarn run dev`

> Browse http://localhost:3000

```
+-----------------------------------------+
|                                         |
|   Sample app using React and Next.js    |
|                                         |
+-----------------------------------------+
```
