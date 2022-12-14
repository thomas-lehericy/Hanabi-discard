# Basic strategies

## No clue in the bank

a- If Alice has no play-hinted card and no remaining clue. She thus MUST discard. 
 * If she has a known trash card, she MAY discard it. This will be interpreted as a trash discard, that does not give any information.
 * If she has a known trash card, she MAY discard another, non-known trash card. This will be interpreted as a play hint.
 * ?? If she has NO known trash card, she MUST discard her card that is most likely to be trash, or a card decided through a known procedure - other players should have had the opportunity to save said card beforehand. This MUST NOT be interpreted as a play hint. (The players should do their best to avoid this situation.)

b- Players who anticipate this behavior and notice that it will lead to the discard of a CRITICAL card MUST prevent this situation from happening, by trash discards or other means. 


## There are no playable cards

We do not want to keep giving trash clues: this would exhaust the clue bank without bringing in any new card. 
Trash discards SHOULD be preferred to trash clues when the game is poor in playable cards. 

?? Consider situations where no trash discard can be safely given ??



## Letting the hint tick

a- Alice gives a play-hint in slot x. Bob and Cathy both have a playable card in slot x.
- At Bob’s turn, Bob does not play his slot x card. 
- Cathy deduces that Bob sees another playable card in slot x. Since no other player except Bob has a playable card in slot x, she knows she is the one with it.
- She now has a card to play. But instead, she **lets the hint tick by not playing her slot x card**, so that Bob is informed that he, too, has a playable card in slot x.
- During the next turn, both Bob and Cathy will play their slot x card.

b- This can be used to inform Alice that she has a playable card in slot x.

c- If more than two playable cards are in slot x, 
- the last player (before Alice) with a playable card will pass once to inform the others that they too have a playable card.
- the penultimate player with a playable card will pass twice,
- the player before him with a playable card will pass thrice,
- etc. 

d- This applies to ANY type of play-hint, be they vanilla (discard / clues) or indirect. 


## Letting someone else give a clue

Ex: Cathy has exactly one non-play-hinted playable card, which is in slot x. 
* If Bob has a valuable card in slot x, Alice SHOULD save it. Cathy would know she was play-hinted, and Bob’s card would be out of danger. 
* If Bob has a trash card in slot x, Alice SHOULD do something unrelated (possibly trash-cluing or trash-discarding). Bob, seeing that his slot x card was not saved, now knows that his slot x card is safe to discard. He MAY discard. 
* Bob should exercise his better judgment when doing so: it may be that Alice had something more urgent to do, e.g. a fix clue to give. In this case they should either give a play-hint without discarding, or let someone else give the play-hint.
* We generalize to the following heuristic: 

a- Giving a play-hint on a card SHOULD be left to the last player (before the card holder) that has trash in this slot. 


# Advanced strategies (WIP!)

## Special trash

Discussed in more details in the issue "Special trash". 

This strategy builds upon "Letting someone else give a clue". 

Ex: Cathy has exactly one non-play-hinted playable card, which is in slot x. Alice gives a trash clue. 
* Bob then knows for certain he has a trash card in slot x. This card is now a known trash card for everyone but Cathy. Since Cathy does not know that Bob knows it is a trash card, she would interpret a discard of this card as a play clue on her. 
* This trash card is now a "special trash", with target Cathy.
* As soon as Cathy plays her card, seeing the history of the game, she will be able to deduce that Bob has a special trash with her as target. This way, information symmetry is restored, and the team now has a very special card to play with.

Special trash can be very common, and a lot of strategies could be enabled by them. 
* If Cathy pretends not to know about the special trash, then only Cathy will interpret a discard of this trash card as a play hint. Bob now has a play clue that ONLY affects Cathy, and may be for example trigger finesses much more conveniently. 
* Players could agree (or not) that special trash does not expire when it is revealed as "known trash" by a trash clue. 
* ?? Players should still have a way to safely discard a special trash clue when its utility has expired. ??


## Finesses and bluffs

Note to H-group players: this is a poor man’s finesse, please look for better ones!

Finesses are tricky, since play hints will be interpreted as "there is a playable card in this slot". The player immediately after the finesse-giver, up to the player who is supposed to play into the finesse (included), MUST not be able to play their card in this slot - either by knowing that it is unplayable, or by having another card to play first. Once someone plays into a finesse, the meaning of the play hint will be made clear and any wrong play avoided. 

