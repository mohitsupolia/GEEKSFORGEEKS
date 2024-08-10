class Solution {
    // Function to rotate a linked list.
    public Node rotate(Node head, int k) {
        // add code here
        Node currentNode=head;
       //traverse first k-1 node
        while(k-->1){
            currentNode=currentNode.next;
        }
        
        //store current position int the tempNode
        Node tempNode=currentNode;
        //check if current Node is at last
        // if at last return original head
        if(currentNode.next==null){
            return head;
        }
        // store new head and traverse onwards
        currentNode=currentNode.next;
        Node newHead=currentNode;
        tempNode.next=null;
        while(currentNode.next!=null){
            currentNode=currentNode.next;
        }
        
        currentNode.next=head;
        
        return newHead;
    }
}
