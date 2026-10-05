# Atividade de Conflitos de Merge

Atividade em sala da disciplina de Desenvolvimento Mobile — **Aula 06: Correção e Versionamento** (Filipe Lopes, 29/09).

## Integrantes

| Nome | Matrícula | GitHub |
|---|---|---|
| João Victor Albernaz | _preencher_ | [@JoaoAlbernaz1](https://github.com/JoaoAlbernaz1) |
| João Pedro | _preencher_ | [@jotape148](https://github.com/jotape148) |

## O que foi pedido

- Criar um repositório público no GitHub, em dupla;
- Realizar modificações em arquivos e subir para o repositório em nuvem dentro de branches;
- Forçar conflitos de merge e solucioná-los;
- Enviar nome, matrícula da dupla e link do repositório.

## O que foi feito

- Repositório público criado com múltiplas branches `feature/*` partindo da `main`;
- Alterações feitas em paralelo nos arquivos `index.html`, `estilo.css` e `sobre.txt`;
- Conflitos de merge forçados propositalmente e resolvidos diretamente na `main`:
  - **Conflito de conteúdo** — duas branches alterando a mesma linha (cor de fundo verde x vermelho);
  - **Conflito modify/delete** — uma branch editando `sobre.txt` enquanto outra branch removia o arquivo.
- Histórico completo de commits e branches disponível neste repositório (aba *Insights → Network*).

## Arquivos

- `index.html` — página simples usada para gerar os conflitos;
- `estilo.css` — estilos da página;
- `sobre.txt` — texto de apoio, alvo do conflito modify/delete.
