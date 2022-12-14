
![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016141198186008586/linha4.png)
## NEWMAN

O Newman é uma ferramenta que permite executar os testes do Postman por linha de comando e foi desenvolvido para ser utilizado com ferramentas de integração contínua.


![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016141198186008586/linha4.png)
## DASHBOARD

O newman é utilizado como um report de execução, onde apresenta: 

 - Quantos testes estão sendo executados; 
 - Quantos passaram; 
 - Quantos foram pulados; 
 - Ele também fornece quais os erros que estão sendo mostrados em suas validações e mostra informação de teste por teste.

![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016141198462820402/linha3.png)
### Minha dashboard de testes 
![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016012861509750824/NovoReport.png)

![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016141203240132629/linha1.png)
 ## COMO UTILIZAR O NEWMAN ?

Ok, primeiramente você precisará ter o [node.js](https://nodejs.org/en/) instalado em sua máquina!

 - Você pode checar se o node.js foi corretamente instalado na sua máquina rodando o comando:
```bash
node-v
```
![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016141208340406322/linha5.png)
## INSTALANDO O NEWMAN

Para instalar o newman é bem simples, basta você abrir o cmd e digitar:

```bash
npm install -g newman
```


![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1015831984511143967/instalando_o_newman.png)



Com a instalação do newman feita podemos instalar os reporters: 
```bash
npm install -g newman-reporter-html
```
```bash
npm install -g newman-reporter-htmlextra
```
Agora finalmente podemos decolar e criar nossos reports ! :)
![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016141198186008586/linha4.png)
## REPORTS

No nosso ultimo passo vou explicar como rodar um report!

Se você estiver utilizando o postman você precisa exportar a sua collection e sua enviroment: 
![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016141208340406322/linha5.png)
## Collections
![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1015833822375456881/exportcollect.png)
![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016141198462820402/linha3.png)
## Enviroments 
Acessar a aba de enviroments -

![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1015833831552598136/exportenv.png)

No canto direito, clicar no menu e em exportar - 
![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1015833839282700398/exportenv2.png)


Após salvar os dois documentos na mesma pasta você vai executar o  seguinte comando:
```bash
cd C:\Users\seunome\pastaquevcsalvou
depois :

newman run YourCollectionName.json -e YourEnvironment.json -n 2 -r htmlextra
```
![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016141198186008586/linha4.png)
## Atenção
- O "YourCollectionName.json" é o nome dos arquivos que você salvou 
- O número "2" é o número de interações que seu teste terá, você pode altera-lo!

Pronto, você está pronto para rodar seus reports! :)

![NPM](https://cdn.discordapp.com/attachments/969607335901298801/1016141203240132629/linha1.png)

// Amanda Paz.





