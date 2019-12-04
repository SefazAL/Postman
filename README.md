# Documentação API SEFAZ
A versão Web pode ser acessada no site oficial

 [http://www.sefaz.al.gov.br/api/](http://www.sefaz.al.gov.br/api/)

ou utilize o link abaixo para ter acesso direto à documentação do no Postman

[https://raw.githubusercontent.com/SefazAL/Postman/master/API.json](https://raw.githubusercontent.com/SefazAL/Postman/master/API.json)

## Para solcitar AppToken
Para ter acesso a API né necessário solicitar um token de acesso **(AppToken)**.
Para isso siga as recomendações oficiais (https://economizaalagoas.sefaz.al.gov.br/desenvolvedor.htm)



## Para importar a documentação no POSTMAN

1. Clique em **import** no canto superior esquerdo
    ![Tela 1](/docs/screen1.png)

2. Clique em **Import From Link** no modal e adicione o endereço da documentação da API e depois clique em **Import**.

    `https://raw.githubusercontent.com/SefazAL/Postman/master/API.json`

    ![Tela 2](/docs/screen2.png)

3. Substitua o campo `{{AppToken}}` do header da requisição pelo token recebido via e-mail.

    ![Tela 3](/docs/screen3.png)


### Contribuidores
@armandobs14