# Primeiros Passos

## Como ligar o equipamento
 Para ligar o dispositivo, conecte a fonte de alimentação na tomada e em seguida conecte-a no equipamento. Após esse  procedimento, o LED indicador de alimentação ficará aceso e um som será emitido. O HVR ligará após a realização do auto  teste. 


 > **IMPORTANTE:** Recomendamos utilizar a fonte fornecida com o produto de modo a evitar problemas com a alimentação do equipamento. A Clear CFTV só garante um funcionamento adequado quando a fonte utilizada é a fornecida pela empresa. Em caso de utilização de outra fonte, **certifique-se de que ela possui as mesmas características técnicas** da fonte original do HVR. 

## Como desligar o equipamento
 Existem duas formas de desligar o HVR

 - Desligamento via Sistema
 1. Clique com o botão direito do mouse na barra de menu
 2. Clique no ícone de Desligar localizado no lado direito, conforme a imagem abaixo:
 
 <!-- Figura 1 do manual -->

 - Desligamento via Hardware

 Para esse tipo de desligamento, desligue a fonte de alimentação do equipamento. 


# Assistente de Configuração (*Setup Wizard*)

 Quando o HVR inicializa, o assistente de configuração aparece pela primeira vez. Para realizar as configurações básicas, siga os passos e as orientações do assistente, mostrados abaixo:

 <!-- Figura 2  -->

 ## Configuração da senha do Administrador

 Após ligar o dispositivo, defina sua senha antes de iniciar a operação. O sistema irá seguir os
 comandos de acordo com as autorizações do usuário.


 Existem dois perfis de usuário padrão, "**admin**" cuja senha é nula (não possui senha) e "**convidado**".


 > Para a segurança de seu sistema, recomendamos alterar a senha após o primeiro login. Após essa configuração, a mensagem de recomendação de mudança de senha não será exibida novamente.

 <!-- Figura 3 -->

 ## Download do Aplicativo 

 Agora, clique em "**Próximo**" para entrar no serviço de núvem P2P através do código QR abaixo: 

 <!-- Figura 4 -->

 Com o seu smartphone, faça a leitura do QRCode a **DIREITA** para baixar o aplicativo. 

 > O aplicativo está disponível apenas para Sistemas Operacionais **Android**. 

 >Para conseguir visualizar as imagens da câmera no seu smartphone, é necessário **CONCLUIR** o Setup Wizard. 

 Se você tem dificuldades de como escanear o QRCode, veja o link abaixo:

 https://www.techtudo.com.br/dicas-e-tutoriais/noticia/2011/03/aprenda-ler-qr-codes-no-seu-android.html


 É importante que agora você conclua as próximas etapas antes de visualizar as imagens no smartphone, pois no próximo passo, configuraremos a rede na qual o HVR estará conectado.  
  
 ## Configuração de Rede
 Existem dois modos de configuração de rede, o modo **automático** (recomendado) e o modo **manual**. 

 1. Modo Automático

    - Marque a opção **Enable DHCP** .
    - Clique em **UPDATE** .
    - O HVR encontrará um endereço IP automaticamente dentro de sua rede .
    - Clique em **SAVE** . 

 Caso a configuração acima não funcione, ou você deseja configurar manualmente a conexão do seu equipamento, siga os passos abaixo:

 2. Modo Manual

   - Certifique-se de desmarcar a opção **Enable DHCP**.
   - Defina um endereço **disponível** IP dentro do range de sua rede.
   - Por exemplo, se seu Gateway possuir o endereço **192.168.2.1**, o endereço IP que deve ser atribuído ao HVR deve respeitar o formato **192.168.2.ABC**, sendo **ABC** um número entre **2** e **254**. Caso haja algum conflito de IP, experimente mudar esse valor, pois provavelmente algum outro dispositivo conectado à sua rede está usando o mesmo endereço IP que você escolheu. 
   - A máscara de sub rede, chamada de **Subnet Mask** deve ser preenchida com **255.255.255.0**.
   - O endereço **Gateway** deve ser o endereço IP do seu Roteador, NO EXEMPLO ACIMA, seria **192.168.2.1**, o de sua rede poderá ser diferente, caso tenha dúvidas de como descobrir o endereço de Gateway, veja o tópico ***Descobrindo o IP do roteador usando Prompt de comando*** no link: https://www.techtudo.com.br/dicas-e-tutoriais/noticia/2012/05/como-descobrir-o-ip-para-acessar-o-roteador.html
   - Agora, vamos definir o DNS, complete esse campo com **1.1.1.1** ou utilize o do seu provedor. 
   - Clique em **SAVE** para continuar.


 > Parabéns, você acabou de finalizar **SETUP WIZARD** do seu HVR Clear CFTV! Veja abaixo, outras configurações disponíveis. 


 Caso em outro momento, após a configuração, você queira alterar as configurações de rede. Acesse:

 **Menu Principal** >> **Sistema** >> **Rede**


