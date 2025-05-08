# azure-tipos-servicos
Tipos de serviços de nuvem

# 🧱 Azure - Tipos de Serviço e Laboratório Prático (VMs e Banco de Dados)

Este documento resume o conteúdo do último laboratório do módulo, abordando a prática com os **tipos de serviços em nuvem** no Microsoft Azure: **IaaS**, **PaaS** e **SaaS**, com foco na criação de **máquinas virtuais** e **bancos de dados SQL**.

---

## ☁️ Modelos de Serviço em Nuvem

### 🏗️ IaaS (Infrastructure as a Service)
- Controle total sobre a infraestrutura.
- Exige configuração e manutenção do sistema operacional, rede e armazenamento.
- Exemplo: Criação manual de máquinas virtuais (VMs).

### 🧰 PaaS (Platform as a Service)
- Plataforma gerenciada para execução de aplicações.
- Usuário se preocupa apenas com os dados e o código.
- Exemplo: Banco de dados SQL como serviço.

### 🧑‍💻 SaaS (Software as a Service)
- Aplicações prontas para uso final, sem preocupações com infraestrutura.
- Exemplo: Microsoft 365, Gmail.

---

## 💻 Criação de Máquinas Virtuais no Azure

### 🧾 Etapas e Considerações
- Escolha da **imagem do sistema operacional** (ex: Windows Server 2019).
- Definição de **tamanho da VM** com custo estimado mensal.
- Adição de **discos adicionais** além do padrão.
- Configuração de **rede virtual**, **endereçamento IP** e exposição à internet.
- Ativação de **gerenciamento e desligamento automático**.
- Configuração detalhada oferece aprendizado essencial antes de partir para automações via código.

> 💡 **Dica:** Explorar o portal antes de automatizar com código ajuda a compreender melhor as opções e os impactos.

---

## 🗄️ Criação de Banco de Dados SQL

### 📌 Principais Configurações
- Nome do banco e criação de **servidor lógico**.
- Escolha da **autenticação** (Microsoft Entra ID ou SQL Server).
- Seleção da **localização geográfica** do servidor.
- Definição do modelo de **redundância** (impacta o SLA).
- Previsão de **custo mensal exibida diretamente no portal**.

> 📊 Utilize a **Calculadora do Azure** para estimar custos com exportação para Excel — útil para orçamentos e envio ao cliente.

---

## 🔄 SLA e Modelo de Serviço

- O nível de **SLA (Service Level Agreement)** depende do modelo escolhido e da configuração do recurso.
- Quanto mais **gerenciado pelo cliente** (ex: IaaS), maior a responsabilidade e o risco de indisponibilidade.
- Quanto mais **gerenciado pela Microsoft** (ex: SaaS), menor o controle, mas também menor o risco.

---

## ✅ Considerações Finais

- Entender os **modelos de serviço** permite fazer melhores escolhas entre custo, controle e esforço de gerenciamento.
- Explorar o portal ajuda a visualizar o impacto de cada escolha antes de automatizar.
- O laboratório introduz conceitos fundamentais para arquitetar soluções reais na nuvem.

> _"A escolha certa do modelo e da arquitetura evita dores de cabeça no futuro e otimiza custos."_ 💡


