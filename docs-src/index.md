---
layout: page.11ty.cjs
title: Brittny Lapierre
---

# Coming Soon!

<my-element></my-element>

```js
import {html, render} from 'lit-html';

const name = 'lit-html';

render(
  html`
    <h2>This is a &lt;my-element&gt;</h2>
    <my-element .name=${name}></my-element>
  `,
  document.body
);
```

  </div>
  <div>

<h2>This is a &lt;my-element&gt;</h2>
<my-element name="lit-html"></my-element>

  </div>
</section>
