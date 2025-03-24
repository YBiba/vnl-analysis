# Analysis of VNL 2023 data

## Prerequisites

- This notebook project was built using python 3.11.5
- All the libraries needed are on the requirement file
run it with the command `pip install -r requirements.txt`

## About the Data
The dataset come from kaggle, you can download it and find more informations [here](https://www.kaggle.com/datasets/yeganehbavafa/vnl-men-2023).

### Dataset columns
- Position Feature represent the real position of each player
    - OH : outside hitter
    - OP : Opposite hitter
    - MB : Middle blocker
    - S : Setter
    - L : Libero
- Attack : A player's overall average during each game in the offense factor
- Block : A player's overall average during each game in the defense 
- Serve : Player's service average during the match
- Set : the average of set
- Dig : the average of digs

## Purpose
Trough this analysis we will try to give an answer to these questions:
1. Outside Hitter receive and dig as well as libero ?
2. Outside hitter attack as well as Opposit hitter ?
3. Can we determine the role of each position ?