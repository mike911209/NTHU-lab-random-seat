# NTHU lab random seat
這個 repo 可以依照 Eeclass 的成員列表與 OJ 帳號 random 產生座位列表及分配帳號。

Maintainer: 李秉綸

if you have any question, you can mail me mike911209@gmail.com


> This repo isn't written by me, I got this from somewhere and fix some bugs, if you are the owner, please contact me, thx

## Prerequisite
```
pip install -r requirement.txt
```

## Input
請將以下 2 files 放在 `./input`
- member.xls：
所有同學的學號、姓名等資訊，從 Eeclass 的「成員」可以下載下來。
- password.txt:
該次考試的帳號與密碼，請從 OJ 取得。

## Output
Output 會生成在 `./output`
- seat.xlsx:
座位表、簽到表、整理過的帳號密碼。可自行剪貼到 word 或其他地方，然後列印輸出。

## Execution Command
```
python ./main.py
```
- main.py
⇒ 疫情前   (無梅花座)
- main_virus.py
⇒ 因應疫情 (座位梅花座)、(加了TEAM_ACCOUNT sheet，因應遠端考試，學生email和帳密的對應)（2024/09/28 bug not fixed yet）