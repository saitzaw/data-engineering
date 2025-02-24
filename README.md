## Envrinoments preparation 

***Disclaimer*** 
The environments mentioned in this content are not intended for developers who use Mac or Apple-related devices.

## Host system requirement 
 - Windows OS / GNU/Linux
 - Check to enable virtulization setting in BIOS/UEFI
 
```TEXT
retstart the computer and enter BIOS/UEFI setting by pressing F2, F10, DEL or ESC at startup 
```
### for Windows OS -> check virtualization [hyper-v, wsl]
  ```TEXT
  win + R > optionalfeatures > enable Hpyer-V > enable wsl > restart  
  ```

| # | name | minimum requiremnt | 
|:-:|:----:|:------------------:|
| 1 | CPU  |  5 cores           | 
| 2 | RAM  |  8 GB              |
| 3 | S/HDD|  100 GB            |

## Requirements for Windows OS 
- Install WSL in Windows [For GNU/Linux skip this step]
- Install Docker Desktop [For GNU/Linux siip this step] 
- Install VScode
- Install PowerBI desktop or Tableau 
- Install Excel or Sheet 

### VScode Extension 
- Apache airflow 
- dbt tool 
- Docker 
- metal [Scala]
- HarshiCorp Terraform
- HCP Terraform 
- Gitlens 
- Gitlens Inspects

### Project Folder structure 

| # | OS | description |file path | 
|:-:|:--:|:---:|:---------:|
| 1 | Windows | project path |%USERPROFILE%\workspace\projectA |
| 2 | Windows | virtual env path | %USERPROFILE%\workspace\venv | 
| 3 | Linux   | project path | $HOME/workspace/projectA | 
| 4 | Lunux   | virtual env path | $HOME/workspace/venv | 

Remark: All the code should run in Docker and integrate with git

### GNU/Linux python version manager 
- Install pyenv 
- Install poetry or pipenv 

### GNU/Linux 
- Install [Docker](https://github.com/saitzaw/data-engineering/blob/main/docker.md) 
- Install [VIM] (https://github.com/saitzaw/data-engineering/blob/main/vim.md)