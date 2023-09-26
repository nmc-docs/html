---
sidebar_position: 10
---

# `<label>`

- Thẻ `<label>` thường đi cùng với thẻ `<input>`, giúp:

  - Khi người dùng click vào label , trình duyệt sẽ tự động focus đến thẻ `<input/>` mà nó liên kết

- Cú pháp:

```html
<label for="">First name</label>
```

| Atrribute | Value type | Ý nghĩa                               |
| --------- | ---------- | ------------------------------------- |
| `for`     | `string`   | Chỉ định**ID** mà label chú thích cho |

:::tip

Để liên kết `<label>` với một phần tử `<input/>`, bạn cần cung cấp cho `<input/>` một attribute **id** . Sau đó, điền giá trị cho attribute `for` một giá trị chính là **ID** đó

:::
