public class TestClass5026211113 {

	public static void main(String[] args) {
		ComputeMethods5026211113 cm = new ComputeMethods5026211113();
		
		//celcius
		double celcius = cm.fToc(86);
		System.out.println("86 F = "+ celcius +" C");

		//hypotenuse
		double hypotenuse = cm.hypotenuse (6,10);
		System.out.println("Hypotenuse = " + hypotenuse);

		//rolldice
		int rolldice = cm.roll();
		System.out.println("Roll 2 Dice result = " + rolldice);
	}
}
