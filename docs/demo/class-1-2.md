---
title: Canvas绘图
group:
  title: 图形基础篇
  order: 2
---

This is a demo.

```jsx
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
