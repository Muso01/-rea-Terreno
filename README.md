Algoritmo "terreno"

Var

   largura : real
   altura : real
   metroQuadrado : real
   area : real
   preco : real

Inicio

   escreva("Digite a largura do terreno")
   leia(largura)
   escreva("Digite a altura do terreno")
   Leia(altura)
   escreva("Digite o valor por metros quadrados")
   leia(metroQuadrado)
   
   area <- largura*altura
   preco <- area*metroQuadrado
   
   escreval("area do predio = ", area:8:2)
   escreval("preco por metros quadrado ", preco:8:2)
   
