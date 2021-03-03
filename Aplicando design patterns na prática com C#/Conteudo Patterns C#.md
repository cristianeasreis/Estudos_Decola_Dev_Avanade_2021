## Aplicando design patterns na prática com C#

> **Desenvolver aplicações em C# confiáveis e estrutruras com as melhores práticas do mercado**

#### **Definição**

> Design Patterns são reutilizáveis para problemas comumente ocorridos (no contexto do design de software). Estes padrões foram iniciados como melhores práticas que foram aplicadas repetidamente a problemas semelhantes encontrados em diferentes contextos. Eles se tornaram populares depois que foram apresentados, de forma estruturada, no livro "Design Patterns - Elements of Resusable Object- Oriented Software"(Gang Of Four ) em 1994.
>
> O "Gang of Four" representa apenas uma de muitas coleções.

#### **O que é Gang of Four e porque usar**

> Os padrões são divididos em três partes.

### **Porque eu devo usar ?**

> - Produtividade : Estes padrões são modelos de resolução de problemas que já foram utilizados e testados inúmeras vezes;
> - Manutenção: Os padrões são baseados em soluções de baixo acoplamento e padronização de soluções;
> - Temos Universais : Os projetos são amplamente conhecidos desta forma as discussões técnicas são facilitadas, é mais simples falar o nome de um "design pattern" do que toda vez ter que explicar o seu comportamento.

### **Desuso**

>  Alguns padrões surgiram para solucionar limitações de linguagens de programação com menos recursos no que diz a respeito à abstração, nestes casos os padrões  eram como "gambiarras" que proporconavam à linguagem a possibilidade de fazer implementações que não eram possíveis nativamente.
>
> Linguagens mais recentes trazem alguns destes recursos nativamente, em alguns outros casos os padrões foram substituídos por padrões mais recentes . 
>
> O padrão Strategy, Por exemplo, pode ser subistituído pelo uso de uma função anõnima.

### **Soluções "Prontas"**

> Os padrões não são soluções prontas, códigos que podemos pegar pronto e "jogar"dentro do projeto, em alguns casos é necessário ajustar o padrão ao contexto em que o projeto necessita, e isso costuma demandar um conhecimento mais profundo por parte da equipe de desenvolvimento.

### **A "bala de prata"**

> É comum ver desenvolvedores que ao conhecer um novo padrão / técnica, tentam encaixar ele em todos os cenários, inclusive em situações onde uma abordagem mais simples seria suficiente para resolver o problema.
>
> Um martelo é ótimo para colocar um prego na parede, mais não funciona tão bem se você tiver um parafuso .
>
> Lembrem-se; Não é uma competição para ver quem usa mais padrões.

### **Os princípios do S.O.L.I.D.**

> - **S** - SRP - Princípio da Responsabilidade Única -Uma classe deve ter um, somente um motivo para mudar.
> - **O** - OCP- Princípio Aberto-Fechado - Você deve ser capaz de estender um comportamento de uma classe, sem modificá-lo.
> - **L** - LSP - Princípio da Substituição de Liskov - Aas classes base devem ser substituíveis por suas classes derivadas.
> - I - ISP - Princípio da Segregação da Interface - Muitas interfaces específicas são melhores do que uma interface única.
> - **D** - DIP - Princípios da Inversão da dependência - Dependa de uma abstração e não de uma implementação.

### **Problemas comuns em aplicações que Não usa o S.O.L.I.D**

> - Duplicidade de Código;
> - Código em estrutura coesa;
> - Dificuldade de manter / evoluir ;
> - Pequenos ajustes podem quebrar o código , inclusive em outras partes do sistema;
> - Dificuldade para executar e criar testes unitários;
> - Dificuldade de reaproveitar código para outras aplicações.



