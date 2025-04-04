<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="media/lerobot-logo-thumbnail.png">
    <source media="(prefers-color-scheme: light)" srcset="media/lerobot-logo-thumbnail.png">
    <img alt="LeRobot，Hugging Face 机器人库" src="media/lerobot-logo-thumbnail.png" style="max-width: 100%;">
  </picture>
  <br/>
  <br/>
</p>
<div align="center">
[![覆盖率](https://codecov.io/gh/huggingface/lerobot/branch/main/graph/badge.svg?token=TODO)](https://codecov.io/gh/huggingface/lerobot)
[![Python 版本](https://img.shields.io/pypi/pyversions/lerobot)](https://www.python.org/downloads/)
[![许可证](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/huggingface/lerobot/blob/main/LICENSE)
[![状态](https://img.shields.io/pypi/status/lerobot)](https://pypi.org/project/lerobot/)
[![版本](https://img.shields.io/pypi/v/lerobot)](https://pypi.org/project/lerobot/)
[![示例](https://img.shields.io/badge/示例-green.svg)](https://github.com/huggingface/lerobot/tree/main/examples)
[![贡献者公约](https://img.shields.io/badge/Contributor%20Covenant-v2.1%20adopted-ff69b4.svg)](https://github.com/huggingface/lerobot/blob/main/CODE_OF_CONDUCT.md)
[![Discord](https://dcbadge.vercel.app/api/server/C5P34WJ68S?style=flat)](https://discord.gg/s3KuuzsPFb)
</div>
<h2 align="center">
    <p><a href="https://github.com/huggingface/lerobot/blob/main/examples/10_use_so100.md">
        打造你自己的 SO-100 机器人！</a></p>
</h2>
<div align="center">
  <img src="media/so100/leader_follower.webp?raw=true" alt="SO-100 主从机械臂" title="SO-100 主从机械臂" width="50%">
  <p><strong>认识 SO-100 —— 每只手臂仅需 110 美元！</strong></p>
  <p>用笔记本电脑简单操作几分钟即可完成训练。</p>
  <p>然后坐看你的创造物自主行动！🤯</p>
  <p><a href="https://github.com/huggingface/lerobot/blob/main/examples/10_use_so100.md">
      查看完整 SO-100 教程。</a></p>
  <p>想更进一步？通过打造 LeKiwi 让你的 SO-100 移动起来！</p>
  <p>查看 <a href="https://github.com/huggingface/lerobot/blob/main/examples/11_use_lekiwi.md">LeKiwi 教程</a>，让你的机器人装上轮子动起来。</p>
  <img src="media/lekiwi/kiwi.webp?raw=true" alt="LeKiwi 移动机器人" title="LeKiwi 移动机器人" width="50%">
</div>
<br/>
<h3 align="center">
    <p>LeRobot：面向现实世界机器人的尖端人工智能</p>
</h3>
---
🤗 LeRobot 旨在为 PyTorch 中的现实世界机器人提供模型、数据集和工具。目标是降低机器人技术的入门门槛，让每个人都能通过共享数据集和预训练模型做出贡献并从中受益。
🤗 LeRobot 包含已被证明可以迁移到现实世界的最先进方法，重点在于模仿学习和强化学习。
🤗 LeRobot 已经提供了一组预训练模型、人类收集的示范数据集和模拟环境，让你无需组装机器人即可开始使用。在接下来的几周内，计划为市场上最经济实惠且功能强大的机器人增加更多现实世界机器人技术的支持。
🤗 LeRobot 在 Hugging Face 社区页面上托管预训练模型和数据集：[huggingface.co/lerobot](https://huggingface.co/lerobot)
#### 模拟环境中的预训练模型示例
<table>
  <tr>
    <td><img src="media/gym/aloha_act.gif" width="100%" alt="ALOHA 环境中的 ACT 策略"/></td>
    <td><img src="media/gym/simxarm_tdmpc.gif" width="100%" alt="SimXArm 环境中的 TDMPC 策略"/></td>
    <td><img src="media/gym/pusht_diffusion.gif" width="100%" alt="PushT 环境中的 Diffusion 策略"/></td>
  </tr>
  <tr>
    <td align="center">ALOHA 环境中的 ACT 策略</td>
    <td align="center">SimXArm 环境中的 TDMPC 策略</td>
    <td align="center">PushT 环境中的 Diffusion 策略</td>
  </tr>
</table>
### 致谢
- 感谢 Tony Zhao、Zipeng Fu 及其同事开源 ACT 策略、ALOHA 环境和数据集。我们的版本改编自 [ALOHA](https://tonyzhaozh.github.io/aloha) 和 [Mobile ALOHA](https://mobile-aloha.github.io)。
- 感谢 Cheng Chi、Zhenjia Xu 及其同事开源 Diffusion 策略、Pusht 环境和数据集，以及 UMI 数据集。我们的版本改编自 [Diffusion Policy](https://diffusion-policy.cs.columbia.edu) 和 [UMI Gripper](https://umi-gripper.github.io)。
- 感谢 Nicklas Hansen、Yunhai Feng 及其同事开源 TDMPC 策略、Simxarm 环境和数据集。我们的版本改编自 [TDMPC](https://github.com/nicklashansen/tdmpc) 和 [FOWM](https://www.yunhaifeng.com/FOWM)。
- 感谢 Antonio Loquercio 和 Ashish Kumar 的早期支持。
- 感谢 [Seungjae (Jay) Lee](https://sjlee.cc/)、[Mahi Shafiullah](https://mahis.life/) 及其同事开源 [VQ-BeT](https://sjlee.cc/vq-bet/) 策略，并帮助我们将代码库适配到我们的仓库中。该策略改编自 [VQ-BeT 仓库](https://github.com/jayLEE0301/vq_bet_official)。
## 安装
下载我们的源代码：
```bash
git clone https://github.com/huggingface/lerobot.git
cd lerobot
```
创建并激活一个 Python 3.10 的虚拟环境，例如使用 [`miniconda`](https://docs.anaconda.com/free/miniconda/index.html)：
```bash
conda create -y -n lerobot python=3.10
conda activate lerobot
```
如果使用 `miniconda` 且环境中没有安装 `ffmpeg`：
```bash
conda install ffmpeg
```
安装 🤗 LeRobot：
```bash
pip install --no-binary=av -e .
```
> **注意：** 如果遇到构建错误，可能需要安装额外的依赖项（`cmake`、`build-essential` 和 `ffmpeg libs`）。在 Linux 上运行：
`sudo apt-get install cmake build-essential python-dev pkg-config libavformat-dev libavcodec-dev libavdevice-dev libavutil-dev libswscale-dev libswresample-dev libavfilter-dev pkg-config`。其他系统请参考：[Compiling PyAV](https://pyav.org/docs/develop/overview/installation.html#bring-your-own-ffmpeg)
对于模拟环境，🤗 LeRobot 提供了可以通过额外安装的 gymnasium 环境：
- [aloha](https://github.com/huggingface/gym-aloha)
- [xarm](https://github.com/huggingface/gym-xarm)
- [pusht](https://github.com/huggingface/gym-pusht)
例如，要安装包含 aloha 和 pusht 的 🤗 LeRobot，使用：
```bash
pip install --no-binary=av -e ".[aloha, pusht]"
```
要使用 [Weights and Biases](https://docs.wandb.ai/quickstart) 进行实验跟踪，请登录：
```bash
wandb login
```
（注意：还需要在配置中启用 WandB。见下文。）
## 快速浏览
```
.
├── examples             # 包含演示示例，从这里开始了解 LeRobot
|   └── advanced         # 包含更多高级示例，适合已经掌握基础的用户
├── lerobot
|   ├── configs          # 包含所有可以在命令行中覆盖的配置类
|   ├── common           # 包含类和工具
|   |   ├── datasets       # 各种人类示范数据集：aloha、pusht、xarm
|   |   ├── envs           # 各种模拟环境：aloha、pusht、xarm
|   |   ├── policies       # 各种策略：act、diffusion、tdmpc
|   |   ├── robot_devices  # 各种真实设备：dynamixel 电机、opencv 摄像头、koch 机器人
|   |   └── utils          # 各种工具
|   └── scripts          # 包含通过命令行执行的函数
|       ├── eval.py                 # 加载策略并在环境中评估
|       ├── train.py                # 通过模仿学习和/或强化学习训练策略
|       ├── control_robot.py        # 远程操作真实机器人，记录数据，运行策略
|       ├── push_dataset_to_hub.py  # 将数据集转换为 LeRobot 数据集格式并上传到 Hugging Face hub
|       └── visualize_dataset.py    # 加载数据集并渲染其示范
├── outputs               # 包含脚本执行结果：日志、视频、模型检查点
└── tests                 # 包含用于持续集成的 pytest 工具
```
### 可视化数据集
查看 [示例 1](./examples/1_load_lerobot_dataset.py)，了解如何使用我们的数据集类，该类会自动从 Hugging Face hub 下载数据。
你也可以通过命令行运行我们的脚本，从 hub 上本地可视化数据集中的片段：
```bash
python lerobot/scripts/visualize_dataset.py \
    --repo-id lerobot/pusht \
    --episode-index 0
```
或者从本地文件夹中的数据集，使用 `root` 选项和 `--local-files-only`（在以下情况下，数据集将在 `./my_local_data_dir/lerobot/pusht` 中搜索）：
```bash
python lerobot/scripts/visualize_dataset.py \
    --repo-id lerobot/pusht \
    --root ./my_local_data_dir \
    --local-files-only 1 \
    --episode-index 0
```
它将打开 `rerun.io` 并显示摄像头流、机器人状态和动作，如下所示：
https://github-production-user-asset-6210df.s3.amazonaws.com/4681518/328035972-fd46b787-b532-47e2-bb6f-fd536a55a7ed.mov?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240505%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240505T172924Z&X-Amz-Expires=300&X-Amz-Signature=d680b26c532eeaf80740f08af3320d22ad0b8a4e4da1bcc4f33142c15b509eda&X-Amz-SignedHeaders=host&actor_id=24889239&key_id=0&repo_id=748713144
我们的脚本还可以可视化存储在远程服务器上的数据集。更多说明请参见 `python lerobot/scripts/visualize_dataset.py --help`。
### `LeRobotDataset` 格式
`LeRobotDataset` 格式的数据集非常易于使用。它可以从 Hugging Face hub 上的仓库或本地文件夹加载，例如 `dataset = LeRobotDataset("lerobot/aloha_static_coffee")`，并且可以像任何 Hugging Face 和 PyTorch 数据集一样进行索引。例如，`dataset[0]` 将从数据集中检索单个时间帧，包含观察结果和动作，作为 PyTorch 张量，可以直接输入模型。
`LeRobotDataset` 的一个特点是，它不仅可以检索单个帧，还可以基于与索引帧的时间关系检索多个帧，通过设置 `delta_timestamps` 为相对于索引帧的相对时间列表。例如，使用 `delta_timestamps = {"observation.image": [-1, -0.5, -0.2, 0]}`，可以检索给定索引的 4 帧：3 个“先前”帧（1 秒、0.5 秒和 0.2 秒前）和索引帧本身（对应 0 条目）。更多关于 `delta_timestamps` 的细节，请参见示例 [1_load_lerobot_dataset.py](examples/1_load_lerobot_dataset.py)。
在底层，`LeRobotDataset` 格式使用了多种序列化数据的方式，如果你计划更密切地使用这种格式，了解这些方式可能会有所帮助。我们尝试创建一种灵活而简单的数据集格式，涵盖强化学习和机器人技术中的大多数特征和特殊性，无论是在模拟环境还是现实世界中，重点是摄像头和机器人状态，但可以轻松扩展到其他类型的感官输入，只要它们可以用张量表示。
以下是典型 `LeRobotDataset` 实例化 `dataset = LeRobotDataset("lerobot/aloha_static_coffee")` 的重要细节和内部结构组织。具体特征会因数据集而异，但主要方面不变：
```
数据集属性：
  ├ hf_dataset: 一个 Hugging Face 数据集（由 Arrow/parquet 支持）。典型特征示例：
  │  ├ observation.images.cam_high (VideoFrame):
  │  │   VideoFrame = {'path': mp4 视频路径, 'timestamp' (float32): 视频中的时间戳}
  │  ├ observation.state (float32 列表): 机械臂关节位置（例如）
  │  ... (更多观察结果)
  │  ├ action (float32 列表): 机械臂关节目标位置（例如）
  │  ├ episode_index (int64): 该样本的片段索引
  │  ├ frame_index (int64): 该样本在片段中的帧索引；每个片段从 0 开始
  │  ├ timestamp (float32): 片段中的时间戳
  │  ├ next.done (bool): 表示片段结束；每个片段的最后一帧为 True
  │  └ index (int64): 整个数据集中的通用索引
  ├ episode_data_index: 包含每个片段的起始和结束索引的 2 个张量
  │  ├ from (1D int64 张量): 每个片段的第一帧索引 — 形状 (num episodes,) 从 0 开始
  │  └ to: (1D int64 张量): 每个片段的最后一帧索引 — 形状 (num episodes,)
  ├ stats: 数据集中每个特征的统计信息字典（最大值、平均值、最小值、标准差），例如
  │  ├ observation.images.cam_high: {'max': 与维度数相同的张量（例如 `(c, 1, 1)` 用于图像，`(c,)` 用于状态），等等。}
  │  ...
  ├ info: 数据集的元数据字典
  │  ├ codebase_version (str): 记录创建数据集时使用的代码库版本
  │  ├ fps (float): 数据集记录/同步的帧率
  │  ├ video (bool): 指示帧是否编码为 mp4 视频文件以节省空间或存储为 png 文件
  │  └ encoding (dict): 如果是视频，记录使用 ffmpeg 编码视频的主要选项
  ├ videos_dir (Path): 存储/访问 mp4 视频或 png 图像的位置
  └ camera_keys (字符串列表): 访问数据集中摄像头特征的键（例如 `["observation.images.cam_high", ...]`）
```
`LeRobotDataset` 使用几种广泛使用的文件格式序列化其各个部分，即：
- hf_dataset 使用 Hugging Face 数据集库序列化为 parquet
- 视频存储为 mp4 格式以节省空间
- 元数据存储为纯 json/jsonl 文件
数据集可以无缝上传/下载到 HuggingFace hub。要在本地数据集上工作，如果不在默认的 `~/.cache/huggingface/lerobot` 位置，可以使用 `root` 参数指定其位置。
### 评估预训练策略
查看 [示例 2](./examples/2_evaluate_pretrained_policy.py)，了解如何从 Hugging Face hub 下载预训练策略，并在其对应环境中运行评估。
我们还提供了一个功能更强大的脚本，可以在同一 rollout 期间并行评估多个环境。以下是一个在 [lerobot/diffusion_pusht](https://huggingface.co/lerobot/diffusion_pusht) 上托管的预训练模型的示例：
```bash
python lerobot/scripts/eval.py \
    --policy.path=lerobot/diffusion_pusht \
    --env.type=pusht \
    --eval.batch_size=10 \
    --eval.n_episodes=10 \
    --policy.use_amp=false \
    --policy.device=cuda
```
注意：训练完自己的策略后，可以使用以下命令重新评估检查点：
```bash
python lerobot/scripts/eval.py --policy.path={OUTPUT_DIR}/checkpoints/last/pretrained_model
```
更多说明请参见 `python lerobot/scripts/eval.py --help`。
### 训练自己的策略
查看 [示例 3](./examples/3_train_policy.py)，了解如何使用我们的核心库在 Python 中训练模型，以及 [示例 4](./examples/4_train_policy_with_
