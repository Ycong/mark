# PublicUserAvatarWidget(头像展示)
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