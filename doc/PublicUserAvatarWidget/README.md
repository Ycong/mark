# PublicUserAvatarWidget(头像展示)
## 定义
```dart
const PublicUserAvatarWidget({
    Key key,
    this.name = '',
    this.style = const TextStyle(color: Colors.white, fontSize: 12),
    this.avatar,
    this.height,
    this.width,
    this.borderWidth = 0,
    this.borderColor = Colors.white,
  }) : super(key: key);
  
  /// 名字
  final String name;

  /// 名字的样式
  final TextStyle style;

  /// 头像URL
  final String avatar;

  /// 高度
  final double height;

  /// 宽度
  final double width;

  /// 边框宽度
  final double borderWidth;

  /// 边框颜色
  final Color borderColor;
```
## 说明
使用时必须传入height与width,控件会以 width/2 为半径画圆.

## 效果
* 无头像无边框

![无头像无边框](doc/PublicUserAvatarWidget/1.png)

* 无头像有边框

![无头像有边框](../../doc/PublicUserAvatarWidget/2.png)

* 有头像无边框

![有头像无边框](doc/PublicUserAvatarWidget/3.png)

* 有头像有边框

![有头像有边框](doc/PublicUserAvatarWidget/4.png)