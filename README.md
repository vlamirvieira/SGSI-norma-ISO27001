# SGSI-norma-ISO27001
A implantação de um Sistema de Gestão da Segurança da Informação (SGSI) baseado na ISO 27001 segue uma metodologia estruturada orientada pelo ciclo de melhoria contínua (PDCA) e pela Estrutura de Alto Nível (Anexo SL) da norma.
 Sequência do Projeto de Implantação do SGSI (ISO 27001)
1. Diagnóstico Inicial e Definição de Escopo (Gap Analysis)
•	Análise do Contexto Organizacional: Mapeamento das questões internas, externas e requisitos das partes interessadas.
•	Delimitação do Escopo: Definição clara dos limites organizacionais, físicos e tecnológicos protegidos pelo SGSI.
•	Análise de Lacunas (Gap Analysis): Avaliação do estado atual da segurança em comparação com os requisitos da norma.
2. Governança, Políticas e Gestão de Riscos
•	Engajamento da Alta Direção: Formalização do patrocínio institucional e alocação de recursos.
•	Política de Segurança da Informação: Elaboração e publicação do documento norteador aprovado pela direção.
•	Inventário de Ativos: Identificação e categorização de informações, sistemas, infraestrutura e pessoas.
•	Avaliação de Riscos: Mapeamento de ameaças, vulnerabilidades, impacto e probabilidade.
•	Declaração de Aplicabilidade (DoA): Seleção e justificativa da adoção ou exclusão dos controles do Anexo A.
3. Implementação e Operação de Controles
•	Aplicação dos Controles (Anexo A): Implantação das medidas organizacionais, de pessoas, físicas e tecnológicas.
•	Conscientização e Treinamento: Realização de programas contínuos de capacitação e simulações para os colaboradores.
•	Procedimentos e Registros Operacionais: Formalização dos processos rotineiros, gestão de acessos, backups e resposta a incidentes.
4. Monitoramento e Auditoria Interna
•	Acompanhamento e Logs: Monitoramento de métricas de desempenho e registros de eventos de segurança.
•	Auditoria Interna: Execução planejada por auditores independentes para identificar não conformidades.
•	Análise Crítica pela Direção: Avaliação periódica do desempenho do sistema e tomada de decisões estratégicas.
5. Certificação e Melhoria Contínua
•	Auditoria Externa - Fase 1: Análise documental e verificação de prontidão realizada pelo organismo certificador.
•	Auditoria Externa - Fase 2: Auditoria presencial/operacional para coleta de evidências práticas de conformidade.
•	Tratamento de Ações Corretivas e Certificação: Correção de eventuais não conformidades e emissão do certificado (válido por 3 anos com auditorias anuais de manutenção).
________________________________________
 Estruturação e Versionamento para Repositórios (Ex: GitHub / DevSecOps)
Para manter o SGSI transparente e auditável em repositórios, a documentação pode ser organizada com suporte ao controle de versão (Seção 7.5 da norma):
•	/docs/01-politicas: Política Global de Segurança, Política de Controle de Acesso e Código de Conduta.
•	/docs/02-riscos-e-doa: Matriz de Avaliação de Riscos e a Declaração de Aplicabilidade (statement-of-applicability.md).
•	/docs/03-procedimentos: Guias operacionais para resposta a incidentes, gestão de mudanças e backups.
•	/docs/04-evidencias: Registros de auditorias internas, ata da análise crítica e relatórios de treinamento.
•	Boas Práticas no Git: Uso de Commits rastreáveis para aprovações, histórico de alterações (Changelog), tags para controle de versão dos documentos (v1.0, v2.0) e Pull Requests para revisão de políticas por gestores.

