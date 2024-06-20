class Solution {
    
    public static long gcd(long a, long b) {
        if (b == 0)
            return a;
        return gcd(b, a % b);
    }
    
    long InternalCount(long p[], long q[], long r[]) {
        // code here
        
        //area
        long area = Math.abs((p[0] * (q[1] - r[1]) + q[0] * (r[1] - p[1]) + r[0] * (p[1] - q[1])) / 2);
        
        //boundary
        long B1 = gcd(Math.abs(p[0] - q[0]), Math.abs(p[1] - q[1])) + 1;
        long B2 = gcd(Math.abs(q[0] - r[0]), Math.abs(q[1] - r[1])) + 1;
        long B3 = gcd(Math.abs(r[0] - p[0]), Math.abs(r[1] - p[1])) + 1;
        
        long B = (B1 + B2 + B3 - 3) / 2;
        long I = area - B + 1;
        
        return I;
    }
};
