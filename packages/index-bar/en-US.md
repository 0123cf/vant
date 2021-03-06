## IndexBar

### Install

``` javascript
import { IndexBar } from 'vant';

Vue.use(IndexBar);
```

### Usage

#### Basic Usage

```html
<van-index-bar>
  <van-index-anchor index="A" />
  <van-cell title="Text" />
  <van-cell title="Text" />
  <van-cell title="Text" />

  <van-index-anchor index="B" />
  <van-cell title="Text" />
  <van-cell title="Text" />
  <van-cell title="Text" />

  ...
</van-index-bar>
```

#### Custom Index List

```html
<van-index-bar :index-list="indexList">
  <van-index-anchor index="1">Title 1</van-index-anchor>
  <van-cell title="Text" />
  <van-cell title="Text" />
  <van-cell title="Text" />

  <van-index-anchor index="2">Title 2</van-index-anchor>
  <van-cell title="Text" />
  <van-cell title="Text" />
  <van-cell title="Text" />

  ...
</van-index-bar>
```

```js
export default {
  data() {
    return {
      indexList: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    }
  }
}
```

### IndexBar Props

| Attribute | Description | Type | Default |
|------|------|------|------|
| index-list | Index List | `Array` | `A-Z` |

### IndexAnchor Props

| Attribute | Description | Type | Default |
|------|------|------|------|
| index | Index | `String | Number` | - |

### IndexAnchor Slots

| Name | Description |
|------|------|
| default | Anchor content, show index by default |
