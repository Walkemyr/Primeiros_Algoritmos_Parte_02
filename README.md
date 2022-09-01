<h1 align="center">
📄<br> Meus Algoritmos Iniciais... 
</h1>

<h1 align="center">
 <img align="center" alt="Walkemyr-pic" height="640" style="border-radius:640px;" 
 src="https://cdn.discordapp.com/attachments/712667373060227102/1014949367515467826/Sem_Titulo-1.png">
 
 ##
 
 </div>

<h1 align="center">
📄<br> Segunda Atividade com Pascalzin... 
</h1>

##

## ☑️ Primeiro Algoritmo PascalZim
 
Program PzaoTemp09 ; var c, f : real;
Begin

  //   Limpar Tela
  clrscr;
  
  writeln ('<<<Conversor de temperatura>>>');
  // recebe a temperatura
  
  write ('Digite a temperatura em Celsius : ');
  // ler a temperatura
  
  readln (c);
  // faz a conversao
  f :=(9 * c + 160)/5;
  // mostra a temperatura convertida
  
  writeln ('Temperatura convertida : ',f);
  
  write ('Tecle "Enter" para sair.');
  
  //   Solicita a leitura de um caracter do teclado. Pode ser utilizado como um comando ou como uma função.
  readkey;
End.

 ## ☑️ Segundo Algoritmo PascalZim
 
 Program PzaoTemp10 ; var f, c : real;
Begin

     writeln ('<<<Conversor de temperatura>>>');
		 write ('Digite a temperatura em fahrenhelt : ');
     
     read (f);
     c :=(f-32) * (5/9);
     
     writeln ('Temperatura convertida : ',c);
     write ('Tecle "Enter" para sair.');
     
   readln;
End.
 
## ☑️ Terceiro Algoritmo PascalZim

Program Pzao11Volume ; var altura, raio, volume : real;
Begin
  //   Limpar Tela
  clrscr;
  
  // recebe a altura da lata
  write ('Informe a altura da lata: ');
  
  // ler altura
  readln(altura);
  
  // recebe o raio da circunferencia da lata
  write ('iforme o raio da circunferencia da lata: ');
  
  // ler raio
  readln(raio);
  
  // faz o calculo do volume
  volume := 3.14 * sqr(raio)* altura;
  
  // mostra o volume da lata
  writeln ('O volume da lata é: ',volume :5:2);
  
  write ('Tecle "Enter" para sair.');
  readln;
  
End.

 ## ☑️ Quarto Algoritmo PascalZim
 
 program Pzao12Combustivel ; const km_litro = 12; var tempo, velmedia, distancia, consumo : real; 
begin

   writeln ('<<<Calculo gasto de Combustivel>>>');
   
   write ('Informe o tempo gasto na viagem em horas :');
   readln (tempo);
  
   write ('Informe a velocidade media em KM/H :');
   readln (velmedia);
   
   distancia := tempo * velmedia;
   consumo := distancia / km_litro;
   
   writeln ('O consumo foi de: ', consumo :0:2,' litros.');
   
   Write('Tecle "Entrer" para sair.');
    Readln;
end.

 ## ☑️ Quinto Algoritmo PascalZim

// Ler 2 valores para as variaveis A e B.
// Efetuar a troca dos valores de forma que a var. A passe a possuir o valor da B.

Program Pzao13Variaveis ; var a, b, c : integer;
Begin

   writeln ('<<<Troca de Variaveis>>>');
   
   write ('Informe o valor da variavel A: ', a);
   read (a);
   
   write ('Informe o valor da variavel B: ', b);
   read (b);
   
   c:=(a);
   a:=(b);
   b:=(c);
   
   writeln ('O valor da variavel B trocado é: ',b);
   writeln (' O valor da variavel A trocado é: ',a);
   
   write ('Tecle "Enter" para sair.');
   readln;
   
End.

## ☑️ Sexto Algoritmo PascalZim

program Pzao14Prestacao; var valor, prestacao, taxa, tempo : real;
begin

  write ('Informe o valor da prestação :');
  readln (valor);
  
  write ('Informe a taxa de juros :');
  readln (taxa);
  
  write ('Informe por quanto tempo foi feito :');
  readln (tempo);
  
  prestacao:= valor + (valor * (taxa / 100) * tempo);
  
  writeln ('prestacao >>>', prestacao :10:0);
  
  Write('Tecle "Entrer" para sair.');
    Readln;
end.

## ☑️ Setimo Algoritmo PascalZim

program Pzao15Multiplicacao; var a, b, c, d : real;
begin

  writeln ('Digite quatro valores a serem somados e multiplicados entre si :');
  
  write ('Digite o valor de A: ');
  readln (a);
  
  write ('Digite o valor de B: ');
  readln (b);
  
  write ('Digite o valor de C: ');
  readln (c);
  
  write ('Digite o valor de D: ');
  readln (d);
  
  writeln ('A soma de A + B é:',(a+b):0:2);
  writeln ('A multiplicacao de A * B é: ',(a*b):0:2);
  
  writeln ('A soma de A + C é: ',(a+c):0:2);
  writeln ('A multiplicacao de A * C é: ',(a*c):0:2);
  
  writeln ('A soma de A + D é:',(a+d):0:2);
  writeln ('A multiplicacao de A * D é: ',(a*d):0:2);
  
  writeln ('A soma de B + C é: ',(b+c):0:2);
  writeln ('A multiplicacao de B * C é: ',(b*c):0:2);
  
  writeln ('A soma de C + D é: ',(c+d):0:2);
  writeln ('A multiplicacao de C * D é: ',(c*d):0:2);
  
  Write('Tecle "Entrer" para sair.');
    Readln;
End.

## ☑️ Oitavo Algoritmo PascalZim

program Pzao16Variaveis; var a, b, c : integer;
begin
  write ('Informe o valor da Variavel A: ');
  readln (a);
  
  write ('Informe o valor da Variavel B: ');
  readln (b);
  
 c:= a;
 a:= b;
 b:= c;
  
  writeln ('Este é o valor de A : ',a);
  writeln ('Este é o valor de B : ',b);
  
  Write('Tecle "Entrer" para sair.');
    Readln;
end.

## ☑️ Nono  Algoritmo PascalZim

program Pzao17Quadrado; var numero, quadrado : integer;
begin
  write ('Informe um numero: ');
  Readln (numero);
  
  quadrado:= numero * numero;
  
  Writeln ('Esta é o quadrado deste numero: ',quadrado); 
  
  Write('Tecle "Entrer" para sair.');
  Readln;
end.

## ☑️ Decimo  Algoritmo PascalZim

program Pzao18Consumo; var km_inic, km_fin, litros, consumoMedio : real;
begin
  write ('Informe a Kilometragem Inicial: ');
  readln (km_inic);
  
  write ('Informe a Kilometragem Final: ');
  readln (km_fin);
  
  write ('Informe a quantidade de Litros Abastecido: ');
  readln (litros);
  
  consumoMedio := (km_fin - km_inic) / litros;
  
  writeln (' O Consumo Medio deste veiculo foi de',consumoMedio :5:0, ' KM/L');
  
  Write('Tecle "Entrer" para sair.');
    Readln;
  
  
end.

## ☑️ Decimo Primeiro Algoritmo PascalZim

program Pzao19VelMedia; var distancia, tempo, kmh : real;
begin
  write ('Informe a distancia em KM: ');
  readln (distancia);
  
  write ('Informe o tempo gasto em Horas: ');
  readln (tempo);
  
  kmh := distancia / tempo;
  
  writeln ('A velocidade media em KM foi de: ',kmh :5:0, ' KM/Hora');
end.


</div>

##
