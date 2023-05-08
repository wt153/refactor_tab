# refactor_tab

## 使用示例
import 'package:refactor_tab/refactor_tab.dart';
import 'package:refactor_tab/refactor_tab.dart' as custom;

RefactorTabBarView(
    children:[
        SizeBox(),
    ]
)

custom.TabBar(
    tabs:[ 
        RefactorTab(),
        indicatorSize: custom.TabBarIndicatorSize.label,
    ]
)
