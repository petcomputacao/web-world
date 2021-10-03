# Contributing
Estamos aguardando ansiosamente para a sua contribuição! Leia a seguir como contribuir com nossos repositórios.

## Passos para contribuir:

### Issues:
A partir das issues você pode requisitar criações ou mudanças em um repositório. Essa é apenas uma das formas de começar a contribuir. Caso opte por ela, não esqueça de comentá-la avisando que está trabalhando naquilo, caso ela ainda não exista, crie-a!

### Clonar o repositório:
Aqui, você deve dar um fork do projeto. Clique no botão para Fork na página do github e, em seguida, copie a url do repositório do fork e clone na sua máquina. Fica nesse formato:
```sh
git clone https://github.com/<seu_usuario>/nome_do_repositorio.git
```
### Commit:
Ao terminar de clonar, será criado um repositório no seu computador. Agora você tem a liberdade de com seu editor favorito fazer as edições que você achar necessário. Quando terminar, dê o commit das suas alterações no seu repositório remoto seguindo os passos a seguir:

No terminal, entre no seu repositório
```sh
cd seu-repositorio
```
Esse primeiro comando vai adicionar todos seus arquivos do diretório atual para serem commitados 
```sh
git add . 
```
Agora você pode commitar seus arquivos, junto com sua mensagem do commit, é importante que você descreva de maneira simples e curta o que você fez 
```sh
git commit -m "<sua_mensagem_de_commit>"
```
Por fim, você enviará para seu repositório remoto todas as alterações feitas 
```sh
git push origin master
```
### Pull Request:
Indo para página do seu fork, será possível ver um aviso solicitando que você faça uma Pull Request para o repositório de origem. Ao clicar, aparecerá uma página em que você poderá preencher informações sobre o que você fez na sua pull request.

Outro material para se aprofundar: [material de aprofundamento](https://blog.da2k.com.br/2015/02/04/git-e-github-do-clone-ao-pull-request/) 
