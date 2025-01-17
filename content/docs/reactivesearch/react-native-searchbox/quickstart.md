---
title: 'QuickStart'
meta_title: 'QuickStart to React Native SearchBox'
meta_description: 'This is a quickstart guide to the React Native searchbox library - learn how to get started with building your search UIs in under 10 mins.'
keywords:
    - quickstart
    - react-native-searchbox
    - search-ui
    - elasticsearch
sidebar: 'docs'
nestedSidebar: 'react-native-searchbox-reactivesearch'
---

[react-native-searchbox](https://github.com/appbaseio/searchbox/tree/master/packages/native) provides declarative props to query Elasticsearch, and bind UI components with different types of search queries. As the name suggests, it provides a default UI component for searchbox.

## Installation

To install `react-native-searchbox`, you can use `npm` or `yarn` to get set as follows:

### Using npm

```js
npm install @appbaseio/react-native-searchbox
```

### Using yarn

```js
yarn add @appbaseio/react-native-searchbox
```

`react-native-searchbox` requires [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) as a peer dependency. [Expo](https://expo.io/) or [create-react-native-app](https://github.com/react-community/create-react-native-app) projects include react-native-vector-icons out of the box, so all you need to do is install `@appbaseio/react-native-searchbox`.

If your project is a standard React Native project created using react-native init (it should have an ios/android directory), then you have to install the [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) along with `react-native-searchbox`.

## Simple usage

### A simple example

The following example renders an autosuggestion search bar(`search-component`) with one custom component(`result-component`) to render the results. The `result-component` watches the `search-component` for input changes and updates its UI when the user selects a suggestion.

<div data-snack-id="@anik_ghosh/searchbox-simple-example" data-snack-platform="ios" data-snack-preview="true" data-snack-theme="light" style="overflow:hidden;background:#F9F9F9;border:1px solid var(--color-border);border-radius:4px;height:505px;width:100%"></div>
<script async src="https://snack.expo.io/embed.js"></script>

### Basic Usage

This example demonstrates the usage of some of the props available with `react-native-searchbox`. Please go over [here](/docs/reactivesearch/react-native-searchbox/examples/#basic-usage) to check it out.

### Controlled Usage

In this example we can see the usage of `search-box` component in a controlled way using the `value` and `onChange` props and also how to use the `transformRequest` prop to get in more context from an extrenal API. Please go over [here](/docs/reactivesearch/react-native-searchbox/examples/#controlled-usage) to check it out.

### Advanced Usage

In this example, we show the usage of an additional facet to display the search results with increased relevancy.  Please go over [here](/docs/reactivesearch/react-native-searchbox/examples/#advanced-usage) to check it out.

### DistinctField Prop Usage

In this example, we have shown how to usage `distinctField` and `distinctFieldConfig` props to display distinct value documents based on the specified field. Please go over [here](/docs/reactivesearch/react-native-searchbox/examples/#distinctfield-prop-usage) to check it out.


### Index Prop Usage

In this example, we can see the usage of the `index` prop in the author-search-component to explicitly specify an index to query against for the component. Please go over [here](/docs/reactivesearch/react-native-searchbox/examples/#index-prop-usage) to check it out.

### TransformRequest Prop Usage

In this example, we show the usage of the `transformRequest` prop, which gives us the request object whenever a query gets triggered from the search-box component. It allows us to either modify the request being sent or create a side-effect based on this request. Please go over [here](/docs/reactivesearch/react-native-searchbox/examples/#transformrequest-prop-usage) to check it out.

Check out the docs for API Reference over [here](/docs/reactivesearch/react-native-searchbox/apireference/).