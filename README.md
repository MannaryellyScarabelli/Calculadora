#include <stdio.h>
#include <stdlib.h>

main(void){
	//variável do tipo inteiro.
	int nmr1, nmr2, op;

        //local onde recebe o número que indica qual operação matemática será feita.
 
	printf("Digite 1 para somar, 2 para subtrair, 3 para multiplicar ou 4 oara divivdir: \n");
	scanf("%d", &op);
	
	printf("Digite o primeiro numero:\n");
	scanf("%d", &nmr1);
	
	printf("Digite o segundo numero:\n");
	scanf("%d", &nmr2);
	
	//Etapa onde os números inteiros serão adicionados pelo usuário para realizar o cálculo de acordo com o escolhido anteriormente.
        
	if (op == 1){
		
		nmr1 = nmr1 + nmr2;
		
		printf("o resultado da soma é: %d", nmr1);
	}
	else if(op == 2){
		nmr1 = nmr1 - nmr2;
			
		printf("o resultado da subtracao é: %d", nmr1);
						
	}
	else if(op == 3){
		nmr1 = nmr1*nmr2;
		
		printf("o resultado da multiplicação é: %d", nmr1);
	}
	else if(op == 4){
		nmr1 = nmr1/nmr2;
		
		printf("o resultado da divisão é: %d", nmr1);
	}
		
	return 0;
	 
	}
