# Projeto de Criação de um Pipeline de ETL

Esse é um projeto do Bootcamp Ciência de Dados da DIO. Foi projetado para ajudar os alunos a terem uma compreensão prática do processo de ETL.

## Objetivos do Projeto

Esse Pipeline de ETL foi desenvolvido para extrair de duas bases de dados, cadastro de clientes e transações bancárias, quais clientes com maiores movimentações nas suas contas, como depósito, saques e transferências, vão receber descontos e ofertas especiais de investimento. Com esse conhecimento o setor responsável poderá entrar em contato com os clientes seja para parabeniza-los ou incentiva-los no próximo ano movimentarem mais as suas contas.

## Visão Geral do Projeto

- Foi criado dois arquivos no Excel contendo dados fictícios, um com o cadastro de clientes de um banco e outro com as transações bancárias.

    - Contém no arquivo cadastro de clientes: 
    
        __ID Cliente:__ a identificação do cliente;
        
        __Primeiro Nome:__ primeiro nome do cliente; 
        
        __Sobrenome:__ o sobrenome do cliente;
        
        __Data Nascimento:__ data de nascimento do cliente;
        
        __Idade:__ quantos anos o cliente tem;
        
        __Gênero:__ se é masculino ou feminino; 
        
        __Endereço:__ endereço do cliente; 
        
        __Telefone:__ número de telefone do cliente;
        
        __Número da Conta:__ número da conta do cliente.

    - Contém no arquivo trasações bancárias:
        
        __ID Transacao:__ identificação da transação;
        
        __Data:__ a data que ocorreu a transação; 
        
        __Tipo de Transacao:__ se foi, depósito, transferência ou saque;
        
        __Conta Origem Transacao:__ o número da conta que fez a transação.

- No Jupyter Notebook foi feito a extração desses arquivos usando o Pandas do Python.

- Foi feito as transformações necessárias como:  

    - A junção de algumas colunas, 
    
    - O preenchimento de valores ausentes, 
    
    - A remoção de valores duplicados,

    - Criação de duas tabelas, uma contendo clientes com que vão receber os benefícios e uma outra com os outros clientes que não receberam os benefícios.

- Por fim, foi criado dois arquivos csv com as duas tabelas criadas de clientes com e sem benefício.

## Autor

[Diego Fonseca](https://github.com/DiegowFonseca)
