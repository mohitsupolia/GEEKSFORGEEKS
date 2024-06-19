class Solution {

    double maxVolume(double perimeter, double area) {
        // code here
        double len = (double)(perimeter - Math.sqrt(perimeter * perimeter - 24 * area))/12;
        double height = (perimeter/4) - (2*(len));
        double res = len * len * height;
        return res;
    }
}
