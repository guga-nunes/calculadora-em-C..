# calculadora-em-C..
cauculadora em C com menu de seleção, e com capacidade de -subitrair, +somar, \dividir, *multiplicar, ^elevar, e fazer mídia aritimetrica

#include <stdio.h> //biblioteca
#include <stdlib.h> //biblioteca



void soma(){ //funcao de soma
    float valor1, valor2, result; //declaração de variaveis parciais
    printf("\nDigite o 1 valor: "); //pede um valor
    scanf ("%f", &valor1); //armazena o valor
    printf("Digite o 2 valor: "); //pede outro valor
    scanf ("%f", &valor2); //armazena o valor em um float
    result = valor1 + valor2; //soma valor1 com valor 2 e coloca em result
    printf("\nResultado: %.2f\n\n ", result); //mostra o resultado 2.36
    system ("pause"); //pausa pra dar tempo de ver
    system("cls"); //limpa a tela apos precinado enter
    menu(); //chama o menu novamente
}

void subtrai(){ //funcao subtração
    float valor1, valor2, result; 
    printf("\ndigite o 1 valor");
    scanf("%F",&valor1);
    printf("\ndigite o 2 valor");
    scanf ("%f",&valor2);
    result= valor1 - valor2;
    printf("\nResultado: %.2f\n\n",result);
    system ("pause");
    system("cls");
    menu();}


void divide(){ //funcao divide
    float valor1, valor2, result;
    printf("\nDigite o 1 valor: ");
    scanf ("%f", &valor1);
    printf("Digite o 2 valor: ");
    scanf ("%f", &valor2);
    result = valor1 / valor2;
    printf("\nResultado: %.2f\n\n ", result);
    system ("pause");
    system("cls");
    menu();
}
	
void multiplica(){ //funcao multiplica
    float valor1, valor2, result;
    printf("\nDigite o 1 valor: ");
    scanf ("%f", &valor1);
    printf("Digite o 2 valor: ");
    scanf ("%f", &valor2);
    result = valor1 * valor2;
    printf("\nResultado: %.2f\n\n ", result);
    system ("pause");
    system("cls");
    menu();
}

