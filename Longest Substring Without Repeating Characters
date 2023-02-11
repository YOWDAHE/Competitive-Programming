class Solution:
    def lengthOfLongestSubstring(self, s: str) -> int:
        start = 0
        answer = 0
        collection = set()
        n = len(s)-1
        end = 0
        while end <= n:
            while s[end] in collection:
                collection.remove(s[start])
                start+=1
            collection.add(s[end])
            answer = max(answer,end-start+1)
            end +=1
        return answer
