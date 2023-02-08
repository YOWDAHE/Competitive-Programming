class Solution:
    def leastInterval(self, tasks: List[str], n: int) -> int:

        count = Counter(tasks)
        ans = 0
        lst = [0 for _ in range(26)]

        for letter in count:
            idx = ord(letter)-65
            lst[idx] = count[letter]
        lst.sort()

        while lst[-1] != 0:
            for i in range(n+1):
                if lst[-1] < 0 or lst[-1] == 0:
                    break

                if 25-i >= 0: 
                    lst[25 - i] -= 1
                ans += 1
            lst.sort()  

        return ans
