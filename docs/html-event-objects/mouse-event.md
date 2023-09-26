---
sidebar_position: 2
---

# MouseEvent

## Các sự kiện thuộc **MouseEvent** object

| Event           | Description                                                                           |
| --------------- | ------------------------------------------------------------------------------------- |
| `onClick`       | Xảy ra khi người dùng nhấp chuột vào element                                          |
| `onDoubleClick` | Xảy khi ra người dùng nháy đúp chuột vào element                                      |
| `onMouseDown`   | Xảy ra khi người dùng nhấn chuột xuống vào element                                    |
| `onMouseUp`     | Xảy ra khi người dùng nhả chuột ra khỏi element                                       |
| `onMouseEnter`  | Xảy ra khi người dùng di con trỏ chuột vào element                                    |
| `onMouseLeave`  | Xảy ra khi người dùng di con trỏ chuột ra khỏi element                                |
| `onMouseMove`   | Xảy khi khi con trỏ chuột di chuyển đến bất kì điểm nào trong element                 |
| `onContextMenu` | Xảy ra khi người dùng click chuột phải để mở contextmenu (F12) ở vị trí thuộc element |

## Các thuộc tính của parameter `event`

| Property                          | Return value                                                                                                                                                                   |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `altKey`                          | Trả về `true` nếu phím **ALT** được nhấn cùng lúc với khi ta click                                                                                                             |
| `shiftKey`                        | Trả về `true` nếu phím **SHIFT** được nhấn cùng lúc với khi ta click                                                                                                           |
| `ctrlKey`                         | Trả về `true` nếu phím **CTRL** được nhấn cùng lúc với khi ta click                                                                                                            |
| `getModifierState(<modifierKey>)` | Trả về true nếu phím "modifierKey" được nhấn hoặc đang Activated<br />Các giá trị mà "modifierKey" có thể nhận: `Alt`, `CapsLock`, `Control`, `NumLock`, `ScrollLock`, `Shift` |
| `button`                          | Trả về number biểu thị chuột bên nào đã được nhấn<br />`0`: Chuột trái được nhấn<br />`1`: Chuột giữa được nhấn (nhấn ở con lăn chuột)<br />`2`: Chuột phải được nhấn          |
| `clientX`                         | Trả về**number** là tọa độ theo chiều ngang của con trỏ chuột tính từ đầu Browser Window                                                                                       |
| `clientY`                         | Trả về**number** là tọa độ theo chiều dọc của con trỏ chuột tính từ đầu Browser Window                                                                                         |
| `pageX`                           | Trả về**number** là tọa độ theo chiều ngang của con trỏ chuột tính từ đầu Webpage                                                                                              |
| `pageY`                           | Trả về**number** là tọa độ theo chiều dọc của con trỏ chuột tính từ đầu Webpage                                                                                                |
| `screenX`                         | Trả về**number** là tọa độ theo chiều ngang của con trỏ chuột tính từ đầu màn hình máy tính của bạn                                                                            |
| `screenY`                         | Trả về**number** là tọa độ theo chiều dọc của con trỏ chuột tính từ đầu màn hình máy tính của bạn                                                                              |
