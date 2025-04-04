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

[![Tests](https://github.com/huggingface/lerobot/actions/workflows/nightly-tests.yml/badge.svg?branch=main)](https://github.com/huggingface/lerobot/actions/workflows/nightly-tests.yml?query=branch%3Amain)
[![Coverage](https://codecov.io/gh/huggingface/lerobot/branch/main/graph/badge.svg?token=TODO)](https://codecov.io/gh/huggingface/lerobot)
[![Python versions](https://img.shields.io/pypi/pyversions/lerobot)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/huggingface/lerobot/blob/main/LICENSE)
[![Status](https://img.shields.io/pypi/status/lerobot)](https://pypi.org/project/lerobot/)
[![Version](https://img.shields.io/pypi/v/lerobot)](https://pypi.org/project/lerobot/)
[![Examples](https://img.shields.io/badge/Examples-green.svg)](https://github.com/huggingface/lerobot/tree/main/examples)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.1%20adopted-ff69b4.svg)](https://github.com/huggingface/lerobot/blob/main/CODE_OF_CONDUCT.md)
[![Discord](https://dcbadge.vercel.app/api/server/C5P34WJ68S?style=flat)](https://discord.gg/s3KuuzsPFb)

</div>

<h2 align="center">
    <p><a href="https://github.com/huggingface/lerobot/blob/main/examples/10_use_so100.md">
        Build Your Own SO-100 Robot!</a></p>
</h2>

<div align="center">
  <img src="media/so100/leader_follower.webp?raw=true" alt="SO-100 leader and follower arms" title="SO-100 leader and follower arms" width="50%">

  <p><strong>Meet the SO-100 – Just $110 per arm!</strong></p>
  <p>Train it in minutes with a few simple moves on your laptop.</p>
  <p>Then sit back and watch your creation act autonomously! 🤯</p>

  <p><a href="https://github.com/huggingface/lerobot/blob/main/examples/10_use_so100.md">
      Get the full SO-100 tutorial here.</a></p>

  <p>Want to take it to the next level? Make your SO-100 mobile by building LeKiwi!</p>
  <p>Check out the <a href="https://github.com/huggingface/lerobot/blob/main/examples/11_use_lekiwi.md">LeKiwi tutorial</a> and bring your robot to life on wheels.</p>

  <img src="media/lekiwi/kiwi.webp?raw=true" alt="LeKiwi mobile robot" title="LeKiwi mobile robot" width="50%">
</div>

<br/>

<h3 align="center">
    <p>LeRobot: State-of-the-art AI for real-world robotics</p>
</h3>

---


🤗 LeRobot 旨在为现实世界机器人技术提供基于 PyTorch 的模型、数据集和工具。我们的目标是降低机器人技术的入门门槛，让每个人都能通过共享数据集和预训练模型参与其中并从中受益。

🤗 LeRobot 包含最先进的算法方案，这些方案已被证实在现实世界中具有迁移应用价值，重点关注模仿学习与强化学习方向。

🤗 LeRobot 现已提供多组预训练模型、人工演示数据集和仿真环境，无需组装实体机器人即可快速上手。未来数周内，我们将持续扩展对高性价比实体机器人的支持。

🤗 LeRobot 所有预训练模型和数据集均托管于 Hugging Face 社区页面：[huggingface.co/lerobot](https://huggingface.co/lerobot)

#### 仿真环境预训练模型示例

<table>
  <tr>
    <td><img src="media/gym/aloha_act.gif" width="100%" alt="ALOHA环境中的ACT策略"/></td>
    <td><img src="media/gym/simxarm_tdmpc.gif" width="100%" alt="SimXArm环境中的TDMPC策略"/></td>
    <td><img src="media/gym/pusht_diffusion.gif" width="100%" alt="PushT环境中的Diffusion策略"/></td>
  </tr>
  <tr>
    <td align="center">ALOHA环境ACT策略</td>
    <td align="center">SimXArm环境TDMPC策略</td>
    <td align="center">PushT环境Diffusion策略</td>
  </tr>
</table>

### 致谢声明

- 感谢 Tony Zhao、Zipeng Fu 等研究者开源 ACT 策略、ALOHA 环境及数据集。我们的实现基于 [ALOHA](https://tonyzhaozh.github.io/aloha) 与 [Mobile ALOHA](https://mobile-aloha.github.io) 项目。
- 感谢 Cheng Chi、Zhenjia Xu 等研究者开源 Diffusion 策略、Pusht 环境与数据集以及 UMI 数据集。我们的实现参考了 [Diffusion Policy](https://diffusion-policy.cs.columbia.edu) 和 [UMI Gripper](https://umi-gripper.github.io) 项目。
- 感谢 Nicklas Hansen、Yunhai Feng 等研究者开源 TDMPC 策略、Simxarm 环境及数据集。我们的实现源自 [TDMPC](https://github.com/nicklashansen/tdmpc) 与 [FOWM](https://www.yunhaifeng.com/FOWM) 项目。
- 感谢 Antonio Loquercio 和 Ashish Kumar 的早期支持。
- 感谢 [Seungjae (Jay) Lee](https://sjlee.cc/)、[Mahi Shafiullah](https://mahis.life/) 等研究者开源 [VQ-BeT](https://sjlee.cc/vq-bet/) 策略并协助代码库适配。该策略改编自 [VQ-BeT 代码库](https://github.com/jayLEE0301/vq_bet_official)。

## 安装指南

下载源代码：
```bash
git clone https://github.com/huggingface/lerobot.git
cd lerobot
```

创建 Python 3.10 虚拟环境并激活（推荐使用 [`miniconda`](https://docs.anaconda.com/free/miniconda/index.html)）：
```bash
conda create -y -n lerobot python=3.10
conda activate lerobot
```

使用 `miniconda` 时若缺少 `ffmpeg` 组件：
```bash
conda install ffmpeg
```

安装 🤗 LeRobot：
```bash
pip install --no-binary=av -e .
```

> **注意：** 如遇编译错误，可能需要安装额外依赖（`cmake`、`build-essential` 和 `ffmpeg 库`）。Linux 系统请执行：
`sudo apt-get install cmake build-essential python-dev pkg-config libavformat-dev libavcodec-dev libavdevice-dev libavutil-dev libswscale-dev libswresample-dev libavfilter-dev pkg-config`。其他系统参见：[PyAV 编译指南](https://pyav.org/docs/develop/overview/installation.html#bring-your-own-ffmpeg)

仿真环境支持通过附加组件安装：
- [aloha](https://github.com/huggingface/gym-aloha)
- [xarm](https://github.com/huggingface/gym-xarm)
- [pusht](https://github.com/huggingface/gym-pusht)

例如安装含 aloha 和 pusht 组件的完整环境：
```bash
pip install --no-binary=av -e ".[aloha, pusht]"
```

使用 [Weights and Biases](https://docs.wandb.ai/quickstart) 进行实验追踪时需登录：
```bash
wandb login
```

（注：还需在配置中启用 WandB 功能，详见后续说明）

## Walkthrough

```
.
├── examples             # contains demonstration examples, start here to learn about LeRobot
|   └── advanced         # contains even more examples for those who have mastered the basics
├── lerobot
|   ├── configs          # contains config classes with all options that you can override in the command line
|   ├── common           # contains classes and utilities
|   |   ├── datasets       # various datasets of human demonstrations: aloha, pusht, xarm
|   |   ├── envs           # various sim environments: aloha, pusht, xarm
|   |   ├── policies       # various policies: act, diffusion, tdmpc
|   |   ├── robot_devices  # various real devices: dynamixel motors, opencv cameras, koch robots
|   |   └── utils          # various utilities
|   └── scripts          # contains functions to execute via command line
|       ├── eval.py                 # load policy and evaluate it on an environment
|       ├── train.py                # train a policy via imitation learning and/or reinforcement learning
|       ├── control_robot.py        # teleoperate a real robot, record data, run a policy
|       ├── push_dataset_to_hub.py  # convert your dataset into LeRobot dataset format and upload it to the Hugging Face hub
|       └── visualize_dataset.py    # load a dataset and render its demonstrations
├── outputs               # contains results of scripts execution: logs, videos, model checkpoints
└── tests                 # contains pytest utilities for continuous integration
```

### Visualize datasets

Check out [example 1](./examples/1_load_lerobot_dataset.py) that illustrates how to use our dataset class which automatically downloads data from the Hugging Face hub.

You can also locally visualize episodes from a dataset on the hub by executing our script from the command line:
```bash
python lerobot/scripts/visualize_dataset.py \
    --repo-id lerobot/pusht \
    --episode-index 0
```

or from a dataset in a local folder with the `root` option and the `--local-files-only` (in the following case the dataset will be searched for in `./my_local_data_dir/lerobot/pusht`)
```bash
python lerobot/scripts/visualize_dataset.py \
    --repo-id lerobot/pusht \
    --root ./my_local_data_dir \
    --local-files-only 1 \
    --episode-index 0
```


It will open `rerun.io` and display the camera streams, robot states and actions, like this:

https://github-production-user-asset-6210df.s3.amazonaws.com/4681518/328035972-fd46b787-b532-47e2-bb6f-fd536a55a7ed.mov?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240505%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240505T172924Z&X-Amz-Expires=300&X-Amz-Signature=d680b26c532eeaf80740f08af3320d22ad0b8a4e4da1bcc4f33142c15b509eda&X-Amz-SignedHeaders=host&actor_id=24889239&key_id=0&repo_id=748713144


Our script can also visualize datasets stored on a distant server. See `python lerobot/scripts/visualize_dataset.py --help` for more instructions.

### The `LeRobotDataset` format

A dataset in `LeRobotDataset` format is very simple to use. It can be loaded from a repository on the Hugging Face hub or a local folder simply with e.g. `dataset = LeRobotDataset("lerobot/aloha_static_coffee")` and can be indexed into like any Hugging Face and PyTorch dataset. For instance `dataset[0]` will retrieve a single temporal frame from the dataset containing observation(s) and an action as PyTorch tensors ready to be fed to a model.

A specificity of `LeRobotDataset` is that, rather than retrieving a single frame by its index, we can retrieve several frames based on their temporal relationship with the indexed frame, by setting `delta_timestamps` to a list of relative times with respect to the indexed frame. For example, with `delta_timestamps = {"observation.image": [-1, -0.5, -0.2, 0]}`  one can retrieve, for a given index, 4 frames: 3 "previous" frames 1 second, 0.5 seconds, and 0.2 seconds before the indexed frame, and the indexed frame itself (corresponding to the 0 entry). See example [1_load_lerobot_dataset.py](examples/1_load_lerobot_dataset.py) for more details on `delta_timestamps`.

Under the hood, the `LeRobotDataset` format makes use of several ways to serialize data which can be useful to understand if you plan to work more closely with this format. We tried to make a flexible yet simple dataset format that would cover most type of features and specificities present in reinforcement learning and robotics, in simulation and in real-world, with a focus on cameras and robot states but easily extended to other types of sensory inputs as long as they can be represented by a tensor.

Here are the important details and internal structure organization of a typical `LeRobotDataset` instantiated with `dataset = LeRobotDataset("lerobot/aloha_static_coffee")`. The exact features will change from dataset to dataset but not the main aspects:

```
dataset attributes:
  ├ hf_dataset: a Hugging Face dataset (backed by Arrow/parquet). Typical features example:
  │  ├ observation.images.cam_high (VideoFrame):
  │  │   VideoFrame = {'path': path to a mp4 video, 'timestamp' (float32): timestamp in the video}
  │  ├ observation.state (list of float32): position of an arm joints (for instance)
  │  ... (more observations)
  │  ├ action (list of float32): goal position of an arm joints (for instance)
  │  ├ episode_index (int64): index of the episode for this sample
  │  ├ frame_index (int64): index of the frame for this sample in the episode ; starts at 0 for each episode
  │  ├ timestamp (float32): timestamp in the episode
  │  ├ next.done (bool): indicates the end of en episode ; True for the last frame in each episode
  │  └ index (int64): general index in the whole dataset
  ├ episode_data_index: contains 2 tensors with the start and end indices of each episode
  │  ├ from (1D int64 tensor): first frame index for each episode — shape (num episodes,) starts with 0
  │  └ to: (1D int64 tensor): last frame index for each episode — shape (num episodes,)
  ├ stats: a dictionary of statistics (max, mean, min, std) for each feature in the dataset, for instance
  │  ├ observation.images.cam_high: {'max': tensor with same number of dimensions (e.g. `(c, 1, 1)` for images, `(c,)` for states), etc.}
  │  ...
  ├ info: a dictionary of metadata on the dataset
  │  ├ codebase_version (str): this is to keep track of the codebase version the dataset was created with
  │  ├ fps (float): frame per second the dataset is recorded/synchronized to
  │  ├ video (bool): indicates if frames are encoded in mp4 video files to save space or stored as png files
  │  └ encoding (dict): if video, this documents the main options that were used with ffmpeg to encode the videos
  ├ videos_dir (Path): where the mp4 videos or png images are stored/accessed
  └ camera_keys (list of string): the keys to access camera features in the item returned by the dataset (e.g. `["observation.images.cam_high", ...]`)
```

A `LeRobotDataset` is serialised using several widespread file formats for each of its parts, namely:
- hf_dataset stored using Hugging Face datasets library serialization to parquet
- videos are stored in mp4 format to save space
- metadata are stored in plain json/jsonl files

Dataset can be uploaded/downloaded from the HuggingFace hub seamlessly. To work on a local dataset, you can specify its location with the `root` argument if it's not in the default `~/.cache/huggingface/lerobot` location.

### 评估预训练策略
参考，该示例展示了如何从Hugging Face平台下载预训练策略，并在对应环境中运行评估。
我们还提供了一个功能更强大的脚本，可在同一轮 rollout 过程中并行评估多个环境。以下是使用[lerobot/diffusion_pusht](https://huggingface.co/lerobot/diffusion_pusht)上托管的预训练模型的示例：
```bash
python lerobot/scripts/eval.py \
    --policy.path=lerobot/diffusion_pusht \
    --env.type=pusht \
    --eval.batch_size=10 \
    --eval.n_episodes=10 \
    --policy.use_amp=false \
    --policy.device=cuda
```
注意：训练完自己的策略后，可以通过以下命令重新评估检查点：
```bash
python lerobot/scripts/eval.py --policy.path={OUTPUT_DIR}/checkpoints/last/pretrained_model
```
更多指令请查看`python lerobot/scripts/eval.py --help`。
### 训练自己的策略
参考[示例3](./examples/3_train_policy.py)，了解如何使用我们的核心Python库训练模型，以及[示例4](./examples/4_train_policy_with_script.md)，了解如何通过命令行使用训练脚本。
如需使用wandb记录训练和评估曲线，请确保已运行`wandb login`作为一次性设置步骤。然后，在运行上述训练命令时，通过添加`--wandb.enable=true`在配置中启用WandB。
终端中还会以黄色显示wandb日志的链接。以下是浏览器中日志的示例。请同时查看[此处](./examples/4_train_policy_with_script.md#typical-logs-and-metrics)了解日志中常用指标的说明。
注意：出于效率考虑，训练期间每个检查点仅使用少量episode进行评估。可以使用`--eval.n_episodes=500`来增加评估的episode数量。或者，训练完成后，可以重新评估最佳检查点，调整评估设置。更多指令请查看`python lerobot/scripts/eval.py --help`。
#### 复现最先进（SOTA）结果
我们在[hub页面](https://huggingface.co/lerobot)提供了一些预训练策略，这些策略可以达到最先进的性能。通过加载其运行的配置，可以复现它们的训练。只需运行：
```bash
python lerobot/scripts/train.py --config_path=lerobot/diffusion_pusht
```
即可复现Diffusion Policy在PushT任务上的SOTA结果。
## 贡献
如果想为🤗 LeRobot做出贡献，请查看我们的[贡献指南](https://github.com/huggingface/lerobot/blob/main/CONTRIBUTING.md)。
### 添加预训练策略
训练完策略后，可以将其上传到Hugging Face平台，使用类似`${hf_user}/${repo_name}`的hub id（例如[lerobot/diffusion_pusht](https://huggingface.co/lerobot/diffusion_pusht)）。
首先需要找到实验目录中的检查点文件夹（例如`outputs/train/2024-05-05/20-21-12_aloha_act_default/checkpoints/002500`）。其中应包含一个`pretrained_model`目录，该目录中应有以下文件：
- `config.json`：策略配置的序列化版本（遵循策略的数据类配置）。
- `model.safetensors`：一组`torch.nn.Module`参数，以[Hugging Face Safetensors](https://huggingface.co/docs/safetensors/index)格式保存。
- `train_config.json`：包含所有训练参数的统一配置。策略配置应与`config.json`完全一致。这对于评估策略或复现结果非常有用。
将这些文件上传到hub，运行以下命令：
```bash
huggingface-cli upload ${hf_user}/${repo_name} path/to/pretrained_model
```
参考[eval.py](https://github.com/huggingface/lerobot/blob/main/lerobot/scripts/eval.py)了解其他人如何使用你的策略。
### 通过性能分析优化代码
以下是一个用于分析策略评估性能的代码片段示例：
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
            # 插入需要分析的代码，可能是eval_policy函数的整个主体
```
```

## 引用说明
如果您希望引用本项目，可以使用以下格式：
```bibtex
@misc{cadene2024lerobot,
    author = {Cadene, Remi and Alibert, Simon and Soare, Alexander and Gallouedec, Quentin and Zouitine, Adil and Wolf, Thomas},
    title = {LeRobot: State-of-the-art Machine Learning for Real-World Robotics in Pytorch},
    howpublished = "\url{https://github.com/huggingface/lerobot}",
    year = {2024}
}
```
此外，如果您使用了特定的策略架构、预训练模型或数据集，建议同时引用原始作者的工作（如下所示）：
- 
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
## 项目星标历史
[](https://star-history.com/#huggingface/lerobot&Timeline)
（注：翻译时保留专有技术名词如Diffusion Policy/ACT/TDMPC等不译；学术文献引用格式严格遵循原文；超链接与图表代码未作改动以确保功能正常）
