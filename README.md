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
 * not letting a player who is likely to break the GTP a chance to do so is good form and MUST/SHOULD be done. Ex: someone who is likely to clue a card that is already clued in their hand. 

d- 
* ?? Save principle ??
* ?? Priority between principles ??


# 3. Play order

To make the game predictable, players must know in which order to resolve the play clue that they receive. This allows "stacking" play clues over a single player, or even between players, in a clean and error-free way. We decided on a simple rule: the card that was marked as playable earliest should be executed first. Of course, exceptions are permitted in exceptional circumstances, but the responsibility of unexpected consequences lies on the player who decides to disregard the play order. 

a- Players will inform each other of which cards are playable through play hints (see Section "Play hints"). Sometimes, cards will receive enough clues to be identifiable, in which case the owner of the card should know to play it.

b- When a player knows that at least a card in their hand is playable, they MUST play.

c- When a player received multiple play hints, the play hints MUST be resolved in the order in which they were received. (Unless it is ABSOLUTELY CLEAR that not doing so will not cause another player to play a not-yet-playable card.)

d- When a player has a mix of play hints and known cards, known cards MUST be played first. 
 * This allow other players to clue subsequent cards with play hints.
 * If a card is filled-in and is revealed playable while the owner still had play-hints to resolve, the owner MUST interrupt the sequence of play-hints to play the revealed card. Indeed, the next play-hint may require this revealed card to be played first. 
 * If the other players do not want the play order to be changed, they should delay revealing the card to its owner. 

e- When giving play hints, players MUST assume that one player’s play hints will be resolved no matter what other players do. In particular, they MUST NOT assume that a player will wait for another card to be played. 
 * Ex1: g1 is played. Bob has g2, Cathy has g3. Alice MUST NOT play-hint the g3. 
 * Ex2: g1 is played. Bob has a play-hinted g2, Cathy has g3. Alice MAY hint g3, because Bob will play g2 before Cathy, making the g3 playable. 

f- If a player with a play hint did NOT play, it means something very urgent has come up. The next players with play hints should use their discretion to know whether to play or delay. 

g- cf. special rules "Letting the clue tick" (4f). 


# 4. Play hints

A play hint is a signal to the other players that a card is playable. Most of the time, the card that is signalled as playable isn’t touched by any clue.

a- To indicate that a card is playable, a player MAY either
 * discard their card in the same slot, 
 * clue a valuable card in a player’s hand, in the same slot. (Interpreted as a "save" from a possible discard.)
 * In the early game, players SHOULD give clues instead of discarding, otherwise they might discard valuable cards. 

b- Players MUST NOT
 * "fill-in" a card to inform their owner that it is playable if this is not a valid play-hint, or otherwise a valid move. (Exception can be made at the end, when all playable cards are visible and the players know it cannot be a play hint - we can rely on the fact that "filled-in" playable cards must be played before play hints.)
 * clue a non-valuable card. When a non-valuable card is clued, another interpretation is needed. See "Trash Clues" for the current suggestion. 
 
c- When play-hinting a card, players SHOULD, in order of preference,
 * if they do not know whether their card in the same slot is trash or valuable, clue a valuable card,
 * if impossible / impractical, or if they know that their card in the same slot is not valuable (but NOT if it is known trash), discard,
 * if impossible / dangerous, clue the play-hinted card directly. 
 
d- When cluing one or more VALUABLE cards in a player’s hand, it means that there is at least one playable card in EVERY slot that was touched by the clue. 
 * Suggestion: the slot of every previously unclued card that was touched by the clue. If every card was already clued, then every affected card. 

e- After witnessing a play-hint, every player (except the one giving the play-hint) MUST make a note of it. If a player observes that no other player has a playable card in this slot, it means they have the playable cards. They write down a play-hint on this card. Otherwise, they MUST still make a note.

Indeed, if a player with a playable card in this slot does not play this card when he had to, it means that they, too, have a playable card. They MUST then add a play-hint to their card. 

f[advanced, letting the clue tick]- In a situation where a single play-clue was given to signal two or more cards, the last player with a playable card will know (by the reasoning in 4e). They MAY choose to NOT play, to inform the other players that they, too, have a playable card. They also write down the play-hint on their card. The initial play hint is considered acknowledged and acted upon, and this non-play is considered a NEW play-hint for the other players. 
* Letting the clue tick may ONLY affect the cards that were in the target slot at the time the clue was given. 

g- Letting the clue tick MAY be used to inform the clue-giver that they, too, have a playable card in the affected slot. 

h[special]- If Alice played or discarded, and a playable card arrived in slot x, Bob MUST NOT discard their card in slot x. This is because they may have a valuable card in slot x that no one had the opportunity to clue before. They MAY give up on play-hint Alice’s card, or they MAY play-hint it provided they do not discard. 

i- If several cards of the same player are touched, they MUST be played from newest to oldest. 
 * Any ordering convention is acceptable provided it is agreed upon beforehand. 
 * If this is not the correct order, a fix clue must be used (see "Fix clue".)


# 5. Trash clue

