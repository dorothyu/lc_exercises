class Solution:
    def reverse(self, x):
        """
        :type x: int
        :rtype: int
        """
        if x < 0:
            s = str(abs(x))
            result = 0 - int(s[::-1])
        else:
            s = str(abs(x))
            result = int(s[::-1])
            
        if result > 2**31-1 or result < -2**31 or x==0:
            return 0
        else:
            return result
