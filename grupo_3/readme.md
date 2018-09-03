# PROJETO HIDROELÉTRICO

  - Ariana Alves Barbosa Flores - 13/0043036
  - Felipe Tomé de Sousa Diniz - 13/0109827
  - Roger Roel Awadraj Anijs - 18/0142038
  

### Projeto do Aproveitamento

O projeto do aproveitamento consistirá na realização e apresentação de cálculos oriundos de dados de um dado aproveitamento hidrelétrico visando a instalação de uma usina hidrelétrica. Cada item deverá ser respondido neste documento do repositório, usando a ferramenta de edição.

  - Cada grupo terá em sua pasta do repositório um conjunto de dados de vazão que deverá ser usado ao longo deste e dos demais projetos quando necessário;
  
  - Modelamento do aproveitamento hidrelétrico. Cada grupo deverá mostrar como ficará o sistema hidromecânico equivalente através do cálculo da energia hidráulica média disponível e do trabalho específico. O grupo 3 deverá usar a  altura de cota **de 10 m** para seu aproveitamento hidrelétrico:

	Energia Hidráulica média disponível:


O aproveitamento da energia potencial, por meio de quedas é determinada como energia hidráulica. A energia hidráulica média disponível, transformada em trabalho, é dada por:


E_1-E_2=(p_1-p_2)/γ+(〖u_1〗^2-〖u_2〗^2)/2g+(z_1-z_2 )

Onde:

	p é a massa específica da água
	γ é o peso específico da água
	u é a velocidade
	z é a altura de elevação
	g é a aceleração da gravidade

Fundamentado nas notas de aula, a energia específica terá seu valor máximo quando as condições a seguir ocorrerem:

p_2/γ=p_1/γ;u_2=0;z_2=0

Assim, quanto mais próximo do ponto 2 estiver o nível de jusante maior será seu aproveitamento hidrelétrico, assumindo seu valor máximo. Considerando que a velocidade no ponto 1 é muito pequena e influencia muito pouco no cálculo da energia, e assumindo a altura de cota de 10 metros, a energia hidráulica média será:

E_1-E_2=z_1

E_1-E_2=10m

Essa energia parte da modelagem do sistema hidromecânico equivalente, realizada a partir dos dados do reservatório.

	Trabalho específico:


Com o valor de queda líquida de aproveitamento (H_l) calculado no tópico a seguir, obtem-se o trabalho específico do sistema hidromecânico:


Y=g∙Hl

Y=9,81∙9,5=93,195 J⁄kg


  - Determinação da queda do aproveitamento: O grupo 3 deverá considerar uma perda de **0,5 m**, onde cada grupo deverá especificar se a central será de baixa ou de alta queda;
  
A queda disponível é definida como a queda máxima (Hb) subtraída pela perda de carga do sistema (hp), como visto na equação abaixo:

Hl=Hb-Hp

Hl= 10-0.5 = 9.5m

Baseado na potência máxima P_tmax=20.984,71kW, pela tabela da página 15 da apostila pode-se dizer que a usina é de baixa queda, pois para classificação de PCH sua potência está entre 1000 kW e 30000 kW, e sua altura é inferior a 25 metros.
       
  - Determinação da vazão média de longo tempo baseado nos dados de vazão dados a cada grupo. Cada grupo deverá mostrar como fez este cálculo e as hipóteses adotadas;
  
  Para determinar a vazão média ao longo do tempo, em m³/s, a média foi baseada nos dados de vazão de todos os dias referentes aos dados
disponibilizados, desde 1931 a 2013. Manipulados com a ferramenta Excel onde foi tirada a média de todos os dias e o valor obtido foi de:

Q = 225,170 m^3⁄s

  
  - Cálculo da potência hidráulica máxima teórica média e da energia máxima teórica média;
  
  a.	Potência Hidráulica Teórica Média
  
  Com os dados de vazão média ao longo do tempo, e queda líquida(H_l) calculados anteriormente é possível definir a potência hidráulica máxima teórica(P_tmax) como:

