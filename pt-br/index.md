# NEO White Paper

## Uma rede distribuída para *Smart Economy*.

### Objetivo do projeto NEO: *Smart Economy*

O NEO é um ecosistema digital que utiliza as tecnologias de *blockchain* e de identidade digital a fim de digitalizar e auto-gerenciar ativos do mundo real em uma rede distribuída. 

### Ativos digitais

Ativos digitais são ativos programáveis que existem sob a forma de dados eletrônicos. Com a tecnologia *blockchain*, a digitalização de ativos pode ser descentralizada, confiável, rastreável, altamente transparente e livre de intermediários. Na *blockchain* NEO, os usuários podem registrar e transferir vários tipos de ativos. É possível comprovar a relação entre os recursos físicos (no mundo real) e digitais (na rede NEO) ao registrar tais recursos através de uma identidade digital válida, uma vez que os ativos registrados dessa forma são protegidos por lei.

O NEO possui duas formas de ativos digitais: ativos globais e ativos contratuais. Os ativos globais são registrados publicamente na rede e podem ser identificados por todos *smart contracts* e clientes/usuários. Já os ativos contratuais são registrados de forma privativa no armazenamento do próprio *smart contract*, sendo reconhecíveis apenas dentro do ambiente do contrato em questão, ou seja, apenas para os clientes compatíveis com as normas de tal contrato.

### Identidade Digital

Como o nome sugere, identidade digital refere-se às informações de identificação de indivíduos, organizações, entidades, etc, em formato eletrônico. Atualmente o sistema de identidade digital mais moderno e amplamente utilizado no mundo é baseado no padrão PKI (do inglês *Public Key Infrastructure*) x.509. No NEO implementaremos um conjunto de normas de identidade digital compatíveis com o PKI x.509, utilizando a *blockchain* para substituir o Protocolo de Status de Certificado Online (OCSP) no gerenciamento da Lista de Revogação de Certificado (CRL) x.509. O NEO também  terá suporte *point-to-point* ao conceito WoT (do inglês *Web of Trust*). Os mecanismos de verificação e garantia de identidade digital do NEO incluirão reconhecimento facial, reconhecimento de impressões digitais e de voz, SMS, entre outros métodos de autenticação multifacetada.

### *Smart Contracts*

O conceito de "contrato inteligente" foi proposto pela primeira vez pelo criptógrafo Nick Szabo em 1994, apenas cinco anos após a criação da World Wide Web. De acordo com a definição de Szabo, *"quando uma condição pré-programada é desencadeada, o contrato inteligente executará os termos contratuais correspondentes"*. A tecnologia de *blockchain* viabiliza um sistema descentralizado, inviolável e altamente confiável, no qual os contratos inteligentes se tornam muito úteis. O NEO possui um sistema de contrato inteligente independente, chamado NeoContract. Para fins de terminologia adequada, seguiremos fazendo uso do termo internacional "*smart contract*" ao invés de "contratos inteligentes".

O NeoContract é o grande fator que viabiliza uma integração sólida entre a rede NEO e o ambiente de desenvolvimento do NEO. Os desenvolvedores não precisam aprender uma nova linguagem específica para a programação de *smart contracts*, mas sim, usar C#, Java e outras linguagens convencionais, permitindo que milhões de pessoas em todo o mundo desenvolvam *smart contracts* em seus ambientes IDE familiares (Visual Studio, Eclipse, etc). Aliado a isso, a máquina virtual da NEO, a NeoVM, possui vantagens de precisão, capacidade para grande simultaniedade e alta escalabilidade. O NeoContract terá um *white paper* exclusivo descrevendo os detalhes de sua implementação.

### Software e Ecossistema

O ecossistema é a essência da comunidade *open source*. Para alcançar o objetivo de uma rede para a *Smart Economy*, o NEO está comprometido com o desenvolvimento do seu ecossistema, fornecendo ferramentas modernas de desenvolvimento, organizando atividades de educação e treinamento, melhorando a qualidade de sua documentação e fornecendo suporte financeiro aos colaboradores. Planejamos recompensar as melhorias e dar suporte ao trabalho nas seguintes soluções tecnológicas na rede NEO:

🔹 Software de nó  

•	Um software para PC completo 

•	Uma versão "lite" de software para PC, leve e que proporcione melhor experiência ao usuário

•	Clientes Web/Android/iOS que não precisem sincronizar com a *blockchain*

•	Hardware para carteira de usuário

🔹 Blockchain Explorer

🔹 Kit para Desenvolvimento de Software (SDK)

•	Suporte às linguagens Java/Kotlin, .NET C#/VB, JavaScript/Typescript, Python, Go

🔹 Compilador de *Smart Contracts* e Plugin IDE

•	C# / VB.Net / F#, Studio Visual

