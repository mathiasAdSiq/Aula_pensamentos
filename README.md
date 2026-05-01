1) Identifique as entradas e saídas do sistema :

As Entradas são :  
   O LDR que depende do  Ambiente claro, a luz média e o ambiente escuro, 
   O botão1 , o botão2, eo botão3.

As Saidas são:
  O LED RGB Verde, Amarelo e Vermelho. 


2)Apresente todos os componentes do sistema e para que eles servem:

  LDR : Ele serve para identificar o nível de iluminação de um ambiente.
  ele sera usado para identificar se o ambiente está no nivel de iluminação claro, médio e escuro.
  
  LED RGB: Ele serve para mostrar ao usuario o nível de iluminação através da coloração do LED , Verde para o nível Claro 
  Amarelo para o nível Médio e Vermelho para o nível escuro.
  
  BOTÂO: 

   botão 1 : Ele ativa o modo automáico, liga o LDR ao LED RGB, todo input que o LDR receber será enviado ao LED RGB.

   botâo 2 : Ele ativa o modo manual de alerta, desliga o LDR e o LED RGB ficara Vermelho.

   botão 3 : Ele Desliga todo o sistema, apagando todos os LEDs e o LDR.

3)Apresente as regras de funcionamento a serem implementadas: 
   
   Primeiramente irei colocar a entrada, Ler o LDR 
       Verificar se o nível de iluminação é Alto, Médio ou Baixo.
    A saida é a cor do LED RGB:
      Se o nível de iluminação é Alto :
        Ligar o LED RGB na cor Verde.
      Se o nível de iluminação é Médio : 
        Ligar o LED RGB na cor Amarelo.
      Se o nível de iluminação é Baixo :
        Ligar o LED RGB Vermelho.
    Entrada botões   
      ler botão 1 :
        Se botão 1 for pressionado:
          Ativar modo automatico, em que o LED RGB irá responder os inputs do LRN.
      Ler botão 2 :  
         Se botão 2 for pressionado :
           Ativar modo alerta, em que o LED RGB irá ficar somente com a coloração vermelha, e não respondera a nehum input do LRN
      Ler botão 3 :
      Se botão 3 for pressionado :
        Desligar todo o sistema, O LED RGB será apagado  e o LDR também.
          
4)Explique como você utilizaria estruturas if para controlar o sistema:

  If a iluminação for clara o Led RGB irá ficar Verde,
  If a iluminação for média o Led RGB irá ficar Amarelo,
  If a iluminação for escura o Led RGB irá ficar Vermelho,

  If o botão 1 for pressionado o Led RGB irá responder ao LRD e varia-a a coloroção de acordo com o ambiente.
  if o botão 2 for pressionado o Led RGB irá ficar com a coloração Vermelha e não respodera a nenhum input do LDR.
  if o botão 3 for pressionado o Led RGB será desligado, apagando todos os LEDs e o LDR.
