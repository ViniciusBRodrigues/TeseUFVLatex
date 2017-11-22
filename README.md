# TeseUFVLatex
Modelo de Tese e Disertação da Universidade Federal de Viçosa, para LaTeX.

O código já está no formato exigido pela UFV e compila as referências separadas por capítulos. Utiliza a fonte Palatino, que acredito ser mais confortável pra leitura.

[![DOI](https://zenodo.org/badge/84732333.svg)](https://zenodo.org/badge/latestdoi/84732333)

---

**Como citar:**

```
@Electronic{Rodrigues2017,
  Title                    = {Modelo de {T}ese e {D}isertação da {U}niversidade {F}ederal de {V}içosa, para {L}a{T}e{X}},
  Author                   = {Rodrigues, V. B.},
  Language                 = {Latex},
  Url                      = {https://github.com/ViniciusBRodrigues/TeseUFVLatex},
  Doi                      = {10.5281/zenodo.905784}
}
```

----


### Como utilizar:

- Inicialmente, preencha as informações no arquivo _dados.tex_ (nome, titulo, cidade, membros da banca, etc.).

- A pasta _preambulo_ contém os seguintes arquivos:
 
**capa.tex:** Não modificar nada;

**aprovacao.tex:** não modificar. O nome dos membros _não_ deve conter prof. ou dr.; caso o número de membros na sua banca for menor ou maior do que o padrão do arquivo, basta modificar as linhas;

**dedicatória.tex** não modificar.

**epígrafe.tex** não modificar.

**agradecimentos.tex** não modificar.

**resumo.tex** não modificar.

**Não compile nenhum dos arquivos anteriores.**

---

- A pasta _capitulos_ deve conter os seus arquivos .tex, figuras e .bib.

**Os capítulos devem ser compilados separadamente. Isso é necessário para que os arquivos auxiliares de referências sejam criados. Só dessa forma os capítulos terão referências separadas.**

---

- Uma vez compliado os capítulos separadamente, abra o arquivo **main.tex**:

_verifique se todos os pacotes necessários estão instalados no seu sistema;_

_verifique se os capítulos estão adicionados com o comando input. Verifique também se os caminhos até os .tex dos capítulos estão corretos. Adicione ou remova-os de acordo com sua necessidade;_

_caso necessário, você pode adicionar um arquivo .pdf com análises estatísticas no fim do arquivo, com o comando includepdf._

**compile o arquivo _main_**

