# algoritimo

#include <iostream> 
 

/*02) Faça uma rotina que receba dois números e calcule a soma, a subtração, a multiplicação e 
 

a divisão desses números. O cálculo só deve ser feito se o primeiro número for maior ou igual 
 

ao segundo, senão retorne um erro. Faça um programa para testar a rotina.*/ 
 

using namespace std; 
 

  float soma(float n1, float n2) 
 

  { 
 

      //METODO USANDO VARIAVEL PARA GUARDAR O VALOR 
 

     /*float resultadoSoma; 
 

     resultadoSoma = n1 + n2; 
 

     return resultadoSoma; */ 
 

      //METODO DIRETO 
 

     /*   return n1 + n2 ;              */ 
 

     return n1 + n2; 
 

 } 

   float divisao(float n1, float n2) 
 

  { 

     return n1/n2; 
 

 } 
 

   float multiplicacao(float n1, float n2) 
 

  { 
 

 

     return n1*n2; 
 

 } 
 

   float subtracao(float n1, float n2) 
 

  { 
 

     return n1-n2; 
 

 } 
 

int main() 
 

{ 
 

  int num1, num2, somatoria, divido, multi, sub; 
 

  cout << "digite o primeiro numero" << endl; 
 

  cin >> num1; 
 
 

  cout << "digite o segundo numero" << endl; 
 

  cin >> num2; 
 
 

 if (num1>=num2) 
 

    { 
 

    somatoria = soma(num1,num2); 
 

    divido = divisao(num1,num2); 
 

    multi = multiplicacao (num1, num2); 
 

    sub = subtracao (num1, num2); 
 

    cout << "soma = " << somatoria << endl; 
 

    cout << "divisao = " <<divido << endl; 
 

    cout << "multiplicacao = " << multi << endl; 
 

    cout << "substracao = " << sub << endl; 
 

    } 
 

 else 
 

    { 
 

    cout<<"ERROR404"<< endl; 
 
 

    } 
 

    return 0; 
 

1semestre
