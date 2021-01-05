# Poker Math

### Lesson 1: Odds and Probabilities

*   Drawings hands -> need to connect with later community cards to win
    *   Outs = cards left in the deck that improve your hand and will help you win the pot at showdown
    *   Hidden outs = reduce the value of your opponent’s hand
        *   Ex: if you have no pairs, opponent has 33, board is JJ56 -> a five or six would give you both a two pair and you have the higher kicker
    *   Discounted outs = when a card you want also helps your opponent
        *   Ex: you are going for straight and calculate 8 outs -> but 2 of those cards could give your opponent a flush -> you have 6 outs
    *   ** be PESSIMISTIC when calculating outs **
*   Probability rules
    *   Hitting draw on next card = outs * 2
    *   Hitting draw on turn and/or river = outs * 4
*   Odds
    *   Ratio between the probability of winning and losing
        *   [Losing probability] = 100% – [winning probability]
        *   Calculated as LOSING / WINNING
    *   Pot odds
        *   The ratio between the size of the pot (chips in the pot and chips added while betting) and the bet facing you
        *   If the pot odds are higher than the odds of you winning -> call/raise
            *   Lower = fold
        *   Ex: you have A2 on flop 6K9 for nut flush draw
            *   9 outs on the flop and the pot is $4, your opponent bets $1
                *   Pot = 4 + 1 = $5 and it costs you $1 to call -> 5:1 pot odds
            *   Odds of hitting flush are 4:1 -> higher pot odds so call!
                *   You are paying $1 with a 4:1 chance of winning 5x
        *   Ex: you have 87 on flop A45 -> gunshot draw with four outs
            *   25 in the pot and opponent bets 5 -> 30 in the pot
                *   6:1 pot odds and $5 to call
            *   Hand odds are 10:1 -> you should fold
                *   You pay $5 with a 10:1 chance of winning only 6x
    *   All in bet -> calculate odds based on the river because no more betting