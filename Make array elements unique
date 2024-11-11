class Solution {
    public int minIncrements(int[] arr) {
        // Code here
        Arrays.sort(arr);
        int sum = 0;
        for (int i = 1; i < arr.length; i++) 
        {
            if (arr[i] <= arr[i - 1]) 
            {
                // If the current element is not greater than the previous, increment it 
                int increment = arr[i - 1] + 1 - arr[i]; 
                arr[i] = arr[i - 1] + 1;
                sum += increment; 
                
            } 
            
        } 
        return sum;
    }
}
