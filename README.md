# Prop 
 Hand cricket game
This is a simple game which works on random numbers. The player selects any number from 1-10. Computer generates a random number in the same range. If computer's number is same as the player's selected number, the player is out and game ends. Otherwise the player's number is added to his score.

## Explanation
```java
//bb is player's entered input
rr=((Math.random())*10); //generate random number for computer
rr=rr+1; //add 1 because random number starts with 0
aa=(int)(rr); //convert to integer
/**...**/
 if(bb==aa) //game over condition
                    {
                        System.out.println(" ");
                        System.out.println("HOWZATTT!!!!!!");
                     }
