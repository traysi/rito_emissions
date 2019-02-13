# rito_emissions
Compute the past and future block reward emissions for Ritocoin

# Building instructions:
Compile this using ```g++ emission.cpp -o emission```

If that fails, add c++11 flags thusly: ```g++ -std=c++11 emission.cpp -o emission```

# Usage:

Call without arguments to get all blocks for 10 years.

Or call with a block height as the arg and it'll tell you the reward for that block. Example: ```./emission 200000```


