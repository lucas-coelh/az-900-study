# Conceitos de Nuvem

## Conteúdo

- [Conceitos de Nuvem](#conceitos-de-nuvem)
  - [Conteúdo](#conteúdo)
  - [Modelos de Nuvem](#modelos-de-nuvem)
    - [Nuvem Pública (Providers)](#nuvem-pública-providers)
    - [Nuvem Privada (On-Premises)](#nuvem-privada-on-premises)
    - [Nuvem Híbrida (Providers + On-Premises)](#nuvem-híbrida-providers--on-premises)
  - [Considerações e Benefícios da Nuvem](#considerações-e-benefícios-da-nuvem)
    - [Benefícios](#benefícios)
    - [Capex Expenditure (CapEx) — Gasto de Capital x Operational Expenditure (OpEx) — Gasto Operacional](#capex-expenditure-capex--gasto-de-capital-x-operational-expenditure-opex--gasto-operacional)
  - [Serviços de Nuvem](#serviços-de-nuvem)
    - [IaaS (Infraestrutura como Serviço)](#iaas-infraestrutura-como-serviço)
    - [PaaS (Plataforma como Serviço)](#paas-plataforma-como-serviço)
    - [SaaS (Software como Serviço)](#saas-software-como-serviço)

## Modelos de Nuvem

**Computação em nuvem:** Entrega de serviços de computação por meio da Internet. _inovação mais rápida_, _recursos flexíveis_, _economia de escala_.

### Nuvem Pública (Providers)

- Propriedade de uma organização que fornece serviços de nuvem a terceiros. ex: AWS, Azure, Google Cloud.
- Fornece recursos e serviços a varias organizações e usuarios.
- Acessado via conexão de rede segura.

### Nuvem Privada (On-Premises)

- Propriedade de uma organização que fornece serviços de nuvem a si mesma.
- Não fornece serviços a terceiros.
- Organização cria o ambiente em seu datacenter.

### Nuvem Híbrida (Providers + On-Premises)

Combinação de nuvem pública e privada, permitindo que dados e aplicativos sejam compartilhados entre elas. Ex: AWS + Datacenter da empresa.

| Nuvem Pública  | Nuvem Privada | Nuvem Híbrida |
| ------------- | ------------- | ------------ |
| Sem _**despesa de capital**_ para escalar verticalmente  | Fica com a seu encargo a compra do hardware  | Maior Flexibilidade |
| Rapidamente provisionados e desprovisionados  | Controle total sobre recursos e segurança | |
| Paga apenas pelo o que usa.  | Organização fica responsavel por tudo, manutenção, atualização e segurança do hardware  | |

_**Despesa de capital (CapEx):**_ Investimento em bens de capital, como equipamentos ou imóveis, que são usados para produzir bens ou serviços e não são consumidos no período em que são adquiridos.

## Considerações e Benefícios da Nuvem

_**Service Level Agreement (SLA):**_ Acordo de Nível de Serviço, é um contrato entre um fornecedor de serviços e o cliente. Define a qualidade do serviço que será prestado.

### Benefícios

- **Alta Disponibilidade:** Acesso a recursos e serviços sem interrupção. (Se fica fora do ar por mais tempo do que o SLA permite, o cliente recebe um reembolso).
- **Tolerância a Falhas (Replicação de informações):** Capacidade de um sistema de continuar funcionando mesmo que um ou mais de seus componentes falhem.
- **Escalabilidade:** Capacidade de aumentar ou diminuir recursos de acordo com a demanda.
- **Elasticidade:** Capacidade de aumentar ou diminuir recursos de acordo com a demanda, mas de forma automática.
- **Alcance Global:** Acesso a recursos e serviços em qualquer lugar do mundo.
- **Capacidade de Latencia do cliente:** Capacidade de resposta rápida a solicitações do cliente. (Estamos trafegando pelo _backbone_ da microsoft)
- **Agilidade:** Capacidade de responder rapidamente a mudanças no mercado.
- **Custo Preditivo:** Previsão de custos de acordo com o uso.
- **Recuperação de Desastres:** Ambiente em espera em outra localização geográfica que pode ser ativado em caso de desastre.
- **Segurança:** Proteção de dados e informações.

### Capex Expenditure (CapEx) — Gasto de Capital x Operational Expenditure (OpEx) — Gasto Operacional

| CapEx | OpEx |
|-------|------|
| Paga na frente| Pagamento conforme o Uso|
| Valor reduzido ao longo do tempo | Recebe a conta imediatamente |
| | Melhor previsão de custos |

## Serviços de Nuvem

### IaaS (Infraestrutura como Serviço)

- Fornece acesso a recursos de computação, como máquinas virtuais, redes, armazenamento e sistemas operacionais.

### PaaS (Plataforma como Serviço)

- Oferece um ambiente de desenvolvimento e implantação de aplicativos sem a complexidade de construir e manter a infraestrutura. ex: Aws, Azure, Google Cloud.

### SaaS (Software como Serviço)

- Fornece software baseado na web que é executado em servidores de terceiros. ex: Office 365, Google Apps, Salesforce.

![alt text](/Imagens/servicos-nuvem.png)

| IaaS | PaaS | SaaS |
|------|------|------|
| Controle total sobre a infraestrutura | Foco no desenvolvimento de aplicativos | Paga pelo software em um modelo de assinatura |
| Você configura e gerencia o hardware para o seu aplicativo | Gerenciamento da plataforma é manipulado pelo provedor de nuvem. |  |

![alt text](/Imagens/servicos-nuvem-responsabilidade.png)