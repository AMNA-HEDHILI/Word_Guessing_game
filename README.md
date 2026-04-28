# 🎯 Word Guessing Game

A simple terminal-based word guessing game written in Python, similar to Hangman. Try to uncover the hidden word one letter at a time before you run out of attempts!

## How to Play

1. A random word is chosen secretly from the word list
2. You see the word displayed as underscores (e.g. `_ _ _ _ _`)
3. Guess one letter at a time
4. If the letter is in the word, it gets revealed in the correct position(s)
5. If the letter is not in the word, you lose one attempt
6. You win by revealing all letters before running out of attempts
7. You lose if you use all **10 attempts** without guessing the word

## Example Round

```
Current word: _ _ _ _ _
Guess a letter: e
Great guess!

Current word: _ e _ _ _
Guess a letter: z
Wrong guess! Attempts left: 9
```

## Getting Started

### Prerequisites
- Python 3.x installed on your machine

### Running the Game

```bash
python game.py
```

## Word List

The current word list includes:

| Word |
|------|
| rizz |
| batata |
| hello |
| apologize |
| skibido |
| laylay |

You can add your own words by editing the `wordList` variable in `game.py`:

```python
wordList = ["rizz", "batata", "hello", "apologize", "skibido", "laylay"]
```

## Game Rules

- You have **10 attempts** per game
- Guesses are **not case-sensitive**
- Each wrong guess costs one attempt
- Repeating a letter you've already guessed will not penalise you

