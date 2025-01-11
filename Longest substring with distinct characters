class Solution {
    public int longestUniqueSubstr(String s) {
        // code here
        int[] arr=new int[26];
        int l=0;
        int maxlen=0;
        for(int r=0;r<s.length();r++){
            int charIndex=s.charAt(r)-'a';
            if(arr[charIndex]!=0){
                l=Math.max(l,arr[charIndex]);
            }
            arr[charIndex]=r+1;
            maxlen=Math.max(maxlen,r-l+1);
        }
        return maxlen;
    }
}
