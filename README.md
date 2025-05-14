# Desafio-DIO
Resumos, anotações e dicas sobre a plataforma de nuvem Microsoft Azure, para o Bootcamp "Microsoft 50 Anos - Computação em Nuvem com Azure" da Digital Innovation One.

Microsoft Azure é o modelo de nuvem pública da Microsoft, que atua globalmente, oferecendo segurança performance e escalabilidade para ambientes tecnológios de infraestrutura.

# Azure Portal
O Portal do Azure funciona como um console unificado baseado na web, sendo uma das ferramentas mais importantes para interagir com a nuvem da Microsoft. Através dele, você consegue acessar, criar e gerenciar seus recursos do Azure de forma manual. A interface é bastante intuitiva e fácil de usar, permitindo navegar pelos serviços e ver detalhes como custos e segurança.
Um local, onde o usuário pode, por exemplo, criar grupos de recursos e redes virtuais, configurar máquinas virtuais, gerenciar IPs públicos e até mesmo definir configurações de rede mais complexas como load balancers ou Front Door. Entre outras funções.

# Azure Virtual Machine
Máquinas Virtuais (VMs) no Azure são como servidores rodando em nuvem, representando infraestrutura como serviço (IaaS). Elas dão ao usuário controle total sobre o ambiente, sem a necessidade da gerência de hardware físico. Ao criar uma VM, deve-se pensar na rede primeiro, definir nome, região, armazenamento e sistema operacional. O Azure oferece ferramentas para monitoramento e atualizações. É possível gerenciar VMs usando o portal, linha de comando, PowerShell ou scripts como ARM templates. Vários tipos de famílias de VMs estão disponíveis, otimizados para diferentes cargas de trabalho.

# Azure Storage
A Conta de Armazenamento do Azure funciona como um contêiner para guardar diversos tipos de dados na nuvem. Nela, é possível trabalhar com Blobs (arquivos), Files (compartilhamentos), Queue (mensagens) Table (NoSQL) e Disk (VMs). Criá-la exige definir performance (Standard/Premium) e redundância para a disponibilidade. O nome deve ser único globalmente.

# Azure SQL
O Azure SQL Database é um serviço de banco de dados relacional disponibilizado publicamente na nuvem como Plataforma como Serviço (PaaS). Ele utiliza a tecnologia do motor de banco de dados Microsoft SQL Server. 
A principal vantagem do SQL Database em PaaS é que a Microsoft cuida da maior parte do gerenciamento da infraestrutura subjacente, sistemas operacionais e atualizações, permitindo que os usuários foquem mais nos seus dados e aplicações. Para quem precisa de mais controle ou compatibilidade com um SQL Server on-premises, é possível usar máquinas virtuais com SQL Server (IaaS) ou o Azure SQL Managed Instance, que também é PaaS mas com maior compatibilidade e benefícios.

# Notas

# Dicas
