# Conflito de Resolução no Git

## Introdução
Os conflitos no Git ocorrem quando duas ou mais alterações são feitas na mesma linha de um arquivo, ou quando um arquivo é removido e modificado simultaneamente em diferentes branches. A resolução de conflitos é uma parte crucial do trabalho em equipe e do uso eficaz do controle de versão.

## Processos de Resolução de Conflitos
1. **Identificação do Conflito**
   - Quando você tenta fazer um merge ou rebase, o Git irá informar que houve um conflito.

2. **Análise do Conflito**
   - Utilize um editor de texto ou uma ferramenta de diffs para inspecionar as partes do código que estão em conflito.

3. **Resolução do Conflito**
   - Edite o arquivo para resolver as partes conflitantes. O Git marcará as seções conflitantes com `<<<<<<<`, `=======`, e `>>>>>>>`.
   - Escolha qual mudança deve ser mantida ou combine as alterações de uma maneira que faça sentido para o projeto.

4. **Marcação como Resolvido**
   - Após editar, você deve adicionar o arquivo novamente ao índice:
     ```bash
     git add <arquivo>
     ```
   - Continue seu merge ou rebase normal.

5. **Finalização**
   - Finalize suas alterações com um commit:
     ```bash
     git commit -m "Resolvendo conflito em <arquivo>"
     ```