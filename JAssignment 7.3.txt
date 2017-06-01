
public class SubstringAlone {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		String str="Hi How are you";
		String str1="Howr";
		int  secondSize=str1.length();
		for(int i=0;i<str.length();i++)
		{
			int j=0;
			for(int k=0;j<secondSize;j++)
			{
				if(str.charAt(i+j)==str1.charAt(j))
				{
				}
				else
					break;
			}
			if(j==secondSize)
			{
				System.out.println("str1 present in str");
				return;
			}
		}
		System.out.println("str1 not present in str");
	}

}
