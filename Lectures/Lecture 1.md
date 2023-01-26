# Lecture 1

## Notes

```dart
void main() {
  print('Hiii');
  
  var number = 42;
  print(number);
  
  int number2 = 33;
  print(number2);
  
  // this is a comment
  
  /*
   * Multi-line 
   * comment
   * */
  
  print("My number is " + number2.toString() + ".");
  print("My number is ${number2}.");
  
  
  late int myInt;
  myInt = 4;
  
  print(myInt);
  
  final name = 'Bob';
  print(name);
  
  //name = 'Alice';
  
  const name2 = 'George';
  print(name2);
  
//   var list = const [99, 88];
//   list[0] = 55;
  
//   print(list);
  
  var foo = const [];
  foo = [1, 2, 3];
  
  foo[0] = 123;
  //foo = 'james';
  
  print(foo);
  
  const Object i = 3; 
  const list = [i as int];
}
```