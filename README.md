# Previsão do Tempo com IA Generalista

## Visão Geral
Este projeto é uma aplicação web para consulta de previsão do tempo em qualquer cidade do mundo, desenvolvida durante o curso de IA Generalista. O objetivo principal é testar funcionalidades, explorar conceitos de Inteligência Artificial e aprimorar habilidades em engenharia de prompt, utilizando abordagens como Traci e o método de árvore.

## Propósito
- Aprender e experimentar conceitos de IA na prática.
- Testar diferentes estratégias de engenharia de prompt para integração com APIs e automação de tarefas.
- Demonstrar como a IA pode aumentar a produtividade no desenvolvimento de software.

## Funcionalidades
- Busca de previsão do tempo em tempo real para qualquer cidade.
- Interface web responsiva, acessível e amigável.
- Tratamento de erros e cenários extremos.
- Testes automatizados para garantir robustez.

## Detalhes Técnicos
- **Frontend:** HTML5, CSS3 (responsivo e acessível), JavaScript puro (ES6+)
- **APIs Externas:**
  - [Open-Meteo Geocoding API](https://open-meteo.com/)
  - [Open-Meteo Weather API](https://open-meteo.com/)
- **Testes:** Jest (testes unitários automatizados)
- **Organização:**
  - `index.html`: Interface principal
  - `style/weather.css`: Estilos visuais
  - `scripts/app2.js`: Lógica de busca de clima
  - `scripts/weather-ui.js`: Integração da interface com a lógica
  - `scripts/app2.test.js`: Testes automatizados

## Camadas do Projeto

### 1. Interface do Usuário (Front-end)
- **Arquivos:** `index.html`, `style/weather.css`, `scripts/weather-ui.js`
- **Descrição:**
  - Proporciona uma experiência agradável, responsiva e acessível para o usuário.
  - Permite a entrada do nome da cidade e exibe o resultado da previsão do tempo.
  - A IA atuou sugerindo e otimizando a estrutura HTML, estilos CSS e lógica de interação, acelerando o desenvolvimento e garantindo boas práticas de acessibilidade.

### 2. Lógica de Negócio (API de Clima)
- **Arquivo:** `scripts/app2.js`
- **Descrição:**
  - Realiza a busca das coordenadas da cidade e consulta a previsão do tempo via APIs públicas.
  - Trata diferentes cenários de erro e retorna mensagens claras ao usuário.
  - A IA foi utilizada para estruturar a função, definir casos de teste e sugerir melhorias de robustez e clareza.

### 3. Testes Automatizados
- **Arquivo:** `scripts/app2.test.js`
- **Descrição:**
  - Garante o funcionamento correto da aplicação em diversos cenários (sucesso, erro, extremos).
  - A IA auxiliou na criação dos casos de teste, cobrindo situações reais e edge cases, otimizando o tempo de desenvolvimento e validação.

## Engenharia de Prompt
Durante o desenvolvimento, foram aplicados diversos modelos de engenharia de prompt, como Traci e o método de árvore, para:
- Estruturar melhor as solicitações à IA.
- Obter respostas mais precisas e contextualizadas.
- Explorar diferentes abordagens para automação e geração de código.

## Aumento de Produtividade com IA
A utilização de IA neste projeto permitiu:
- Redução significativa do tempo de desenvolvimento.
- Geração automática de código, testes e documentação.
- Sugestões de boas práticas e melhorias contínuas.

## Guia Prático: Como Executar o Projeto em Outra Máquina

### Pré-requisitos
- Navegador moderno (Chrome, Edge, Firefox, etc.)
- (Opcional) Node.js e npm para rodar os testes automatizados

### Passo a Passo
1. **Clone ou baixe o projeto:**
   - Via git:
     ```bash
     git clone <URL_DO_REPOSITORIO>
     ```
   - Ou baixe o ZIP e extraia em uma pasta.

2. **Acesse a pasta do projeto:**
   ```bash
   cd ProjetoIA
   ```

3. **Execute a aplicação:**
   - Basta abrir o arquivo `index.html` no navegador de sua preferência.
   - Não é necessário servidor local, pois a aplicação é 100% client-side.

4. **(Opcional) Rodar os testes automatizados:**
   - Instale o Node.js e npm, se ainda não tiver.
   - Instale as dependências:
     ```bash
     npm install
     ```
   - Execute os testes:
     ```bash
     npm test
     ```

### Observações
- O projeto consome APIs públicas, portanto é necessário estar conectado à internet.
- Caso queira customizar estilos ou funcionalidades, edite os arquivos na pasta `scripts` e `style`.

## Responsável
**Caique Gomes**

---
Este projeto é um experimento prático de integração entre desenvolvimento web e Inteligência Artificial, focado em aprendizado, inovação e aumento de produtividade.
