hello master module

[explicação de funcionamento do sub-modulo](https://gist.github.com/gitaarik/8735255)

## Considerações
- os sub-modulos são repositórios independentes dos master

## Comandos úteis
- `git submodule update --init --recursive` baixar submodulos e inicia-los caso necessário
- `git config --global alias.update '!git pull && git submodule update --init --recursive'` cria um atalho para o comando acima mais um pull do repositório principal, assim ao digitar `git update` todas as operações necessarias serão realizadas para atualizar o repositório pai e os filhos
