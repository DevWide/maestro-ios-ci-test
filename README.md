# Projeto de Testes Automatizados com Maestro

Este projeto utiliza o [Maestro](https://maestro.mobile.dev/) para testes automatizados em aplicações mobile. Usamos o Maestro Cloud para gerenciar e executar os fluxos de teste, proporcionando uma configuração simplificada e uma fácil integração com pipelines de CI/CD.

## Estrutura do Projeto

- **package.json**: Arquivo de configuração do Node.js, com scripts úteis para o projeto.
- **samples**: Diretório que contém os fluxos de teste `.yaml` e o aplicativo `sample.zip` para teste.
  - `ios-flow.yaml`: Exemplo de fluxo de teste para iOS.
  - `sample.zip`: Binário do aplicativo de exemplo.

## Pré-requisitos

1. **Node.js**: Certifique-se de que o Node.js está instalado (para gerenciar dependências e scripts do projeto).
2. **Maestro CLI**: Instale o CLI do Maestro seguindo os passos abaixo.

### Instalação do Maestro CLI

Se você ainda não tem o Maestro instalado, execute o seguinte comando (caso use o Homebrew):

```bash
brew install maestro
````

