# ⚖️ Smart Vade Mecum I.A. | Repositório Jurídico Inteligente e Base Vetorial Nacional

Um sistema corporativo e acadêmico de alta performance desenvolvido em Python para centralizar, auditar e realizar buscas semânticas em **100% do ordenamento jurídico brasileiro**, unindo legislação codificada, microssistemas, regimentos internos e jurisprudência consolidada de tribunais superiores e estaduais.

---

## 🚀 Visão Geral do Projeto

O **Smart Vade Mecum I.A.** foi idealizado para suprir a necessidade de uma ferramenta de consulta jurídica instantânea, abrangente e blindada contra lacunas normativas. Diferente de repositórios tradicionais baseados apenas em palavras-chave exatas, este sistema utiliza **Inteligência Artificial baseada em Embeddings (Vetores)** para compreender o contexto e a essência de petições, casos práticos e teses jurídicas, cruzando-os com milhares de dispositivos legais.

---

## 🛠️ Stack Tecnológica

* **Linguagem:** Python 3.10+
* **Banco de Dados Vetorial:** ChromaDB (Persistente local)
* **Processamento de Linguagem Natural (PLN):** `sentence-transformers` (`all-MiniLM-L6-v2`)
* **Automação e Sincronização:** Scripts customizados de auditoria de teto legal (`sincronizar_legislacao.py`)
* **Arquitetura de API (Próxima fase):** FastAPI

---

## 📚 Escopo e Cobertura do Acervo

O banco de dados indexa e gerencia mais de **11.000 registros vetoriais**, abrangendo o ecossistema jurídico brasileiro de ponta a ponta:

1. **Grandes Códigos e Constituição:**
   * Constituição Federal (CF), Código Civil (CC), Código de Processo Civil (CPC), CLT, Código Penal (CP), Código de Processo Penal (CPP), Código Penal Militar (CPM), Código de Processo Penal Militar (CPPM), Código Eleitoral (CE), Código de Trânsito Brasileiro (CTB), Código Tributário Nacional (CTN), Código de Defesa do Consumidor (CDC).
2. **Microssistemas e Legislação Extravagante:**
   * Estatuto da Criança e do Adolescente (ECA), Nova Lei de Licitações (Lei 14.133/21), Lei de Execução Penal (LEP), Lei de Drogas, Lei de Improbidade Administrativa (LIA), Lei do Inquilinato, Recuperação Judicial e Falências, Estatuto da Pessoa com Deficiência e Estatuto do Idoso.
3. **Normas de Cúpula e Regimentos:**
   * LINDB, Regimento Interno do Senado Federal (RISF), da Câmara (RICD) e do Congresso Nacional (RICN), além dos Provimentos e Resoluções do Conselho Nacional de Justiça (CNJ).
4. **Jurisprudência, Súmulas e Precedentes:**
   * Súmulas Vinculantes e jurisprudência do STF, Súmulas e recursos repetitivos do STJ, precedentes do TST, TSE, STM, TRFs (1ª à 6ª Região) e tribunais de justiça estaduais (TJSP, TJRJ, TJMG, TJRS, TJES, entre outros).

---

## ⚙️ Arquitetura de Sincronização e Auditoria

O projeto conta com um script automatizado de auditoria (`sincronizar_legislacao.py`) que:
* **Mapeia o estado atual do banco:** Conta e cataloga os itens presentes por diploma legal.
* **Compara com o teto oficial real:** Identifica discrepâncias ou dispositivos faltantes.
* **Gera e injeta embeddings em lote:** Processa novos artigos de forma segura, garantindo integridade sem sobrecarregar o hardware local.

---

## 🗺️ Roadmap do Projeto

- [x] **Fase 1:** Concepção da estrutura de dados e inserção em lotes.
- [x] **Fase 2:** Desenvolvimento do script de sincronização inteligente e auditoria de teto de artigos.
- [x] **Fase 3:** Expansão massiva para cobrir todo o ordenamento jurídico nacional e estaduais (11k+ registros).
- [ ] **Fase 4:** Desenvolvimento do servidor de API assíncrona em **FastAPI**.
- [ ] **Fase 5:** Integração com interface web/extensão para análise automatizada de casos jurídicos.
