# Voucher.js

---

Main module

## Usage

```js
//index.js
import React from 'react';
import {render} from 'react-dom';
import Voucher from './Voucher';

render(<Voucher
    currentEdit="0"
    subjectsUrl="static/data/subjects.json"

/>, document.getElementById('root') );

// isZyEditAble= { true }       // 摘要字段是否可以编辑
// isKjkmEditAble= { true }     // 会计科目字段是否可以编辑
// subjectsUrl="static/subjects.json" // 是否是异步获取科目表
```

## Properity

| **Properity** | Type | Default | Remark |
| :--- | :--- | :--- | :--- |
| currentEdit | String | 0 | 默认编辑的行 index |
| subjectsUrl | String | "" | 获取会计科目的 URI address |
| isZyEditAble | Boolean | true | 摘要字段是否可编辑 |
| isKjkmEditAble | Boolean | true | 会计科目字段受否可编辑 |







