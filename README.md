#### Reforma Tributária - Nota Técnica nº 49/2024, COCAD/SUARA/RFB - Novo formato de CNPJ em alfanumérico:
- [Nota Técnica](http://sadd.receita.fazenda.gov.br/sadd-internet/pages/validadocumento.xhtml)
<p>O novo número de identificação – CNPJ alfanumérico – terá o mesmo tamanho que o número atual, com 14 posições. As oito primeiras posições terão caracteres alfanuméricos (letras e números) e identificarão a raiz do novo número. </p>
  <p></p>As quatro posições seguintes à raiz também terão caracteres alfanuméricos (letras e números) e identificarão a ordem do estabelecimento a ser inscrito.</p>
  <p>As duas últimas posições serão numéricas e identificam os dígitos verificadores deste CNPJ alfanumérico. O desenho abaixo identifica a transição da identificação numérica para alfanumérica:</p>
  <p></p>- A fórmula de cálculo do dígito verificador do CNPJ Alfanumérico não muda: foi mantido o cálculo pelo módulo 11.</p>
  <p></p>- Porém, para garantir a utilização dos atuais números do CNPJ (tipo numérico), será necessária a alteração do modo como se calcula o dígito verificador pelo módulo 11. Serão utilizados, no cálculo do módulo 11, os valores relativos a letras maiúsculas lastreadas na tabela denominada código ASCII, como solução para unificar a representação de caracteres alfanuméricos.</p>
<p>Na rotina de cálculo do Dígito Verificador (DV)no CNPJ, serão substituídos os valores numéricos e alfanuméricos pelo valor decimal correspondente ao código constante na tabela ASCII e dele subtraído o valor48. Desta forma os caracteres numéricos continuarão com os mesmos montantes, e os caracteres alfanuméricos terão os seguintes valores: A=17, B=18, C=19… e assim sucessivamente. Esta definição permitirá que o atual número do CNPJ tenha o mesmo cálculo do seu dígito verificador quando os sistemas iniciarem a identificação alfanumérica.</p>

![image](https://github.com/jayronsoares/cnpj_alpha/assets/248106/b0638362-9588-485e-8298-1ac42fd1a211)
