
# 📘 Tarefa: Jogo da Forca

## 🎯 Objective

Construa o clássico jogo de adivinhar palavras usando strings, loops, condicionais e seleção aleatória em Python. Pratique manipulação de estruturas de dados, controle de fluxo e interação com o usuário.

## 📝 Tasks

### 🛠️ Configurar e Inicializar o Jogo

#### Descrição
Configure a lógica inicial do jogo, incluindo a seleção aleatória de uma palavra e a exibição do estado inicial da partida.

#### Requisitos
O programa completo deve:

- Importar o módulo `random` para seleção de palavras
- Definir uma lista com pelo menos 5 palavras para o jogo
- Selecionar uma palavra aleatoriamente da lista
- Inicializar variáveis para rastrear: letras adivinhadas, tentativas restantes e progresso (formato _ _ _)
- Exibir uma mensagem de boas-vindas ao iniciar o jogo

### 🛠️ Processar Palpites do Usuário

#### Descrição
Implemente a lógica para aceitar palpites de letras do usuário e atualizar o estado do jogo.

#### Requisitos
O programa completo deve:

- Solicitar ao usuário para adivinhar uma letra
- Validar a entrada (garantir que seja uma única letra e não tenha sido tentada antes)
- Atualizar a lista de letras adivinhadas
- Mostrar o progresso da palavra com letras acertadas e espaços em branco (_) para letras não adivinhadas
- Informar ao usuário se acertou ou errou

### 🛠️ Controlar Tentativas e Fim de Jogo

#### Descrição
Implemente o sistema de tentativas e a lógica para determinar vitória ou derrota.

#### Requisitos
O programa completo deve:

- Rastrear tentativas incorretas restantes (começar com um número definido, por exemplo 6)
- Decrementar tentativas a cada palpite incorreto
- Exibir o número de tentativas restantes a cada rodada
- Implementar condição de vitória: palavra completamente adivinhada
- Implementar condição de derrota: tentativas esgotadas
- Exibir mensagens e a palavra final ao encerrar o jogo
- Oferecer ao usuário a opção de jogar novamente