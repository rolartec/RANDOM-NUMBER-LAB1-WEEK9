RANDOM-NUMBER-LAB1-WEEK9
========================

LAB1 WEEK9



public class RandomNumber 
{
	public int GetALowHighNumber(int low, int High)
	{
		int computerNumber;

		computerNumber = (low + (int)(Math.random() *High));
		return computerNumber;
	}
	public int GetAHighNumber(int High)
	{
		int computerNumber;

		computerNumber = 0 + (int)(Math.random() *High);
		return computerNumber;
	}
	public int GetANumber_Between_1_and_10()	
	{		
		int computerNumber;
		computerNumber = 0 + (int)(Math.random() *10);		
	return computerNumber;	
	}
}
