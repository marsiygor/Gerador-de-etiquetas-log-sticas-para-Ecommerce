# Nome do meu projeto

Rápida descrição do objetivo de fazer esse projeto

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Titulo do meu projeto**
| :label: Tecnologias | Python
| :rocket: URL         | https://github.com/marsiygor/Gerador-de-etiquetas-logisticas-para-Ecommerce.git



## Detalhes do projeto

# Gerador de Etiquetas Logística para E-commerce

## Descrição

Este projeto é um gerador de etiquetas logística para e-commerce, que recebe a informação do destinatário e cria uma etiqueta com um código de barras único. A etiqueta pode ser impressa, ou seja, pode ser enviada diretamente para a impressora térmica. Esse código de barra, depois ele só é colado em cima da encomenda.

Este projeto tem como objetivo facilitar o processo de envio de encomendas para os vendedores online, automatizando a criação das etiquetas e garantindo a rastreabilidade das entregas.

## Status

Este projeto está em desenvolvimento.

## Funcionalidades

- Receber os dados do destinatário, como nome, endereço, telefone, etc.
- Gerar um código de barras único para cada etiqueta, usando o padrão EAN-13
- Formatar a etiqueta de acordo com as especificações dos Correios
- Enviar a etiqueta para a impressora térmica configurada
- Salvar a etiqueta em formato PDF, caso o usuário queira imprimir depois

## Demonstração

Aqui está uma imagem de uma etiqueta gerada pelo projeto:

![Exemplo de etiqueta](exemplo_etiqueta.png)

## Instalação

Para instalar e executar este projeto, você precisa ter os seguintes pré-requisitos:

- Python 3.8 ou superior
- Pip
- Uma impressora térmica compatível com o projeto

Depois de clonar o repositório, você deve instalar as dependências do projeto usando o comando:

```bash
pip install -r requirements.txt
```

Em seguida, você deve configurar a sua impressora térmica seguindo as instruções do fabricante.

## Execução

Para executar o projeto, você deve usar o comando:

```bash
python main.py
```

O projeto irá solicitar os dados do destinatário e gerar a etiqueta correspondente. A etiqueta será enviada para a impressora térmica e salva em PDF na pasta "etiquetas".

## Tecnologias

As tecnologias utilizadas neste projeto são:

- Python
- PyBarcode
- ReportLab
- PySerial

## Autores e Colaboradores

Este projeto foi criado por [Ygor Marsi] (https://github.com/marsiygor).

Se você quiser contribuir com este projeto, sinta-se à vontade para enviar um pull request ou entrar em contato comigo.

## Contato e Suporte

Se você tiver alguma dúvida, sugestão ou feedback sobre este projeto, por favor, envie um e-mail para [ygor.marsi@gmail.com] ou abra uma issue no GitHub.

Obrigado por usar este projeto! 😄
```




