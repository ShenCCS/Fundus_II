# Fundus Image for RETFound model and ViT model
# =====Training data split by ID=====
>
## Enviroment
* python 3.7.5 
* conda env : retfound & gpu
* Model execution environment : Nvidia A5000
> link : https://github.com/rmaphoh/RETFound_MAE

## Data Preprocessing _ Row data
> Route: /john/network/RETFound/data/
> 
> Raw data(Zip from Keelung) :/john/network/RETFound/data/Zip
> 
> Raw data(unzip)_images : /john/network/RETFound/data/dataset
> 
* code: RETFound_data_preprocessing.ipynb (Move file together)

## Data Preprocessing _ Images select ROI
> Image Route : /john/network/RETFound/data/ROI
>
* code: RETFound_data_preprocessing.ipynb (ROI)

## Data Preprocessing _ ID classification
> Files Route : /john/network/RETFound/data/Images_Files
>
* code : RETFound_data_preprocessing.ipynb (ID)
> split Training & validation & Testing data for RETFound model
> 
* code : RETFound_data_preprocessing.ipynb (Training validaion Testing)

## Images split by years
> File Route : /home/john/network/RETFound/data/dataSplitByYears
* code: dataSplitByYears.ipynb

# model(RETFound)
> code File : /john/network/RETFound_MAE-main/Newdata/RETFound
* code : Age(2521).ipynb、BMI(2521).ipynb....
* Note : GPU -> A5000

# Note:
* code Route:當時是使用周博的電腦執行的，如果要使用我們的Ubuntu執行，Input data 需做替換(或是從周博的電腦中把資料帶回來)
