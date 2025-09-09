# Computação em Nuvem: Domínio do objeto
Computação em nuvem descreve a entrega via Internet ("a nuvem") de recursos de computação - como servidores, armazenamento, bancos de dados, redes, software, analytics e inteligência - com vistas à inovação mais rápida, recursos flexíveis e economia de escala. O domínio do objeto neste contexto está normalmente associado aos objetivos ou os domínios da certificação profissional, tais como as do CompTIA Cloud+, AWS Certified Cloud Practitioner ou Microsoft Azure Fundamentals, onde os domínios abordam conceitos fundamentais, arquitetura, segurança, operações e conformidade.

Os objetivos principais incluem:
Compreensão dos benefícios da nuvem, para redução de custos, aumento de agilidade e escalabilidade.
Identificação dos riscos - como dependência de um fornecedor e riscos de segurança de dados.
Aplicação de conceitos em casos reais - como migração da infraestrutura local para nuvem.

# Comparação de Modelos de Nuvem
Os modelos de nuvem são categorizados em **modelos de implantação** (deployment models) e modelos de serviço (service models). Aqui segue uma comparação detalhada:

### Modelos de implantação
Definem como a infraestrutura de nuvem é provisionada e acessada.

**Modelo Público**: Recursos compartilhados entre múltiplos usuários, mantidos por um terceiro. Vantagens: Muito baixo custo inicial, escalabilidade infinita, nenhuma manutenção pelo usuário. Desvantagens: Menor controle sobre dados e segurança; dependência do fornecedor. Exemplos: AWS, Azure, Google Cloud.

**Modelo Privado**: Infraestrutura dedicada a uma única organização, pode ser on-premises ou hospedada. Vantagens: Alto controle, segurança e conformidade personalizadas. Desvantagens: Alto custo de manutenção e escalabilidade limitada.. Exemplos: Nuvens internas do setor corporativo, como os bancos.

**Modelo Híbrido**: Este modelo é uma combinação dos anteriores, onde dados sensíveis permanecem no privado e workloads escaláveis no público. Vantagens: Flexibilidade, otimização de custo e conformidade. 
Desvantagens: complexidade de integração e gerenciamento. Exemplos: empresas que utilizam Azure para aplicativos públicos e servidores locais para dados regulados.

Modelo Comunitária: Utilizado por um conjunto de organizações com interesses comuns. Vantagens: Colaboração e custos compartilhados, que favorecem a conformidade do setor; desvantagens: Governança compartilhada pode ser desafiadora. Exemplos: Clouds para as agências governamentais.

Modelos de Serviço
Estes definem o nível de abstração e responsabilidade.

Modelo IaaS (Infrastructure as a Service): Fornece infraestrutura virtual (servidores, armazenamento, redes). Responsabilidades do Usuário: Gerenciar SO, apps e dados. Vantagens: O máximo de flexibilidade, como um data center virtual. Desvantagens: Mais trabalho de configuração. Exemplos: AWS EC2, Azure Virtual Machines.

Modelo PaaS (Platform as a Service): Fornece plataforma para desenvolvimento e deployment de apps. Responsabilidades do Usuário: Gerenciar apenas apps e dados. Vantagens: Foco no desenvolvimento, escalabilidade automática .Desvantagens: Menos controle sobre infraestrutura subjacente . Exemplos : Google App Engine, Heroku

**Modelo SaaS (Software as a Service)**: Oferece software já configurado através da internet. Responsabilidade do Usuário: Apenas usar o software. Vantagens: Simples de usar, atualização automática. Desadvantages: Dependência total do fornecedor, têm de customizá-lo. Exemplos: Gmail, Salesforce, Microsoft 365.

