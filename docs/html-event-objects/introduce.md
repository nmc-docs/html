---
sidebar_position: 1
---

# Giới thiệu

- Khi một **event** của một Element (thẻ) trong HTML xảy ra thì **event** đó thuộc về một **Event Object** nhất định.
- Mỗi **Event Object** có thể có nhiều loại **event** . **event** đó là một function nhận một object `event` làm parameter.
- Các **Event Object** khác nhau thì các phương thức, thuộc tính của parameter `event` sẽ khác nhau, nhưng nó có 3 phương thức, thuộc tính chung sau đây:

| Property / Method   | Description                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------ |
| `target`            | Trả về [Element](../html-elements) đang lắng nghe sự kiện đó                                     |
| `preventDefault()`  | Ngăn không cho hành vi mặc định của Element xảy ra khi event được thực thi                       |
| `stopPropagation()` | Ngăn không cho sự kiện của Element cha (nếu có) xảy ra khi sự kiện của element con được thực thi |

- Ví dụ về một **event** :

```js
element.onkeydown = function (event) {
  event.preventDefault();
  console.log(event.target);
};
```

- Dưới đây là một số **Event Object** phổ biến:
  - [MouseEvent](./mouse-event)
  - [KeyboardEvent](./keyboard-event)
  - [ChangeEvent](./change-event)
  - [FocusEvent](./focus-event)
  - [ClipboardEvent](./clipboard-event)
  - [AnimationEvent](./animation-event)
  - [UIEvent](./ui-event)
  - [SyntheticEvent](./synthetic-event)
