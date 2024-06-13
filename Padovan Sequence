class Solution
{
  public int padovanSequence(int n)
    {
        //code here.
        long [] arr= new long[n+1];
        long m = 1000000007;
        
        if(n<3){
            
            return 1;
        }
        else{
            arr[0] =1;
        arr[1]=1;
        arr[2]=1;
        
        for(int i=3; i<=n;i++){
            arr[i] = (arr[i-2]+arr[i-3])%m;
        }
        
        int ans = (int)arr[n];
        return ans;
        }
        
    }
    
}