void quadrado(){
	float valor1, result;
	printf("\nEscola o valor");
	scanf("%f", &valor1);
	result = valor1 * valor1;
	printf("\nResultadp: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
	
}

void cubo(){
	float valor1, result;
	printf("\nEscola o valor");
	scanf("%f", &valor1);
	result = valor1 * valor1 * valor1;
	printf("\nResultadp: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
	
}

void potencia4(){
	float valor1, result;
	printf("\nEscola o valor");
	scanf("%f", &valor1);
	result = valor1 * valor1 * valor1 * valor1;
	printf("\nResultadp: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
	
}

void potencia5(){
	float valor1, result;
	printf("\nEscola o valor");
	scanf("%f", &valor1);
	result = valor1 * valor1 * valor1 * valor1 * valor1;
	printf("\nResultadp: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
	
}

void potencia6(){
	float valor1, result;
	printf("\nEscola o valor");
	scanf("%f", &valor1);
	result = valor1 * valor1 * valor1 * valor1 * valor1 * valor1;
	printf("\nResultadp: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
	
}

void potencia7(){
	float valor1, result;
	printf("\nEscola o valor");
	scanf("%f", &valor1);
	result = valor1 * valor1 * valor1 * valor1 * valor1 * valor1 * valor1;
	printf("\nResultadp: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
	
}

void potencia8(){
	float valor1, result;
	printf("\nEscola o valor");
	scanf("%f", &valor1);
	result = valor1 * valor1 * valor1 * valor1 * valor1 * valor1 * valor1 * valor1;
	printf("\nResultadp: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
	
}

void potencia9(){
	float valor1, result;
	printf("\nEscola o valor");
	scanf("%f", &valor1);
	result = valor1 * valor1 * valor1 * valor1 * valor1 * valor1 * valor1 * valor1 * valor1;
	printf("\nResultadp: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
	
}

void potencia10(){
	float valor1, result;
	printf("\nEscola o valor");
	scanf("%f", &valor1);
	result = valor1 * valor1 * valor1 * valor1 * valor1 * valor1 * valor1 * valor1 * valor1 * valor1;
	printf("\nResultadp: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
	
}


void media()
{
	float valor1, valor2, result;
	printf("\nEscolha o 1 valor"); 
	scanf("%f", &valor1);
	printf("\nEscolha o 2 valor");
	scanf("%f", &valor2);
	result = (valor1 + valor2) / 2;
	printf("\nResultado: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
}


void media2(){
	float valor1, valor2, valor3, result;
	printf("\nEscolha o 1 valor"); 
	scanf("%f", &valor1);
	printf("\nEscolha o 2 valor");
	scanf("%f", &valor2);
	printf("\nEscolha o 3 valor"); 
	scanf("%f", &valor3);
	result = (valor1 + valor2 + valor3) / 3;
	printf("\nResultado: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
}

void media3(){
	float valor1, valor2, valor3, valor4, result;
	printf("\nEscolha o 1 valor"); 
	scanf("%f", &valor1);
	printf("\nEscolha o 2 valor");
	scanf("%f", &valor2);
	printf("\nEscolha o 3 valor"); 
	scanf("%f", &valor3);
	printf("\nEscolha o 4 valor"); 
	scanf("%f", &valor4);
	result = (valor1 + valor2 + valor3 + valor4) / 4;
	printf("\nResultado: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
}

void media4(){
	float valor1, valor2, valor3, valor4, valor5, result;
	printf("\nEscolha o 1 valor"); 
	scanf("%f", &valor1);
	printf("\nEscolha o 2 valor");
	scanf("%f", &valor2);
	printf("\nEscolha o 3 valor"); 
	scanf("%f", &valor3);
	printf("\nEscolha o 4 valor"); 
	scanf("%f", &valor4);
	printf("\nEscolha o 5 valor"); 
	scanf("%f", &valor5);
	result = (valor1 + valor2 + valor3 + valor4 + valor5) / 5;
	printf("\nResultado: %.2f\n\n", result);
	system("pause");
	system("cls");
	menu();
}

void menuelevado(){
	int escolhaE;
	printf("\t\tEscolha a potencia\n\n");
	
	printf("\t2 Ao quadrado\n");
	printf("\t3 Ao cubo\n");
	printf("\t4 A 4 potencia\n");
	printf("\t5 A 5 potencia\n");
	printf("\t6 A sexta potencia\n");
	printf("\t7 A setima potencia\n");
	printf("\t8 A oitava potencia\n");
	printf("\t9 A nona potencia\n");
	printf("\t10 A decima potencia\n");
	printf("Operacao: "); //msg na tela
    scanf ("%d", &escolhaE); //armazena o int digitado em escolha
	
	switch (escolhaE){
		
		case 2:
			quadrado();
		break;
		
		case 3:
			cubo();
		break;
		
		case 4:
			potencia4();
		break;
		
		case 5:
			potencia5();
		break;
		
		case 6:
			potencia6();
		break;
		
		case 7:
			potencia7();
		break;
		
		case 8:
			potencia8();
		break;
		
		case 9:
			potencia9();
		break;
		
		case 10:
			potencia10();
		break;
	}
	
	system("pause");
	system("cls");
	menu();
	
}


void menumedias(){
	int escolhaM;
	printf("\t\tEscolha a quantidade de números\n\n");
	
	printf("\t2 2 numeros\n");
	printf("\t3 3 numeros\n");
	printf("\t4 4 numeros\n");
	printf("\t5 5 numeros\n");
	printf("Operacao: "); //msg na tela
    scanf ("%d", &escolhaM); //armazena o int digitado em escolha
	switch (escolhaM){
		case 2:
			media();
		break;
		
		case 3:
			media2();
		break;
		
		case 4:
			media3();
		break;
		
		case 5:
			media4();
	}
	
	system("pause");
	system("cls");
	menu();

}

void menu(){ //menu
    int escolha; //variavel inteira

    printf("\t\tBem vindo Familia Nunes\n\n"); //imprime msg na tela \n = salta linha

    printf("Selecione uma operacao matematica:\n"); // msg na tela
    printf("\t1- Adicao\n");
    printf("\t2- Subtracao\n");
    printf("\t3- Divisao\n");
    printf("\t4- Multiplicacao\n");
    printf("\t5- elevado \n");
    printf("\t6- Media aritimetica\n");
    printf("\t7- sair\n");
    printf("Operacao: "); //msg na tela
    scanf ("%d", &escolha); //armazena o int digitado em escolha

    switch (escolha){ //funcao de selecao de escolha do ,menu
        case 1: //caso digitado 1 execute isto:
            soma(); //funcao soma feita anteriomente acima
        break; //termina a funcao de soma

        case 2:
            subtrai();
        break;

        case 3:
            divide();
        break;

        case 4:
            multiplica();
            break;
            
        case 5:
        	menuelevado();
        	break;
        	
        case 6:
        	menumedias();
        	break;

        case 7: //caso selecionado 5 executa:
            system("exit"); // fechar o programa
            printf("\nFinalizando...\n\n"); //da uma msg na tela
        break; // termina a funcao 5 seleciojada

        default: // caso nao se digite nenhum do case disponoveis execute
            printf("\nComando invalido, tente novamente!\n\n"); //msg
            system ("pause"); //pausa
            system ("cls"); //limpa
            menu(); //volta pro menu inicial
            break; //termina funcao
    }
}
		
int main()
{ 
    menu(); //chama o menu
    system("pause"); //pausa
    return 0;
}


	
