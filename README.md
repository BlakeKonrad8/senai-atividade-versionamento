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
- COMMIT_CONFLICT_TEST — alteração que gerou conflito na branch `feature/conflict-test`.
- COMMIT_INDEX_HTML_CHANGE — alteração divergente na branch `feature/index-html`.
- RESOLUTION_COMMIT — commit que resolveu o conflito e consolidou a versão final.

(As referências COMMIT_* serão substituídas pelos SHAs reais no relatório final.)

## Simulação de conflito
A branch `feature/conflict-test` alterou o mesmo trecho do arquivo `index.html` que a `feature/index-html`. As alterações divergiram e foram resolvidas com uma versão final consolidada em `feature/index-html`.

## Resultado final
A página principal está em HTML válido, com a versão final e a documentação no README.
