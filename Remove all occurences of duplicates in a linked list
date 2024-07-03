class Solution {
    public Node removeAllDuplicates(Node head) {
        // code here
        Node ans = new Node(0);
        Node list = ans;
        int n = -1;
        
        while(head != null){
            if(head.next == null && n != head.data){
                ans.next = head;
                ans = ans.next;
                break;
            }
            if(head.next != null && head.data != head.next.data && n != head.data){
                ans.next = head;
                ans = ans.next;
            }
            n = head.data;
            head = head.next;
        }
        ans.next = null;
        head = list.next;
        return head;
    }
}
