# **Conda**

## Liệt kê các môi trường Conda
```
conda env list
```

## Tạo môi trường
```
conda create --prefix ./my_env python=<version_python>
```

## Vào môi trường đã tạo
```
conda activate pyspark_env
```

## Coi thông tin cơ bản conda (đường dẫn)
```bash
conda info --envs
```

## Xuất tên các thư viện conda
```bash
conda env export --no-builds > <name_file>.yml
```

## Create new env with yml file export conda
```bash
conda env create -f <name_file>.yml
```

## To remove a conda environment
```bash
conda env remove -n <env_name>
```