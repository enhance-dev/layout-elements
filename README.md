# Enhance Layout Elements
A collection of custom elements for implementing layout patterns.

⚠️ **Currently under active development and not recommended for use in production.**

## Usage

1. Install the package:
    ```shell
    npm i @enhance/layout-elements
    ```
1. Expose the element you'd like to use:
    ```js
    // app/elements/layout-collection.mjs
    import { collection } from '@enhance/layout-elements'
    export default collection
1. Use the element in your app:
    ```js
    // app/pages/index.html
    <layout-collection>
      <img src='…' alt='…' />
      <img src='…' alt='…' />
      <img src='…' alt='…' />
    </layout-collection>
    ```
    
Individual element descriptions and links to their docs follow below.

## Elements

### Collection

A single file component for creating a horizontally scrollable collection of items, with optional scroll snapping.

[Read the docs](https://github.com/enhance-dev/layout-elements/tree/main/packages/collection)

### Sidebar

A single file component for creating an adaptive sidebar layout.

[Read the docs](https://github.com/enhance-dev/layout-elements/tree/main/packages/sidebar)
