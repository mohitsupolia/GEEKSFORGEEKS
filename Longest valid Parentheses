class Solution{
    static int maxLength(String S){
        // code here
        Stack<Integer>s=new Stack<>();
        char[]arr=S.toCharArray();
        int max=0;
        for(int i=0;i<arr.length;i++){
            if(!s.isEmpty() && arr[s.peek()]=='(' && arr[i]==')')s.pop();
            else s.push(i);
            int curr=(s.isEmpty())  ? i+1:i-s.peek();
            max=Math.max(curr,max);
        }
        return max;
    }
}
