# Material complementar

Simuladores digitais no ensino de eletrônica e sistemas embarcados: revisão sistematizada da produção na SBC OpenLib

Arquivos:

- `material_complementar.xlsx`: planilha com as abas Leia-me, Registros triados, Extração e Excluídos no texto completo.
- `registros_triados.csv`: os 70 registros triados, com a decisão e o motivo.
- `extracao.csv`: dados extraídos dos 39 estudos incluídos.
- `excluidos_texto_completo.csv`: os 9 registros excluídos após a leitura do texto completo ou não recuperados.

Os CSV usam codificação UTF-8 e vírgula como separador.

## Protocolo

- **Base de dados:** SBC OpenLib (SOL), ferramenta Busca integrada, bases Anais e Periódicos.
- **Data da busca:** 21/11/2026
- **Filtros:** Busca no campo Resumo; publicações a partir de janeiro de 2010; sem restrição de idioma.
- **Expressão S1:** (simula* OR "laboratório virtual" OR "laboratórios virtuais" OR "virtual laboratory" OR "virtual lab") AND (eletr* OR elétric* OR electr* OR circuit* OR arduino OR microcontrol* OR embarcad* OR embedded) AND (ensino OR aprendizagem OR educa* OR didátic* OR aluno* OR estudante* OR teaching OR student*)
- **Expressão S2:** (Tinkercad OR Wokwi OR Proteus OR SimulIDE OR PhET OR Falstad OR Fritzing OR LTspice OR Multisim OR EveryCircuit OR CircuitLab) AND (ensino OR aprendizagem OR educa* OR didátic* OR aluno* OR estudante* OR teaching OR student*)
- **Fluxo de seleção:** 83 registros identificados (S1 = 53; S2 = 30); 13 duplicatas removidas; 70 triados por título e resumo; 22 excluídos na triagem; 48 buscados em texto completo; 3 não recuperados; 45 lidos na íntegra; 6 excluídos na leitura; 39 incluídos (27 com avaliação com participantes).
- **Códigos:** S1-nn e S2-nn indicam a expressão de busca e a posição do registro na lista de resultados da SOL. Registros retornados pelas duas expressões aparecem uma única vez, com o código de S1 e a indicação "S1 e S2".
- **CI1:** Estudo primário publicado em anais ou periódico da SOL a partir de 2010.
- **CI2:** Uso, desenvolvimento ou avaliação de simulador digital com finalidade educacional.
- **CI3:** Domínio de eletrônica analógica ou digital, circuitos elétricos ou lógicos, microcontroladores e sistemas embarcados (incluindo IoT), arquitetura de computadores simulada no nível de hardware ou eletrotécnica em realidade virtual.
- **CI4:** Em estudos de robótica educacional, presença de simulador de circuitos ou de microcontrolador.
- **CE1:** Ausência de simulador digital: só hardware físico, laboratório remoto com equipamento real ou atividade desplugada.
- **CE2:** Simulador de outro domínio (por exemplo, mecânica, ondas, química ou saúde).
- **CE3:** Software usado apenas para modelagem 3D ou desenho, sem simulação de circuitos.
- **CE4:** Estudo secundário (revisão de literatura).
- **CE5:** Texto completo indisponível para leitura.
- **Registros triados: colunas:** Código; título, autores, veículo, ano e link como constam na SOL; expressão que retornou o registro; etapa em que a decisão foi tomada; decisão final (Incluído, Excluído ou Não recuperado); critério aplicado; motivo; se o estudo incluído relata avaliação com participantes.
- **Extração: colunas:** Dados extraídos do texto completo de cada estudo incluído: referência, ano, veículo, tipo de publicação, simulador(es), área do conteúdo, nível de ensino, contexto e modalidade, participantes, desenho do estudo, instrumentos, principal resultado reportado pelos autores e presença de avaliação com participantes. "—" indica que o campo não se aplica (estudo sem aplicação com participantes).
- **Observação:** Os estudos sem avaliação com participantes foram incluídos, mas analisados apenas quanto às características das ferramentas e das propostas. As decisões registradas são as finais; o uso de ferramentas de IA no processo está descrito na declaração de uso de IA do artigo.