•	Java / Kotlin, Eclipse

•	C / C++ / GO

•	JavaScript / TypeScript

•	Python / Ruby

🔹 dApps ( Aplicações Descentralizadas )

•	*Smart fund* - Fundo financeiro inteligente

•	*Smart contracts* assistidos por IA

•	Rede Social

•	Provedores de tokens automáticos de liquidez

•	Intercâmbio descentralizado

•	Protocolo de comunicação segura

•	Mercado de intercâmbio de dados

•	Mercado de intercâmbio de propriedade intelectual

•	Previsão de mercado

•	Mercado de publicidade

•	Mercado Hashpower

•	Mercado NeoGas

## Modelo da Gestão NEO

### Modelo econômico

O ecossistema NEO possui dois tokens nativos: NEO e NeoGas (abreviado a GAS).

O NEO é limitado em um máximo de 100 milhões de tokens disponíveis e representa o direito de participar no gerenciamento da rede, como em votações para definições e mudanças de parâmetros da rede, e assim por diante. A unidade mínima de NEO é 1 e os tokens não podem ser subdivididos.

O GAS, com limite máximo total de 100 milhões, é o token com papel de alimentação da rede, utilizado no controle de recursos da mesma. A rede NEO cobra GAS pelas operações e armazenamento de tokens e *smart contracts*, assim gerando incentivos para os Nós de Consenso e impedindo o abuso de recursos. A unidade mínima de GAS é 0,00000001.

No bloco gênese da rede NEO, 100 milhões de NEOs foram gerados, porém nenhum GAS. 100 milhões de GAS, correspondentes aos 100 milhões de NEO, serão gerados através de um algoritmo de decaimento por um período de aproximadamente 22 anos. Quando NEO é transferido para um novo endereço, o GAS subsequentemente gerado por esse NEO será creditado ao novo endereço.

Será estabelecido através de votação um limiar para isentar o GAS de certa quantidade de transações, como transferências e operações de *smart contracts*, a fim de incentivar e melhorar a experiência de novos usuários. Quando uma grande quantidade de transações *spam* ocorrer, o NeoID será usado para priorizar transações e *smart contracts* com identidades digitais qualificadas. Transações e *smart contracts* sem identidades qualificadas podem ser priorizados através do pagamento de um valor em GAS.

### Mecanismo de Distribuição

Distribuição NEO:

Os 100 milhões de tokens NEO serão divididos em duas partes. A primeira parcela é de 50 milhões de tokens distribuídos proporcionalmente aos apoiadores da NEO durante o financiamento colaborativo. Esta parcela já foi distribuída.

A segunda parcela é de 50 milhões de NEOs administrados pelo Conselho NEO para apoiar o desenvolvimento, operação e manutenção a longo prazo da NEO e seu ecossistema. A NEO nesta parcela tem um período de bloqueio de 1 ano e é desbloqueado somente após 16 de outubro de 2017. Essa parcela não entrará nas bolsas e é apenas para suporte a longo prazo dos projetos da NEO. Para isso os planos são os seguintes:

🔹 10 milhões de tokens (10% do total) serão usados para motivar desenvolvedores NEO e membros do Conselho NEO

🔹 10 milhões de tokens (10% do total) serão usados para motivar desenvolvedores no ecossistema NEO

🔹 15 milhões de tokens (15% do total) serão utilizados para investir em outros projetos de cadeia de blocos, pertencentes ao Conselho NEO e utilizados apenas para projetos NEO

🔹 15 milhões (15% do total) serão mantidos como contingência

🔹 O uso anual de NEO em princípio não deve exceder 15 milhões de tokens

Distribuição de GAS:

O GAS é gerado com cada novo bloco. A quantidade total inicial de GAS é zero. Com a crescente taxa de geração de novos blocos, o limite total de 100 milhões de GAS será alcançado em cerca de 22 anos. O intervalo entre cada bloco é de cerca de 15-20 segundos, e 2 milhões de blocos são gerados em cerca de um ano.

Cada ano serão gerados cerca de 2 milhões de blocos e a geração inicial será de 8 GAS por bloco. Haverá uma redução anual de 1 GAS por bloco, por ano, para coincidir com a passagem de cada 2 milhões de blocos. A redução continuará a apenas 1 GAS por bloco e será realizada a essa taxa por cerca de 22 anos. Após o 44º bloco, o GAS total gerado terá atingido os 100 milhões e, a partir deste ponto, não haverá mais geração de GAS a partir de novos blocos.

De acordo com esta curva de lançamento, 16% do GAS serão criados no primeiro ano, serão criados 52% do GAS nos primeiros quatro anos e 80% do GAS serão criados nos primeiros 12 anos. Esses GAS serão distribuídos proporcionalmente de acordo com a relação de retenção NEO, registrada nos endereços correspondentes. Os titulares do NEO podem iniciar uma transação de reivindicação a qualquer momento e reivindicar esses tokens GAS em seus endereços de espera.

