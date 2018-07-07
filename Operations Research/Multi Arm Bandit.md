## Dynamic Price Optimization using Multi-Arm Bandit Problem  

### Multiarm bandit  
> Problems solved by MAB algorithms don't have states but actions and rewards.

> For the problem we are considering, an action or decision is the price of an item and reward is the profit achieved for that price. To summarize, an MAB algorithm involves the follwing steps

          1. Trial and error decision making:- In a  trial and error setting, any Multi Arm Bandit algorithm has 
             to carefully balance exploration of the serach space while leveraging the better decisions leanred 
             so far to maximize long term reward.
          2. Receiving reward and using that to influence future decisions

#### Various MAB algorithms available are essentially charaterized by how exploration and exploitation is balanced. Here is a list of some of the popular algorithms.

1. Random greedy
2. Upper confidence bound one
3. Upper confidence bound two
4. Softmax
5. Interval estimate
6. Thompson sampling
7. Reward comparison
8. Action pursuit
9. Exponential weight  

