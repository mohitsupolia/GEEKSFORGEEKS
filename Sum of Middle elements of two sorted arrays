class Solution {
    public int SumofMiddleElements(int[] arr1, int[] arr2) {
        int n=arr1.length+arr2.length;
       int res[]=new int[n];
       for(int i=0;i<arr1.length;i++){
           res[i]=arr1[i];
       }
       int a=arr1.length;
       for(int i=0;i<arr2.length;i++){
           int p=i+a;
           res[p]=arr2[i];
       }
       Arrays.sort(res);
       int m=n/2;
       int m1=n/2-1;
       return res[m]+res[m1];
    }
}
