# assignment3

public class example { public static void main (String args[]) { int num=99; int count_of_factors= 0;

for(int i=1;i<=num;i++) { if(num%i==0) {

	count_of_factors= 	count_of_factors+1;
}
} if(count_of_factors%2!=0) System.out.println( "proper square"); else System.out.println( "not a proper square"); }

}
