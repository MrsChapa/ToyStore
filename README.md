# Toy Class (Part 1)
Lab Description :   Create a Toy class that stores a Toy name and a count and how many of that toy exist.   Use the sample runner code below to help you create the class and define the methods.


Sample Runner Code : 
```
Toy t = new Toy( "sorry" );
System.out.println( t.getCount() );
System.out.println( t );
System.out.println( t.getName() );

Toy s = new Toy( "ji goe" );
System.out.println(s.getCount() );
s.setCount( 5 );
System.out.println(s.getCount() );
System.out.println( s );
```


Sample Output : 
```
1
sorry 1
sorry
1
5
```



# Toy Store Class (Part 2)
Lab Description :   Create a program that will store a list of Toys and keep track of how many times a particular toy occurs.

BONUS CHALLENGE  -   Write a method to return the Toy that occurs in the list most frequent and another method to sort the toys by count.


Sample Runner Code : 
```
ToyStore sto = new ToyStore();
System.out.println( sto );

String[] s;
s = "sorry bat sorry sorry sorry train train teddy teddy ball ball".split(" ");                 

sto.loadToys( s );
System.out.println( sto );	
System.out.println( "max == " + sto.getMostFrequentToy() );	
System.out.println( sto.getThatToy( "sorry" ) );
```

Sample Output : 
```
[]
[sorry 4, bat 1, train 2, teddy 2, ball 2]
max == sorry
sorry 4
```
