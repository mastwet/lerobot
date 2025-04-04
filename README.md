<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="media/lerobot-logo-thumbnail.png">
    <source media="(prefers-color-scheme: light)" srcset="media/lerobot-logo-thumbnail.png">
    <img alt="LeRobot, Hugging Face Robotics Library" src="media/lerobot-logo-thumbnail.png" style="max-width: 100%;">
  </picture>
  <br/>
  <br/>
</p>
<div align="center">
[![覆盖率](https://codecov.io/gh/huggingface/lerobot/branch/main/graph/badge.svg?token=TODO)](https://codecov.io/gh/huggingface/lerobot)
[![Python版本](https://img.shields.io/pypi/pyversions/lerobot)](https://www.python.org/downloads/)
[![许可证](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/huggingface/lerobot/blob/main/LICENSE)
[![状态](https://img.shields.io/pypi/status/lerobot)](https://pypi.org/project/lerobot/)
[![版本](https://img.shields.io/pypi/v/lerobot)](https://pypi.org/project/lerobot/)
[![示例](https://img.shields.io/badge/示例-green.svg)](https://github.com/huggingface/lerobot/tree/main/examples)
[![贡献者公约](https://img.shields.io/badge/Contributor%20Covenant-v2.1%20adopted-ff69b4.svg)](https://github.com/huggingface/lerobot/blob/main/CODE_OF_CONDUCT.md)
[![Discord](https://dcbadge.vercel.app/api/server/C5P34WJ68S?style=flat)](https://discord.gg/s3KuuzsPFb)
</div>
<h2 align="center">
    <p><a href="https://github.com/huggingface/lerobot/blob/main/examples/10_use_so100.md">
        构建你自己的SO-100机器人！</a></p>
</h2>
<div align="center">
  <img src="media/so100/leader_follower.webp?raw=true" alt="SO-100主从机械臂" title="SO-100主从机械臂" width="50%">
  <p><strong>认识SO-100 - 每只手臂仅需110美元！</strong></p>
  <p>只需几分钟，在笔记本电脑上用几个简单动作就能训练它。</p>
  <p>然后坐下来观看你的创造物自主行动！🤯</p>
  <p><a href="https://github.com/huggingface/lerobot/blob/main/examples/10_use_so100.md">
      获取完整的SO-100教程。</a></p>
  <p>想更上一层楼？通过构建LeKiwi让你的SO-100移动起来！</p>
  <p>查看<a href="https://github.com/huggingface/lerobot/blob/main/examples/11_use_lekiwi.md">LeKiwi教程</a>，让你的机器人装上轮子动起来。</p>
  <img src="media/lekiwi/kiwi.webp?raw=true" alt="LeKiwi移动机器人" title="LeKiwi移动机器人" width="50%">
</div>
<br/>
<h3 align="center">
    <p>LeRobot：面向现实世界机器人的尖端AI</p>
</h3>
---
🤗 LeRobot旨在为PyTorch中的现实世界机器人提供模型、数据集和工具。目标是降低机器人技术的入门门槛，让每个人都能通过共享数据集和预训练模型做出贡献并从中受益。
🤗 LeRobot包含已被证明可以迁移到现实世界的最先进方法，重点研究模仿学习和强化学习。
🤗 LeRobot已经提供了一组预训练模型、人工收集演示的数据集和模拟环境，无需组装机器人即可开始使用。未来几周，计划为最经济实惠且功能强大的机器人增加更多现实世界机器人支持。
🤗 LeRobot在Hugging Face社区页面托管预训练模型和数据集：[huggingface.co/lerobot](https://huggingface.co/lerobot)
#### 模拟环境中的预训练模型示例
<table>
  <tr>
    <td><img src="media/gym/aloha_act.gif" width="100%" alt="ALOHA环境中的ACT策略"/></td>
    <td><img src="media/gym/simxarm_tdmpc.gif" width="100%" alt="SimXArm环境中的TDMPC策略"/></td>
    <td><img src="media/gym/pusht_diffusion.gif" width="100%" alt="PushT环境中的Diffusion策略"/></td>
  </tr>
  <tr>
    <td align="center">ALOHA环境中的ACT策略</td>
    <td align="center">SimXArm环境中的TDMPC策略</td>
    <td align="center">PushT环境中的Diffusion策略</td>
  </tr>
</table>
### 致谢
- 感谢Tony Zhao、Zipeng Fu及其同事开源ACT策略、ALOHA环境和数据集。我们的工作改编自[ALOHA](https://tonyzhaozh.github.io/aloha)和[Mobile ALOHA](https://mobile-aloha.github.io)。
- 感谢Cheng Chi、Zhenjia Xu及其同事开源Diffusion策略、Pusht环境和数据集，以及UMI数据集。我们的工作改编自[Diffusion Policy](https://diffusion-policy.cs.columbia.edu)和[UMI Gripper](https://umi-gripper.github.io)。
- 感谢Nicklas Hansen、Yunhai Feng及其同事开源TDMPC策略、Simxarm环境和数据集。我们的工作改编自[TDMPC](https://github.com/nicklashansen/tdmpc)和[FOWM](https://www.yunhaifeng.com/FOWM)。
- 感谢Antonio Loquercio和Ashish Kumar的早期支持。
- 感谢[Seungjae (Jay) Lee](https://sjlee.cc/)、[Mahi Shafiullah](https://mahis.life/)及其同事开源[VQ-BeT](https://sjlee.cc/vq-bet/)策略并帮助我们调整代码库。该策略改编自[VQ-BeT仓库](https://github.com/jayLEE0301/vq_bet_official)。
## 安装
下载源代码：
```bash
git clone https://github.com/huggingface/lerobot.git
cd lerobot
```
创建Python 3.10虚拟环境并激活，例如使用[`miniconda`](https://docs.anaconda.com/free/miniconda/index.html)：
```bash
conda create -y -n lerobot python=3.10
conda activate lerobot
```
使用`miniconda`时，如果环境中没有`ffmpeg`：
```bash
conda install ffmpeg
```
安装🤗 LeRobot：
```bash
pip install --no-binary=av -e .
```
> **注意：** 如果遇到构建错误，可能需要安装额外依赖项（`cmake`、`build-essential`和`ffmpeg libs`）。在Linux上运行：
`sudo apt-get install cmake build-essential python-dev pkg-config libavformat-dev libavcodec-dev libavdevice-dev libavutil-dev libswscale-dev libswresample-dev libavfilter-dev pkg-config`。其他系统请参考：[编译PyAV](https://pyav.org/docs/develop/overview/installation.html#bring-your-own-ffmpeg)
对于模拟，🤗 LeRobot附带可通过extras安装的gymnasium环境：
- [aloha](https://github.com/huggingface/gym-aloha)
- [xarm](https://github.com/huggingface/gym-xarm)
- [pusht](https://github.com/huggingface/gym-pusht)
例如，要安装带aloha和pusht的🤗 LeRobot：
```bash
pip install --no-binary=av -e ".[aloha, pusht]"
```
要使用[Weights and Biases](https://docs.wandb.ai/quickstart)进行实验跟踪，登录：
```bash
wandb login
```
（注意：你还需要在配置中启用WandB。见下文。）
## 使用指南
```
.
├── examples             # 包含演示示例，从这里开始了解LeRobot
|   └── advanced         # 包含更高级的示例，适合已掌握基础的用户
├── lerobot
|   ├── configs          # 包含配置类，其中包含可以在命令行中覆盖的所有选项
|   ├── common           # 包含类和实用工具
|   |   ├── datasets       # 各种人工演示数据集：aloha, pusht, xarm
|   |   ├── envs           # 各种模拟环境：aloha, pusht, xarm
|   |   ├── policies       # 各种策略：act, diffusion, tdmpc
|   |   ├── robot_devices  # 各种真实设备：dynamixel电机，opencv摄像头，koch机器人
|   |   └── utils          # 各种实用工具
|   └── scripts          # 包含通过命令行执行的函数
|       ├── eval.py                 # 加载策略并在环境中评估
|       ├── train.py                # 通过模仿学习和/或强化学习训练策略
|       ├── control_robot.py        # 远程操作真实机器人，记录数据，运行策略
|       ├── push_dataset_to_hub.py  # 将数据集转换为LeRobot数据集格式并上传到Hugging Face hub
|       └── visualize_dataset.py    # 加载数据集并渲染其演示
├── outputs               # 包含脚本执行结果：日志、视频、模型检查点
└── tests                 # 包含持续集成的pytest实用工具
```
### 可视化数据集
查看[示例1](./examples/1_load_lerobot_dataset.py)，了解如何使用我们的数据集类，它会自动从Hugging Face hub下载数据。
你也可以通过从命令行执行我们的脚本，在本地可视化hub上数据集的片段：
```bash
python lerobot/scripts/visualize_dataset.py \
    --repo-id lerobot/pusht \
    --episode-index 0
```
或使用`root`选项和`--local-files-only`从本地文件夹中的数据集（在以下情况下，数据集将在`./my_local_data_dir/lerobot/pusht`中搜索）
```bash
python lerobot/scripts/visualize_dataset.py \
    --repo-id lerobot/pusht \
    --root ./my_local_data_dir \
    --local-files-only 1 \
    --episode-index 0
```
它将打开`rerun.io`并显示相机流、机器人状态和动作，如下所示：
https://github-production-user-asset-6210df.s3.amazonaws.com/4681518/328035972-fd46b787-b532-47e2-bb6f-fd536a55a7ed.mov?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240505%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240505T172924Z&X-Amz-Expires=300&X-Amz-Signature=d680b26c532eeaf80740f08af3320d22ad0b8a4e4da1bcc4f33142c15b509eda&X-Amz-SignedHeaders=host&actor_id=24889239&key_id=0&repo_id=748713144
我们的脚本还可以可视化存储在远程服务器上的数据集。更多说明请参见`python lerobot/scripts/visualize_dataset.py --help`。
### `LeRobotDataset`格式
`LeRobotDataset`格式的数据集使用非常简单。它可以从Hugging Face hub上的仓库或本地文件夹加载，只需使用例如`dataset = LeRobotDataset("lerobot/aloha_static_coffee")`，并且可以像任何Hugging Face和PyTorch数据集一样索引。例如`dataset[0]`将从数据集中检索单个时间帧，包含作为PyTorch张量的观察结果和动作，准备输入模型。
`LeRobotDataset`的一个特点是，我们可以基于与索引帧的时间关系检索多个帧，通过将`delta_timestamps`设置为相对于索引帧的相对时间列表。例如，使用`delta_timestamps = {"observation.image": [-1, -0.5, -0.2, 0]}`可以检索给定索引的4帧：3个"先前"帧（索引帧前1秒、0.5秒和0.2秒）和索引帧本身（对应0条目）。更多关于`delta_timestamps`的细节请参见示例[1_load_lerobot_dataset.py](examples/1_load_lerobot_dataset.py)。
在底层，`LeRobotDataset`格式使用了几种序列化数据的方法，如果你计划更密切地使用这种格式，了解这些方法可能会有所帮助。我们尝试创建一种灵活而简单的数据集格式，涵盖强化学习和机器人技术中大多数类型的特征和特性，在模拟和现实世界中，重点关注相机和机器人状态，但可以轻松扩展到其他类型的感官输入，只要它们可以用张量表示。
以下是使用`dataset = LeRobotDataset("lerobot/aloha_static_coffee")`实例化的典型`LeRobotDataset`的重要细节和内部结构组织。确切的特性会因数据集而异，但主要方面不会改变：
```
数据集属性：
  ├ hf_dataset: 一个Hugging Face数据集（由Arrow/parquet支持）。典型特性示例：
  │  ├ observation.images.cam_high (VideoFrame):
  │  │   VideoFrame = {'path': 指向mp4视频的路径, 'timestamp' (float32): 视频中的时间戳}
  │  ├ observation.state (float32列表): 机械臂关节位置（例如）
  │  ... (更多观察结果)
  │  ├ action (float32列表): 机械臂关节目标位置（例如）
  │  ├ episode_index (int64): 此样本的片段索引
  │  ├ frame_index (int64): 此样本在片段中的帧索引；每个片段从0开始
  │  ├ timestamp (float32): 片段中的时间戳
  │  ├ next.done (bool): 指示片段结束；每个片段的最后一帧为True
  │  └ index (int64): 整个数据集中的通用索引
  ├ episode_data_index: 包含每个片段的开始和结束索引的2个张量
  │  ├ from (1D int64张量): 每个片段的第一帧索引 — 形状 (num episodes,) 从0开始
  │  └ to: (1D int64张量): 每个片段的最后一帧索引 — 形状 (num episodes,)
  ├ stats: 数据集中每个特性的统计信息字典（最大值、平均值、最小值、标准差），例如
  │  ├ observation.images.cam_high: {'max': 与维度数相同的张量（例如图像为`(c, 1, 1)`，状态为`(c,)`），等等。}
  │  ...
  ├ info: 数据集元数据字典
  │  ├ codebase_version (str): 记录创建数据集时使用的代码库版本
  │  ├ fps (float): 数据集记录/同步的帧率
  │  ├ video (bool): 指示帧是否编码为mp4视频文件以节省空间或存储为png文件
  │  └ encoding (dict): 如果是视频，记录使用ffmpeg编码视频的主要选项
  ├ videos_dir (Path): 存储/访问mp4视频或png图像的位置
  └ camera_keys (字符串列表): 访问数据集中相机特性的键（例如`["observation.images.cam_high", ...]`）
```
`LeRobotDataset`使用几种广泛使用的文件格式序列化其每个部分，即：
- hf_dataset使用Hugging Face数据集库序列化为parquet
- 视频以mp4格式存储以节省空间
- 元数据以纯json/jsonl文件存储
数据集可以无缝地上传/下载到HuggingFace hub。要在本地数据集上工作，如果它不在默认的`~/.cache/huggingface/lerobot`位置，你可以使用`root`参数指定其位置。
### 评估预训练策略
查看[示例2](./examples/2_evaluate_pretrained_policy.py)，了解如何从Hugging Face hub下载预训练策略，并在其对应环境中运行评估。
我们还提供了一个功能更强大的脚本，可以在同一rollout期间并行评估多个环境。以下是使用托管在[lerobot/diffusion_pusht](https://huggingface.co/lerobot/diffusion_pusht)上的预训练模型的示例：
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
更多说明请参见`python lerobot/scripts/eval.py --help`。
### 训练自己的策略
查看 [示例 3](./examples/3_train_policy.py)，了解如何使用我们的核心库在 Python 中训练模型，以及 [示例 4](./examples/4_train_policy_with_script.md)，了解如何通过命令行使用我们的训练脚本。
要使用 wandb 记录训练和评估曲线，请确保已运行 `wandb login` 作为一次性设置步骤。然后，在运行上述训练命令时，通过添加 `--wandb.enable=true` 在配置中启用 WandB。
终端中还会以黄色显示指向 wandb 日志的链接。以下是它们在浏览器中的示例。请同时查看了解日志中常用指标的解释。
注意：为了效率，训练期间每个检查点仅评估少量片段。你可以使用 `--eval.n_episodes=500` 来评估比默认更多的片段。或者在训练后，你可能希望在更多片段上重新评估最佳检查点或更改评估设置。更多说明请参见 `python lerobot/scripts/eval.py --help`。
#### 复现最先进（SOTA）结果
我们在 [hub 页面](https://huggingface.co/lerobot) 提供了一些预训练策略，可以达到最先进的性能。你可以通过加载其运行的配置来复现它们的训练。只需运行：
```bash
python lerobot/scripts/train.py --config_path=lerobot/diffusion_pusht
```
即可复现 Diffusion Policy 在 PushT 任务上的 SOTA 结果。
## 贡献
如果你想为 🤗 LeRobot 做出贡献，请查看我们的[贡献指南](https://github.com/huggingface/lerobot/blob/main/CONTRIBUTING.md)。
### 添加预训练策略
训练完策略后，你可以使用类似 `${hf_user}/${repo_name}` 的 hub id（例如 [lerobot/diffusion_pusht](https://huggingface.co/lerobot/diffusion_pusht)）将其上传到 Hugging Face hub。
首先需要找到位于实验目录中的检查点文件夹（例如 `outputs/train/2024-05-05/20-21-12_aloha_act_default/checkpoints/002500`）。其中有一个 `pretrained_model` 目录，应包含：
- `config.json`：策略配置的序列化版本（遵循策略的数据类配置）。
- `model.safetensors`：一组 `torch.nn.Module` 参数，以 [Hugging Face Safetensors](https://huggingface.co/docs/safetensors/index) 格式保存。
- `train_config.json`：包含训练使用的所有参数的统一配置。策略配置应与 `config.json` 完全匹配。这对于想要评估你的策略或复现结果的人很有用。
要将这些上传到 hub，运行以下命令：
```bash
huggingface-cli upload ${hf_user}/${repo_name} path/to/pretrained_model
```
查看 [eval.py](https://github.com/huggingface/lerobot/blob/main/lerobot/scripts/eval.py) 了解其他人如何使用你的策略的示例。
### 通过性能分析改进代码
以下是一个代码片段示例，用于分析策略评估的性能：
```python
from torch.profiler import profile, record_function, ProfilerActivity
def trace_handler(prof):
    prof.export_chrome_trace(f"tmp/trace_schedule_{prof.step_num}.json")
with profile(
    activities=[ProfilerActivity.CPU, ProfilerActivity.CUDA],
    schedule=torch.profiler.schedule(
        wait=2,
        warmup=2,
        active=3,
    ),
    on_trace_ready=trace_handler
) as prof:
    with record_function("eval_policy"):
        for i in range(num_episodes):
            prof.step()
            # 插入要分析的代码，可能是 eval_policy 函数的整个主体
```
## 引用
如果你想，可以引用这项工作：
```bibtex
@misc{cadene2024lerobot,
    author = {Cadene, Remi and Alibert, Simon and Soare, Alexander and Gallouedec, Quentin and Zouitine, Adil and Wolf, Thomas},
    title = {LeRobot: State-of-the-art Machine Learning for Real-World Robotics in Pytorch},
    howpublished = "\url{https://github.com/huggingface/lerobot}",
    year = {2024}
}
```
此外，如果你使用了任何特定的策略架构、预训练模型或数据集，建议引用原始工作的作者，如下所示：
- [Diffusion Policy](https://diffusion-policy.cs.columbia.edu)
```bibtex
@article{chi2024diffusionpolicy,
	author = {Cheng Chi and Zhenjia Xu and Siyuan Feng and Eric Cousineau and Yilun Du and Benjamin Burchfiel and Russ Tedrake and Shuran Song},
	title ={Diffusion Policy: Visuomotor Policy Learning via Action Diffusion},
	journal = {The International Journal of Robotics Research},
	year = {2024},
}
```
- [ACT 或 ALOHA](https://tonyzhaozh.github.io/aloha)
```bibtex
@article{zhao2023learning,
  title={Learning fine-grained bimanual manipulation with low-cost hardware},
  author={Zhao, Tony Z and Kumar, Vikash and Levine, Sergey and Finn, Chelsea},
  journal={arXiv preprint arXiv:2304.13705},
  year={2023}
}
```
- [TDMPC](https://www.nicklashansen.com/td-mpc/)
```bibtex
@inproceedings{Hansen2022tdmpc,
	title={Temporal Difference Learning for Model Predictive Control},
	author={Nicklas Hansen and Xiaolong Wang and Hao Su},
	booktitle={ICML},
	year={2022}
}
```
- [VQ-BeT](https://sjlee.cc/vq-bet/)
```bibtex
@article{lee2024behavior,
  title={Behavior generation with latent actions},
  author={Lee, Seungjae and Wang, Yibin and Etukuru, Haritheja and Kim, H Jin and Shafiullah, Nur Muhammad Mahi and Pinto, Lerrel},
  journal={arXiv preprint arXiv:2403.03181},
  year={2024}
}
```
## Star 历史
[![Star History Chart](https://api.star-history.com/svg?repos=huggingface/lerobot&type=Timeline)](https://star-history.com/#huggingface/lerobot&Timeline)
