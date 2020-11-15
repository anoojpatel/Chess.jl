# Chess


A modified version of Chess.jl which contains the additional ruleset of [Dark Chess](https://en.wikipedia.org/wiki/Dark_chess) or also known as [Fog of War Chess](https://www.chess.com/terms/fog-of-war-chess). Dark Chess is a Chess Variant with Imperfect-Information, which means you can only see pieces on the board that are yours, or spaces where your pieces can move/capture opponent pieces. Note, that you can Castle into and out of check. You can also move into Check (Resulting in losing the game if the opponent chooses to capture your King).

I'm  using this as the Chess backend for experimenting in building a Chess Engine/Agent for Dark Chess.
The main purpose of this Repo is to take advantage of the great tools in Chess.jl such as `GameNode` and `UCI` interface.  

 Julia library for computer chess. Visit the
[documentation](https://romstad.github.io/Chess.jl/dev/) for more details.
