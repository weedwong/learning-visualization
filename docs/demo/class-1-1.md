---
title: 四种可视化方式
group:
  title: 图形基础篇
  order: 1
---

This is a demo.

```jsx
/**
 * title: 我是标题
 * description: 我是简介，我可以用 `Markdown` 来编写
 */

import { useState } from 'react';

export default () => {
  const [value, setValue] = useState(0);

  return (
    <div>
      <div>{value}</div>
      <div>
        <button onClick={() => setValue(() => value + 1)}>+1</button>
      </div>
    </div>
  );
};
```
