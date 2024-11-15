# EcoDicas - Aplicativo de Dicas Sustentáveis

## Descrição
EcoDicas é um aplicativo Android desenvolvido em Kotlin que permite aos usuários gerenciar e compartilhar dicas sobre práticas sustentáveis e economia de energia. O aplicativo foi projetado com uma interface intuitiva e amigável, utilizando uma temática verde para reforçar seu propósito ambiental.

## Funcionalidades Principais

### 1. Adição de Dicas
- Campo para título da dica
- Campo para descrição detalhada
- Botão "ADICIONAR DICA" para salvar as informações
  ![Tela de Adição](images/add_tip.png)

### 2. Pesquisa de Dicas
- Barra de pesquisa no topo do aplicativo
- Filtragem em tempo real das dicas
- Ícone de limpeza (X) para resetar a pesquisa
  ![Pesquisa em Ação](images/search_feature.png)

### 3. Visualização de Dicas
- Lista de dicas em formato de cards
- Exibição clara do título e descrição
- Design limpo e organizado
  ![Lista de Dicas](images/tips_list.png)

### 4. Persistência de Dados
- Armazenamento local usando Room Database
- Manutenção das dicas mesmo após fechar o aplicativo
  ![Dicas Salvas](images/saved_tips.png)

## Tecnologias Utilizadas
- Kotlin
- Android SDK
- Room Database
- MVVM Architecture
- Material Design Components
- LiveData e ViewModel
- RecyclerView
- Coroutines

## Arquitetura
O projeto segue a arquitetura MVVM (Model-View-ViewModel) e está organizado nas seguintes camadas:
- **Data**: Entidades e DAOs para o Room Database
- **Repository**: Camada de abstração para acesso aos dados
- **ViewModel**: Gerenciamento de estado e lógica de negócios
- **UI**: Activities e Adapters para a interface do usuário

## Identidade Visual
- Tema verde para reforçar a consciência ambiental
- Fundo suave em verde claro para melhor legibilidade
- Elementos de interface consistentes com o Material Design

## Equipe de Desenvolvimento
- Guilherme Loureiro 98722
- Tiago Gomes 95849

## Como Usar
1. Digite o título da dica sustentável
2. Adicione uma descrição detalhada
3. Clique em "ADICIONAR DICA"
4. Use a barra de pesquisa para encontrar dicas específicas
5. Visualize todas as dicas na lista principal

## Requisitos do Sistema
- Android 7.0 (API 24) ou superior
- Aproximadamente 10MB de espaço em disco

## Licença
Este projeto é parte de uma avaliação acadêmica para a FIAP.