class Solution {
    public static String oddEven(String s) {

       HashMap<Character,Integer>mp=new HashMap<>();
       for(int i=0;i<s.length();i++){
          mp.put(s.charAt(i),mp.getOrDefault(s.charAt(i),0)+1);
       }
       int count=0;
       Iterator<Map.Entry<Character,Integer>> iterator = mp.entrySet().iterator();
       while(iterator.hasNext()){
          Map.Entry<Character,Integer> entry = iterator.next();
          int t=(int)entry.getKey();
          int k=entry.getValue();
          if((t%2==0&&k%2==0)||(t%2!=0&&k%2!=0)) count++;
          
       }
       if(count%2==0) return "EVEN";
       return "ODD";
       }
}
