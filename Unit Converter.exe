#include <stdio.h>
int main() {
  char category;
  int tempChoice;
  int currencyChoice;
  int massChoice;
  int userinputF; // User inputted Fahreinheit;
  int userinputC; // User inputted Celsius;
  int userinputUSDtoEuro; // User inputted for USD to EURO;
  int userinputUSDtoRUPEE; // User inputted for USD to RUPEE;
  int userinputUSDtoRMB; // User inputted for USD to RMB;
  int userinputkilogram; // User inputted for kilogram;
  int userinputGram; // User inputted for Gram;
  int userinputTone; // User inputted for Kilogram;
  int fahrenheitToCelcius; // variable that stores the converted F->C;
  int celciusToFahrenheit; // variable that stores the converted C->F;
  float USDtoEURO ; // varaible that stores the converted USD->EURO;
  float USDtoRUPEE; // stores the converted USD->RUPEE;
  float USDtoRMB; // stores the converted USD->RMB;
  float kilogramToGram; // stores the converted kilogram->Gram;
  float ToneToKilogram; // stores the converted Tone->Kilogram;
  
  printf("Welcome to Super Unit Converter! \n");
  printf("Here is a list of conversation to choose from: \n");
  printf("Temperature(T),Currency(C),Mass(M) \n");
  printf("Please enter the letter you want to convert.\n");
  scanf("%c",&category);
  
  if(category == 'T'){
      printf("Welcome to Temperature Converter! \n");
      printf("Here is a list of conversations to choose from: \n");
      printf("Enter 1 for Fahrenheit to Celsius. \n");
      printf("Enter 2 for Celsius to Fahrenheit. \n");
      scanf("%d",&tempChoice);
      if(tempChoice == 1){
          printf("Please enter the Fahrenheit degree: \n");
          scanf("%d",&userinputF);
          fahrenheitToCelcius =  ((userinputF-32) * (5.0/9.0));
          printf("Celcius: %d",fahrenheitToCelcius);
      }
      else if(tempChoice == 2){
        printf("Please enter the Celcius degree: \n");
        scanf("%d",&userinputC);
        celciusToFahrenheit = ((9.0/5.0)*userinputC + 32);
        printf("Fahrenheit: %d",celciusToFahrenheit);
      }
      else
        printf("Please enter the correct choice. \n");
  }
  
  else if(category == 'C') {
      printf("Welcome to Currency Converter! \n");
      printf("Here is a list of conversations to choose from: \n");
      printf("Enter 1 for USD to Euro. \n");
      printf("Enter 2 for USD to RUPEE . \n");
      printf("Enter 3 for USD to RMB. \n");
      scanf("%d",&currencyChoice);
      if(currencyChoice == 1){
          printf("Please enter the USD amount: \n");
          scanf("%d",&userinputUSDtoEuro);
          USDtoEURO = userinputUSDtoEuro * 0.94;
          printf("Euro: %.2f",USDtoEURO); // %.2f = rounds the float to only 2 decimal places;
      }
      else if(currencyChoice == 2){
          printf("Please enter the USD amount: \n");
          scanf("%d",&userinputUSDtoRUPEE);
          USDtoRUPEE = userinputUSDtoRUPEE * 76.66;
          printf("RUPEE: %.2f",USDtoRUPEE);
      }
      else if(currencyChoice == 3) {
        printf("Please enter the USD amount: \n");
        scanf("%d",&userinputUSDtoRMB);
        USDtoRMB = userinputUSDtoRMB * 6.56;
        printf("RMB: %.2f",USDtoRMB);
      }
      else
        printf("Please enter correct choice. \n");
   }
  else if(category == 'M'){
      printf("Welcome to Mass Converter! \n");
      printf("Here is a list of conversations to choose from: \n");
      printf("Enter 1 for Kilogram to Gram. \n");
      printf("Enter 2 for Tone to Kilogram. \n");
      scanf("%d",&massChoice);
      if(massChoice == 1){
          printf("Please enter the kilogram amount: \n");
          scanf("%d",&userinputkilogram);
          kilogramToGram = userinputkilogram *1000;
          printf("Gram: %.0f",kilogramToGram);
      }
      else if(massChoice == 2) {
          printf("Please enter the Tone amount: \n");
          scanf("%d",&userinputTone);
          ToneToKilogram = userinputTone *1000;
          printf("Kilogram: %.0f",ToneToKilogram);
      }
      else 
        printf("Please enter the correct choice. \n");
   }
  return 0;
}
