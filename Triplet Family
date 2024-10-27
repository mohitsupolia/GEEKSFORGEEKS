class Solution {
    public boolean findTriplet(int[] arr) {
        Arrays.sort(arr);
        for(int i=2;i<arr.length;i++){
            int target=arr[i];
            int left=0;
            int right=i-1;
            while(left<right){
                int sum=arr[left]+arr[right];
                if(sum==target) {
                    return true;
                }
                else if(sum<target){
                    left++;
                }
                else{
                    right--;
                }
            }
        }
        return false;
    }
}
