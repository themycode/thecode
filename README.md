# Dark Matter - VS Code 主题

一款简洁舒适的暗色系 VS Code 主题，采用深灰色调 (#272a36) 作为主背景色，适合长时间编码使用。

![Version](https://img.shields.io/visual-studio-marketplace/v/thecode.dark-matter)
![License](https://img.shields.io/github/license/themycode/thecode)
![Downloads](https://img.shields.io/visual-studio-marketplace/d/thecode.dark-matter)

## 🎨 主题特色

- **统一深色背景** - 主色调 #272a36，减少视觉疲劳
- **精心配色的语法高亮** - 函数、类、关键字层次分明
- **简洁的 UI 设计** - 侧边栏、状态栏、活动栏统一风格
- **舒适的标签页** - 活动标签页带有淡绿色背景 (#80cbc420)
- **Python 友好** - 针对 Python 代码优化的粗体效果

## 📦 安装

### 方法一：在 VS Code 中安装

1. 打开 VS Code
2. 按 `Ctrl+P` (Windows/Linux) 或 `Cmd+P` (Mac)
3. 输入 `ext install thecode.dark-matter`
4. 按回车确认安装

### 方法二：通过扩展面板

1. 打开 VS Code 扩展面板 (`Ctrl+Shift+X`)
2. 搜索 `Dark Matter`
3. 点击安装

### 方法三：手动安装

1. 从 [GitHub Releases](https://github.com/themycode/thecode/releases) 下载 `.vsix` 文件
2. 在 VS Code 中按 `Ctrl+Shift+P`
3. 选择 `Extensions: Install from VSIX`
4. 选择下载的文件

## 🚀 使用

安装完成后：

1. 按 `Ctrl+K Ctrl+T` 打开主题选择器
2. 选择 **Dark Matter** 主题
3. 或者在设置中修改：
   ```json
   {
     "workbench.colorTheme": "Dark Matter"
   }
   ```

## 📝 配色方案

主题采用深灰色调，主要配色：

| 元素     | 颜色      | 说明                        |
| -------- | --------- | --------------------------- |
| 背景色   | #272a36   | 深灰色主背景                |
| 前景色   | #cccccc   | 默认文本颜色                |
| 选中背景 | #204182cc | 选中区域背景                |
| 关键字   | #569cd6   | `if`, `for`, `def`, `class` |
| 函数名   | #dcdcaa   | 自定义函数、内置函数        |
| 类名     | #4ec9b0   | 类定义                      |
| 字符串   | #ce9178   | 字符串内容                  |
| 注释     | #7a7e8a   | 注释文本                    |
| 变量     | #9cdcfe   | 变量名                      |
| 数字     | #b5cea8   | 数字常量                    |

## 🎯 粗体效果

为了代码结构清晰，以下元素使用粗体显示：

- ✅ 关键字 (`if`, `for`, `while`, `def`, `class`, `import`, `return`)
- ✅ 函数名 (自定义函数、内置函数)
- ✅ 魔术方法 (`__init__`, `__str__` 等)
- ✅ Python 类名
- ✅ 装饰器 (`@decorator`)
- ✅ Python 常量 (`True`, `False`, `None`, `self`)

## 🔧 开发

```bash
# 安装依赖
npm install

# 调试扩展
F5 或点击运行面板

# 打包扩展
vsce package

# 发布扩展
vsce publish
```

## 📄 许可证

Apache-2.0 License

## 🔗 链接

- [GitHub 仓库](https://github.com/themycode/thecode)
- [VS Code 市场](https://marketplace.visualstudio.com/items?itemName=thecode.thecode)
- [提交问题](https://github.com/themycode/thecode/issues)
