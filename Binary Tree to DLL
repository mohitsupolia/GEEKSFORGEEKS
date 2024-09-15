class Solution {
    Node prev = null;
    
    Node bToDLL(Node root) {
    	if(root == null){
    	    return null;
    	}
    	
    	Node head = null;
    	
    	head = bToDLL(root.left);
    	
    	if(prev==null){
    	    head = root;
    	}
    	else{
    	    prev.right = root;
    	    root.left = prev;
    	}
    	
    	prev = root;
    	
    	bToDLL(root.right);
    	
    	return head;
    }
}
