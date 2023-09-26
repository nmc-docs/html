---
sidebar_position: 7
---

# AnimationEvent

## Các sự kiện thuộc AnimationEvent object

:::caution

Lưu ý: các event dưới đây chỉ hoạt động khi style của phần tử có thuộc tính `animation`

:::

| Event                  | Description                       |
| ---------------------- | --------------------------------- |
| `onAnimationStart`     | Xảy ra ngay khi hiệu ứng bắt đầu  |
| `onAnimationEnd`       | Xảy ra ngay khi hiệu ứng kết thúc |
| `onAnimationIteration` | Xảy ra khi hiệu ứng lặp lại       |

## Các thuộc tính của parameter `event`

| Property        | Return value                                                                                        |
| --------------- | --------------------------------------------------------------------------------------------------- |
| `animationName` | Trả về tên animation tương ứng với phần tử                                                          |
| `elapsedTime`   | Trả về một**number** là thời gian (đơn vị giây) mà hiệu ứng đã chạy, cộng dồn nếu animation lặp lại |
