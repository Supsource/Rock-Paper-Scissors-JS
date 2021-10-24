# Rock-Paper-Scissors-JS

An experiment involving a game of rock, paper and scissor. During the first 3 rounds the computer chooses a move (rock, paper or scissor) at random. After that, it assumes it has enough data about the player to predict it's pattern. The data set consists of the player last two moves, being the last one, the one they'll do after the first one. Kind of confusing, right?! Simple put, the computer stores the first move as a input x and the move after that as a label or target y, meaning that after the player choosing rock, for instance, there's a possibility they'll choose paper as the next move. If the computer predicts the player will play rock, it plays paper, so on and so forth. Every time the computer loses, it trains the neural network again.


# Contributors

Pull requests and stars are always welcome.
