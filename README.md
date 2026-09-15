# Hi, I'm Zihao Wu

**Embodied AI · Vision-Language-Action · LLM Agents**

你好，我是 Zihao Wu。我关注具身智能与大模型 Agent，围绕机器人操作、多模态决策和工具调用开展项目实践，希望把模型的感知与规划能力连接到可执行、可验证的任务流程。

[GitHub](https://github.com/WWWzzzjy) · [双臂操作](https://github.com/WWWzzzjy/agentic-skill-vla) · [灵巧抓取](https://github.com/WWWzzzjy/beliefvla-grasp)

## Focus

- **具身智能与机器人学习**：VLA、模仿学习、双臂协作、灵巧抓取与 Sim2Real。
- **大模型 Agent**：多模态任务规划、结构化输出、技能调用与执行验证。
- **系统实现与评测**：数据采集、训练与评估流程、异步推理和机器人部署。

## Selected Projects

### [Agentic Skill-VLA](https://github.com/WWWzzzjy/agentic-skill-vla) — 双臂长程操作

面向双 SO-101 的分层机器人系统，将 VLM 规划、SmolVLA 技能执行与完成状态验证连接起来。

- 通过受约束的技能图组织单臂与双臂技能，结合视觉和本体状态判断技能是否完成。
- 使用技能过渡数据改善连续操作，并通过 RTC、动作限幅与执行状态管理实现动作块切换。
- 仓库报告的方块交接真机实验中，在相同数据预算、每种方法 30 次测试下，成功次数由端到端 SmolVLA 的 **16/30** 提升至 **22/30**。

`VLM Planning` `SmolVLA` `LeRobot` `Bimanual Manipulation`

### [BeliefVLA-Grasp](https://github.com/WWWzzzjy/beliefvla-grasp) — 欠感知灵巧抓取

面向缺少触觉和真实手指关节反馈的 ORCA Hand V2，探索特权教师监督与少样本 Sim2Real。

- 在 π0.5 中加入循环 Belief Encoder，结合执行历史与当前视觉语言信息估计隐含状态。
- 实现仿真教师、三阶段训练、Quest 遥操、双相机数据采集与异步推理部署组件。

`π0.5` `Belief State` `Isaac Lab` `ROS 2` `Sim2Real`

## Project Stack

| 方向 | 项目中使用的技术 |
| --- | --- |
| 模型与训练 | Python、PyTorch、Transformers、模仿学习 |
| 具身智能 | SmolVLA、π0.5、LeRobot、Isaac Lab |
| 系统与部署 | ROS 2、Linux、异步推理 |

欢迎交流具身智能、机器人学习与大模型 Agent 相关项目。
