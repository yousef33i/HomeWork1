# lec19
import javax.swing.JOptionPane;
public class lec19 {

	public static void main(String[] args) {
		int name[]= new int[5];
		for(int i=0;i<5;i++)
		 name[i]=Integer.parseInt(JOptionPane.showInputDialog("Enter your number"));
		for(int i=0;i<5;i++) 
			if(name[i]>=60) 
				System.out.println("Grade :" + name[i]);
			
	}
	}





	






