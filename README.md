# VanitySearch-appspot
VanitySearch, v1.15.4, fork, fix - vanitypool.appspot.com

New 5 algorithms uncompatible with split-key project vanitypool.appspot.com
Reduce algos to one (basic). 
I commented out all the symY/endo; also excluded the use of the algo for compressed keys with negative zero.
We lost speed, but now the calculations are fully compatible with the pool.

Source: https://github.com/JeanLucPons/VanitySearch
Thx JeanLuc for this instrument
