# CNU-Physical_Oceanography_Lab
Captioned code written during Physical Oceanography Practice.  
물리해양학 실험 과목에서 작성된 코드에 설명을 달아 올립니다. (2018년 수업)

## Important! This repo is under GPL v3 liscense. 
## 중요! 이 저장소는 GPL v3 라이선스 아래에 있습니다. 
이 곳에 있는 코드는 사용 시 GPL v3 라이선스에 의해 코드 원작자 표기의 의무, 변경 시 코드 공개의 의무, 재배포 시 GPL v3 라이선스 적용의 의무가 있습니다. **참조만 하고 과제는 자신이 하세요!**

## Requirements
numpy, matplotlib, basemap, xarray, gsw, dask,(Will be update)
dask pip install "dask[complete]" toolz

## How to run these files? 
터미널로 접속하거나 jupyter 상의 셀에 아래 줄들을 치세요. 후자의 경우는 매 앞 마다 !를 붙여야 합니다. 
```
cd 
git clone https://github.com/hyoseupjang/CNU-Physical_Oceanography_Lab.git
```
뒤 jupyter lab에 가서 보면 파일들이 홈 디렉터리에 올라와 있게 됩니다. 보기만 하는 것은 Github 상에서도 무방합니다. 

## 목차
1. 파이썬 기초: 조건문 및 반복문 (파일 제공 안 함) 
1. 파이썬 기초: Numpy 및 행렬, Matplotlib 사용법 (파일 제공 안 함) 
1. Argo float data 의 처리(xarray)와 플로팅(pyplot) 연습 및 gsw 라이브러리를 이용한 간단한 해수 속성 계산. **(03.ipynb)**
1. NetCDF 데이터 다루기와 선형회귀: ERSST 데이터를 이용한 해수면 온도와 지구온난화의 관계 찾아보기. **(04.ipynb)**

지속적으로 업데이트 예정. 

## Data Credit 
1. Extended Reconstructed Sea Surface Temperature (ERSST) v4

https://www1.ncdc.noaa.gov/pub/data/cmb/ersst/v4/netcdf/
1. Precipitation data

ftp://ftp.cdc.noaa.gov/Datasets/cmap/std/precip.mon.mean.nc