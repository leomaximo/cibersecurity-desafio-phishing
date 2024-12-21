# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Custom Import ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com


### Alternativa contra defesa do site
->Uma possibilidade de resolução do caso, está no próprio ```setoolkit``` onde se pode realizar ```Custon Import```. Nesta opção iremos realizar uma clonagem e em seguida uma pequena edição no código fonte  original. 

![CUSTOM IMPORT](https://github.com/user-attachments/assets/604cae8e-111e-43c3-a530-252871c19bc6)

### Salvar página e ID button

->Na página original, iremos salvar a página com o nome ```index.html``` e em seguida iremos inspecionar o botão ```Log In```. 

![ETAPA SALVAR PAG E ID BUTTON](https://github.com/user-attachments/assets/9f8e1356-3777-45eb-9cad-2321909af532)

->Em seguida iremos indentificar o button ID. 

![Identificando ID button](https://github.com/user-attachments/assets/ff090128-63be-4c71-ad11-42f34120e83c)

### Editando código fonte

->Em seguida iremos copiar o código fonte do site 'www.facebook.com' e colar no nosso arquivo ```index.html```

![COPIANDO COD FONTE DA PAG ORIGINAL](https://github.com/user-attachments/assets/d74c3cba-c485-42a7-9376-fd83dc89e53d)

->Agora no código fonte iremos identificar em qual script o ```button ID``` está sendo chamado e em seguida apagar.

![Deletando script](https://github.com/user-attachments/assets/c8738d9c-cbff-4086-8a5d-a154d369affd)

->Em seguida no ```setoolkit``` iremos selecionar a opção ```Custom Import``` e apontar para a pasta onde o código fonte manipulado se encontra.

->Copie o diretorino da pasta onde se localiza o código fonte manipulado.

->Cole o diretório no setoolkit. 

![COLAR O DIRETORIO](https://github.com/user-attachments/assets/4f49c8a4-9877-4af6-b537-b3ca57533681)

->Selecione ```Copy the entire folder```

![OPÇÃO COPIAR A PASTA INTEIRA](https://github.com/user-attachments/assets/7ecadd9c-1229-4e74-9894-f423d6023aa3)

->Em seguida defina a ```URL``` do site importado.

![DEFINIR COM A URL DA PAG FONTE](https://github.com/user-attachments/assets/50e80c13-6ea2-42e9-ab2c-399edf6f20dd)

## Resultado após aplicação do método contra a defesa
![42eb6c7e-6ce2-424a-bf53-4cc8967832ef](https://github.com/user-attachments/assets/80ee4634-ee4c-4775-b737-14a90ce4f3a2)






