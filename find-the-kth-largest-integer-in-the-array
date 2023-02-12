class Solution:
    def kthLargestNumber(self, nums: list[str], k: int) -> str:
        converted = []
        for number in nums:
            converted.append(int(number))
            
        converted.sort()
        return str(converted[-1*k])
