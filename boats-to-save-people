class Solution:
    def numRescueBoats(self, people: List[int], limit: int) -> int:
        people.sort()
        start,counter = 0,0
        end = len(people)-1
        while start <= end:
            diff = limit - people[end]
            end-=1
            counter+=1       
            if diff>=people [start]:
                start+=1
    
        return counter
