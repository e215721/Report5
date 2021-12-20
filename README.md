package jp.ac.uryukyu.ie.e215721;

public class Main {
    //public static void main(String[] args)    lever1
    public static void main(String[] args) throws NullPointerException {
        String str = null;
            //System.out.println(str.length()); lever1
        try {
            System.out.println(str.length());
        } catch (NullPointerException e) {
            System.out.println("Error: NullPointerException");
            System.out.println(e.getMessage());
        }
        
        
    }
}
