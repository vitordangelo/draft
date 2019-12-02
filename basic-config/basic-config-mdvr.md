# Configuração básica

> Siga o passo a passo abaixo para configurar o MDVR para gravação e conexão com o servidor V2Tech. <br> Este processo de configuração é o mais comum.

## Data e Hora

_Geral/Data&Hora_

> Nesta tela iremos configurar a data e hora do dispositivo e o tempo que o equipamento deve permanecer ligado.

!['Data e Hora'](./images/009.jpg)

- Em __Formato Date__ escolha o formato da data desejado, o mais comum a ser utilizado é __D/M/A__ (dia/mês/ano).

- No campo __Date__ insira a data atual (caso o dispositivo tenha GPS instalado é provavel que já tenha sido preenchido automaticamente).

- Em __Fuso Tempo__ selecione GMT-03:00 ou outro caso esteja em uma região cujo fuso horário seja diferente do de Brasília.

- __DST__ é referente ao horário de versão, recomendamos que mantenha em __OFF__.

- __Acionar Atraso__ recomendamos que matenha o valor padrão de 5 min.

- __Ajuste Modo__ selecione GPS caso seu dispositivo tenha módulo GPS. Este recurso fará ajuste na data e hora automaticamente utilizando dados de GPS.

- A opção __Ajuste Tempo__ determina o horário que será ajustado a data/hora automaticamente pelo GPS.

- __Modo Energia__ é uma das configurações mais importantes, caso deseje que o equipamento seja __desligado__ depois de x minutos após desligar o veículo mantenha a opção __ignição__, ajuste o tempo que deseja desligar o equipamento no campo __Atraso para desligar__ o tempo desejado.

- Em _manutenção_ é definido o horário que o equipamento será reiniciado, recomendamos manter em **Off**.

## Veículo

_Geral/Veiculo_

> Nesta opção iremos configurar o IDNO (identificador do equipamento) no servidor.

!> Caso for utilizar o servidor da V2Tech, nos forneceremos este número, entre em contato e solicite o seu.

!['Veículo'](./images/008.jpg)

- No campo __Dispositivo-num__ insira o código para identificar o equipamento no servidor.

## Rede

_Geral/Rede_

> Aqui iremos configurar o MDVR para conectar no servidor, o exemplo abaixo é utilizando o servidor da V2Tech.

!['Rede'](./images/007.jpg)

- Em __Modo Net__ altera para a opção __domain__.

- No campo __Dominio__ insira o endereço do servidor: __v2servidor.ddns.net__, ao abrir o teclado para digitar o endereço, aperte o botão - no controle remoto para remover o "espaço" presente na frente da primeira letra.

- No campo __DNS__ insira o IP: __001.001.001.001__

As demais informações permanecem padrão e os campos __Endereço IP, Mascara e Gateway__ são relacionados a porta RJ45 (interface ethernet).

## Modo Canal

> Nesta tela iremos configurar o tipo de câmera que será utilizada no MDVR.

!['Modo Canal'](./images/006.jpg)

1. Opção para quando é utilizado 4 câmeras HD de 720p
2. Esta opção é para quando utilizará 4 câmeras 960H
3. Esta opção é utilizado para 2 câmeras 720p e 2 câmeras 960H
4. Nesta opção é possível utilizar 4 câmeras 960H e 1 câmera IP 1080p

## Gravação

_Recorde/Normal_

> Aqui iremos configurar o tempo de cada pacote de vídeo e o tipo de gravação.

!['Gravação'](./images/005.jpg)

- __Recorde Tipo__ mantenha a opção __normal__.
- __Modo Viver__ selecione quatro para aparecer os 4 canais de vídeo.
- __Recorde Modo__ deve ser __auto__.
- __Cobertura__ é uma opção muito importante, pois nesta configuração que é definido se um arquivo de vídeo será sob-escrito por um vídeo mais novo. Se desativado quando o cartão de memória estiver cheio as gravações serão interrompidas. Se estiver ligado e o cartão de memória encher os novos vídeos serão gravados em cima dos vídeos mais antigos (reciclagem).

As demais configurações podem ser mantidas padrão como mostrado na imagem acima.

## Main Code

_Recorde/Main Code_

> Esta tela é muito importante pois é definido a qualidade da gravação do vídeo.

!['Main COde'](./images/004.jpg)

!> **Lembre-se que quanto maior a qualidade de gravação, mais espaço será necessário para armazenar os arquivos de vídeo de modo que o ciclo de gravações será reduzido.**

![Quality](./images/quality-record.png)

| Campo  | Informação                                                                                                                                                                      |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RECORD | Esse campo habilita a gravação de cada um dos canais. **ON** para gravação habilitada **OFF** para gravação desabilitada                                                        |
| RES    | Define a resolução de gravação do canal. <br> É importante lembrar que quanto maior a resolução, maior será o espaço ocupado no dispositivo de armazenamento.                   |
| FPS    | Selecione qual será a taxa de quadros por segundo que será gravada no vídeo. Essa é uma configuração de fluidez de imagem. Quanto maior o valor, maior será a fluidez do vídeo. |
| QUAL   | **(Valores de 1 a 8)** Essa é uma configuração de qualidade de imagem de gravação, quanto **menor** o valor, **melhor** a qualidade da imagem.                                  |
| Audio  | Permite habilitar a gravação de áudio, desde que o canal selecionado esteja equipado com um microfone **ON** Habilita a função **OFF** Desabilita a função                      |
| Enable | **ON** Habilita o alarme de perda de vídeo **OFF** Desabilita o alarme de perda de vídeo                                                                                        |

## Configuração 3G

_Perifericos/Sem Fio_

> Nesta parte iremos configurar o chip 3G. Para usar este recurso é importante salientar que é necessário ter o módulo 3G instalado no MDVR.

![3G](./images/3g.png)

- **wirelles** selecione a opção _ON_.
- **type** selecione _WCDMA_
- **APN** insira a APN de sua operadora (veja nas tabelas abaixo)
- **center-Num** deve ser o padrão como mostrado na imagem
- **username** e **password** são de acordo com a sua operadora (veja nas tabelas abaixo)

APN VIVO:

| Parâmetro | Descrição       |
| --------- | --------------- |
| APN       | zap.vivo.com.br |
| User Name | vivo            |
| Password  | vivo            |

APN Oi:

| Parâmetro |   Descrição    |
| :-------: | :------------: |
|    APN    | gprs.oi.com.br |
| User Name |       oi       |
| Password  |       oi       |

APN TIM:

| Parâmetro |  Descrição   |
| :-------: | :----------: |
|    APN    | timbrasil.br |
| User Name |     tim      |
| Password  |     tim      |

APN Claro:

| Parâmetro |  Descrição   |
| :-------: | :----------: |
|    APN    | claro.com.br |
| User Name |    claro     |
| Password  |    claro     |

Com estas configurações realizadas seu equipamento já esta apto a realizar gravações.
