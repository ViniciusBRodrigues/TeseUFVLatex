# TeseUFVLatex
Modelo de Tese e Disertação da Universidade Federal de Viçosa, para LaTeX.

---

**Versão: 0.7**

----


### Manual

- Inicialmente, preencha as informações dentro da pasta _preambulo_. Essa pasta contém os seguintes arquivos:
 
**capa.tex:** preencher o seu nome completo, o título da tese, nome do programa, o título (Magister Scientiae ou Doctor Scientiae), cidade e data

**aprovacao.tex:** preencher o seu nome completo, o título da tese, nome do programa, o título (Magister Scientiae ou Doctor Scientiae), data de aprovação e membros da banca. O mês deve ser preenchido por extenso. O nome dos membros _não_ deve conter prof. ou dr.; caso o número de membros na sua banca for menor ou maior do que o padrão do arquivo, basta modificar as linhas

**dedicatória.tex**

**epígrafe.tex**

**agradecimentos.tex**

**resumo.tex**

**Não compile nenhum dos arquivos anteriores.**

---

- A pasta _capitulos_ deve conter os seus arquivos .tex, figuras e .bib.

** Os capítulos devem ser compilados separadamente. Isso é necessário para que os arquivos auxiliares de referências sejam criados. Só dessa forma os capítulos terão referências separadas.**

---

- Uma vez compliado os capítulos separadamente, abra o arquivo **main.tex**:

_verifique se todos os pacotes necessários estão instalados no seu sistema;_

_verifique se os capítulos estão adicionados com o comando _input_. Verifique também se os caminhos até os .tex dos capítulos estão corretos. Adicione ou remova-os de acordo com sua necessidade;

_preencha as informações para serem exibidas no rodapé da tese (fancyhead e fancyfoot);

_caso necessário, você pode adicionar um arquivo _.pdf_ com análises estatísticas no fim do arquivo, com o comando **includepdf**.

**compile o arquivo _main_**

