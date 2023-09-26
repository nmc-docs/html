---
sidebar_position: 5
---

# `<video>`

- Thẻ `<video>` được sử dụng để nhúng nội dung video vào tài liệu, chẳng hạn như một đoạn phim hoặc các luồng video khác.
- Cú pháp:

```html
<video src=" " ...></video>
```

| Attribute  | Value type | Ý nghĩa                                                                                                             |
| ---------- | ---------- | ------------------------------------------------------------------------------------------------------------------- |
| `src`      | `string`   | Chỉ định URL của file video                                                                                         |
| `autoplay` | `boolean`  | Chỉ định video sẽ tự động mở                                                                                        |
| `controls` | `boolean`  | Người dùng tự điều khiển nút phát của video                                                                         |
| `loop`     | `boolean`  | Video sẽ tự lặp lại khi kết thúc                                                                                    |
| `muted`    | `boolean`  | Ban đầu video sẽ không có tiếng, muốn có tiếng người dùng tự chỉnh                                                  |
| `height`   | `number`   | Điều chỉnh chiều cao của video                                                                                      |
| `width`    | `number`   | Điều chỉnh chiều dài của video                                                                                      |
| `poster`   | `string`   | Chỉ định một hình ảnh sẽ được hiển thị trong khi video đang tải xuống hoặc cho đến khi người dùng nhấn vào nút phát |
