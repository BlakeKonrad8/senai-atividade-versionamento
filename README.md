# senai-atividade-versionamento
solução de conflitos

## Objetivo
Demonstrar o uso de versionamento com branches, commits, merge e resolução de conflitos.

## Arquivos
- `index.html`: página principal da atividade.
- `README.md`: documentação do processo e da resolução.

## Histórico de execução (commits relevantes)
- `dcf051c` — commit inicial com `index.txt`.
- `012f686` — atualiza a estrutura do HTML e adiciona documentação na branch `feature/index-html`.
- `13db0d` — alteração que gerou conflito na branch `feature/conflict-test`.
- `7ea76c8` — alteração divergente na branch `feature/index-html`.
- `46df33c` — commit que resolveu o conflito e consolidou a versão final.

## Simulação de conflito
A branch `feature/conflict-test` alterou o mesmo trecho do arquivo `index.html` que a `feature/index-html`. As alterações divergiram e foram resolvidas com uma versão final consolidada em `feature/index-html`.

## Resultado final
A página principal está em HTML válido, com a versão final e a documentação no README.

## Observações e próximas ações
- Substituí os placeholders COMMIT_* pelos SHAs reais dos commits relevantes e completei a descrição truncada.
- O arquivo `index.txt` foi classificado como histórico — seu conteúdo foi movido para `history/index.txt` e o arquivo original foi marcado no topo com uma nota explicativa.
- Recomendo revisar / mesclar a branch final (`feature/index-html`) para `main` se desejar que a versão consolidada esteja definitivamente na branch principal. Depois de mescladas, as branches de feature podem ser removidas para limpeza do repositório.

## Acesso
Repositório: https://github.com/BlakeKonrad8/senai-atividade-versionamento
Arquivo principal (index): https://github.com/BlakeKonrad8/senai-atividade-versionamento/blob/main/index.html
