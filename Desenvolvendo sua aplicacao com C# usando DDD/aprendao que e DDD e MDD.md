### **Domain Driven Desing**

#### **Introdução ao curso e o que é Domain-Driven Design**

> "É uma abordagem de design de software disciplinada que reúne um conjunto de conceitos , técnicas e princípios para construção de softwares baseados em um modelo de domínio."
>
> Domínio é todo e qualquer conhecimento utilizado em uma determinada área.

#### **Um pouco de história** 

> Ele veio do título do livro escrito por Eric Evans, dono da DomainLanguage, uma empresa especializada em treinamento e consultoria para desenvolvimento de software.
>
> O livro de Evans é um grande catálogo de Padrões , baseados em experiências do autor ao longo de mais de 20 anos desenvolvendo software utilizando técnicas de Orientação a Objetos.

#### **Principais conceitos do DDD**

> - Alinhamento do código com o negócio: o contato dos desenvolvedores com os especialistas do domínio é algo essencial quando de faz DDD (o pessoal de métodos ágeis já sabe disso faz tempo). Se faz necessário o uso de uma linguagem úbiqua (comum entre todos) para descrever o domínio de suas regras .
> - Favorecer reutilização : os blocos de construção que veremos adiante,facilitam aproveitar um mesmo conceito de domínio ou um mesmo código em vários lugares;
> - Mínimo de acoplamento: Com o modelo bem feito, organizado, as várias partes de um sistema interagem sem que haja muito dependência entre módulos ou classes de objetos de conceitos distintos;
> - Independência da Tecnologia : DDD não foca em tecnologia, mais sim em entender as regras de negócios e como elas devem estar refletidas no código e no modelo de domínio . Não que a tecnologia usada não seja importante , mas essa não é uma preocupação de DDD.

#### **Criando um modelo de domínio (MDD)**

> A ideia por trás de MDD é de que seu modelo abstrato deve ser uma representação perfeita do seu domínio . Tudo que existe no seu negócio deve aparecer no modelo. Só aparece no modelo aquilo que está no negócio.
>
> O desenho do modelo é criado em conjunto entre especialistas de negócio e domínio , analistas, arquitetos e desenvolvedores, utilizando a linguagem úbiqua para que todos tenha o mesmo entendimento do domínio.
>
> O processo de maturação de um sistema desenvolvido usando MDD deve ser contínua . O modelo servirá de guia para a criação do código e , ao mesmo tempo, o código ajuda a aperfeiçoar o modelo.

#### **Blocos de construção do MDD** 

> Uma vez que decidimos criar um modelo usando MDD, precisamos , inicialmente , isolar o modelo de domínio das demais partes que compõem o sistema. Essa separação pode ser feita utilizando-se uma arquitetura em camadas, que dividirá nossa aplicação em quatro partes:
>
> 1. Interface de Usuário - parte responsável pela exibição de informações do sistema ao usuário e também por interpretar comandos do usuário;
> 2. Aplicação- essa camada não possui lógica de negócio. Ela é apenas uma camada fina, responsável por conectar a interface de Usuário às camadas inferiores;
> 3. Domínio- representa os conceitos, regras e lógicas de negócio. Todo o foco de DDD está nessa camada . Nosso trabalho , daqui para frente , será aperfeiçoar e compreender profundamente essa parte;
> 4. Infra-estrutura - fornece recursos técnicos que darão suporte às camadas superiores. São normalmente as partes de um sistema responsáveis por persistência de dado, conexões com bando de dados, envio de mensagens por redes, gravação e leitura de discos , etc,







