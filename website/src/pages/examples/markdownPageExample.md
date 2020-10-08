---
title: Markdown Page example title
description: Markdown Page example description
---

# Markdown page

This is a page generated from markdown to illustrate the markdown page feature.

It supports all the regular MDX features, as you can see:

:::info

Useful information.

:::

```jsx live
function Button() {
  return (
    <button type="button" onClick={() => alert('hey')}>
      Click me!
    </button>
  );
}
```

### Using relative path

![](../../../static/img/docusaurus.png)

### Using absolute path

![](/img/docusaurus.png)

import Tabs from '@theme/Tabs';

import TabItem from '@theme/TabItem';

<Tabs defaultValue="apple" values={[ {label: 'Apple', value: 'apple'}, {label: 'Orange', value: 'orange'}, {label: 'Banana', value: 'banana'} ]}><TabItem value="apple">This is an apple 🍎</TabItem><TabItem value="orange">This is an orange 🍊</TabItem><TabItem value="banana">This is a banana 🍌</TabItem></Tabs>

## Import Mdx and Md files

```js
// *.md file
import Chapter1 from './_chapter1.md';

<Chapter1 />;

// *.mdx file
import Chapter2 from './_chapter2.mdx';

<Chapter2 />;
```

import Chapter1 from './\_chapter1.md';

<Chapter1/>

import Chapter2 from './\_chapter2.mdx';

<Chapter2/>
