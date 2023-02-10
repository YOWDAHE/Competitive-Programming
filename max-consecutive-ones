class Solution:
    def longestOnes(self, nums: List[int], k: int) -> int:
        n = len(nums)
        result = 0
        j = 0
        zeros = 0
        for i in range(n):
            if nums[i] == 0:
                zeros+=1
            while k < zeros:
                if nums[j] == 0:
                    zeros-=1
                j+=1
            result = max(result,i-j+1)

            
        return result
