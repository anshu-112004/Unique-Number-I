# Unique-Number-I
class Solution:
    def findUnique(self, arr):
        # code here 
        from functools import reduce
        from operator import xor
        return reduce(xor, arr)
