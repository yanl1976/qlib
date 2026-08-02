# My Qlib Dev

基于 [Microsoft Qlib](https://github.com/microsoft/qlib) 的量化策略开发仓库。

## 说明
- `qlib/`、`examples/`、`tests/`、`scripts/`、`docs/` 等为 Qlib 官方源码，**不纳入本仓库**（见 `.gitignore`）。
- 本仓库只保存**我自己开发的策略、脚本与配置**。
- 本地使用 Qlib：通过 `pip install pyqlib`（或 `git clone https://github.com/microsoft/qlib` 后 `pip install -e .`）安装，源码放在本目录但被 git 忽略。

## 目录约定
- 自己的策略/脚本放在本仓库根目录或自建子目录（如 `my_strategies/`），会被 git 正常跟踪。
