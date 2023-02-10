#Definition for singly-linked list.
# class ListNode:
#     def init(self, val=0, next=None):
#         self.val = val
#         self.next = next
class Solution:
    def middleNode(self, head: Optional[ListNode]) -> Optional[ListNode]:
        first = ListNode()
        first = head
        second = ListNode()

        second = head
        while second and second.next:
            
            second = second.next.next
            first = first.next
        return first
