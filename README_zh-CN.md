# 随机抽签系统

[English](README.md) | 简体中文 | [繁體中文](README_zh-TW.md)

## 概述

随机抽签系统是一个简单且高效的基于网页的应用程序，旨在根据输入的数据进行随机抽签。无论是组织抽奖、团队选择，还是任何需要随机结果的活动，该工具都提供了安全且直观的体验。所有处理过程都在您的浏览器中本地完成，确保了数据的完全隐私性。

## 功能特点

- **本地处理：** 所有随机抽签过程都在您的浏览器本地执行，您的数据不会离开您的设备。
- **可定制的输入：** 输入格式化的数据，包括名称和对应的次数，以根据您的特定需求调整结果。
- **灵活的抽签选项：** 设置生成结果的数量以及名称会被加入到抽签范围的最大`times`值。
- **用户友好的界面：** 系统具有干净且响应迅速的界面，可以在现代浏览器中无缝运行。
- **结果跟踪：** 系统记录抽签的时间，并跟踪页面打开以来抽签按钮的点击次数。

## 使用方法

1. **输入数据：** 将格式化的数据粘贴到文本框中。格式应为 `name times`（例如，`小明 3`），其中 `name` 是参与者的名字，`times` 表示该参与者在此抽签前参加活动的次数。
2. **配置抽签设置：**
   - 输入要生成的结果数量。
   - 设置最大的 `times` 值，表示如果参与者的 `times` 小于或等于此值，他们将有机会被抽中（无论他们的 `times` 值是多少，所有参与者被选中的概率相同）。
3. **生成结果：** 点击“生成随机结果”按钮。系统将根据输入的数据和设置执行抽签。
4. **查看结果：** 结果将显示在按钮下方，显示被选中的参与者及其原始`times`值、用于抽签的随机种子，以及抽签发生的具体时间。

## 许可证

本程序遵循 GNU 通用公共许可证 v3.0。您可以在 [https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html) 获取该许可证的副本。

- 您可以在相同的许可证下使用、修改和分发此软件。
- 任何修改都必须在相同条款下共享。
- 除 GPL 规定外，不能对本软件施加任何附加限制。

## 贡献

欢迎为本项目贡献力量！如果您有改进建议、错误修复或新功能的想法，欢迎 fork 代码库并提交 pull request。任何有助于增强系统的贡献都表示感谢。

## 作者

本系统由 [wangwmg](https://github.com/wangwmg) 开发。如有任何问题或建议，请在 [GitHub 仓库](https://github.com/wangwmg/RandomDraw) 提交 issue。

---

**Disclaimer:** This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