# Menu Principal
## Sistema 
___
## - Básico
 As configurações básicas que podem ser feitas nessa seção, são:
    
 | Configuração | Descrição |
 | --- | --- | 
 | Nome do HVR | Define um nome para seu equipamento. <br> Para alterá-lo, clique no botão      **Configurações, logo abaixo do nome exibido na tabela. |
 | Número ID do HVR| Define uma ID para o HVR. | 
 | Língua | Selecione o idioma que deseja aplicar ao equipamento. |
 | Saída automática |  Defina um intervalo de tempo que o menu feche após um período de inatividade. |
 | Transparência do menu | Opção que deixa o menu mais transparente. |
 | Definir a resolução | Define a resolução da saída de vídeo HDMI / VGA. **Isso não influencia a qualidade de gravação do equipamento. Apenas na visualização. |
 | Padrão TV OUT | Define o padrão do formato de vídeo. |
 | Modo de câmera | Identificação dos tipos de câmeras que serão usadas no HVR |
 | Assistente de configuração| Habilita ou Desabilita o Assistência de Configuração. |
 | Auto limpar o alarme |  ... | 

 Também é possível configurar a **DATA E HORA** nessa seção. Para isso, clique na aba Data e Hora na parte superior da tela. <br>
 A aba **DST** é responsável por configurar o horário de verão. 
## - Exibição 
 As configurações possíveis são: <br>
 | Configuração| Descrição | 
 |---|---|
 | Canal de Áudio | Define qual canal será o canal de áudio. |
 | TV-OUT Ajustar | Ajusta a posição da tela no monitor. |
 
 Existe, nessa janela, uma outra aba, chamada **CONFIGURAÇÃO**. 

 Nessa aba é possível configurar:
 - Tempo de Permanência do vídeo na sequência. 
 - Duração do evento de alarme
 -  Modo de tela 
 -  Sequência de câmeras que serão exibidas na tela principal. 


## - Usuário

 Essa seçã exibe os usuários que usam o equipamento. Também é possível adicionar,    alterar e remover usuários. <br>
 Ao clicar em **modificar**, é exibido um botão chamado de **autoridade**. Esse botão  é responsável por configurar as permissões de acesso do usuário no equipamento. 

## - Rede

A configuração de rede, é a mesma do **Setup Wizard**. São elas: <br>
Existem dois modos de configuração de rede, o modo **automático** (recomendado) e o modo **manual**. 

 1. Modo Automático

    - Marque a opção **Enable DHCP** .
    - Clique em **UPDATE** .
    - O HVR encontrará um endereço IP automaticamente dentro de sua rede .
    - Clique em **SAVE** . 

 Caso a configuração acima não funcione, ou você deseja configurar manualmente a conexão do seu equipamento, siga os passos abaixo:

 2. Modo Manual

   - Certifique-se de desmarcar a opção **Enable DHCP**.
   - Defina um endereço **disponível** IP dentro do range de sua rede.
   - Por exemplo, se seu Gateway possuir o endereço **192.168.2.1**, o endereço IP que deve ser atribuído ao HVR deve respeitar o formato **192.168.2.ABC**, sendo **ABC** um número entre **2** e **254**. Caso haja algum conflito de IP, experimente mudar esse valor, pois provavelmente algum outro dispositivo conectado à sua rede está usando o mesmo endereço IP que você escolheu. 
   - A máscara de sub rede, chamada de **Subnet Mask** deve ser preenchida com **255.255.255.0**.
   - O endereço **Gateway** deve ser o endereço IP do seu Roteador, NO EXEMPLO ACIMA, seria **192.168.2.1**, o de sua rede poderá ser diferente, caso tenha dúvidas de como descobrir o endereço de Gateway, veja o tópico ***Descobrindo o IP do roteador usando Prompt de comando*** no link: https://www.techtudo.com.br/dicas-e-tutoriais/noticia/2012/05/como-descobrir-o-ip-para-acessar-o-roteador.html
   - Agora, vamos definir o DNS, complete esse campo com **1.1.1.1** ou utilize o do seu provedor. 
   - Clique em **SAVE** para continuar. 

