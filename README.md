# Desafio 0

Desafio preparatório para a [Maratona Behind the Code](https://ibm.biz/maratona) para testar os participantes. Este desafio 0 (zero) terá como prêmio, um drone `DJI Tello` para aquele que concluir com maior pontuação.

> Storytelling: A Maratona Behind the Code é uma oportunidade para te ensinar novas tecnologias (emergentes) através de treinamentos gratuitos liberados para os participantes inscritos. Mas será que todos conhecem um pouco sobre a IBM Cloud e até mesmo da Maratona? Suba o seu site e responda as perguntas feito pelo robô. 

> Dica: Acesse a [IBM Cloud](https://cloud.ibm.com/catalog) e conheça mais sobre alguns serviços.

## Como subir na IBM Cloud

1. Registrar-se na [Maratona Behind the Code](https://ibm.biz/maratona).

2. Registrar-se na [IBM Cloud](https://ibm.biz/BdzsFc).

[![Deploy to IBM Cloud](https://cloud.ibm.com/devops/setup/deploy/button.png)](https://cloud.ibm.com/devops/setup/deploy?repository=https://github.com/pablosls/desafio-0.git)

3. Clique no botão `Deploy to IBM Cloud` e depois...

    * Renomeie o nome do app para `{seu-id}-d0`.
    * Clique em `Create+` para criar uma chave de API na IBM Cloud.
    * Selecione a sua região (`Dallas` é a região mais usada), organização e espaço (ou use o `defaults`).
    * Clique em `Deploy`.

4. Na ferramenta, clieque em `Delivery Pipeline` para acompanhar o *deploy* do app. Uma vez na IBM Cloud, o app pode ser visto clicando em `Visit App URL`. Nota: Você pode ter que executar o processo novamente, caso apareça uma falha.

5. Para ver o app e os serviços criados e configurados, acesse o [dashboard](https://cloud.ibm.com/resources) da IBM Cloud. Este app deve ser renomeado por `{seu-id}-d0`.

## Executar localmente

### 1. Clone o repositório

```sh
git clone https://github.com/pablosls/desafio-0.git
```

### 2. Instale todas as dependências

```sh
cd desafio-0
npm install
```

### 3. Execute o app

```sh
npm start
```

## License

MIT License

Copyright (c) 2019 Maratona Behind the Code