### Mecanismo de governança

Governança da cadeia: os titulares do token NEO são proprietários e gerentes das redes, gerenciando a rede através da votação na rede, usando o GAS gerado a partir de NEO para utilizar as funções na rede. Os tokens NEO podem ser transferidos.

Governança fora da cadeia: o Conselho NEO é composto pelos membros fundadores do projeto NEO, nos quais o comitê de gestão, o comitê técnico e o secretariado, respectivamente, são responsáveis pela tomada de decisões estratégicas, pela tomada de decisões técnicas e pela implementação específica. O Conselho NEO é responsável pela comunidade NEO para a promoção e desenvolvimento do ecossistema NEO como o seu principal objetivo.

## Implementação da tecnologia NEO

### Mecanismo de Consenso: dBFT

O dBFT é uma sigla em inglês para ‘delegated Byzantine Fault Tolerance’, chamado de tolerante de falhas byzantinas delegadas, um mecanismo de consensus tolerante a falhas bizantino que permitem a participação em grande escala no consenso através da votação por procuração. O titular do token NEO pode, ao votar, escolher o contador que ele aceitar. O grupo selecionado de contadores, através do algoritmo BFT, alcança um consenso e gera novos blocos. A votação na rede NEO continua em tempo real, em vez de em conformidade com um prazo fixo.

O dBFT fornece tolerância a falhas de f = ⌊ (n-1) / 3 ⌋ para um sistema de consenso composto de ‘n’ nós de consenso. Esta tolerância a falhas também inclui segurança e disponibilidade, resistente a falhas gerais e bizantinas e é adequada para qualquer ambiente de rede. O DBFT tem boa finalidade, o que significa que uma vez que as confirmações são finais, o bloco não pode ser bifurcado e a transação não será revogada ou revertida.

No mecanismo de consenso NEO dBFT, levando cerca de 15 a 20 segundos para gerar um bloco, o rendimento da transação é medido até cerca de 1000TPS, o que é um excelente desempenho entre as cadeias públicas. Através da otimização apropriada, há potencial para atingir 10.000TPS, permitindo-lhe suportar aplicações comerciais em larga escala.

O dBFT combina tecnologia de identidade digital, o que significa que os contadores de livros podem ser um verdadeiro nome do indivíduo ou instituição. Assim, é possível congelar, revogar, herdar, recuperar a transferência de propriedade devido a decisões judiciais sobre eles. Isso facilita o registro de ativos financeiros compatíveis na rede NEO. A rede NEO planeja suportar essas operações quando necessário.

### Sistema de contrato inteligente: NeoContract

O sistema de contratos inteligentes da NEO consiste em três partes:
NeoVM – Maquina Virtual de Cadeia de Blocos Universal:

O NeoVM é uma máquina virtual leve e de uso geral cuja arquitetura é muito próxima da JVM e do .NET Runtime, semelhante a uma CPU virtual que lê e executa instruções no contrato em sequência, executa o controle do processo com base na funcionalidade das operações de instrução , Operações lógicas e assim por diante. Possui uma boa velocidade de inicialização e versatilidade, é muito adequado para pequenos programas, como contratos inteligentes, também pode ser portado para não-blocos da cena ou integrado com o IDE para fornecer uma experiência de desenvolvimento ideal. A funcionalidade do NeoVM pode ser estendida, como a introdução de um mecanismo JIT (compilador em tempo real), melhorando assim a eficiência da implementação.

InteropService - Serviços interoperáveis:

Utiliza-se para carregar o ledger de blocos, ativos digitais, identidade digital, área de armazenamento persistente e outros serviços subjacentes. Eles são como máquinas virtuais que são fornecidas para máquinas virtuais, permitindo que contratos inteligentes acessem esses serviços em tempo de execução para conseguir algumas funcionalidades avançadas. Através deste design de baixo acoplamento, o NeoVM pode ser portado para qualquer cadeia de blocos ou mesmo sistema não bloqueado usado, aumentando a utilidade dos contratos inteligentes.

DevPack - Compilador e plug-in IDE:

O DevPack inclui o compilador de linguagem de alto nível e o plug-in IDE. Como a arquitetura do NeoVM é muito semelhante à JVM e ao .NET Runtime, os compiladores no DevPack podem compilar o código de byte Java e o .NET MSIL no conjunto de instruções do NeoVM. Os desenvolvedores de Java / Kotlin, C # não precisam aprender novos idiomas e começarão imediatamente a desenvolver contratos inteligentes em ambientes VS, Eclipse e outros IDE familiares. Isso reduz consideravelmente a curva de aprendizado para o desenvolvimento de contratos inteligentes, o que nos permite construir facilmente uma comunidade vibrante em torno do NeoContract.

