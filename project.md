# Yahtzee Simulation

**How the game is played**

Yahtzee is a popular dice game that was first introduced in the 1950s. The game involves the use of five standard six-sided dice and a scorecard with 13 categories, listed in Table 1.1 and 1.2 below. The objective of the game is to score the highest number of points by filling in each category with a specific combination of dice.

_Table 1.1: Upper Section Categories_

| **Category** | **Description** | **Score**                         |
| ------------ | --------------- | --------------------------------- |
| Aces         | Any combination | The sum of dice with the number 1 |
| Twos         | Any combination | The sum of dice with the number 2 |
| Threes       | Any combination | The sum of dice with the number 3 |
| Fours        | Any combination | The sum of dice with the number 4 |
| Fives        | Any combination | The sum of dice with the number 5 |
| Sixes        | Any combination | The sum of dice with the number 6 |

_Table 1.2: Lower Section Categories_

| **Categories**  | **Descriptions**                       | **Scores**      |
| --------------- | -------------------------------------- | --------------- |
| Three Of A Kind | At least three dice the same           | Sum of all dice |
| Four Of A Kind  | At least four dice the same            | Sum of all dice |
| Full House      | Three of one number and two of another | 25              |
| Small Straight  | Four sequential dice                   | 30              |
| Large Straight  | Five sequential dice                   | 40              |
| Yahtzee         | All five dice the same                 | 50              |
| Chance          | Any combination                        | Sum of all dice |

Each player takes turns rolling the dice up to three times, with the option to keep any dice they want after each roll. The player must choose which category to score after their roll, with each category having a different point value.

During the game, a player must decide which category to score based on their current dice roll and what categories they have yet to fill on their scorecard. There are various combinations that can be achieved, each with their own point value, and each player must weigh the risk and reward of going for a higher-scoring category versus settling for a lower-scoring one.

In the standard game, each player takes 13 turns.

In addition, the game involves probability and statistical analysis. Players must consider the likelihood of rolling certain combinations and use this knowledge to make informed decisions during their turn. For example, the odds of rolling a Yahtzee are 1 in 1296, while the odds of rolling a full house are 1 in 25.

**Basic strategies to consider**

There are several basic strategies that players can consider when playing Yahtzee:

Focus on filling in the upper section of the scorecard: The upper section of the scorecard consists of categories for each number from one to six. Filling in these categories can provide a guaranteed minimum score and can help to avoid the risk of scoring zero in the upper section.

Try to get a bonus: If a player scores a total of 63 or more points in the upper section of the scorecard, they receive a bonus of 35 points. Focusing on filling in the upper section and achieving the bonus can provide a significant advantage in the game.

Keep good dice and re-roll others: After the first roll, players should consider which dice they want to keep and which they want to re-roll. It's generally a good idea to keep dice that are part of a potential scoring combination and re-roll the others.

Consider the probability of achieving certain combinations: Some combinations, like a Yahtzee, have a very low probability of occurring, while others, like a full house or a large straight, have a higher probability. Players should consider the likelihood of achieving certain combinations and weigh the potential points against the risk.

**Implementing the game in Python**

Defining the functions

  
  


Putting it all together
