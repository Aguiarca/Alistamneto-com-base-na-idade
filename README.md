# Alistamneto-com-base-na-idade
Programa que mostra se o alistamento será obrigatório ou não, com base na idade digitada.


Scanner leia = new Scanner(System.in);
int idade;
double altura;

System.out.print("Insira a idade do cidadao:");
idade = leia.nextInt();

System.out.print("Insira a altura do cidadao:");
altura = leia.nextDouble();

if((idade>=18)&&(altura>=1.70))
{
System.out.print("Deu ruim, vai pro exercito");
}
else {
 System.out.print("Ufa, pegou dispensa garoto!");  
}
