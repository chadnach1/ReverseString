public class GitReverseString {
    
    public static void main(String[] args) {
        
        if (s == null) break;
        
        // Take in the string
        String s = args[0];
        
        // Create a return string
        String smod = "";
        
        // Create a character array
        char[] c = new char[s.length()];
       
        
        // Break down string into character array
        for (int i = 0; i < s.length(); i++) {
             c[s.length() - 1 - i] = s.charAt(i);
        }
        
       for (int i = 0; i < s.length(); i++) {
             smod += c[i];
        }
        
       System.out.println(smod);
                                               
    }
}
