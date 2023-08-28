#include <stdio.h>
float n1, n2, n3, n4, n5;
int main ()
{
 printf ("\n Qual foi a nota do exame I?");
 scanf ("%f", & n1);
 printf ("\n Qual foi a nota do exame II?");
 scanf ("%f", & n2);
 printf ("\n Qual foi a nota do exame III?");
 scanf ("%f", & n3);
 printf ("\n Qual foi a nota do exame IV?");
 scanf ("%f", & n4);
 printf ("\n Qual foi a nota do exame V?");
 scanf ("%f", & n5);
 if (n1>=70 && n2>=70 && n3>=70 && n4>=70 && n5>=70){
    printf ("\n Aprovado A");
    if (n1>=70 && n2>=70 && n4>=70 && n3<70 || n5<70){
        printf ("\n Aprovado B");
        if  (n1>=70 && n2>=70 && n4>=70 && n3>=70 && n5<70){
            printf("\n Aprovado C");
    }

 }
}
    else {
        printf ("Reprovado em todas as outras situacoes");
    }
return 0;
}
