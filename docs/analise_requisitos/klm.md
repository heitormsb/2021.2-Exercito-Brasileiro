<style>body {text-align: justify}</style>

# 1. Análise de Tarefas: KLM
O **KLM (Keystroke-level Model)** é um método que permite prognosticar o tempo de operação de uma tarefa sem erros de uma execução por um usuário experiente. Esse método não pressupõem um esforço cognitivo, por isso tem suas limitações. Usa uma lista operadores primários de operação, que são eles:

| **Operação** | **Duração Média (segundos)** |
|--------------|-------------------|
| K significa o apertar de uma tecla | (Mediano) 0,20 |
|--------------|-------------------|
| T[n] indica o tempo para se digitar uma tecla | n x K s |
|--------------|-------------------|
| P indica o apontar o mouse | 1,10 |
|--------------|-------------------|
| B indica o pressionar e soltar o botão do mouse | 0,10 |
|--------------|-------------------|
| H indica posicionar de mãos | 0,40 |
|--------------|-------------------|
| M indica prepação mental para ação | 1,20 |
|--------------|-------------------|
| R indica tempo de resposta do sistema | Depende do sistema |
|--------------|-------------------|
<small>Tabela 1 - Operadores e duração média de cada um.

# 2. Análise de desempenho do site do Exército Brasileiro com o KLM
<img src="../img_klm/Tabela2KLM.png" width="200px"><br><small>Tabela 2 - Análise de operadores pelos métodos propostos

## Referências bibliográficas
BARBOSA, Simone; SILVA, INTERAÇÃO HUMANO-COMPUTADOR. Local de publicação: Elsevier Editora Ltda, 2010.
AUAD, Tássio. Análise de Tarefas com GOMS, KLM e CMN-GOMS. The Blog of Tássio Auad, 2017. Disponível em: https://tassioauad.com/2017/04/10/analise-de-tarefas-com-goms-klm-e-cmn-goms/. Acesso em: 27, fevereiro e 2022

## Versionamento

|Versão|Data|Descrição|Autor|Revisor|
|------|----|:---------:|-----|-----|
|0.1|27/02/2022|Adicionando arquivo KLM|[Levi Queiroz](github.com/leviQ27)||