P_tmax=g∙Q∙Hl

P_tmax=9,81∙225,170∙9,5

P_tmax = 20.984,71kW

   b.	Energia Máxima Teórica Média

A energia hidráulica máxima teórica, com base numa estimativa de tempo(t) de retorno de 24h é:

E_tmax=g∙Q∙Hl∙t

E_tmax=9,81∙225,170∙9,5∙24

E_tmax = 503.632,22kWh

  
  - Análise dos dados de vazão e energia máxima teórica média;
  
  A vazão deste projeto é alta, que consequentemente acarreta uma grande produção de energia caso funcione durante 24 horas.
  
  - Escolha do tipo de central e o arranjo utilizado;
  
  Como referenciado nas notas de aula, de acordo com Resolução 652 da ANEEL, a classificação para enquadramento de aproveitamento energético são baseadas na potência e altura de queda. Visto que possui uma potência entre 1000kW e 30MW, é classificadao como Pequena Central Hidrelétrica(PCH).
  O arranjo será fio d'água
  
  - Estimativa da potência instalada;
 
 Assumiremos a potência máxima com eficiência de uma turbina kaplan de 80%:
 P_installed = η∙P_tmax

P_installed = 0,8∙20.984,71

P_installed = 16.787,768kW

Assumiremos a usina com produção para auto consumo.

  
  - Desenho esquemático do sistema hidromecânico equivalente;
  Enviado no documento por e-mail.
  
  - Cada grupo deverá preencher uma ART (Anotação de Responsabilidade Técnica) para:

    - **Cargo e Função**, designando a tarefa de cada membro do grupo;
    - **Atuação**, designando os projetos a serem executados para a construção da usina;
    - **Obras e Serviços**, designando quais obras e serviços **relacionados a estudos, serviços e projetos civis** deverão ser executados para a construção da usina;

        Um arquivo de ajuda de preenchimento e um modelo de ART estão disponibilizados neste repositório. **Cada grupo deverá fazer suas ARTs baseado no modelo disponibilizado e fazer o *upload* para este repositório, sem recorrer a arquivos prontos na internet**;
        
- Projetos que não tiverem todos estes itens respondidos **não serão avaliados!**
Este projeto deverá ser feito neste arquivo, com o *upload* das respectivas ARTs, será até o dia **02/09/2018**. Pedidos de adiamento só serão concedidos em casos excepcionais, a serem decididos pelo professor.

As ART foram enviadas por email.

### Projeto Hidrológico

O projeto hidrológico consistirá na realização e apresentação de cálculos hidrológicos para o projeto de uma central hidrelétrica. Cada item deverá ser respondido neste documento do repositório, usando a ferramenta de edição.


  - Com os dados de vazão usados no projeto do aproveitamento, os grupos deverão identificar e organizar os dados em médias semanais (Se a disposição dos dados for diária) ou anuais (Se a disposição dos dados for mensal);
  
  - Cada grupo deverá realizar uma caracterização estatística destes dados. Para a caracterização dos dados, o grupo deverá utilizar de programação, onde a linguagem de programação é de livre escolha do grupo. **O algoritmo programado deverá ser enviado ao repositório via *upload*. Não será permitida a utilização de planilhas excel ou de programas já feitos**. Os seguintes itens deverão ser respondidos neste documento:
  
       - Fluviograma dos dados, dispostos em valores anuais e decenais;
       
       - Curva de duração de vazões;
       
       - Curva de duração de potência para uma queda (Determinada no projeto do aproveitamento) e rendimento de **70%**;
       
       - Diagrama de Rippl;      

       - Determinação do período crítico;
        
       - Determinação de períodos seco e úmido;
        
       - Determinação de valores extremos;
        
       - Estimativa da vazão firme e da vazão de projeto para dimensionamento de uma central hidrelétrica;
        
      
       - Cálculo da vazão regularizada: O grupo deverá fazer um cálculo da vazão regularizada baseado nos dados fornecidos de vazão. O método a ser usado é o método de Conti-Varlet. A formulação deste método está disponível no livro-texto do curso (Souza, Z., Santos, A. H. M e Bortoni, E. C.  **Centrais Hidrelétricas: Implantação e Comissionamento**, 2a. Edição, Editora Interciência.). Para este cálculo o grupo deverá:
        
       - Usar o programa disponibilizado pelo livro-texto do curso ou implementar o método em uma linguagem de programação da escolha do grupo. Caso o grupo escolha a segunda alternativa, **o algoritmo programado deverá ser enviado ao repositório via *upload***;
       
       - Análisar o resultado obtido de vazão regularizada e comparar este resultado com as vazões firme e de projeto calculados anteriormente;
        
  - Projetos que não tiverem todos estes itens respondidos ou que estiverem incompletos **não serão avaliados!**
