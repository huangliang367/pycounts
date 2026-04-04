# pycounts

Calculate word counts in a text file!

## Installation

```bash
pip install pycounts
```

## Usage

- TODO

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts` was created by Huang Liang. It is licensed under the terms of the MIT license.

## Credits

`pycounts` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).

## 创建python虚拟环境

```shell
conda create --name pycounts python=3.12 -y
conda activate pycounts
conda deactivate
```

## 创建工程模板

```shell
cookiecutter https://github.com/py-pkgs/py-pkgs-cookiecutter.git
```

## 安装测试工具

```shell
poetry add --group dev pytest
poetry add --group dev pytest-cov
```

测试命令,包含代码覆盖率:

```shell
pytest tests/ --cov=pycounts
```

工具都安装在pycounts虚拟环境里了。

