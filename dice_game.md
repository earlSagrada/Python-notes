# The expected payoff of a dice game

The question is here:

> You have the option to throw a die up to three times.
> You will earn the face value of the die.
> You have the option to stop after each throw and walk away with the money earned.
> The earnings are not additive. What is the expected payoff of this game?

I saw that on the BNP Paribas online test and then I searched the answer of it.

> Let's suppose we have only 1 roll. What is the expected payoff?
> Each roll is equally likely, so it will show 1, 2, 3, 4, 5, 6 with equal probability.
> Thus their average of 3.5 is the expected payoff.

> Now let's suppose we have 2 rolls.
> If on the first roll, I roll a 6, I would not continue.
> The next throw would only maintain my winnings of 6 (with 1/6 chance) or make me lose.
> Similarly, if I threw a 5 or a 4 on the first roll, I would not continue, because my expected payoff on the last throw would be a 3.5.
> However, if I threw a 1, 2 of 3, I would take that second round. This is again because I expect to win 3.5.

> So in the 2 roll game, if I roll a 4, 5, 6, I keep those rolls, but if I throw a 1, 2, 3, I reroll.
> Thus I have a 1/2 chance of keeping a 4,5,6, or a 1/2 chance of rerolling.
> Rerolling has an expected return of 3.5. As the 4, 5, 6 are equally likely, rolling a 4,5 or 6 has expected return 5.
> Thus my expected payout on 2 rolls is .5(5)+.5(3.5)=4.25.

> Now we go to the 3 roll game. If I roll a 5 or 6, I keep my roll.
> But now, even a 4 is undesirable, because by rerolling, I'd be playing the 2 roll game, which has expected payout of 4.25.
> So now the expected payout is 1/3*(5.5)+2/3*(4.25)=4.66

https://math.stackexchange.com/questions/179534/the-expected-payoff-of-a-dice-game
