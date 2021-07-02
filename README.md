# Java_Portfolio_RubenGavidia0x
Java-Oracle_Portfolio_RubenGavidia0x

´´´
/*2.26 (Multiples) Write an
application that reads two
integers, determines whether
the first is a multiple of
the second and prints the
result. [Hint: Use the
remainder operator.]*/

import java.util.Scanner;
public class NumberMultiple {
  public static void main ( String[] args){
    Scanner input = new Scanner(System.in);
    int numero1;
    int numero2;

    System.out.print(" Ingrese numero1: ");
    numero1 = input.nextInt();
    System.out.print(" Ingrese numero2: ");
    numero2 = input.nextInt();

    if (numero1 % numero2 == 0)
      System.out.printf(" El numero %d es multiplo de %d ", numero1, numero2);
    if (numero1 % numero2 != 0)
      System.out.printf(" El numero %d NO es multiplo de %d ", numero1, numero2 );
  }
}
´´´

```
import java.util.Scanner;
public class OddOrEven {
  public static void main ( String[] args){
    Scanner input = new Scanner(System.in);
    int numero1;

    System.out.print(" Ingrese numero1: ");
    numero1 = input.nextInt();

    if (numero1 % 2 == 0)
      System.out.printf("  %d es par ", numero1);
    if (numero1 % 2 != 0)
      System.out.printf(" %d es impar", numero1 );
  }
}
```

```
// SumProductQuotient
import java.util.Scanner;
public class SumProductQuotient{
	public static void main ( String[] args ){
		// crea objeto Scanner para obtener
		//la entrada de la ventana de comandos
		Scanner entrada = new Scanner(System.in);
		int _under_bar_;
		int numero2;
		int suma, product, quotient;

		System.out.print("numero1");
		_under_bar_ = entrada.nextInt();

		System.out.print("numero2");
		numero2 = entrada.nextInt();

		suma=_under_bar_+numero2;
		System.out.printf("suma = %d%n",suma);

    product = _under_bar_*numero2;
		System.out.printf("product = %d%n",product);

    quotient=_under_bar_/numero2;
		System.out.printf("quotient = %d%n",quotient);
	}
}
```

```
import java.util.Scanner;

public class Suma{
	public static void main ( String[] args ){
		// crea objeto Scanner para obtener
		//la entrada de la ventana de comandos
		Scanner entrada = new Scanner(System.in);
		int _under_bar_;
		int numero2;
		int suma;

		System.out.print("numero1");
		_under_bar_ = entrada.nextInt();

		System.out.print("numero2");
		numero2 = entrada.nextInt();

		suma=_under_bar_+numero2;
		System.out.printf("suma = %d",suma);
	}
}
```


```
import java.util.Scanner;
public class Comparacion {
  public static void main ( String[] args){
    Scanner input = new Scanner(System.in);
    int numero1;
    int numero2;

    System.out.print(" Ingrese numero1: ");
    numero1 = input.nextInt();
    System.out.print(" Ingrese numero2: ");
    numero2 = input.nextInt();

    if (numero1 == numero2)
    System.out.printf("  %d == %d%n ", numero1, numero2 );
    if (numero1 != numero2)
    System.out.printf(" %d != %d%n ", numero1, numero2 );
    if (numero1 > numero2)
    System.out.printf("  %d > %d%n ", numero1, numero2 );
    if (numero1 < numero2)
    System.out.printf(" %d < %d%n ", numero1, numero2 );
    if (numero1 >= numero2)
    System.out.printf(" %d >= %d%n ", numero1, numero2 );
    if (numero1 <= numero2)
    System.out.printf(" %d <= %d%n ",  numero1, numero2 );
  }
}
```


