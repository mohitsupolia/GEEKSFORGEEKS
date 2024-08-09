class Solution {

    int Maximize(int arr[]) {
        int n = arr.length;
        long sum = 0;
        int MOD = 1000000007;
        Arrays.sort(arr);
        for (int i = 0; i < n; i++) {
            sum = (sum + (long) i * arr[i]) % MOD;
        }
        return (int) sum;
    }
}
