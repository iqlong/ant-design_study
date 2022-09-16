1. 组件设计总结与概括
   - 组件大小和样式的封装通过自定义的属性体现
   - onClick 事件和对原生事件的支持
     - 比较特别的 htmlType 属性
   - 按钮 loading 和 icon 的使用
     - 4.21.3 版本出现了中文文字以组件的形式出现在 button 组件中，文字和 loading 会重合
   - ？？？组件中的内容的默认样式

```目录结构
button                                组件文件
├─__test__                            测试文件(新加了我的阅读笔记)
├─demo                                页面中的demo示例(位于api的上面一块)
|   ├─basic.md                        按钮类型
|   ├─block.md                        Block 按钮
├─style                               样式文件
├─index.zh-CN.md                      页面的中文配置文件
├─index.en-US.md                      页面的英文配置文件
├─button-group.tsx                    路由配置
├─button.tsx                          路由配置
├─index.tsx                           路由配置
├─LoadingIcon.tsx                     路由配置

```
