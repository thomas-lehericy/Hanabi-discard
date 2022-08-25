# Hanabi-discard

This is an experimental convention for 3p+, based on a fun premise. Initially an intellectual challenge, it turned out surprisingly efficient, although that was more a side-effect than an intended feature.

The idea of this convention is that players tell other players that they have a playable card by discarding a card in the same slot. Clues are used mostly to save valuable cards (not necessarily critical) from being discarded. Combined with the good touch principle, as the game progresses a lot of "saved" cards will be known as playable. 

If you are interested in learning about this convention, the current README will teach you the fundamentals: no strategy, but every concept that you need to start building them. Strategies (elementary and more advanced) are gathered in "Strategies.md". 


# 0. Modals

a- MUST refers to a rule that should always be followed. Players MUST assume that a rule containing "MUST" is followed. They will know something is up if the rule is not followed. 

b- MUST NOT refers to a situation that MUST be avoided. 

e- SHOULD refer to a rule that should preferably be followed when no clear preference occurs between two options. SHOULD NOT refer to a situation that SHOULD be avoided. 

d- MAY refer to a decision that a player is free to take. (?? Priority ??)


# 1. Valuable cards

a- A card is critical if it has exactly one copy remaining. 
Ex: at the beginning of the game, only 5 are critical.

b- A card is valuable if it must be played in the future, and no other copy of it have already been clued or play-hinted (See Section "Play hints" for a definition).

c- A card is trash if it has already been played. It is known trash if the player who has it in hand knows it is trash.

d- When determining which card to save first, critical cards SHOULD be saved first, then valuable cards. Cards that are closer to playable SHOULD be saved first. 


# 2. General principles

a- Always Play Principle: if you know that one of your cards is playable, you MUST play. Any delay sends a message to your partners. 
* It is the other players’ responsibility to ensure that critical cards will not be discarded. 

b- Minimum clue value principle (MCVP): a clue MUST bring new information to the team. Players MUST NOT give a play-hint that only affects already play-hinted cards. We have special rules when no "useful" move is possible, see "Trash clues".

c- Good touch principle (GTP): cards that receive clues SHOULD, as much as possible, be valuable. Exception can and will occur (Ex: someone clues the duplicate of a valuable card that is already clued in their hand), but MUST be avoided whenever possible. 


# 3. Play order

To make the game predictable, players must know in which order to resolve the play clue that they receive. This allows "stacking" play clues over a single player, or even between players, in a clean and error-free way. We decided on a simple rule: the card that was marked as playable earliest should be executed first. Of course, exceptions are permitted in exceptional circumstances, but the responsibility of unexpected consequences lies on the player who decides to disregard the play order. 

a- Players will inform each other of which cards are playable through play hints (see Section "Play hints"). 

b- When a player knows that at least a card in their hand is playable, they MUST play.

c- When a player received multiple play hints, the play hints MUST be resolved in the order in which they were received. 

d- When a player has a mix of play hints and known cards that are playable, the known cards MUST be played first. 

e- When giving play hints, players MUST assume that one player’s play hints will be resolved no matter what other players do. In particular, they MUST NOT assume that a player will wait for another card to be played. 
 * Ex1: g1 is played. Bob has g2, Cathy has g3. Alice MUST NOT play-hint the g3. 
 * Ex2: g1 is played. Bob has a play-hinted g2, Cathy has g3. Alice MAY hint g3, because Bob will play g2 before Cathy, making the g3 playable. 

f- If a player with a play hint did NOT play, it means something very urgent has come up. The next players with play hints should use their discretion to know whether to play or delay. Cf. special rules "Letting the clue tick" (Strategies.md). 


# 4. Play hints

A play hint is a signal to the other players that a card is playable. Most of the time, the card that is signalled as playable isn’t touched by any clue.

a- To indicate that a card is playable, a player MAY either
 * discard their card in the same slot, 
 * clue a valuable card in a player’s hand, in the same slot. (Interpreted as a "save" from a possible discard.) 

b- Players MUST NOT
 * "fill-in" a card to inform their owner that it is playable if this is not a valid play-hint, or otherwise a valid move. 
 * clue a non-valuable card. See "Trash Clues".
 
c- When play-hinting a card, players SHOULD, in order of preference,
 * clue a valuable card,
 * if impossible / impractical, discard,
 * if impossible / dangerous, clue the play-hinted card directly. 
 * In the early game, players SHOULD give clues instead of discarding, otherwise they might discard valuable cards.
 
d- When cluing one or more VALUABLE cards in a player’s hand, it means that there is at least one playable card in EVERY slot that was touched by the clue. 

e- A play hint may target you, even if there is another visible target. If none of the possible targets before you played when they could have (take into account their play queue), it means you have a playable card, and you MUST play. Cf. "Letting the clue tick" (Strategies.md). 

f[special]- If Alice played or discarded, and a playable card arrived in slot x, Bob MUST NOT discard their card in slot x. This is because they may have a valuable card in slot x that no one had the opportunity to clue before. They MAY give up on play-hint Alice’s card, or they MAY play-hint it provided they do not discard. 

g- If several cards of the same player are touched, they MUST be played from newest to oldest. 


# 5. Trash clue

Sometimes, a player just has nothing relevant to do. In most conventions, they would discard their chop card. This is not possible here - a discard would be interpreted as a play hint. Instead, they have the Trash clue. 

a- A trash clue is a clue that everyone agrees is not a play hint. Its sole purpose is to express that the clue giver has nothing better to do. 

b- A 1 clue is ALWAYS a trash clue, by convention. (It is thus a good idea to keep at least one 1 among all players’ hands.)

c- A clue that touches at least one unplayable card is ONLY a trash clue if, after receiving the clue, the receiver KNOWS that at least one of the affected cards is trash. The receiver MUST then mark all affected cards as known trash. If the receiver does not know that at least one of the affected cards is trash, it is a normal play clue. 

d- Known trash MAY be discarded without it giving any information whatsoever. It MUST NOT be interpreted as a play hint. (Let us call it a "Trash discard".)

# 6. Fix clue

When a mistake is about to be made, we allow a clue that "fixes" it - and only does that. 

a- A fix clue is a clue that affects a card that is about to be played. 

b- Fix clues MUST NOT be taken as a play clue, but only as preventing a misplay. 

c- The fixed player MUST erase all affected cards (including the one they are about to play) from the play queue, and proceed with the next item. 

 * Ex: No card is played. Bob knows that his slot 1 card is unplayable. Alice clues three red to Cathy, including her slot 1; there is no non-play-hinted playable card in anyone’s hand but Cathy, so Cathy knows the play hints are for her. Cathy would play them from left to right. Immediately after Alice, Bob clues the left-most one as a 5 (possibly touching another 5); it is a fix clue, so no one interprets it as a play hint for them. Cathy would then play the middle red (and place r1), then the right-most red (and play r2), then stop there. 

d- Player should trust their partners and NOT rush to give a fix clue - instead, they should consider whether they missed a previous play hint targetted at themselves. Only when there is no other reasonable possibility, and they are certain that a mistake is indeed about to be made, should they "fix" the clue. 
