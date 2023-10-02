# Orientação a Objetos e UML: Diagramação de Classes do iPhone

![uml](https://img.shields.io/badge/-UML-white?style=for-the-badge&logo=UML&color=FABD14&logoColor=white)

Este é um diagrama UML que representa a estrutura de classes e interfaces para um sistema que inclui a modelagem do iPhone, um dispositivo que incorpora funcionalidades de um reprodutor de música, um telefone e um navegador de internet. Este diagrama foi criado como parte do desafio de projeto do Santander Bootcamp 2023 - Fullstack Java+Angular na DIO.me.

![iphone](https://raw.githubusercontent.com/Lipez800/Diagrama-de-Classes-UML-Para-Desenvolvimento-iPhone/main/iphone.png)

## Descrição das Interfaces e Classes

### Reprodutor Musical (ReprodutorMusical)

A interface `Reprodutor Musical` é responsável por implementar a funcionalidade de reprodução de arquivos de áudio. Ela possui métodos como `tocar()`, `pausar()`, `selecionarMusica()`, entre outros. Além disso, há a classe `Musica` que armazena informações sobre as músicas, como nome e caminho.

### Aparelho Telefônico (AparelhoTelefonico)

A interface `Aparelho Telefônico` é responsável por implementar a funcionalidade de um telefone. Ela possui métodos como `fazerChamada()`, `atenderChamada()`, `encerrarChamada()`, `enviarMensagem()`, `receberMensagem()`, entre outros. A classe `Contato` armazena informações de contatos, como nome e número.

### Navegador de Internet (NavegadorInternet)

A interface `Navegador de Internet` é responsável por implementar a funcionalidade de um navegador web. Ela possui métodos como `conectarInternet()`, `desconectarInternet()`, `navegarInternet()`, entre outros.

## Entidades

Além das interfaces e classes mencionadas, há também algumas entidades representadas no diagrama:

- `IPhone`: Representa o próprio dispositivo iPhone, que incorpora as funcionalidades de reprodutor musical, aparelho telefônico e navegador de internet.

- `FireFox` e `Chrome`: Representam navegadores de internet.

- `Nokia 3310` e `Motorola Razr V3`: Representam outros dispositivos telefônicos.

- `Walkman` e `Discman`: Representam dispositivos de reprodução de música.

- `Fone de Ouvido`, `Carregador` e `Cabo USB`: Representam acessórios relacionados ao iPhone.

## Como Visualizar o Diagrama

Para visualizar o diagrama UML, você pode copiar o código PlantUML e colá-lo em um editor compatível com PlantUML ou usar uma ferramenta online de renderização de PlantUML, como o [PlantText](https://www.planttext.com/). Cole o código na área de texto e clique no botão "Refresh" para gerar o diagrama.

Lembre-se de que este é apenas um diagrama de classe de exemplo e pode ser personalizado e estendido para atender às necessidades específicas do seu projeto.