a- Simple finesse / bluff:
- Alice gives a play clue on slot x, where there is at least one valuable but unplayable card. 
- Bob’s card in slot x is known (by him) unplayable. 
- No one else has a playable card in slot x. 
- If Bob does nothing, the first person with a non-known-unplayable card will attempt to play it.
- But Alice would not play-hint a truly unplayable card. This means there is a card that must be played that will resolve the situation and make at least one card playable.
- Bob thus plays the card that is most likely to make one of the slot x cards playable (based on his clues; if several are possible, the left-most one (or any arbitrary convention); if there are no compatible clues, Bob plays his finesse position.)
- This card may or may not actually allow a card to be played. In any case, the other players should take note that a finesse has occured, and as such, that NONE of them has a playable card in slot x, but that at least one of them has a valuable card that was not yet playable at the time the play-hint was given.
- If the newly placed card makes one of their card possibly playable (based on their clues), they MUST attempt to play it. (Finesse are to be considered before Bluffs.) This MAY trigger multiple bluffs (if a card is falsely playable, it means that someone has a playable card in a position to be played before the play-hinted card is played). 
- Note that, by seeing Bob react to the finesse, the clue-receiver should acknowledge that he received a clue on a, at this time, UNPLAYABLE card. If, at his turn, his card’s playability has not changed (based on the previous player’s reactions), he should not play it. If nothing tells him that the card is unplayable, he MUST attempt to play it. 
- In this example, if Donald has the play-hinted card and Cathy has nothing to do (and will thus play if Bob does nothing), then Bob MUST play into the finesse, EVEN IF CATHY HAS A PLAYABLE CARD IN HER FINESSE POSITION, and even if this playable card is the one needed for the finesse. That is because if Bob does nothing, Cathy will not play her finesse card, but her slot x card. It is likely that Bob’s finesse card is playable (but different from Cathy’s) - and that Cathy, now understanding that it is a finesse, will play her finesse card immediately after. 
- In this last case, Bob’s first hypothesis MUST be that his card will not necessarily be the one of the finesse. He MUST thus only play a clued card if it is compatible with EVERY possible case (ex: clued "2" when all the 1s, and no other card, are placed) - otherwise, he must play the finesse card. 

Signalling a finesse (by playing the first card of the finesse) take precedence over EVERY OTHER ACTION (including plays), otherwise bad information may be transmitted. It is the finesse-starter’s responsibility to ensure that this will not harm the team. 
- Signalling the finesse MUST be done by one of the players following the hint-giver who knows that it is a finesse, in a way to prevent anyone from misguidedly trying to play.
- After this point however, the situation is not as urgent. Since the play-hinted card is queued like any play-hint, the rest of the finesse may be played over several game turns. It may also force the same player to play several cards. 

Ex: Bob has no playable card in slot x, but he has a card to play. Donald has y2 in slot x. Cathy has y1 in her finesse position, and knows that her slot x card is unplayable.
- Alice play-hints slot x, for example by discarding, or by cluing Cathy’s slot 3 in a way that makes it clear that Cathy’s slot 3 is not playable.
- Bob, seeing the state of the game, writes down (wrongly) that he has a playable card in slot x (and notes, looking at Cathy’s hand, the possibility of a finesse). He proceeds to play his current card. 
- Cathy knows the play-hint cannot possibly be for her. She concludes that this is a finesse, and plays her y1. 
- Seeing this, Bob realizes that it is, indeed, a finesse. He erases his note that his slot x card is playable. 
- Donald plays his y2. 
- In this example, Bob should NOT signal the finesse: indeed, first, he can see Cathy’s y1, and second, his next queued card may be a y1. He should thus play his cards as usual. 

Ex (of things going wrong): Bob has a playable card in slot 1, and y1 in slot 2. Cathy has nothing playable. Donald has y2 in slot x.
- Alice play-hints slot x, thinking that this indicates Bob’s finesse position.
- But in fact, Bob interprets this as "the card I will play is y1" - which it is not.
- Bob plays his card as usual. Cathy tries to play her slot x card, and fails. Noting the failure, everyone else marks that they do not have any playable card in slot x, and Bob understands that he missed a finesse (for no fault of his own). 
- If players agree to not "forget" about the wrong clue, Bob will thus attempt to signal the finesse by playing his finesse card (at the time of the play hint) - in this case, his slot 2 card - during his next turn. If this card is not playable, someone must give Bob a fix clue. Bob would thus remove his slot 2 card from his playing queue, emptying it. The finesse is stopped, and the mistake is corrected. 

Ex: g3, p3, y2, b1 and r2 are placed. Alice play-hints slot x. Bob’s card in slot x is clued 5, Cathy’s is trash, and Donald’s card is clued 4. The target of the finesse is either Bob or Donald. 
- If Bob does nothing, Donald deduces that he has g4. But Bob plays his finesse card, which is r3. Donald then knows that he has neither g4 nor p4. 
- Cathy then plays her finesse card, and places y3. Donald deduces that his card is not r3 - otherwise, Cathy wouldn’t have played. 
- It is now Donald’s turn. He may have b4 (unplayable) or y4 (playable). If he had b4, Cathy would have known that she couldn’t make the card playable, and would thus have fix-clued him. His card is thus y4. Donald plays it. (In any case, if there is a possibility that the card is playable, Donald MUST play it.) 
- Note that Bob HAS to play his finesse card, even though he can see that Cathy has the card that is ACTUALLY required for the finesse. Indeed, if Bob did not play, Cathy would NOT know that this was a finesse, and she would instead try to play her slot x card. 
- If Cathy had played b2 instead, Donald still deduces that his card is y4, and he would see that y4 is not yet playable. He thus does not play it. 
- If Bob had played g4 and Cathy had done nothing, Donald would have deduced that the finesse card had been made playable, and is thus Bob’s 5 and not his 4. (It should be clear to him anyway since he sees Bob’s card, and knows that it is playable.)

b- Simple self-finesse: If all cards in slot x (besides Bob) are trash, then Bob knows that he is the only possible target of the finesse. He must proceed as above. 

c- If, at the time where the play-hinted player should play the card, the card is known by its holder as not playable, then the finesse ends - as a bluff. No other player should keep trying to play cards into the finesse. 
