# 实验二：A* 算法
## Q1: 森林宝⽯的秘密通道  
### 题⽬描述  
在⼀个神秘的森林⾥，有⼀块由9个⼩⽅格组成的魔法⽯板。⽯板上有8个宝⽯，每个宝⽯上刻有1-8中
的⼀个数字（每个数字都不重复）。⽯板上还有⼀个空位，⽤0表⽰。通过移动空位周围的宝⽯，你可
以改变宝⽯的位置。传说中，当宝⽯按照某个特定的顺序排列时（本题设为1 3 5 7 0 2 6 8 4），魔法⽯
板将会显露出通往⼀个宝藏的秘密通道。  
现在，你站在这块魔法⽯板前，需要找到⼀种最少步骤的移动⽅法，将宝⽯排列成⽬标顺序。为了解
开这个谜题，请使⽤A*算法来设计⼀个程序，帮助你从初始状态成功解锁秘密通道。  
要求只能⽤A*算法。

共9个格子 123456780 0表示空格  
只能移动空格周围的板块  
目标状态：1 3 5 7 0 2 6 8 4  
寻找到：最少步骤的移动方法  
输入：初始状态  
输出：最少步骤  

**例：**  
输⼊：  
150732684    
输出：  
2  

1. 135720684    1
2. 105732684    1
3. 015732684    2
4. 135782604    1
5. 715032684    3


实现语言：Java  