Sometimes, a player just has nothing relevant to do. In most conventions, they would discard their chop card. This is not possible here - a discard would be interpreted as a play hint. Instead, they have the Trash clue. 

a- A trash clue is a clue that everyone agrees is not a play hint. Its sole purpose is to express that the clue giver has nothing better to do. 

b- A 1 clue is ALWAYS a trash clue, by convention. (It is thus a good idea to keep at least one 1 among all players’ hands.)

c- A clue that touches at least one unplayable card is ONLY a trash clue if, after receiving the clue, the receiver KNOWS that at least one of the affected cards is trash. The receiver MUST then mark all affected cards as known trash. If the receiver does not know that at least one of the affected cards is trash, it is a normal play clue. 
 * Ex: Filling in a clued card that could (by GTP) be valuable, and revealing that it is not. This is a trash clue.
 ** ?? If the card is not yet played, if the other copy is marked and in another player’s hand, it is a trash clue, and a "gentleman discard" is allowed. ??
 * Ex: Every 2 is played. Alice clues 2. This is a trash clue. 
 * Ex: Every 2 but the blue one is played. Alice clues 2 on a previously unclued card. This is NOT a trash clue, and in fact, it reveals that the clued 2 is the b2. To everyone else, it is a play-hint on b2, and only on b2. If there is another playable card in the b2 slot, the holder of the clued b2 MAY let the clue tick. 
 * It is not a good idea to give a trash clue that will not be interpreted as a trash clue by the clue receiver, and then to fix it. Indeed, it may be interpreted as a play clue, then a fix clue: they will play the other cards. It is also very clue-consuming. 

d[??]- Known trash MAY be discarded without it giving any information whatsoever. It MUST NOT be interpreted as a play hint. (Let us call it a "Trash discard".)

e- A "1" trash clue may fill in cards and reveal them playable - but it is STILL a trash clue. 
 * It is reasonable to give such a "trash clue" even when there are relevant things to do - so such a trash clue should not be interpreted as a stall.


# 6. Fix clue

When a mistake is about to be made, we allow a clue that "fixes" it - and only does that. 

a- A fix clue is a clue that affects a card that is about to be played. 
 - It may reveal to the card owner that the card is unplayable. This is recommended, but not necessary.
 - Indeed, the only other explanation is that there are two playable cards in this slot. If that is the case, then the card owner will see at least one playable card in this slot. If there is none, they will conclude without a doubt that it is a fix clue. If there is one, the situation is ambiguous; the card owner should err on the side of caution and delay playing their card. 
 - In the latter case, and if it is not immediately clear to its owner that the "fixed" card is unplayable, the other players MUST recognize the reason for the delay, and note that they have a playable card in the slot that was about to be played. If the clue was indeed a fix, then they MUST NOT play before the "fixed" player’s turn. If the clue was not a fix but a legitimate double play hint, at least one of them MUST play before the "fixed" player’s turn (bypassing their own queue if needed - no "letting the hint tick", see Strategies) to let the delaying player’s play queue resume as soon as possible. 

b- Fix clues MUST NOT be taken as a play clue, but only as preventing a misplay. 
 * They MAY touch other cards, in which case they SHOULD give useful information to the receiving player (like filling in trash cards, or cluing valuable cards). 
 * A possible fix clue that reveals trash cards MUST be considered as a fix clue before being considered a trash clue; as such, it is allowed to touch a mix of trash and valuable cards. 
 * In this case, a "1" clue will be considered a fix clue before being considered a trash clue. 

c- The fixed player MUST erase all affected cards (including the one they are about to play) from the play queue, and proceed with the next item. 

 * Ex: No card is played. Bob knows that his slot 1 card is unplayable. Alice clues three red to Cathy, including her slot 1; there is no non-play-hinted playable card in anyone’s hand but Cathy, so Cathy knows the play hints are for her. Cathy would play them from left to right. Immediately after Alice, Bob clues the left-most one as a 5 (possibly touching another 5); it is a fix clue, so no one interprets it as a play hint for them. Cathy would then play the middle red (and place r1), then the right-most red (and play r2), then stop there. 
 * In this case, if Bob did not know that his slot 1 card is unplayable, he should attempt to play it. Doing so will tell Cathy that her slot 1 card is unplayable (she will already know it by looking at Bob’s hand).

d- Player should trust their partners and NOT rush to give a fix clue - instead, they should consider whether they missed a previous play hint targetted at themselves. Only when there is no other reasonable possibility, and they are certain that a mistake is indeed about to be made, should they "fix" the clue. 

e- What is important in determining whether a clue is a fix clue or not is whether the clue giver meant it as a fix clue or not. 
 * Normally (see 6d) everyone should be on the same page. But mistakes happen. 
 * Caution should be exerted in case of a potential erroneous fix clue. 
 * To avoid such ambiguous cases, clues that are not fix clues SHOULD NOT touch cards that are about to be played. 



?? Allow other fix moves ??
?? It is not a good idea to allow "stomping" on a clue to be a fix clue, since it could be interpreted as a finesse. ??
