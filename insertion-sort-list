# Definition for singly-linked list.
# class ListNode:
#     def init(self, val=0, next=None):
#         self.val = val
#         self.next = next
class Solution:
    def insertionSortList(self, head: Optional[ListNode]) -> Optional[ListNode]:
        arr=[]
        temp=head
        while(temp):
            arr.append(temp.val)
            temp=temp.next
        for i in range(1,len(arr)):
            key=arr[i]
            j=i-1
            while(j>=0 and key<arr[j]):
                arr[j+1]=arr[j]
                j-=1
            arr[j+1]=key
        dummy=temp=ListNode()
        for num in arr:
            dummy.next=ListNode(num)
            dummy=dummy.next
        return temp.next
