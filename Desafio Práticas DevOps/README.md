# Desafio: Implementação de Práticas DevOps na Tech

## 1. Diagnóstico Cultural (C de CALMS)

### Processo Identificado
O processo de **deploy de aplicações** na Tech, especialmente para o Sistema de Gestão de Vendas (LEGADO) e a Plataforma de E-commerce, apresenta pontos críticos que podem ser aprimorados com práticas DevOps.

### Descrição do Processo Atual
- **Entrega de Código:** Desenvolvedores preparam pacotes de implantação e enviam para operações.
- **Deploy:** Realizado manualmente, sem padronização ou automação.
- **Testes:** Testes manuais pós-deploy feitos pela equipe de operações.
- **Monitoramento:** Monitoramento manual dos logs após deploy.

#### Pontos de Atrito e Oportunidades de Melhoria
- Falta de integração entre desenvolvimento e operações.
- Processo manual e suscetível a erros.
- Ausência de padronização e automação.
- Feedback lento e pouco estruturado.
- Conhecimento concentrado em poucos profissionais (ex: Delphi).

## 2. Automação (A de CALMS)

### Solução Proposta
Implementação de **Pipeline de Integração e Entrega Contínua (CI/CD)** utilizando ferramentas como Jenkins, GitHub Actions ou Azure DevOps para automatizar:
- Build
- Testes automatizados
- Deploy padronizado
- Notificações de status

### Plano de Implementação
1. **Mapear o processo atual** e identificar etapas automatizáveis.
2. **Escolher ferramentas** adequadas ao stack da empresa.
3. **Criar pipelines** para build, testes e deploy automatizado.
4. **Treinar as equipes** para uso das ferramentas.
5. **Implementar gradualmente**, começando por projetos menos críticos.
6. **Documentar procedimentos** e criar guias de uso.
7. **Coletar feedback** e ajustar o pipeline conforme necessário.

### Minimização de Resistências
- Envolver as equipes desde o início.
- Demonstrar ganhos de tempo e redução de erros.
- Oferecer treinamentos e suporte contínuo.

## 3. Mensuração e Compartilhamento de Conhecimento (M e S de CALMS)

### Métricas Relevantes
- **Lead Time:** Tempo entre entrega do código e deploy em produção.
- **Taxa de sucesso dos deploys.**
- **Número de incidentes pós-deploy.**
- **MTTR (Mean Time to Recovery).**
- **Cobertura de testes automatizados.**

### Plano de Disseminação de Conhecimento
- Realizar **workshops internos** sobre DevOps e automação.
- Criar uma **wiki interna** com documentação dos processos e pipelines.
- Promover **reuniões de retrospectiva** para compartilhar aprendizados.
- Incentivar o **mentoring** entre profissionais experientes e iniciantes.

## 4. As Três Maneiras do DevOps

### Primeira Maneira: Acelerar o Fluxo
- Automatizar build, testes e deploy para reduzir o tempo de entrega.
- Padronizar processos para evitar retrabalho e erros manuais.
- Utilizar infraestrutura como código para provisionamento rápido.

### Segunda Maneira: Ampliar o Feedback
- Implementar notificações automáticas de falhas e sucessos no pipeline.
- Coletar feedback dos usuários e equipes após cada deploy.
- Utilizar dashboards para monitoramento em tempo real.

### Terceira Maneira: Experimentar e Aprender
- Incentivar experimentação com novas ferramentas e práticas.
- Tratar falhas como oportunidades de aprendizado, promovendo cultura "blameless".
- Realizar post-mortems colaborativos após incidentes.

---

## Conclusão
A adoção de práticas DevOps na Tech trará maior colaboração entre equipes, processos mais ágeis e confiáveis, além de promover uma cultura de aprendizado contínuo. O plano proposto visa não apenas automatizar tarefas, mas também transformar a cultura organizacional, tornando a empresa mais inovadora e preparada para desafios futuros.