# Mermaid Flowchart for Assignment
```mermaid
flowchart TD
  Start([Start]) --> GenerateRandom[generate a random number]
  GenerateRandom --> Guess[User makes a guess]
  Guess --> check{Is Guess correct?}
  Check -- Yes --> End([End Game])
  Check -- No --> TryAgain[Guess again]
  TryAgain --> Guess
