# js 快捷语法

## 强依赖 vs code以及code rhythm 插件



@js

| 快捷                          | 示例说明              |
| --------------------------- | ----------------- |
| @js_promise                 | promise基本示例       |
| @js_switch                  | switch            |
| @js_array.concat            | 数组合并              |
| @js_array.every             | 检测数组中所有元素是否都大于x值  |
| @js_array.forEach           | 数据遍历              |
| @js_array.includes          | 数组是否包含某元素         |
| @js_array.filter            | 数组返回符合指定条件的元素组    |
| @js_array.indexOf           | 数组指定元素的序列         |
| @js_array.join              | 转为字符串             |
| @js_class_extends           | 继承示例              |
| @js_class                   | class基本示例         |
| @js_async                   | async用法           |
| @js_function.apply          | 改变this,参数数组       |
| @js_function.bind           | bind用法            |
| @js_function.call           | call用法，参数依次传入     |
| @js_object.defineProperties | 定义属性              |
| @js_object.defineProperty   | 单一属性              |
| @js_object.freeze           | 冻结对象不能修改          |
| @js_object.is               | 判断值是否相同           |
| @js_object.keys             | 枚举：数组 & 对象        |
| @js_object.values           | 返回数组：可枚举对象的values |
| @js_string.charAt           | 字符串指定索引内容         |
| @js_string.concat           | 合并字符串             |
| @js_string.endsWith         | boolen:是否以某字符串结尾  |
| @js_string.includes         | boolen:是否包含字符     |
| @js_string.match            | ary:匹配结果          |
| @js_string.padEnd           | 尾填充               |
| @js_string.padStart         | 头填充               |
| @js_string.replace          | 替换                |
| @js_string.slice            | 截取字符串             |
| @js_string.split            | 分割成数组             |
| @js_string.substr           | 返回指定长度字符串         |
| @js_string.substring        | 索引范围内字符串          |
| @js_string.low&up           | 大小写               |
| @js_string.trim             | 去除空格              |
| @js_array.from              | 类数组转为数组           |
| @js_map                     | 类Object对象         |
| @js_async_all               | async并发           |
| @js_async_promise_all       | 混合处理并发            |
| @js_map_foreach             | map数据遍历           |
| @js_object.hasOwnProperty   | 对象是否有某属性          |
| @js_string.replace.reg      | 正则替换              |
| @js_object_string           | obj转为string       |
|                             |                   |

@module

| 快捷                            | 示例说明      |
| ----------------------------- | --------- |
| @module_export                | es6模块导出   |
| @module_import                | es6模块导入   |
| @module_node_exports_children | cmd导出子属性  |
| @module_node_exports          | cmd导出默认模块 |

@reg

| 快捷            | 示例说明    |
| ------------- | ------- |
| @reg_email    | email验证 |
| @reg_mobile   | 手机      |
| @reg_id       | 身份证     |
| @reg_chinese  | 中文      |
| @reg_sentence | 中英文及数字  |
| @reg_url      | url     |
|               |         |

@axios

| 快捷                   | 示例说明    |
| -------------------- | ------- |
| @axios_get_base      | 基本get   |
| @axios_get_params    | get参数形式 |
| @axios_async         | es7异步写法 |
| @axios_post_base     | 基本post  |
| @axios_whole_config  | 完整配置    |
| @axios_response_list | 返回列表    |

@antd

| 快捷                       | 示例说明            |
| ------------------------ | --------------- |
| @antd_table_check        | 勾选框table        |
| @antd_table_base         | 基本表格            |
| @antd_table_nest_base    | 基本嵌套表格          |
| @antd_form_base(login)   | 基本form表单(login) |
| @antd_modal_base         | 基本modal框        |
| @antd_modal_confirm_warn | modal基本确认警告框    |

@react

*部分示例需要更新*

