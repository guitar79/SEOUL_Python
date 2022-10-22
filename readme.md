# SEOUL_Python

# Windows

## 가상환경 리스트
conda env list
​
## 가상환경 만들기
conda create -n SEOUL_Python_win_env

## activate 가상환경 시작
conda activate SEOUL_Python_win_env
​
## deactivate 가상환경 종료
deactivate
​
## install module
conda install matplotlib
​
## 가상환경 내보내기 (export)
conda env export > SEOUL_Python_win_env.yaml

## .yaml 파일로 새로운 가상환경 만들기
conda env create -f SEOUL_Python_win_env.yaml
​
## 가상환경 제거하기
conda env remove -n SEOUL_Python_win_env

# ubuntu
## 가상환경 리스트 출력
conda env list
​
## 가상환경 만들기 
conda create -n SEOUL_Python_ubuntu_env
​
## activate 가상환경 시작
conda activate SEOUL_Python_ubuntu_env
​
# deactivate 가상환경 종료
conda deactivate
​
# install module
conda install matplotlib

# 가상환경 내보내기 (export)
conda env export > SEOUL_Python_ubuntu_env.yaml
​
# .yaml 파일로 새로운 가상환경 만들기
conda env create -f SEOUL_Python_ubuntu_env.yaml
​
# 가상환경 제거하기
conda env remove -n SEOUL_Python_ubuntu_env