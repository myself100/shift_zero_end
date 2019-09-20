# shift_zero_end

package elclipse;
import java.util.*;
public class Zero_End {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		int a[]= {4 ,6 ,1, 0, 0, 8 ,0,12};
		int count=0;
		for(int i=0;i<a.length;i++) {
			if(a[i]!=0) {
				a[count]=a[i];
				count++;}
		}
		while(count <a.length) {
			a[count++]=0;
		}
		System.out.print(Arrays.toString(a));
	}

}

///time complexity o(n^2)
