# RELATORIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 21/07/2025

Empresa: Abstergo Pharmaceutical Industries

Responsável: Giliano Gomes Novais

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Pharmaceutical Industries, realizado por Giliano Gomes Novais. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Base de Segurança e Acesso

* __Ferramenta__: __AWS IAM (Identity and Access Management)__
* __Foco__: Estabelecer uma fundação de segurança forte e gratuita.
* __Descrição de uso__: Antes de armazenar qualquer dado na nuvem, a empresa precisa definir quem pode fazer o quê. Usando o __IAM__, é possível criar usuários para cada membro da equipe, agrupá-los por função (por exemplo, "Pesquisadores", "Administração", "TI") e aplicar políticas de permissão. Isso garante que cada pessoa tenha acesso somente aos recursos de que precisa para seu trabalho, seguindo o princípio do privilégio mínimo. Esta etapa não tem custo e protege a conta desde o primeiro dia.

### Etapa 2: Armazenamento e Backup de Dados Críticos

* __Ferramenta__: __Amazon S3 (Simple Storage Service)__
* __Foco__: Eliminar a dependência de hardware de armazenamento local.
* __Descrição de uso__: A indústria pode usar o __Amazon S3__ para fazer backups de dados críticos, como relatórios de pesquisa, dados clínicos e documentos financeiros, que hoje estão em servidores locais. O S3 oferece durabilidade de 99,999999999% e é mais resiliente a falhas de hardware e desastres do que a infraestrutura local, tudo a um custo de armazenamento muito baixo. Isso reduz os gastos com a compra e manutenção de discos rígidos e fitas de backup.

### Etapa 3: Acesso Híbrido aos Dados com Baixa Latência

* __Ferramenta__: __AWS Storage Gateway__
* __Foco__: Facilitar a transição para a nuvem sem perder agilidade.
* __Descrição__: Para que a equipe de pesquisa e desenvolvimento possa acessar grandes arquivos de forma rápida, mas ainda se beneficiar do S3, o __AWS Storage Gateway__ pode ser implementado. Ele cria um volume de armazenamento em cache no escritório da empresa, mas que tem o Amazon S3 como backend. Isso significa que os arquivos frequentemente acessados permanecem no local com baixa latência, enquanto todos os dados são automaticamente sincronizados com o S3 para segurança e durabilidade. A equipe pode continuar usando as ferramentas que já conhece, enquanto a empresa desfruta dos benefícios da nuvem.

## Conclusão

A implementação de ferramentas na empresa Abstergo Pharmaceutical Industries tem como esperado à _Redução de Custos_, _Aumento da Segurança_, _Melhoria na Resiliência_ e _Transição Suave para nuvem_, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa

## Anexos

Documentação e os manuais para esses serviços nos links abaixo, que fornecem guias de usuário, referências de API e informações sobre como começar.

### AWS IAM (Identity and Access Management)

O manual do IAM fornece informações sobre como gerenciar usuários, grupos, funções e permissões para proteger sua conta e seus recursos.

https://docs.aws.amazon.com/iam/

### Amazon S3 (Simple Storage Service)

A documentação do S3 inclui guias detalhados sobre como armazenar, gerenciar e proteger objetos na nuvem, além de informações sobre classes de armazenamento e segurança.

https://docs.aws.amazon.com/pt\_br/s3/?icmpid=docs\_homepage\_featuredsvcs

### AWS Storage Gateway

O manual do AWS Storage Gateway explica como usar o serviço para conectar o seu ambiente local com o armazenamento na nuvem. A documentação é dividida por tipo de gateway.

https://docs.aws.amazon.com/pt\_br/storagegateway/

###
------
###

### Assinatura do Responsável pelo Projeto:

### Giliano Gomes Novais