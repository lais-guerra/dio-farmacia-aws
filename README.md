# 📝 RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 12 de Dezembro de 2025

**Empresa:** **Abstergo Industries**

**Responsável:** **Laís Guerra**

---

### 🌟 Introdução
Este relatório apresenta o processo de planejamento e sugestão de implementação de ferramentas AWS na empresa **Abstergo Industries**, realizado por **Laís Guerra**. O objetivo do projeto foi elencar 3 serviços da Amazon Web Services (AWS) com a finalidade de realizar uma **diminuição de custos imediatos** e otimização de recursos existentes.

### 💡 Descrição do Projeto
O projeto de otimização de custos e implementação de serviços AWS foi dividido em 3 sugestões de etapas, cada uma com seus objetivos específicos focados na economia e eficiência.

#### Etapa 1: Otimização de Armazenamento com S3 Intelligent-Tiering
* **Nome da Ferramenta:** **Amazon S3 Intelligent-Tiering**
* **Foco da Ferramenta:** **Redução de custos de armazenamento** em *hot* e *cold data*.
* **Descrição de Caso de Uso:** A **Abstergo Industries** possui grandes volumes de dados históricos (*datasets* de pesquisa e *backups* de sistemas legados) no S3. Muitos desses dados são acessados com alta frequência no primeiro mês, mas o acesso diminui drasticamente após 60 dias. O **S3 Intelligent-Tiering** monitora automaticamente os padrões de acesso e move os objetos não acessados para *tiers* de armazenamento mais baratos (como o *Standard-IA* e *Archive Access*), sem intervenção manual, garantindo que o custo se ajuste ao uso real dos dados, resultando em economia imediata no armazenamento de grandes volumes de informações.

#### Etapa 2: Gerenciamento de Cargas de Trabalho Não Contínuas com EC2 Spot Instances
* **Nome da Ferramenta:** **Amazon EC2 Spot Instances**
* **Foco da Ferramenta:** **Diminuição drástica dos custos de computação** para cargas de trabalho flexíveis.
* **Descrição de Caso de Uso:** A **Abstergo Industries** executa simulações complexas de ciência de dados, processamento de vídeos para treinamento de IA e testes de estresse que podem ser interrompidos e reiniciados. Ao migrar essas cargas de trabalho para **EC2 Spot Instances**, a empresa pode obter capacidade de computação não utilizada da AWS com descontos de até 90% em comparação com as *On-Demand Instances*. Isso proporciona uma grande economia no custo de infraestrutura para tarefas de processamento massivo que não exigem disponibilidade contínua e imediata.

#### Etapa 3: Governança e Otimização de Custos com AWS Cost Explorer
* **Nome da Ferramenta:** **AWS Cost Explorer**
* **Foco da Ferramenta:** **Visualização, análise e controle** detalhado dos gastos da AWS.
* **Descrição de Caso de Uso:** Para alcançar a meta de redução de custos, é crucial entender de onde vêm os gastos. O **Cost Explorer** será implementado para fornecer relatórios visuais e *dashboards* que mostram o uso e os custos ao longo do tempo. Será usado para identificar recursos subutilizados ou inativos (como volumes EBS desconectados ou instâncias EC2 ociosas), permitindo que a equipe de operações, liderada por **Laís Guerra**, realize ações de *shutdown* ou redimensionamento, garantindo que os recursos estejam sempre adequados à necessidade (*right-sizing*).

---

### ✅ Conclusão
A implementação das ferramentas sugeridas na empresa **Abstergo Industries** tem como resultado esperado a **redução imediata e sustentável dos custos operacionais de nuvem**, combinada com uma melhor governança de recursos. O uso do S3 Intelligent-Tiering e das EC2 Spot Instances atacará diretamente os maiores centros de custo (armazenamento e computação), enquanto o AWS Cost Explorer fornecerá o monitoramento e a inteligência necessários para manter a otimização a longo prazo. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

### 📎 Anexos
* [Link para Documento de Análise de Padrão de Acesso do S3 (Simulação)]
* [Link para Planilha de Projeção de Economia com Spot Instances (Estimativa)]
* [Link para Guia Rápido de Configuração do AWS Cost Explorer (Manual)]
* [Link para o Repositório GitHub do Projeto (Este arquivo README e outros documentos)]

---

**Assinatura do Responsável pelo Projeto:**

***Laís Guerra***