## - SysAlarm 

 Essa é uma seção importante. Aqui pode-se configurar as ações que serão tomadas quando ocorrem alarmes do tipo:
  - Disco Cheio
  - Erro no HD
  - Acesso ilegal do usuário
  - Conexão de Rede Pública 
 
 <!-- VERIFICAR -->
 
## - Digital 

 Esse ambiente permite que você defina a quantidade de câmeras analógicas (AHD/TVI/CVI/CVBS) e digitais (IPs) que podem ser usadas no seu equipamento. 

 Para mudar a quantidade de câmeras (digitais x analógicas) utilize as **setas** que se encontram na parte superior da tela para alterar essa configuração. 

## Câmera 
___

## - OSD

Essa é uma configuração chamada *On-screeen Display*. Ela sobrepõe sobre o vídeo um texto. Nesse caso, é possível **renomear** o nome do canal de acordo com o local que a câmera está instalada.
## - Cor
Essa configuração permite alterar os seguintes parâmetros de imagem:
- Brilho
- Contraste
- Croma
- Saturação 
- Nitidez horizontal
- Nitidez vertical
- Redução de ruído


O botão **Padrão** restaura as configurações de fábrica. <br> 
O botão **Confirmar** aplica as configurações desejadas para o canal.  


## - Inteligente

Essa função tem o objetivo de detectar rostos. Marque a opção para ativar essa funcionalidade. 

## - Movimento

Essa configuração habilita a detecção de movimento. Selecione o canal que deseja configurar e marque a opção ***Habilitar Detecção de Movimento***. Os parâmetros configuráveis são:

| Configuração | Descrição |
|---|---|
| Sensibilidade da Detecção| A sensibilidade da detecção pode ser:<br> Mais alto<br> Alto<br> Normal<br> Baixo <br> Mais baixo <br>|
| Cronograma de Detecção | É possível deixar a detecção por movimento o dia todo com a opção *Detecção de movimento ativa o dia todo<br> Ou é possível personalizar selecionando a opção *Personalize o cronograma de detecção de movimento*|
|Tela cheia ao ter movimento | Quando há movimento, o canal onde foi detectado o movimento fica em tela cheia|
| Gravar ao ter movimento | Quando há detecção de movimento, é feita a gravação de acordo com os canais selecionados. Para isso, clique em *Configurações* para definir os canais. |
| Tirar snapshot ao ter movimento | Quando há detecção de movimento, é tirada uma foto de acordo com os canais selecionados. Para isso, clique em *Configurações* para definir os canais. |
|Mover PTZ ao ter movimento | Move a câmera que possui configuração PTZ ao detectar movimento. É necessário configurá-la para a posição que deseja. |
| Enviar e-mail ao ter movimento | Envia um email quando ocorre detecção de  movimento  


## - Perda de vídeo

Essa configuração alerta o usuário quando há perda no sinal de vídeo. 
| Configuração | Descrição |
|---|---|
| Cronograma de Detecção | É possível deixar a detecção por perda de vídeo o dia todo com a opção *Detecção  ativa o dia todo<br> Ou é possível personalizar selecionando a opção *Personalize o cronograma de detecção*|

## - Máscara 

Ao habilitar essa função, é possível ocultar uma região da imagem. Selecione clicando nos quadros onde deseja ocultar. 

## - PTZ 

Essa configuração habilita o uso de uma câmera PTZ em um canal específico. Nessa aba podem ser definidos:
| Configuração | Descrição| 
| --- | --- | 
| CH. | Canal que será usado o PTZ.| 
| Habilitar PTZ | Habilita ou desabilita o modo PTZ do canal.|
| Endereço PTZ | Define o endereço PTZ de acordo com o fabricante da câmera. |
| Taxa de transmissão PTZ | Define o baud rate de acordo com o fabricante da câmera. |
| Protocolo PTZ | Define o protocolo de comunicação de acordo com o fabricante da câmera.|
| Execução Automática PTZ | Define uma sequência de movimentos para a cÂmera PTZ.|

