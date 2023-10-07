# Desafio Controle Fluxo - DIO

Este é um projeto Java simples que demonstra o controle de fluxo usando um loop `for` e exceções personalizadas apresentado para o módulo de Controle de Fluxo do Santander Bootcamp 2023 - Fullstack Java+Angular ministrado pela DIO - Digital Innovation One.

## Como Executar
1. Clone este repositório para o seu ambiente local:

   ```bash
   git clone https://github.com/fahcavalcanti/controle-fluxo.git

2. Navegue até o diretório do projeto: 

   ```bash
   cd DesafioControleFluxo

3. Compile o código Java: `javac controleFluxo/Contador.java`
4. Execute o programa: `java controleFluxo.Contador`
5. Siga as instruções no terminal para fornecer os dois números inteiros como entrada.
6. O programa imprimirá a sequência de números incrementados ou lançará a exceção se a entrada for inválida.

## Exceção Personalizada
Se o segundo parâmetro for menor ou igual ao primeiro, o programa lançará a exceção ParametrosInvalidosException com a mensagem "O segundo parâmetro deve ser maior que o primeiro".

## Estrutura do Projeto
`Contador.java`: Contém a classe principal que implementa a lógica do programa.
`ParametrosInvalidosException.java`: Contém a classe que define a exceção personalizada.

## Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter detalhes.

