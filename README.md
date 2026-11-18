# Higienização de Dados, Mapeamento Físico e Governança de Endereços em WMS (Supply Chain)

## 🎯 Visão Geral do Projeto
Este projeto aborda a auditoria, limpeza e reestruturação da base de endereçamento do sistema WMS (Bluesoft) em um Centro de Distribuição (CD 801). Devido a falhas e distorções na criação inicial de cadastros, o sistema contava com mais de 95 mil endereços irreais, poluindo processos operacionais e gerando falhas sistêmicas. O objetivo foi realizar um mapeamento físico completo em campo, higienizar a base de dados reduzindo para menos de 8 mil endereços reais e parametrizar atributos físicos para otimizar a tomada de decisão logística.

---

## 🔍 O Problema
Na operação diária, identificou-se um gargalo crítico originado pela poluição de dados mestres no WMS:
* **Inchaço Sistêmico (95k+ Endereços):** Acúmulo de dezenas de milhares de endereços fantasmas ou inoperantes criados em implementações anteriores sem validação de campo.
* **Erros de Direcionamento:** O WMS solicitava operações (endereçamento, estocagem e separação) em locais que fisicamente não existiam, gerando quebras de fluxo, perda de tempo e erros operacionais.
* **Falta de Governança de Dados Mestres:** Ausência de rotinas de manutenção diária e desconhecimento da capacidade real de armazenamento e volumetria do CD.

---

## 🛠️ A Abordagem e Solução

Para sanar o problema de ponta a ponta sem paralisar a operação, a iniciativa foi estruturada em quatro etapas:

1. **Mapeamento Físico do CD em Campo:**
   * Montagem e liderança de equipe dedicada para varredura e levantamento *in loco* da estrutura física do Centro de Distribuição.
   * Identificação e contagem precisa de áreas, tipos de picking (único vs. compartilhado), estruturas de pulmão e túneis operacionais.
2. **Higienização e Inativação Sistêmica:**
   * Confronto entre o cadastro do WMS e a realidade física mapeada.
   * Inativação em massa de endereços fantasmas/inexistentes, reduzindo o escopo ativo de mais de **95.000 para menos de 8.000 endereços** altamente qualificados e funcionais.
3. **Parametrização de Atributos Físicos (Master Data):**
   * Definição sistemática de regras para cada endereço, incluindo **altura, peso máximo suportado e quantidade limite de paletes**.
4. **Habilitação de Estratégias Operacionais:**
   * Utilização dos novos parâmetros estruturados para montar estratégias dinâmicas de alocação e fluxo de mercadorias ao longo do dia.

---

## 📈 Resultados e Impactos de Negócio

* **Agilidade Extrema no Endereçamento:** Eliminação de rotas e ordens para locais inexistentes, trazendo fluidez e velocidade para a equipe de operação.
* **Rastreabilidade e Assertividade:** Confiabilidade absoluta nos dados de inventário, garantindo visibilidade clara do espaço disponível.
* **Clareza de Processos e Base para BI:** Limpeza do banco de dados que serve de fundação sólida para futuras extrações de dados e relatórios de ocupação de armazém.

---

## 🛠️ Tecnologias e Conceitos Aplicados
* **Sistemas:** WMS (Bluesoft).
* **Conceitos:** Gestão de Dados Mestres (MDM), Higienização de Dados, Mapeamento de Layout Logístico, Ocupação de Armazém, Supply Chain Operations.
