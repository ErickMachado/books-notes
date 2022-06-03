# Clean Code

- **Autor**: Robert C. Martin
- **Lançamento**: 2009
- **Versão lida**: PT-BR

# Capítulo 1 - Código limpo

- Para que a programação exista, ela depende de um problema que precisa ser resolvido. Desse problema, conseguimos retirar os requisitos. Traduzir e especificar os requisitos de tal forma que o computador possa executar, é programar.

  > Bobagens! Nunca nos livraremos dos códigos, pois eles representam os detalhes dos requisitos. Em certo nível, não há como ignorar ou abstrair esses detalhes; eles precisam ser especificados. E especificar requisitos detalhadamente de modo que uma máquina possa executá-los é _programar_ - E tal especificação é o código - **Página 2**

- Podem existir diversos motivos pelos quais uma pessoa escreve um código sujo, mas acredito que os principais são: falta de experiência, e pressa para terminar logo a feature.

  1. Falta de experiência;
  2. Desânimo de trabalhar no projeto;
  3. Pressa para terminar a feature;

  > É claro que um código ruim já lhe atrasou. Mas, então, por que você o escreveu dessa forma? Estava tentanto ser rápido? Estava com pressa? Provavelmente. Talvez você pensou que não tivesse tempo para fazer um bom trabalho; que seu chefe ficaria com raiva se você demorasse um pouco mais para limpar o seu código. - **Página 3**

- O código sujo impede que os desenvolvedores tenham mobilidade no projeto. As manutenções e criações de features ficam cada vez mais lentas porque os desenvolvedores gastam mais tempo entendendo o que foi feito no código do que escrevendo novos códigos. A gerência, tentando aumentar o ritmo das entregas, contratam mais devs para trabalharem no projeto, o que causa uma confusão ainda maior e piora ainda mais a produtividade.

- O que é um código limpo segundo alguns programadores experientes:

  - **Bjarne Stroustrup**

    - Lógica direta para dificultar o encobrimento de bugs;
    - Dependências mínimas (não necessariamente pacotes de terceiros);
    - Tratamento de erros;
    - Desempenho;
    - Faz bem apenas uma coisa;
