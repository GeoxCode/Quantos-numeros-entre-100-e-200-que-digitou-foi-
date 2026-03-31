# Quantos-numeros-entre-100-e-200-que-digitou-foi-
//uma questao simples no c, usando while e if

#include<stdio.h>
#include<locale.h>

int main(){
setlocale (LC_ALL, "portuguese");
int n;
int c = 0;

while(n != 0){
printf(" Digite um numero: \n");
scanf(" %d",&n);

if(n >= 100 && n <= 200){
c++;}}
printf(" Quantos numeros entre 100 e 200 que digitou foi %d",c);

return 0;}
