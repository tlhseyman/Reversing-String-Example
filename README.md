# Reversing-String-Example
Displaying a string as a reversed

package sample;

public class ReversingString1 {
    public static void main(String[] args)
    {
        String toBeReversed = "google";
        //String assignedString = "";
        for(int i=toBeReversed.length()-1; i>=0; i--){
            System.out.print(toBeReversed.charAt(i));
        }
    }
}
// in this code, defined string printed as reversed, "elgoog".
