# DSP Quantizing Calculator

Dyson Sphere Program quantitative calculator

戴森球量化计算器

[![pdm-managed](https://img.shields.io/badge/pdm-managed-blueviolet)](https://pdm.fming.dev)

## Introduce

TBW

## Install

- 项目需要 `Python>=3.9`
- 我们十分推荐使用 [PDM](https://github.com/pdm-project/pdm) 来管理项目。本项目基于 PDM 进行第三方库管理，以下将给出基于 PDM 安装本项目的说明。

### 安装 PDM

PDM 的安装参见：[PDM Installation](https://github.com/pdm-project/pdm#installation) 。以下是简短的说明

对于 Linux/Mac 用户

```bash
curl -sSL https://raw.githubusercontent.com/pdm-project/pdm/main/install-pdm.py | python3 -
```

对于 Windows 用户

```powershell
(Invoke-WebRequest -Uri https://raw.githubusercontent.com/pdm-project/pdm/main/install-pdm.py -UseBasicParsing).Content | python -
```

最简单的做法

```shell
pip install pdm
```

### 安装依赖

如果你使用 PDM

```shell
pdm sync
```

不使用 PDM，也可以

```shell
pip install -r requirements.txt
```
