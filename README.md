# Minicurso Fundamentos de Análise de Dados

Minicurso - Fundamentos de **Análise de Dados**


## Preparação do ambiente de trabalho

### Versionamento

- GITHUB E GITLAB: rede social para compartilhar código
- GIT: versionar o código
  
[OhShitGit](https://ohshitgit.com/)

### Versionando o Código

- Com as alterações feitas, cria-se uma nova versão do código. Ao invés de criar vários arquivos, o git gerencia essas mudanças. Fica slavo no Git como versões anteriores. Controle do Avanço.

```
git add .
```

'Git add ponto' - 'ponto' pega da página atual e as subpastas. O gitadd pede para o git monitorar todas as pastas e arquivos que estão dentro desta pasta

```
git commit - m "inserir mensagem aqui"
```

É uma etiqueta. Oque tem naquela versão? O que foi alterado? Monitora e põe uma etiqueta. 'Faz um commit'. Salvar a Versão e deixar disponível no remoto, com a etiqueta do que foi alterado.

### Sincronizar o repositório local com o remoto

- Deixar o Versionamento disponível no GitLab ou no GitHub. Interagir o seu computador com a núvem.  

```
git pull origin main
```

"Trazer para Você" - verifica se há algo novo no repositório remoto que está na nuvem, se houver alguma diferença, ele traz essa coisa nova para você em seu repositório local. 

```
git push origin main
```

Deixa as alterações feitas no local disponíveis no repositório para todos. 
### Comandos basicos Linux
cd
ls
cd ..
mkdir
history
cat
touch
rm - caminho_do_Arquivo
cp - caminho_de_origem caminho_destino
move - caminho de origem caminho destino

### Editor de Codigo
- [Vscode]
- Google Colab

### Ambiente Virtual
- Software utilizado para gestao do ambiente: `conda`

```
conda env create -f enviroment.yml
```

```
conda activate nome_ambiente
```

```
conda env uptade
```
git