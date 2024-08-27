class Solution {
    public int findMaxDiff(int[] arr) {
       int left[]=new int[arr.length];
       int right[]=new int[arr.length];
       
      int i=0,j=1;
      Stack<Integer> st=new Stack<>();
      while(i<arr.length && j<arr.length){
          
          if(arr[i]<=arr[j]){
              st.push(i);
              i++;
              j++;
          }
          else{
              right[i]=arr[j];
              while(st.size()>0 && arr[st.peek()]>arr[j]){
                  right[st.pop()]=arr[j];
            
              }
              
                  i=j;
                  j++;
             
          }
          
      }
      
      i=arr.length-1;
      j=arr.length-2;
      st=new Stack<>();
       while(i>=0  && j>=0){
          
          if(arr[i]<=arr[j]){
              st.push(i);
              i--;
              j--;
          }
          else{
              left[i]=arr[j];
                while(st.size()>0 && arr[st.peek()]>arr[j]){
                  left[st.pop()]=arr[j];
            
              }
                  i=j;
                  j--;
              
          }
          
      }
      
      int max=0;
      for(int k=0;k<arr.length;k++){
         max=Math.max(max,Math.abs(left[k]-right[k])) ;
      }
      return max; 
    }
}
