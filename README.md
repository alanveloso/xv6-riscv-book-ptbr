# xv6: um sistema operacional simples, tipo Unix, para ensino (Tradução)

Este é o projeto de tradução do livro "xv6: a simple, Unix-like teaching operating system" para o português. O objetivo deste projeto é fornecer um recurso acessível e compreensível para a comunidade de sistemas operacionais de língua portuguesa, especialmente para aqueles que só podem, ou preferem, ler em português.

## Importante: Revisão Contínua

A tradução de um livro técnico é um processo complexo e trabalhoso. Apesar do empenho e da boa intenção dos colaboradores, é natural que alguns erros ou imprecisões possam ter passado despercebidos durante o processo inicial de tradução.

Por isso, enfatizamos a importância da revisão contínua por parte da comunidade. Seu *feedback* e contribuições são essenciais para aprimorar e refinar esta tradução ao longo do tempo. Encorajamos todos os leitores a reportarem quaisquer erros encontrados, sugerirem melhorias na clareza ou precisão do texto, e participarem ativamente no processo de revisão.

Juntos, podemos garantir que esta tradução se torne um recurso cada vez mais valioso e confiável para a comunidade de programação competitiva de língua portuguesa.

## Sobre o Livro

Esta edição do livro foi convertida para LaTeX. Para compilá-la, certifique-se de ter uma distribuição TeX que inclua o comando `pdflatex`. Com isso, você poderá compilar o livro executando `make`, que irá clonar o próprio sistema operacional e gerar o livro em `book.pdf` no diretório principal.  

As figuras são desenhadas usando o `inkscape`.  


## Licença

A licença do livro é [LICENCE](/LICENSE).


## Contribuição

Apesar da tradução inicial estar completa, sempre há espaço para melhorias, seja na correção de erros, revisão de termos técnicos ou aprimoramento da fluidez do texto. Sua contribuição é bem-vinda!

<div align="center">
  <img src="https://repobeats.axiom.co/api/embed/4f1dd30f25229b935ea1f60eb4bb47af1ee7dc39.svg" alt="Repobeats analytics image" title="Repobeats analytics image"/>
</div>

### Como Contribuir

1. **Fork do Repositório**: Faça um fork deste repositório para sua conta do GitHub.

2. **Clone o Fork**: Clone o fork para sua máquina local.

3. **Edição**:
   - Para iniciantes no LaTeX, recomendamos usar o Overleaf, um editor LaTeX online:
     1. Baixe o repositório como um arquivo .zip
     2. No Overleaf, crie um novo projeto e faça upload do arquivo .zip
     3. Você pode então editar os arquivos diretamente no Overleaf
   - Se você já está familiarizado com LaTeX, pode editar os arquivos localmente com seu editor preferido.

4. **Tradução**: Traduza o texto, mantendo as estruturas LaTeX inalteradas. Foque apenas no conteúdo textual.

5. **Teste**: Se estiver usando o Overleaf, você pode compilar o documento para ver o resultado em PDF. Isso ajuda a verificar se não há erros de formatação.

6. **Commit e Push**: Faça commit das suas alterações e push para o seu fork no GitHub.

7. **Pull Request**: Abra um Pull Request para que suas alterações sejam revisadas e incorporadas ao projeto principal.

### Dicas

- Mantenha a formatação e estrutura originais do LaTeX.
- Preste atenção especial à tradução de termos técnicos.
- Se tiver dúvidas sobre algum termo ou trecho, deixe um comentário no PR para discussão.
- Para iniciantes: No arquivo `book.tex`, há a inclusão dos capítulos. Para incluir um capítulo específico no PDF compilado, remova o comentário da linha correspondente. Por exemplo:
  - Para incluir o Capítulo 1, mude `%\input{latex.out/unix}` para `\input{latex.out/unix}`
  - Isso permite que você trabalhe e visualize capítulos específicos sem precisar compilar o livro inteiro.