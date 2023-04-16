# testando-servidor-web
Atividade da matéria de laboratório de redes 2022.2 - LABORATÓRIO DE REDES DE COMPUTADORES - Turma 01 - **DENISSON SANTOS ALVES DE FREITAS**

Realizei a criação da rede da minha empresa utilizando como base o WebQuest "Testando Aplicação de Rede". Utilizei a máquina virtual CursoIPV6br com o CORE4.6 para criar as estruturas e as ligações entre as máquinas e os hosts. Em seguida, implementei a rede utilizando os arquivos TCPServer.py para configurar os hosts e TCPClient.py para configurar as máquinas clientes da minha empresa.

O primeiro host é o host do meu site, que por se tratar de um site wordpress feito na hostinger, o host se encontra na nuvem, e o segundo host é um host local utilizado para realização de backups.

As máquinas Alice e Bob foram configuradas de modo a se conectarem ao host do meu site na nuvem, enquanto que a máquina do Zack foi configurada para se conectar com o host de backup.

Na pasta imgs-testes pode-se verificar os resultados com testes de conexão utilizando o IP correto dos hosts, estabelecendo a conexão corretamente, testes induzindo erro de conexão trocando o IP correto para um IP incorreto, impossibilitando a conexão, e alguns erros de tratamento de strings que foram apresentados em alguns testes. Além disso lá também contém a planta de cabeamento estruturado contendo uma visão ampla da conexão da minha empresa.