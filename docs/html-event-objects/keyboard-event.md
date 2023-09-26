---
sidebar_position: 3
---

# KeyboardEvent

## Các sự kiện thuộc **KeyboardEvent** object

| Event       | Description                                    |
| ----------- | ---------------------------------------------- |
| `onKeyDown` | Xảy ra khi người dùng ấn xuống bất kì phím nào |
| `onKeyUp`   | Xảy ra khi người dùng nhả ra bất kì phím nào   |

## Các thuộc tính của parameter `event`

| Property                          | Return value                                                                                                                                                                      |
| --------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `altKey`                          | Trả về `true` nếu phím **ALT** được nhấn cùng lúc với khi ta click                                                                                                                |
| `shiftKey`                        | Trả về `true` nếu phím **SHIFT** được nhấn cùng lúc với khi ta click                                                                                                              |
| `ctrlKey`                         | Trả về `true` nếu phím **CTRL** được nhấn cùng lúc với khi ta click                                                                                                               |
| `getModifierState(<modifierKey>)` | Trả về true nếu phím "modifierKey" được nhấn hoặc đang Activated<br />Các giá trị mà "modifierKey" có thể nhận:`Alt`, `CapsLock`, `Control`, `NumLock`, `ScrollLock`, `Shift`,... |
| `key`                             | Trả về `string` là tên của phím được nhấn                                                                                                                                         |
