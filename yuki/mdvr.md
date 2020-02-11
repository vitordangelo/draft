# Login

Para acessar o menu de login clique na tecla <kbd>Login</kbd>, aparecerá a tela abaixo solicitando a senha de administrador.

> A senha padrão é: **111111** ou **888888**

![Login](./login.png)

# Menu Principal

Menu principal de configuração do MDVR. Utilize as setas do controle remoto ou ligue um mouse da entrada USB frontal para navegar no menu.

![Main Menu](./main-menu.png)

# Record

![Record](./record1.png)

![Video Search](./video-search.jpg)

> O dia que possui gravação é destacado em verde no calendário no lado esquerdo da tela.

Nesta tela podemos listar os vídeos gravados no cartão de memória selecionando o dia na opção **Date** e marcando o período de tempo gravado em **Start time** (hora de início) e **End time** (hora de fim) e o tipo de vídeo em **Video Type** entre os tipos:

- REC-ALL: Corresponde a todos os tipos de gravação
- REC-ALM: Corresponde a vídeos de eventos de alarme
- IO: Rabicho de entrada
- GSensor: Acelerômetro
- Speed: Alarme de Velocidade
- Move: Detecção de movimento
- Fatigue: Alerta de fadiga do motorista
- **<span style="color: red"> OCC</span>**

**Disk Type**: Mídia de armazenamento que deseja realizar a busca.

Clique em **Search** para listar os arquivos de vídeos gravados.

![List Videos](./list-videos.png)

Será mostrado todos os vídeos correspondente a data selecionada, aperte o botão <kbd>Play</kbd> para reproduzir o vídeo desejado.

**<span style="color: red"> Export</span>**

Descrição dos campos do resultado de busca

| Campo       | Descrição                     |
| ----------- | ----------------------------- |
| CHN         | Canal de vídeo                |
| Type        | Tipo de gravação              |
| Start       | Horário de início da gravação |
| End         | Horário de fim da gravação    |
| Size        | Tamanho do arquivo            |
| Record date | Data de gravação              |

Clique em **Show** para listar os arquivos de vídeos gravados.

![Show Videos](./show-results.jpg)

Como na opção anterior, os vídeos são listados conforme os campos de pesquisa preenchidos.

# Log

O recurso de log registra todos os eventos ocorridos no dispositivo tais como ligar, desligar, eventos de alarme, comportamento do módulo GPS, 3G/4G, conexão com o servidor entre outras informações importantes e alterações de configuração realizadas.

![Log](./log.png)

![Log Search](./log-search.png)

Descrição dos compos

| Campo      | Descrição                          |
| ---------- | ---------------------------------- |
| Date       | Dia que deseja fazer análise       |
| Start Time | Horário Inicial                    |
| Type       | Tipo de registro                   |
| End Time   | Horário de fim                     |
| Page       | Quantidade de páginas do relatório |
| Time       | Horário que ocorreu o evento       |

Os botões: _First_, _Prev_, _Next_, _Last_ são para navegar entre as páginas do relatório gerado.

# Picture

Realiza a busca de fotos armazenadas no sistema.

![Picture](./picture.png)

A navegação pelo resultado e o preenchimento dos filtros de busca é igual dos passos apresentados anteriormente.

![Picture](./list-picture.png)

# Terminal

Nesta configuração iremos preencher informações sobre o dispositivo, veículo e dados para acesso ao servidor.

![Terminal](./terminal.png)

![Terminal](./terminal-data.png)

| Campo                                    | Descrição                                                                                           |
| ---------------------------------------- | --------------------------------------------------------------------------------------------------- |
| Plate No                                 | Dados da placa do veículo                                                                           |
| Dev Id                                   | Este é um código que deve ser único no servidor, caso for usar o da V2Tech iremos passar seu código |
| State                                    | Estado (UF)                                                                                         |
| City                                     | Cidade                                                                                              |
| Language                                 | Idioma                                                                                              |
| <span style="color: red">GuiAlpha</span> |
| Terminal                                 |                                                                                                     |
| FactorID                                 |                                                                                                     |
| TerminID                                 |                                                                                                     |

# User

Interface para gerenciamento da conta de usuário para configuração do MDVR.

![User](./user.png)

![User](./user-management.png)

- **Password:** Opção para ativar ou desativar a necessidade de inserir senha para manipular as configurações do MDVR.
- **User:** Insira a senha para o usuário de nome User.
- **ADMIN:** Insira a senha para o usuário de nome Admin.
- **Confirm:** Confirme a senha, inserindo novamente.

# Time

![Time](./time.png)

Nesta parte iremos configurar os parâmetros de data e hora.

![Time](./time-setup.png)

- **Date Type:** Formato de data, o formato mais utilizado no Brasil é DD/MM/YY que corresponde: dia/mês/ano
- **Time Sync:** Opção na qual o relógio será sincronizado, recomendamos usar a opção **GPS**
- **NTP Addr:** Endereço do servidor NTP que deseja obter dados de data e hora, _caso for utilizar a sincronização via GPS ignore este campo_.
- **DST Mode:** Ativar horário de verão
- **Date:** Insira a data atual
- **Time:** Horário atual
- **Timezone:** Insira o fusorario, normalmente é utilizado GMT-3 em boa parte do território brasileiro.
- **Port:** Porta do servidor NTP que fará consulta

# Power Management

Estas são configurações relacionadas ao tempo que o dispositivo deve permanecer ligado.

![Power](./power.png)

![Power](./power-management.png)

- **Power Mode:**
  - **Acc:** Selecione esta opção caso deseja ligar o MDVR no pós chave do veículo, nesta opção é possível configurar quantos minutos o equipamento deve permanecer ligado após desligar o veículo (Delay Off).
  - **Timing Mode:** Nesta opção é determinado o horário que o equipamento deve ligar e desligar.
- **Delay Off:** Insira quantos minutos deseja que o MDVR fique ligado após desligar o pós chave.
- **PowerOn e PowerOff:** Insira o horário para ligar e desligar o equipamento, respectivamente.
- **Red Delay:**
- **Record:**
- **Auto Reboot:** Opção para o equipamento reiniciar em um horário específico.
- **Reboot time:** Horário que deseja que o equipamento seja reiniciado.
- **LowPowerOff:**
- **WakeUpSw:**

- **Reboot**: Botao para reiniciar o dispositivo.

# Parameter
