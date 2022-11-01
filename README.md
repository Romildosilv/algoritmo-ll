# algoritmo-ll
Porcentagem //

#include <stdio.h>
#include <math.h>
double preco,total,desc;
int qtd;
 
int main(){
	
printf ("digite a quantida:");
scanf ("%d",&qtd);
printf ("\ndigite o preço:");
scanf ("%lf",&preco);
if(preco>=0 && qtd>=0){
 total=qtd*preco;
     if (qtd<=5) {
	
 	desc=total*0.02;
	 }
	 else if (qtd>=6 && qtd<=9){
		desc=total*0.03;
	 }
     else if (qtd>=9){
 	desc=total*0.05;
     }
     total=total-desc;
		printf ("\no total e R$%.2lf\n",total);

}
 
else{

printf("dados invalido");	}

	return 0;
}