| 快捷                      | 示例说明                   |
| ----------------------- | ---------------------- |
| @react_comp_func        | func无状态组件              |
| @react_comp_state_redux | state组件with redux      |
| @react_entry            | 入口 store,router,render |
| @react_comp_constructor | base组件                 |
| @react_comp_ref         | 非受控组件ref               |
| @react_comp_cycle       | 组件生命周期                 |
| @react_children         | 包含子组件写法                |
| @react_proptypes_demo   | proptype校验             |
| @react_img              | 插入图片                   |
| @react_img_folder       | 引入图片文件夹                |
|                         |                        |

@moment

| 快捷              | 示例说明     |
| --------------- | -------- |
| @moment_date    | 转为日期     |
| @moment_convert | 转为moment |
| @moment_compare | 日期比较     |

@utils

包含了一些常用的小工具及设计模式

| 快捷                       | 示例说明          |
| ------------------------ | ------------- |
| @utils_data_format       | 日期时间格式化       |
| @utils_countdown_simple  | 最简单倒计时        |
| @utils_scroll_watch      | 滚动监听          |
| @utils_scrolltop         | 返回顶部无动画       |
| @utils_insertScript      | 动态插入script    |
| @utils_getCookie         | 获取cookie      |
| @utils_offset            | 距离document的位置 |
| @utils_pattern_pub/sub   | 观察订阅模式        |
| @utils_pattern_single    | 单体模式          |
| @utils_pattern_factory   | 工厂模式          |
| @utils_pattern_singleton | 单例模式          |
| @utils_pattern_adapter   | 交换头（适配器）模式    |
| @utils_pattern_Decorator | 装饰器：扩展现有接口    |
| @utils_pattern_proxy     | 代理(缓存)模式.用于优化 |
| @utils_pattern_flyweight | 合并重复,非一般清爽    |
| @utils_pattern_facade    | 外套模式,人模狗样     |
| @utils_base64            | base64转换      |
| @utils_pattern_chain     | 链式写法          |
| @utils_json_pretty_tab   | json美化形式      |
| @utils_add_remove_class  | 增加删除类         |
| @utils_data_type         | 判断数据类型        |

@element

element-UI 常见UI组件

| 快捷                          | 示例说明     |
| --------------------------- | -------- |
| @element_radio              | 单选框      |
| @element_radio_group        | 单选框组     |
| @element_radio_group_button | 按钮单选框组   |
| @element_radio_border       | 带边框单选框组  |
| @element_checkbox           | 多选框      |
| @element_input              | 输入框      |
| @element_input_icon         | 带icon输入框 |
| @element_input_area         | 文本域      |
| @element_input_complex      | 复合型输入框   |
| @element_select             | 选择框      |
| @element_select_group       | 分组选择框    |
| @element_select_create_item | 可创建条目选择框 |
| @element_switch             | 开关       |
| @element_slider             | 滑块       |
| @element_time_picker        | 时间选择器    |
| @element_date_picker        | 日期选择器    |
| @element_date_rate          | 评级       |
| @element_color_picker       | 颜色选择器    |
| @element_form_validate      | 带验证表单    |
| @element_table              | 表格       |
| @element_table_multiple     | 多级表格     |
| @element_table_filter       | 可筛选表格    |
| @element_table_customer     | 自定义列表格   |
| @element_table_toggle       | 可展开列表格   |
| @element_tag                | 可删除标签    |
| @element_tag_deleteable     | 可删除标签    |
| @element_progress           | 标准进度条    |
| @element_tree               | 树形表      |
| @element_pagination         | 分页       |
| @element_badge              | 标记       |
| @element_alert              | 警告       |
| @element_message            | 消息       |
| @element_confirm            | 确认框      |
| @element_notification       | 通知       |
| @element_NavMenu            | 普通导航菜单   |
| @element_NavMenu_vertical   | 纵向导航菜单   |
| @element_tab                | 标准tab    |
| @element_breadcrumb         | 面包屑      |
| @element_drop               | 下拉菜单     |
| @element_steps              | 步骤条      |
| @element_dialog             | 对话框      |
| @element_popover            | 弹出框      |
| @element_card               | 卡片       |
| @element_carousel           | 走马灯      |
| @element_collapse           | 折叠面板     |