## Gravação 
___

Essa aba é responsável por todas as configurações de gravação do HVR. A seguir, é detalhada cada uma delas. 

## - Configuração 

Aqui é feita a configuração da qualidade da gravação. A tabela abaixo especifica o que cada campo faz. 
| Configuração | Descrição | 
| --- | --- | 
| CH.| Canal que será configurado. | 
| Codec | Tipo de codificação de compressão do vídeo. <br> O uso do **H265** é mais eficiente em relação ao **H264**. |
| Tipo de gravação | **Somente vídeo:** Não faz a captura do áudio. <br> **Vídeo e Áudio**: Captura áudio e vídeo da gravação. Certifique-se que seu sistema está preparado para captação de áudio. | 
| Resolução |  Resolução da gravação.<br> D1, 960H, 720P, 1080P, 1080N, 3MP-N, 4 MP-N, 5MP,N|
| Taxa de quadro| Taxa de quadros do vídeo, quanto mais alto mais fluidez o vídeo possui, porém o aumento da taxa aumenta o tamanho do arquivo de armazenamento|
| Tipo de taxa de bit | it variável reduz ocupação de espaço no HD quando não há movimentação. Bit constante grava sempre constante independentemente se houver movimentação.|
|Qualidade| Qualidade da gravação |


## - Snapshot 

Essa funcionalidade permite a configuração do snapshot do vídeo, ou seja, uma **foto** do vídeo, como por exemplo quando ocorre um alarme. 

É possível definir a **resolução**, **qualidade**, **quantidade** e o **intervalo de tempo** entre as fotos. 

## - Cronograma 
Essa configuração permite que você defina os dias da semana que o equipamento fará a gravação, seja por **gravação contínua** seja por **movimento**, seja por **alarme** ou pela combinação entre eles. 

> Mais uma vez, é importante lembrar que esse tipo de configuração é individual para cada canal de vídeo. Certifique-se dos canais que estão sendo configurados.

Para acessar essa configuração, selecione **Menu** >> **Gravação** >> **Cronograma**. 

Os pequenos quadrados a frente de cada dia da semana representam uma hora do dia referente àquele dia (segunda, terça, etc). 

As cores representam o modo que durante aquele dia, o canal em questão está configurado. 

|Cor|Modo|
|---|---|
|Branco| Gravação por agendamento desabilitada. |
|Amarelo | Gravação por alarme + detecção.|
|Azul| Modo comum + alarme + detecção. |
| Vermelho| Gravação por alarme. |
## - Avançado

Essa opção permite que seja feita uma simulação para saber quanto tempo de gravação "caberá" no seu HD de acordo com os parâmetros estabelecidos.

## HD
___

## - Básico 
Essa aba permite verificar o status do HD do seu HVR. É possível verificar o quanto de capacidade de armazenamento ainda está disponível no dispositivo. 

O botão **AÇÃO** realiza a **formatação** dO HD. 

## - Avançado 

Essa função exibe algumas informações avançadas sobre a saúde do HD. 

## Visualização de Imagem 
___

## - Local 

Busca por gravações que estão armazenadas localmente, ou seja, no HD. 

Deve-se selecionar a data do lado direito da dela e depois selecionar o canal logo acima do calendário. 

Busque pelo arquivo desejado clicando sobre ele na lista que é exibida no centro da tela. 

## - Externo 

Busca por gravações em um dispositivo conectado externamente ao HVR. O modo de busca por imagens é semelhante a busca na aba **Local**. 

## Informação 
___

## - Informação

Essa aba exibe informações sobre o HVR, Câmeras, Registro (como está setado os parâmetros de gravação), os parâmetros de rede, o status do HD, e os usuários do sistema. 

## - Registro 

Aqui são registrados as seguintes ocorrências:

|Tipo de Registro |
| --- |
| Ocorrência de Alarme | 
| Ocorrência de Sistema|
| Gerenciamento de armazenamento |
| Ocorrência de rede | 
| Todos | 
## - Configurações
Exibe as configurações de um dispositivo conectado externamente ao HVR.  
## - Atualizar 

Atualiza o *firmware* do HVR a partir de um dispositivo USB. 

## - Restaurar
Restaura as configurações do HVR para as configurações de fábrica. 

## - Manutenção  
 Ativa o agendamento do modo Manutenção do HVR. 
 