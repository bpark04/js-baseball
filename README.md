# Text Baseball 
JavaScript Diary - Jul 04, 2021

##  How To Play
This is simple 'Bulls and Cows' game modified to baseball terms. (Because I'm a big fan of baseball😂😂)
  
  1. Opponent(computer) will choose 4 non-repeated numbers between 1 to 9. 
  2. Player must answer the **right numbers with right position** within 10 tries.  
  3. For each try, the computer will give a hint following the rule:
      - **Ball**: One of player's input number is in the opponent's answer
      - **Strike**: One of player's input number is in the opponent's answer **AND** it is in the right position
      - **Out**: None of the player's input numbers match with opponent's answer
 
  4. For example, let's suppose the opponent's choice is 7249:
      - If your input is 8351, the hint is 'Out' because none of the number matches to answers.
      - If your input is 9427, the hins is '**0 Strike 4 Ball**' because all four numbers match to answers but positions are all wrong.
      - If your input is 4173, the hint is '**0 Strike 2 Balls**' because two of the numbers match to answers but their positions are wrong.
      - If your input is 7942, the hint is '**2 Strike 2 Ball**' because all four numbers match to answers but only two numbers are in right position (7,4)
      - If your input is 7143, the hins is '**2 Strick 0 Ball**' because two numbers are right AND in right position (7, 4).
   
  To play, please click this link: https://bpark04.github.io/js-baseball/
      
**Good Luck!!**



 
  