Este projeto deverá ser feito neste arquivo até o dia **23/09/2018**. Pedidos de adiamento só serão concedidos em casos excepcionais, a serem decididos pelo professor.


### Projeto do Conduto

O projeto do conduto consistirá na realização e apresentação de cálculos de condutos e canais para a central hidrelétrica. 


  - Projeto do canal para a futura usina hidrelétrica utilizando as fórmulas de Chezy, determinando de acordo com os dados de vazão de cada grupo:
     
       -A melhor forma geométrica de seção para o canal em questão;
       
       - O diâmetro hidráulico da seção;
       
       - Velocidade da água no canal;
       
       - Vazão de água no canal;
       
      
  - Baseado nos valores de queda dispostos no projeto do aproveitamento, o grupo deverá inserir no desenho esquemático deste projeto os seguintes itens:
        
       - Valores de cota de altura;
       - Alturas de queda;
       - Linhas piezométrica e de energia;
        
  - Determinação do semiperíodo da onda de pressão para dimensionamento do conduto fechado. Cada grupo poderá fazer as considerações que achar necessárias;
  
  - Determinação de valores de golpe de aríete positivo máximo;
  
  - Determinação de valores do golpe de aríete aceitável;
  
  - Projetos que não tiverem todos estes itens respondidos ou que estiverem incompletos **não serão avaliados!**
Este projeto deverá ser feito neste arquivo até o dia **07/10/2018**. Pedidos de adiamento só serão concedidos em casos excepcionais, a serem decididos pelo professor.


### Projeto da Turbina

O dimensionamento preliminar de uma turbina consistirá em determinar e dimensionar uma turbina para uma dado aproveitamento hidrelétrico. 

  - Cada grupo deverá especificar qual devem ser a potência e vazão da turbina a ser projetada, baseados nos cálculos dos projetos anteriores;
  
  - Estime a rotação nominal da turbina, considerando um gerador com 10 pólos e frequência de corrente de 60 Hz;
  
  - Para um modelo reduzido de 0,075 m de diâmetro, estime qual deve ser a razão de escala geométrica necessária para se obter os valores de potência e vazão determinados no primeiro item;
  
  - Mostre o triângulo de velocidades para estas condições para turbinas Kaplan, Francis e Pelton. Faça as considerações que achar necessárias e explique-as;
  
  - Determine a rotação específica e classifique a turbina como lenta, rápida ou extra-rápida;
  
  - Estime a velocidade de disparo da turbina;
  
  - Estime o fator de capacidade;
  
  - Qual é o tipo de turbina mais adequado para este aproveitamento?
  
  - Se for o caso, determine a altura de sucção e diga se existe risco de cavitação;
  
  - Com os cálculos, a usina que conterá esta turbina será classificada como? (Pequena central hidrelétrica, Grande central hidrelétrica, etc.)
  
  - Projetos que não tiverem todos estes itens respondidos ou que estiverem incompletos **não serão avaliados!**


Os dados faltantes poderão ser estimados pelo grupo, desde que a forma de estimativa seja devidamente explicada. É facultada a utilização de ferramentas computacionais. Este projeto deverá ser feito neste arquivo até o dia **25/11/2018**. Pedidos de adiamento só serão concedidos em casos excepcionais, a serem decididos pelo professor.