# Comparação entre CapEx e OpEx
Os gastos Capitais (CapEx) e os gastos operacionais (OpEx) são modelos de gastos financeiros. A nuvem incentiva a passagem de CapEx para OpEx.
**Aspecto Definição**: CapEx: Gastos em ativos fixos de longo prazo (ex: compra de servidores, hardware). OpEx: Gastos recorrentes em operação habitual (por exemplo: assinatura de nuvem, manutenção).**Características**: CapEx: Pagamento antecipado, depreciado ao longo do tempo. Alto risco de perda em caso de subutilização. OpEx: Pagamento somente na utilização, flexível e escalonável.
**Benefícios**: CapEx: Propriedade do ativo, depreciação como dedução fiscal. OpEx: Diminuição do risco financeiro, maior previsibilidade de custos e foco em inovação.
**Desvantagens**: CapEx: Grande custo de capital inicial, má escala, obsolescência. OpEx: Pode resultar em custos acumulados se não monitorado e sem propriedade.
**Exemplo na Nuvem**: CapEx: Provimento de Data Centers próprios (tradicional). OpEx: Acesso adotado no AWS (nuvem) com pagamento por utilização por hora.
**Impacto na Nuvem**: As abordagens tradicionais de provisionamento em locais on-premises têm consistido em CapEx, levando a ineficiências . A nuvem é uma abordagem de OpEx, permitindo maior escalabilidade e adaptabilidade sem a necessidade de grandes investimentos

# Computação em Nuvem - Revisão
- **Principais Benefícios**: Escalabilidade (elástica), disponibilidade em nível mundial, recuperação de desastres, segurança em nível integrado (ex.: criptografia, firewalls) e inovação desigual em nível de velocidade via serviços gerenciados como IA e ML.
- **Principais Desafios**: Segurança e privacidade (ex.: conformidade com o GDPR e LGPD), lock-in com o provedor, custos imprevisíveis se não forem otimizados e latência em aplicações sensíveis.

### Comparação de Modelos em Nuvem - Modelos de Implementação
- **Nuvem Pública**: Recursos partilhados por diversos usuários, vendidos por um prestador de serviços. Vantagens são o custo inicial baixo e a escalabilidade ilimitada, além de que o usuário não precisa fazer manutenção de hardware nem software. Desvantagens são a falta de controle sobre os dados e a segurança, e a dependência do prestador de serviços. Exemplos: AWS, Azure, Google Cloud.
- **Nuvem Privada**: Infraestrutura dedicada a uma única organização, possivelmente on-premises ou hospedada. Vantagens incluem alto controle, segurança e conformidade. Desvantagens são o alto custo de manutenção e a escalabilidade limitada. Exemplos: Nuvens internas - como bancos.
- **Nuvem Híbrida**: Uma mistura de nuvem pública e privada, onde dados sensíveis são mantidos na nuvem privada e workloads escaláveis na nuvem pública. Vantagens são flexibilidade, otimização de custos e conformidade. Desvantagens incluem complexidade de integração e gerenciamento. Exemplos: empresas que utilizam Azure para apps públicos e servidores locais para dados regulados.

## Diferenças entre CapEx e OpEx
- **CapEx (Capital Expenditure)**: Se refere aos gastos em ativos fixos e de longo prazo, como a aquisição de servidores ou de hardware. Suas características são: pagamento upfront(adiantado), depreciação ao longo do tempo e risco elevado, caso subutilizado. Suas vantagens são a propriedade do ativo e a possibilidade de deduzir os gastos correspondentes a depreciação. Suas desvantagens são alto custo inicial, dificuldade de escalar e obsolescência. Um exemplo na nuvem: aquisição de data centers próprios (modelo tradicional). E o seu impacto para a nuvem: os modelos tradicionais on-premises focam no CapEx, e acabam resultando em ineficiências.

- **OpEx (Operational Expenditure)**: Se refere a gastos recorrentes nas operações do dia-a-dia, tais como as assinaturas de nuvem ou custo de manutenção. Suas características são: pagos por uso (pay-as-you-go), flexibilidade e escalabilidade. Suas vantagens são o risco financeiro reduzido, previsibilidade (de custo) e foco em inovação. Suas desvantagens são a possibilidade de acumular custo na ausência de monitoramento e a ausência de propriedade. Um exemplo na nuvem: pagar por horas de uso no AWS. E o seu impacto para a nuvem: a nuvem converte gastos em OpEx e possibilita escalá-los sem investimentos massivos.
