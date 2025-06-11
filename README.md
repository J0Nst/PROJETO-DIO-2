# Armazenando dados de um E-Commerce na Cloud 

Entrega de Projeto HTML Dio

Armazenar dados de um e-commerce na nuvem do Azure envolve escolher a opção de armazenamento mais adequada para o tipo de dados e a sua frequência de acesso. Opções como Armazenamento de Blobs (para dados não estruturados como imagens e vídeos), Armazenamento de Arquivos (para dados estruturados com acesso compartilhado) e Data Lake Storage (para análise de big data) estão disponíveis. Além disso, o Azure oferece serviços como o Banco de Dados SQL para dados transacionais e o Azure Data Explorer para análise. 
Opções de Armazenamento:
Armazenamento de Blobs:
Ideal para dados não estruturados, como imagens, vídeos, documentos e outros arquivos binários. É altamente escalável, fácil de usar e econômico, podendo ser acessado por APIs REST e SKDs. 
Armazenamento de Arquivos:
Adequado para dados estruturados que exigem acesso compartilhado a arquivos através do protocolo SMB. É útil para aplicativos que dependem de compartilhamentos de arquivos, como aplicativos de e-commerce que precisam de acesso a dados de produtos e informações de clientes. 
Data Lake Storage:
Uma solução altamente escalável e econômica para a análise de Big Data. Combina o poder de um sistema de arquivos de alto desempenho com a escala e economia necessárias para acelerar o tempo de obtenção de insights. É ideal para analisar grandes volumes de dados de diferentes fontes, como sites, aplicativos, dispositivos IoT e outros. 
Banco de Dados SQL do Azure:
Um serviço de banco de dados totalmente gerenciado para armazenar e gerenciar dados transacionais, como informações de clientes, carrinho de compras e histórico de pedidos. 
Azure Data Explorer:
Um serviço de análise de dados ideal para analisar grandes volumes de dados diversos, como dados de sites, aplicativos e dispositivos IoT. É utilizado para diagnósticos, monitoramento, relatórios, aprendizado de máquina e outras análises. 
Considerações:
Tipo de dados:
Determine se os dados são estruturados ou não estruturados para escolher a opção de armazenamento adequada.
Frequência de acesso:
Se os dados são acessados com frequência, o Armazenamento de Blobs Hot ou o Banco de Dados SQL podem ser mais adequados. Se o acesso é menos frequente, o Armazenamento de Blobs Cool, Cold ou Archive podem ser mais econômicos. 
Requisitos de escalabilidade:
Se o seu e-commerce espera ter um grande volume de dados, considere opções como o Data Lake Storage ou o Armazenamento de Blobs. 
Segurança e privacidade:
O Azure oferece diversas opções de segurança e privacidade para proteger os dados do seu e-commerce, como criptografia em repouso e em trânsito, controle de acesso e monitoramento de segurança. 
Exemplo de Implementação:
Um e-commerce pode usar o Armazenamento de Blobs para armazenar imagens de produtos, vídeos de demonstração e documentos de política de privacidade, enquanto o Armazenamento de Arquivos pode ser usado para armazenar informações de clientes, histórico de pedidos e dados de carrinho de compras. O Banco de Dados SQL pode ser usado para armazenar dados transacionais, como informações de pagamento e detalhes de envio. 
Backup e Recuperação:
O Azure oferece serviços de backup e recuperação para proteger os dados do seu e-commerce. O Backup do Azure permite fazer backup de dados e aplicativos locais para a nuvem, enquanto o Armazenamento de Blobs pode ser usado como um destino de backup. 
Em resumo, ao escolher as opções de armazenamento no Azure para o seu e-commerce, é importante considerar o tipo de dados, a frequência de acesso, os requisitos de escalabilidade e as necessidades de segurança e backup. 


💻 Sobre o Projeto
Este bootcamp avançado foi projetado para capacitar desenvolvedores e profissionais de TI com as habilidades práticas possíveis para construir, implantar e gerenciar aplicações modernas utilizando a plataforma Microsoft Azure. O foco está em tecnologias como App Services, Azure Container Apps, além de conceitos fundamentais de DevOps aplicados ao ecossistema Microsoft.

📚 Pré-requisitos de Habilidades e Níveis de Conhecimento
Antes de ingressar neste conteúdo, é necessário possuir conhecimento prévio nas seguintes áreas:

Antes de ingressar neste conteúdo, é necessário possuir conhecimento prévio nas seguintes áreas:

Azure | Básico

Git e GitHub | Básico

Lógica de Programação | Intermediário

Conhecimentos de Desenvolvimento Web | Intermediário

Terminal/CLI | Básico

Outros pré-requisitos:

Experiência desejável com alguma linguagem de programação como C#, JavaScript ou Python.
🛠️ Habilidades e Sub-habilidades que vamos aprender neste conteúdo
Fundamentos da Plataforma Azure

Serviços de aplicativos

CLI e Portal do Azure

Armazenamento de dados

Contêineres e Orquestração

Aplicativos de contêiner do Azure
Serviço Azure Kubernetes (AKS)
Deploy de aplicações em contêineres
Monitoramento e Desempenho

Insights de aplicação
Análise de Logs
Práticas de Observabilidade
Projeto Final Integrado

Construção de solução ponta a ponta
Armazenamento em nuvem
Implantar manual
🎯 Objetivos e Resultados Esperados
Após a conclusão do curso/projeto, os estudantes deverão aptos a:

Criar, configurar e gerenciar aplicações modernas utilizando serviços PaaS e CaaS do Microsoft Azure.

Realize a implantação de aplicações web e APIs utilizando Azure App Services e Container Apps.

Monitorar e diagnosticar aplicações usando ferramentas integradas do Azure.

Construir um aplicativo completo com backend em contêiner, armazenando dados na nuvem e com observabilidade configurada.
