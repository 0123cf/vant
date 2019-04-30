## Loading

### Install
``` javascript
import { Loading } from 'vant';

Vue.use(Loading);
```

### Usage

#### Type

```html
<van-loading />
<van-loading type="spinner" />
```

#### Color

```html
<van-loading color="#1989fa" />
<van-loading type="spinner" color="#1989fa" />
```

#### Text

```html
<van-loading size="24px">Loading...</van-loading>
```

### API

| Attribute | Description | Type | Default |
|------|------|------|------|
| color | Loading color | `String` | `#c9c9c9` |  |
| type | Can be set to `spinner` | `String` | `circular` |
| size | Icon size | `String | Number` | `30px` |
| text-size | Text font size | `String | Number` | `14px` |

### Slot

| Name | Description |
|------|------|
| default | Loading text |
