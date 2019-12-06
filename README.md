import java.util.Scanner;

public class hi5 {
	public static void main(String[] args){
	int[] s=new int[5];
	int sum=0;
	
	
	Scanner scan=new Scanner(System.in);
	for(int i=0; i<s.length; i++){
	System.out.print("성적을 입력하세요:  " );
	s[i]= scan.nextInt();
	sum += s[i];}
	
	int c = sum/5;
	System.out.println("합계:  " + sum );
	System.out.print("평균:  " + c );	
		
	}

}
