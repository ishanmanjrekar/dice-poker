# 🎲 Dice Poker

A card-and-dice hybrid game you can play solo or with a friend.  
Test your luck and strategy by rolling dice, drawing cards, and building the best Poker hands for points.

##### Read [this][https://gamedesignbites.substack.com/p/free-poker-style-card-game] for more context and details.
- This is a playable version of the solo variant of this game.
- It has been made using GPT5.
- You can read the setup and rules of the physical game below.

---

## 🌱 To Begin
You’ll need:
- A standard 52-card deck
- A 6-sided die

---

## 🕹️ Rules

### 👤 1-Player Game

#### 🎴 Setup
- Prepare **6 decks**.
- For each deck:
  - Place **7 cards face-down**.
  - Place **1 face-up card** on top.
- Arrange the decks in a row, numbered **1 to 6** (left to right).
- Deal **4 cards** into your hand.
- Keep a 6-sided die nearby.

#### 🎲 Gameplay
- Roll the die.
- Draw the top card from the deck that matches the roll, and add it to your hand.
- Reveal the next face-down card in that deck (if any).
- You may roll up to **3 times per round**.
- If you roll a number where the deck is empty, the roll still counts, but you draw nothing.
- **Hand limit:** 7 cards.  
  If you’re at the limit, you cannot roll again until you play a hand.

#### 🃏 Playing a Hand
- After rolling (or reaching your hand limit), you must play.
- Play up to **5 cards**.
- Score your hand using Poker ranks (pair, flush, full house, etc.).
- Discard the used cards.
- Begin a new round.

#### 🏁 Game End
- You score the total value of the cards used in each hand (see **Scoring** below).
- Play **15 hands** in total.
- Add up your scores — your total reflects your performance.

---

### 👥 2-Player Game

#### 🎴 Setup
- Same setup as solo play:
  - 6 decks, each with **7 face-down + 1 face-up** card.
  - Decks numbered **1–6**.
- Each player starts with **2 cards**.
- **Hand limit:** 5 cards.
- Decide who goes first randomly.
- Keep a die nearby.

#### 🎲 Gameplay
On your turn:
1. Roll the die.  
2. Take the top card from the matching deck.  
3. Reveal the next face-down card (if any).  
   - If the deck is empty, the roll is wasted.  
4. You may roll up to **3 times**, as long as your hand isn’t full.  
5. If you reach your hand limit, you cannot roll further.  

#### 🃏 Playing
- After rolling, you may **play a hand** or **pass**.
- You can play up to **5 cards** from your hand.
- Score the hand using Poker ranks.
- Discard all played cards.
- If you pass, end your turn without playing.

#### ♻️ Discards
- Each player has **3 discards total** for the game.
- You may discard any number of cards from your hand at any time.
- Use this to clear unwanted cards without wasting a play.

#### 🏁 Game End
- Players alternate turns, playing or passing.
- Each hand scores based on the total value of the cards played.
- The game ends when:
  - One player has played **10 hands**.  
  - If this is the first player, the second player gets one final turn.  
- The player with the **highest score** wins.

---

## 💯 Scoring

Each card has a base point value when used in a played hand:
- Number cards = face value (2–10)
- Face cards (J, Q, K) = 10 points
- Ace = 11 points

When you play a hand:
1. Add up the values of the cards in the hand.
2. Apply a multiplier based on the Poker hand you achieved.  
   - Higher ranks → bigger multipliers.

#### Example
- You play **Two Pair**: two 7s and two Queens.  
- Card total = `7 + 7 + 10 + 10 = 34`  
- Multiplier for Two Pair = `×3`  
- Final Score = `34 × 3 = 102`

⚡ Tip:  
Only the cards forming the hand score points.  
You can include low-value or unwanted cards in your play to free space in your hand.
