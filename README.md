# Volvo Cars - Front-end Coding Test

Este projeto é uma implementação do teste de codificação front-end para a Volvo Cars, utilizando React e TypeScript para exibir carros elétricos "Recharge" no site com design responsivo.

## Visão Geral

O objetivo deste projeto é renderizar uma lista dos carros elétricos Volvo usando um design pré-definido tanto para **desktop** quanto para **mobile**. A estrutura de dados, fornecida em um arquivo JSON, é carregada e exibida no navegador de acordo com o design específico.

## Dados

Os dados dos carros estão localizados em `public/api/cars.json`, com a seguinte estrutura:

```json
[
  {
    "id": "xc90-recharge",
    "modelName": "XC90 Recharge",
    "bodyType": "suv",
    "modelType": "plug-in hybrid",
    "imageUrl": "/images/xc90_recharge.jpg"
  }
]
```
Funcionalidades
Renderização de Dados: Busca os dados de cars.json e renderiza uma lista dos carros.
Links Dinâmicos: Gera links para as páginas "Learn" e "Shop" de cada carro ao concatenar o id do carro com as URLs de base (/learn/ e /shop/).
Responsivo: Suporte para visualização tanto em desktop quanto em mobile.
Acessibilidade: Implementação com atenção a boas práticas de acessibilidade.
Componentização e Reutilização: Código estruturado para facilitar a reutilização de componentes.
Requisitos
Projeto criado com Next.js.
Suporte para navegadores modernos (evergreen).
Implementado em React e TypeScript.
Pontos Bônus
Utilização da biblioteca de componentes da Volvo, VCC-UI.
Barra de filtro no topo para filtrar carros por bodyType.
Como Rodar o Projeto
Clone este repositório:

bash
Copiar código
git clone <URL_DO_REPOSITORIO>
Instale as dependências:

bash
Copiar código
npm install
Inicie o servidor de desenvolvimento:

bash
Copiar código
npm run dev
Acesse o projeto em http://localhost:3000.

Estrutura de Código
Componentização: Os componentes são criados para serem reutilizáveis e organizados de forma modular.
Acessibilidade: As práticas de acessibilidade foram aplicadas para tornar o site mais inclusivo.
Design Responsivo: Adapta-se automaticamente para exibir corretamente em diferentes tamanhos de tela.
Envio
Este repositório é apenas um exemplo para o teste técnico. Para o envio final, compacte o projeto em um arquivo .zip e envie-o conforme as instruções recebidas, sem incluir dados pessoais no código.
