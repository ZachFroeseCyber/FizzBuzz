//Fizz Buzz Interview Challenge

include <iostream>
 //FIZZBUZZ Exercise

 int main(){

   for ( int i = 1; i <= 100; i++){
    
    //Multiplier of 15
    if (i % 15 == 0){
   
    std::cout << "FizzBuzz\n";
     
     //Multiplier of 5
   } else if (i % 5 == 0){

    std::cout << "Buzz\n";

       //Multiplier of 3
   } else if (i % 3 == 0){

    std::cout << "Fizz\n";

    //Standard i print
   }else{

    std::cout << i << "\n";
   }
   }
 }
