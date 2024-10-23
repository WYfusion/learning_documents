# Anaconda

### 更新conda到最新版本

- 在开始升级Anaconda之前，首先需要确保conda自身是最新版本。这可以通过运行以下命令来完成：

  ```bash
  conda update conda
  ```

  此命令会检查conda是否有新版本，并提示你进行更新。这是非常重要的步骤，因为更新conda有助于确保后续Anaconda的更新过程更加顺利。

### 更新Anaconda

- 一旦conda更新到最新版本，接下来就可以更新Anaconda了。虽然

  ```bash
  conda update anaconda
  ```

  命令在某些情况下可以直接使用，但更推荐的方法是使用以下命令，因为这个命令会更新所有已安装的包，包括Anaconda本身。

  ```bash
  conda update --all
  ```

  这个命令会检查所有已安装的包，包括Anaconda，并尝试将它们更新到最新版本。请注意，这个过程中可能会遇到一些依赖性问题或版本不兼容的情况，conda会尝试自动解决这些问题，但有时可能需要你手动介入。

### 创建环境

使用以下语句

```bash
conda create --name pytorch python=3.8
```

使用以下语句激活

```bash
conda activate pytorch
```

### 搭建环境

```bash
conda install pytorch==1.11.0 torchvision==0.12.0 torchaudio==0.11.0 cudatoolkit=11.3 -c pytorch
```

### 批量安装软件包

```bash
pip install -r .\requirements.txt
```

.\requirements.txt是当前目录下的requirements.txt文件，该文件里面包含了要求的软件包（一列）
