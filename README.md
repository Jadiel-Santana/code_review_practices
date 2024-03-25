# Práticas de Code Review

## O que é
* É um **processo de desenvolvimento** de software em que uma pessoa faz uma **revisão construtiva** do código de outro desenvolvedor, avaliando-o em relação aos **padrões de qualidade**.
* Aumenta **a qualidade do software** porque evita bugs, defeitos e vulnerabilidades de segurança.
* O código revisado tem **2x menos probabilidade de introduzir defeitos** em comparação com o código não revisado.


## Prós
* Encontrar defeitos antecipadamente, melhorando a qualidade do código e reduzindo erros.
* Melhorar a qualidade do código, por meio de formatação consistente, convenções de nomenclatura e adesão a padrões.
* Identificar soluções alternativas e melhores para o projeto.
* Facilitar a transferência de conhecimento e o compartilhamento de melhores práticas entre os desenvolvedores.
* Promover a conscientização e a transparência da equipe, permitindo feedbacks sobre as mudanças.
* Promover uma cultura de propriedade e responsabilidade compartilhada do código.
* Pode reduzir os custos de um projeto, ao evitar bugs.


## Contras
* Se o código revisado for muito grande, demandará de muito tempo do revisor.
* As revisões de código podem ser subjetivas e o feedback fornecido pode depender das preferências pessoais, preconceitos ou experiência do revisor.
* Em alguns casos, os desenvolvedores podem se tornar dependentes de revisores de código para detectar erros/problemas, em vez de assumirem a responsabilidade pela qualidade de seu próprio código.
* Precisam ser conduzidas adequadamente para não se tornar uma fonte de conflito dentro da equipe e causar diminuição da produtividade
* O desenvolvedor pode resistir as alterações sugeridas pelo(s) revisor(es), principalmente se sentir que seu código está sendo criticado injustamente ou que as alterações afetarão negativamente seu trabalho.


## Como fazer
* Aponte bugs, defeitos ou vulnerabilidades de segurança.
* Crie uma lista de verificação
  * **Legibilidade:** há algum comentário redundante no código?
  * **Segurança:** O código expõe o sistema a um ataque cibernético?
  * **Cobertura de testes:** Há necessidade de testar mais casos?
  * **Arquitetura:** O código usa encapsulamento e modularização para conseguir a separação de interesses?
  * **Reutilização:** o código usa componentes, funções e serviços reutilizáveis?
* Elogie os **pontos positivos**.
* A **Cisco** fez um estudo e descobriu que, depois que os desenvolvedores revisaram mais de **200 linhas**, sua capacidade de identificar defeitos diminuiu
* Gaste menos de 60 minutos revisando


## Eficácia
* Em **Code Complete**, Steve McConnell afirma que as revisões de código são o processo de qualidade de código mais eficaz:

![Effectiveness of software defect detection](https://github.com/Jadiel-Santana/code_review_practices/assets/48699769/9bae9440-a09f-4a33-baa1-9161c842b2bf)


## Referências
* https://josipmisko.com/code-reviews
* https://josipmisko.com/code-review-best-practices
* https://github.com/google/eng-practices













