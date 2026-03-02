public class UseCase3PalindromeCheckerApp {



&nbsp;   public static void main(String\[] args) {



&nbsp;       String original = "level";

&nbsp;       String reversed = "";



&nbsp;       for(int i = original.length() - 1; i >= 0; i--) {

&nbsp;           reversed = reversed + original.charAt(i);

&nbsp;       }



&nbsp;       if(original.equals(reversed)) {

&nbsp;           System.out.println(original + " is a Palindrome");

&nbsp;       } else {

&nbsp;           System.out.println(original + " is not a Palindrome");

&nbsp;       }

&nbsp;   }

}

