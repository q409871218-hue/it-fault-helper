# it-fault-helper

AI驱动的IT故障诊断助手 - 基于 OpenClaw Agent

## 功能

帮助用户快速诊断常见IT故障，包括：
- 💻 硬件故障（无法开机、蓝屏、显示器无信号）
- 🌐 网络故障（无法上网、WiFi问题、网络受限）
- 📀 软件故障（程序无响应、系统卡顿、应用报错）

## 安装

将 skill 复制到你的 OpenClaw 工作目录：

```bash
cd ~/.openclaw/extensions/
git clone https://github.com/q409871218-hue/it-fault-helper.git
```

## 使用方法

当用户报告故障时，按以下流程处理：

1. **收集故障信息** - 文字描述、图片截图、语音
2. **查询知识库** - 优先匹配 `references/common-issues.md` 中的已知问题
3. **网络搜索** - 未命中时搜索解决方案
4. **输出诊断结果** - 按标准模板输出

## 目录结构

```
it-fault-helper/
├── SKILL.md                    # Skill 定义文件
└── references/
    └── common-issues.md         # 常见故障知识库
```

## 故障诊断模板

```
🔧 故障诊断结果

📌 可能原因：
xxx

📝 解决步骤：
1. xxx
2. xxx
3. xxx

⚠️ 注意事项：
xxx

💡 预防建议：
xxx
```

## 适用场景

- 企业IT运维支持
- 学校电脑故障诊断
- 家庭电脑常见问题处理
- 智能客服对话系统

## License

MIT
