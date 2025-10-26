# Estrutura do Projeto

Este documento explica a função de cada pasta e arquivo criado neste projeto.

## public/
Contém arquivos estáticos servidos como estão, como favicon, manifest ou imagens. Usamos `.gitkeep` para manter a pasta no controle de versão vazia.

## src/
Diretório principal do código fonte.

- `components/`: Componentes reutilizáveis para a interface do usuário.
- `features/`: Módulos organizados por domínio ou funcionalidade.
- `services/`: Código para integração com APIs e chamadas HTTP.
- `hooks/`: Hooks personalizados para lógica reutilizável em React (ou outra lib).
- `styles/`: Estilos globais e variáveis de design ou tokens.
- `main.tsx`: Ponto de entrada da aplicação, onde o app é inicializado.

## package.json
Arquivo de configuração para gerenciamento de dependências e scripts para build e start do projeto.

## structure/README.md
Documento que explica a estrutura do projeto e responsabilidades de cada pasta/arquivo.
