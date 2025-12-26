# Escola de Música - Banco de Dados

Banco de dados SQL criado como **atividade da faculdade (2º período)** para gerenciamento de **orquestras, músicos, sinfonias e apresentações**.

---

## Estrutura

- **orquestra**: id, nome, cidade, país, data de criação, continente  
- **sinfonia**: id, nome, compositor, data, país  
- **musico**: id, nome, identidade, nacionalidade, data de nascimento, gênero, cidade, instrumento, orquestra, continente  
- **instrumento**: id, nome  
- **funcao**: id, nome  
- **apresentacao**: id, data, orquestra, sinfonia  
- **musico_funcao_apresentacao**: associa músicos, funções, instrumentos e apresentações  

---

## Dados de exemplo

- Orquestras: Filarmônica de Viena, Orquestra Sinfônica Brasileira  
- Sinfonias: Sinfonia Nº5 (Beethoven), Sinfonia Fantástica (Berlioz)  
- Músicos: João Silva, Anna Müller, Yuki Tanaka  
- Instrumentos: Violino, Viola, Piano  
- Funções: Violinista, Pianista, Flautista  

---

## Consultas principais

- Músicos brasileiros / estrangeiros  
- Músicos por continente  
- Músico e instrumento / orquestra  
- Músico mais jovem / mais velho  
- Orquestra que toca a sinfonia mais antiga / mais nova  

---

## Views

- view_musicos_brasileiros / view_musicos_estrangeiros  
- view_musicos_sul_americanos / view_musicos_nao_sul_americanos  
- view_musicos_homens / view_musicos_mulheres  
- view_musico_instrumento / view_musico_orquestra  
- view_musico_mais_jovem / view_musico_mais_velho  
- view_orquestras_europeias / view_orquestras_nao_europeias
