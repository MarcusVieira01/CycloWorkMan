# **CycloWork Maintenance**

## Introdução
O CycloWorkMan tem por objetivo fornecer ao usuário um controle profissional sobre a manutenção de suas bicicletas. Não importa se é elétrica, MTB, Roaad ou qualquer outro tipo. 

## Funcionalidades

1. Registro da bicicleta - Registrar os atributos do equipamento com os atributos abaixo:
    
    BIKE
    | Tabela/Atributo    | Descrição                   | Tipo   | Extensão/Precisão | Nullable? | Incremento |
    | ------------------ | --------------------------- | ------ | ----------------- | --------- | ---------- |
    | bik_code(PK)       | Código de cadastro          | Number | 4                 | FALSE     | TRUE       |
    | bik_brand          | Fabricante                  | String | 100               | FALSE     | FALSE      |
    | bik_model          | Modelo                      | String | 100               | FALSE     | FALSE      |
    | bik_yearmdl        | Ano do modelo               | String | 4                 | TRUE      | FALSE      |
    | bik_price          | Preço de compra             | Float  | 6,2               | TRUE      | FALSE      |
    | bik_datecad        | Data de criação do cadastro | Date   | -                 | FALSE     | FALSE      |
    | bik_dateupd        | Data do último update       | Date   | -                 | FALSE     | FALSE      |
    | user_cod(FK)       | Vínculo do usuário          | Number | 10                | FALSE     | FALSE      |

    
