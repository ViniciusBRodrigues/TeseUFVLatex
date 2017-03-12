# TeseUFVLatex
Modelo de Tese e Disertação da Universidade Federal de Viçosa, para LaTeX.

---

**Versão: 0.6**

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

- Coloque todas as figuras e gráficos do seu trabalho na pasta _imagens_

- Mova o seu arquivo de referências _(.bib)_ para o diretório da tese. De preferência, renomeie o seu arquivo para _referencias.bib_ e substitua o arquivo original

- A pasta _capitulos_ contém os arquivos para o preenchimento com os textos

**introducao.tex:** apague o arquivo de exemplo e cole o seu texto. Cuidado para não apagar o cabeçalho original. No cabeçalho, preencha com o seu nome e com o título resumido da tese nos locais indicados. Caso deseje, pode deixar em branco essas opções

**cap02.tex:** apague o exemplo e cole o seu texto. Não precisa preencher cabeçalho.

**se necessário, crie outros capítulos.**

---

- Abra o arquivo **main.tex**:

_verifique se todos os pacotes necessários estão instalados no seu sistema;_

verifique se os capítulos estão adicionados com o comando _imput_. Adicione ou remova-os de acordo com sua necessidade;

confirme o nome do seu arquivo de referências _.bib_;

caso necessário, você pode adicionar um arquivo _.pdf_ com análises estatísticas no fim do arquivo, com o comando **includepdf**.

**compile (o _main_ é o único arquivo que pode ser compilado).**

