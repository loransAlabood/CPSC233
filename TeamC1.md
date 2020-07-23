public class TeamC1 {

	public static void main(String[] args) {
		printFibonacciSeries(10);
	}

	public static void printFibonacciSeries(int count) {
		int a = 0;
		int b = 1;
		int c = 1;
		for (int i = 1; i <= count; i++) {
			System.out.print(a + ", ");
			a = b;
			b = c;
			c = a + b;
		}

		public static void printFibonacciSeries(int count) {
			int a = 0;
			int b = 1;
			int c = 1;
			for (int i = 1; i <= count; i++) {
				System.out.print(a + ", ");
				a = b;
				b = c;
				c = a + b;
			}

	}
}
