# application
Referenced: https://www.youtube.com/watch?v=l9dqITtikD8&t=686s \
The logic doesn't completely work but I followed this tutorial and made the necessary changes to bring it up to date (mostly null saftey). I used the same images that the tutorial used.\
The issue is likely that _findwinner always reurns tileState.EMPTY so the _showWinnerDialog is never triggered.\