O NeoContract pode criar uma árvore de chamadas de contratos inteligentes através de análise estática antes de executar um contrato inteligente. Através da árvore de chamadas determinista, o nó NEO pode fragmentar dinamicamente o contrato inteligente para alcançar uma expansão teoricamente ilimitada, que supera o "efeito de interferência" causado pela fragmentação estática de outros sistemas de cadeia de bloqueios.

### Acordo de interoperabilidade entre cadeias: NeoX

O NeoX é um protocolo que implementa interoperabilidade entre cadeias. O NeoX é dividido em duas partes: "protocolo de troca de ativos de cadeia cruzada" e "protocolo de transação distribuída em cadeia cruzada".

Contrato de troca de ativos de cadeia cruzada:
O NeoX foi estendido em protocolos de troca de ativos atômicos de cadeia dupla existentes para permitir que vários participantes troquem ativos em diferentes cadeias e para garantir que todas as etapas em todo o processo de transação sejam bem-sucedidas ou falhem em conjunto. Para alcançar essa função, precisamos usar a função NeoContract para criar uma conta de contrato para cada participante. Se outras cadeias de bloqueios não forem compatíveis com o NeoContract, elas podem ser compatíveis com o NeoX, desde que possam fornecer funcionalidades de contrato inteligente simples.

Protocolo de transação distribuída entre cadeias:
As transações distribuídas de cadeia cruzada significam que várias etapas de uma transação estão espalhadas por diferentes cadeias de bloqueio e que a consistência de toda a transação é assegurada. Esta é uma extensão da troca de ativos de cadeia cruzada, estendendo o comportamento da troca de ativos ao comportamento arbitrário. Em termos leigos, a NeoX possibilita contratos cruzados em cadeia, onde um contrato inteligente pode realizar diferentes partes em múltiplas cadeias, que sucede ou reverte como um todo. Isso oferece excelentes possibilidades para colaborações de cadeia cruzada e estamos explorando cenários de aplicativos de contratos inteligentes de cadeia cruzada.

### Protocolo de armazenamento distribuído: NeoFS

NeoFS é um protocolo de armazenamento distribuído que utiliza a tecnologia ‘Distributed Hash Table’. NeoFS indexa os dados através do conteúdo do arquivo (Hash) em vez do caminho do arquivo (URI). Os arquivos grandes serão divididos em blocos de dados de tamanho fixo que são distribuídos e armazenados em muitos nós diferentes.

O principal problema com este tipo de sistema é a necessidade de encontrar um equilíbrio entre redundância e confiabilidade. O NeoFS planeja resolver essa contradição por meio de incentivos token e o estabelecimento de nós de backbone. Os usuários podem escolher os requisitos de confiabilidade do arquivo. Os arquivos com baixos requisitos de confiabilidade podem ser armazenados e acessados de forma gratuita ou quase gratuita. Serviços de serviços estáveis e confiáveis para arquivos com requisitos de alta confiabilidade serão fornecidos por nós de backbone.

NeoFS servirá como um dos serviços de interoperabilidade InteropService no sistema NeoContract, permitindo contratos inteligentes para armazenar arquivos grandes na cadeia de blocos e definir acesso para esses arquivos. Além disso, o NeoFS pode ser combinado com identidade digital para que os certificados digitais utilizados pelas identidades digitais possam ser atribuídos, enviados e revogados sem um servidor central para gerenciá-los. No futuro, os dados do bloco antigos podem ser armazenados no NeoFS, de modo que a maioria dos nós completos podem liberar os dados antigos para uma melhor escalabilidade e, ao mesmo tempo, garantir a integridade dos dados históricos.

### Mecanismo de criptografia anti-quântico: NeoQS

O surgimento de computadores quânticos representa um grande desafio para os mecanismos criptográficos RSA e ECC. Os computadores quânticos podem resolver o grande número de problemas de decomposição (em que o RSA se baseia) e o logaritmo discreto da curva elíptica (em que o ECC depende) em um tempo muito curto. NeoQS (Quantum Safe) é um mecanismo criptográfico baseado em rede. Atualmente, os computadores quânticos não têm a capacidade de resolver rapidamente o Problema do vetor mais curto (SVP) e o problema do vetor mais próximo (CVP), que é considerado o algoritmo mais confiável para resistir aos computadores quânticos.

## Resumo	

A NEO é uma rede distribuída que combina ativos digitais, identidades digitais e contratos inteligentes. O sistema NEO usará DBFT, NeoX, NeoFS, NeoQS e muitas outras tecnologias originais, como a infra-estrutura para a economia inteligente do futuro.

