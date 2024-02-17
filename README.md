### Introdução ao Language Studio e a Criação de uma IA utilizando essa Tecnologia 👾.


Iremos criar uma IA capaz de analisar textos ,como por exemplo um serviço de avaliação,onde ela separa comentarios **positivos/negativos** utilizando palavras chaves .

#### 1️⃣ Crie um novo recurso no azure
![recurso no azure](https://github.com/FelipeAPiresBR/Reconhecimento-Facial-/blob/main/inputs/Criar%20um%20Recurso.png?raw=true) 
* Em seguida,selecione **IA + Machine Learning,depois Análise de Texto** clique em criar . 
![Legenda](https://github.com/FelipeAPiresBR/IA-Language-Studio/blob/main/inputs/img/IA+machine%20Learning%20An%C3%A1lise%20de%20texto.png?raw=true)
 * Na sequencia clique em Continuar a criação do seu recurso 
 ![Criar o recurso ](https://github.com/FelipeAPiresBR/IA-Language-Studio/blob/main/inputs/img/Continue%20to%20create%20your%20resource.png?raw=true)


#### 2️⃣ Na página criar um Idiota,Configure com as seguintes configurações : 
* Assinatura : sua assinatura do Azure .
* Grupo de recursos : Selecione ou crie um grupo de recursos com um nome de sua escolha
* Região :  Para custos mais baixos,selecione Leste dos EUA.
* Nome : Insira um nome de sua escolha  .
* Nível de preços : Selecione o plano Free FO
* Ao marcar esta caixa, confirmo que li e compreendi todos os termos abaixo : Selecionado .
* Examinar + Criar ,quando terminar de examinar clique em Criar para realmente de fato ser criado seu serviço . 
* Aguarde terminar de criar, pode demorar de **05 a 10 minutos**⏰

![Criar um idiota.png](https://github.com/FelipeAPiresBR/IA-Language-Studio/blob/main/inputs/img/Configura%C3%A7%C3%B5es%20Criar%20um%20idioma.png?raw=true)

#### 3️⃣Em outra guia do navegador,abra o [Language Studio](https://language.cognitive.azure.com/?azure-portal=true)
* Faça login com sua conta do Azure que está localizado o serviço que acabou de criar .
* Em Seguida,clique em **Select a resource** e coloque as seguintes configurações :
* Diretório do Azure : diretório padrão, o diretório que você está usando
* Assinatura do Azure : selecione a assinatura que você está usando
* Tipo de recurso : Idioma
* Nome do recurso : selecione o recurso de serviço de idioma que você acabou de criar na plataforma da **Azure**
* Clique em Finalizar .
![Config Select an azure 01.png](https://github.com/FelipeAPiresBR/IA-Language-Studio/blob/main/inputs/img/Config%20Select%20an%20azure%2001.png?raw=true)

https://github.com/FelipeAPiresBR/IA-Language-Studio/blob/main/inputs/img/Config%20Select%20an%20azure%2001.png?raw=true

### OBS :Caso não aparece o passo anterior, pode haver que você tenha algum serviço de idiota já criado .
* Para corrigir esse problema faça o seguinte passo a passo :
* Na barra na parte superior da página, selecione Configurações (⚙) .
* Na página Configurações , visualize a guia Recursos .
* Selecione o recurso que você acabou de criar e selecione Alternar recurso . Certifique-se de que o recurso gerenciado esteja habilitado .

#### 4️⃣ Na guia inicial do Language Studio,selecione **Classificar texto** e em seguida selecione a atividade **Analisar sentimentos e extrair opiniões** .
![Analisar sentimentos e minerar opnioes.png](https://github.com/FelipeAPiresBR/IA-Language-Studio/blob/main/inputs/img/Analisar%20sentimentos%20e%20minerar%20opnioes.png?raw=true)

#### 5️⃣A Aplicação será aberta conforme a imagem a baixo :
![Legenda](https://github.com/FelipeAPiresBR/IA-Language-Studio/blob/main/inputs/img/final%20language%20studio.png?raw=true)

* Selecione o idioma de sua escolha,nesse exemplo irei utilizar o ingles 
* Verifique se seu recurso está aparecendo 
* Digite a frase que deseja realizar o teste ou faça upload da mesma em um bloco de notas .
* Marque a opção de aviso  
* Clique em iniciar . 

#### 6️⃣Finalizado a ação o resultado surgira  como no exemplo a baixo :
![Resultado do teste executado.png](https://github.com/FelipeAPiresBR/IA-Language-Studio/blob/main/inputs/img/resultado%20analise%20de%20linguagem.png?raw=true)


# Epílogo 
 Chegamos ao fim de mais um Resumão,simples,mas eficiente, de como Criar uma IA capaz de realizar o mapeamento de documentos/textos para transformar em analise de feedbacks e outras aplicações que podem ser utilizadas no cotidiano ,esse tutorial foi dedicado a pessoas que ainda não conhecem a ferramenta e estão em busca de algo prático.

 Em breve será disponibilizado 	[novos artigos](https://github.com/FelipeAPiresBR/ReconhecimentoFacial_Metamorfose-De-Imagens-Em-Dados.git) sobre IA e criação dos mais variados tipos para te auxiliar no dia-a-dia.

 O máterial de apoio que utilizei para realizar esse artigo se encontra aqui :  
 https://language.cognitive.azure.com/tryout/sentiment


#### Qualquer dúvida ou Sugestão e muito bem vinda!🔁


