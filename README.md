# 99 | Desafio desenvolvedor front-end

O objetivo deste desafio é avaliar seus conhecimentos em organização, estilo, boas práticas e habilidades front-end.

## Desafio
Criar uma aplicação que retorne a previsão do tempo com base na localidade. Essa consulta poderá ser feita de duas formas, utilizando a busca ou com base na latitude e longitude. [Clique aqui](https://metaweather-app.herokuapp.com) para ver o exemplo do projeto em funcionamento (o layout é apenas uma sugestão e poderá ser feito de outra forma, apenas atente-se ao comportamento dos componentes).

### Dicas
1. Utilize o proxy [https://metaweather-proxy-api.herokuapp.com/api](https://metaweather-proxy-api.herokuapp.com/api) para contornar o problema de CORS da API do MetaWeather. Exemplo de requisição: [https://metaweather-proxy-api.herokuapp.com/api/location/455827](https://metaweather-proxy-api.herokuapp.com/api/location/455827);
1. Caso opte em trabalhar com o Vuetify como framework, crie a aplicação utilizando o Vue.js na versão 2;
1. Sempre quando houver dúvida faça um teste na [aplicação de exemplo](https://metaweather-app.herokuapp.com) para mapear todos os comportamentos.

## Requisitos

### Funcionais
- Como usuário gostaria de digitar o nome de uma cidade no input e obter uma lista de previsões do tempo;
- Como usuário gostaria de clicar no botão ao lado do input e obter uma lista de previsões do tempo com base na minha localização (latitude e longitude);
- Como usuário gostaria de receber uma informação caso a consulta não retorne nenhum dado;
- Como usuário gostaria de receber um feedback (loading) quando a consulta está sendo feita;
- Como usuário gostaria de receber uma mensagem caso ocorra algum erro durante a requisição;
- Como usuário gostaria de obter as informações em PT-BR;
- Como usuário gostaria que a aplicação se adeque a dispositivos móveis.

### Não funcionais
- Tente reutilizar o máximo de código possível;
- Realize commits (git) constantes de acordo coma progressão das atividades;
- Aqui na 99 utilizamos o Vue.js, mas você pode utilizar qualquer framework JavaScript que quiser (indicamos Vue ou React). Se optar pelo Vue.js toda a documentação necessária para criar a aplicação está na seção **Links relacionados**;
- Pode ser utilizado frameworks como Bootstrap, Foundation, Semantic para construção do layout, na [aplicação de exemplo](https://metaweather-app.herokuapp.com/) foi utilizado o [Vuetify](https://vuetifyjs.com/en/getting-started/installation);
- Crie um arquivo `README.md` com informações úteis e instruções de como rodar o projeto.

## Funcionalidade extra (opcional)
Implemente um filtro que agrupe os dias por previsão, por exemplo, dias de sol, chuva, tempestade e etc.

## Etapas para o envio
1. Faça fork deste repositório;
1. Envie o link do seu repositório por e-mail, para que possamos avaliar seu código, boas práticas, padrões utilizados, frameworks e bibliotecas.

## Links relacionados
- [Projeto de exemplo](https://metaweather-app.herokuapp.com);
- [Vue.js guide](https://vuejs.org/v2/guide);
- [Criando um projeto Vue.js](https://cli.vuejs.org/guide/creating-a-project.html);
- [Vuetify (Vue.js framework baseado no material design)](https://vuetifyjs.com/en/getting-started/installation);
- [Documentação da API](https://www.metaweather.com/api).
