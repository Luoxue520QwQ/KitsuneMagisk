# KitsuneMagisk 现代化 UI 美化指南

## 概述
这个美化包为 KitsuneMagisk 提供了现代化的 Material Design 3 设计风格，显著提升了应用的视觉体验和交互反馈。

## 新增功能

### 1. 现代化配色方案
- **主色调**：深蓝色系 (#1A237E)，保持专业感
- **次要色**：紫色系 (#7B1FA2)，增加活力
- **强调色**：鲜艳蓝色 (#2962FF)，用于重要操作
- **深色模式**：完整的夜间模式支持

### 2. 优化的圆角设计
- **适中圆角**：4dp-20dp 范围，避免过大圆角
- **层次感**：不同组件使用不同的圆角大小
- **一致性**：统一的圆角设计规范

### 3. 增强的动画效果
- **按钮反馈**：点击缩放动画
- **页面切换**：滑动和淡入效果
- **加载状态**：改进的进度指示器

### 4. 现代化组件样式
- **卡片**：增强阴影和边框效果
- **按钮**：标准化的高度和间距
- **图标**：统一的尺寸和色调

## 文件结构

```
app/src/main/res/
├── values/
│   ├── colors_modern.xml          # 现代化配色方案
│   ├── dimens_modern.xml          # 间距和圆角系统
│   ├── styles_md2_modern.xml      # 现代化样式定义
│   ├── themes_md2_modern.xml      # 现代化主题
│   └── strings_modern.xml        # 相关字符串
├── values-night/
│   └── colors_modern.xml          # 夜间模式配色
└── anim/
    ├── button_scale.xml           # 按钮缩放动画
    ├── button_scale_reverse.xml   # 按钮恢复动画
    ├── fade_in.xml               # 淡入动画
    └── slide_in_bottom.xml        # 底部滑入动画
```

## 启用方法

### 方法一：在主题设置中启用
1. 打开 KitsuneMagisk 应用
2. 进入设置 > 主题
3. 选择 "现代主题" 或相关变体

### 方法二：代码层面启用
```kotlin
// 在 Activity 中设置主题
setTheme(R.style.ThemeFoundationMD2_Modern)
```

## 定制选项

### 主题变体
- `ThemeFoundationMD2.Modern.Primary` - 主色主题
- `ThemeFoundationMD2.Modern.Secondary` - 次要色主题
- `ThemeFoundationMD2.Modern.Accent` - 强调色主题

### 组件样式
- `WidgetFoundation.Card.Modern` - 现代化卡片
- `WidgetFoundation.Button.Modern` - 现代化按钮
- `WidgetFoundation.Icon.Modern` - 现代化图标

## 设计原则

### 1. 适度圆角
- 避免过大圆角，保持专业感
- 不同组件使用不同大小圆角
- 确保视觉层次清晰

### 2. 色彩对比
- 高对比度的文本颜色
- 适当的色彩饱和度
- 良好的可访问性支持

### 3. 动画反馈
- 微妙的交互反馈
- 流畅的过渡动画
- 不干扰用户操作

## 兼容性

- 支持 Android 5.0+ (API 21+)
- 与现有主题系统兼容
- 不影响应用功能

## 效果预览

应用启用现代主题后，你将看到：
- 更现代化的界面设计
- 更好的视觉层次感
- 流畅的动画效果
- 一致的交互体验

## 贡献

欢迎提交改进建议和代码贡献！