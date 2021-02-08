# pokerObserver
This repo contains a draft version for approach of poker game analyzing.

poker_observer.ipynb - a solution for reading the current state of poker table. Determines mainly what cards are present on table and what is pot value.

loop_test.ipynb - live testing of buttons showing whose turn is it etc.

The approach for analyzing game and sending nofications later (for example to computing server) is based on idea that every move can be predicted by only monitoring turn shifts and pot changes. 

analyze_strategy.ipynb - the strategy behind the idea
