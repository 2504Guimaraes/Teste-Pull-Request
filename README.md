# Teste de Pull Requests - Tutorial
Repositório feito para ser um tutorial ilustrativo, para
auxílio do nosso TCC (TCC Fatec Rubens Lara 2º Sem 2021) e afins! 😄

## 1º Passo: Crie ou já tenha um repositório
No meu caso, eu criei esse repositório para servir de base para esse
tutorial. No momento em que eu escrevi isso ele está com essa cara:

![img-repositorio](https://raw.githubusercontent.com/2504Guimaraes/Teste-Pull-Request/master/images/img1.PNG)

Meu repositório terá um projeto de teste dentro dele, ele tem essa aparência:

![img-meu-projeto-de-teste](https://raw.githubusercontent.com/2504Guimaraes/Teste-Pull-Request/master/images/img2.PNG)


Vamos testar nossos pull requests nele.

## 2º Passo: Crie um novo branch / galho para o seu projeto

Imagine o seguinte:

Você tem um repositório com um projeto seu, e você quer testar modificações
que inovarão seu projeto, mas você não tem certeza se as mesmas darão certo.
Então logicamente, você cria um novo branch para testar suas ideias.

Eu vou fazer os seguintes comandos, eles servem para todas as situações na qual temos um projeto e queremos criar um novo branch para adicionar uma modificação no mesmo.

    1. git branch   <- mostra todos os seus branchs (por padrão você tem só 1).
    2. git branch --show-current  <- mostra o branch em que você está dentro.
    3. git branch "novoCss"  <- cria um novo a partir desse branch ao qual você está.
    4. git checkout novoCss  <- sai do branch atual e faz você entrar no branch criado.

Dependendo do seu caso, você pode fazer apenas os passos 3 e 4. E se você não estiver no branch o qual você deseja criar algo a partir; digite o comando:

    git checkout nome-branch-que-vc-quer

Assim você vai entrar nele, caso ele exista.

Bem, eu vou criar um novo branch com esse nome *novoCss* e entrarei no mesmo para "testar" minha nova ideia genial, e se bem sucedida, mesclá-la ao meu branch principal. 

### Conclusão do 2º Passo

Bem, minha *"ideia genial"* era simplesmente adicionar CSS ao meu projeto, no caso, ficou desse jeito:

![img-adicao-css-no-proj](https://raw.githubusercontent.com/2504Guimaraes/Teste-Pull-Request/novoCss/images/img3.PNG)