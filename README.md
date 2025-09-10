# OOPs---Assignment-2
package nullpointer;
public class NullPointerException {
    public static void main(String[] args) {
        try {
            String str = null;
            System.out.println(str.length());
        } catch (java.lang.NullPointerException e)
        { 
            System.out.println("Caught a NullPointerException!");
            System.out.println("Exception message: " + e.getMessage());
        }
    }
}
