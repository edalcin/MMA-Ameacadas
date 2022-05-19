# Plano de Trabalho

[Fluxo de trabalho](fluxograma.md) - [Gantt](https://github.com/edalcin/MMA-Ameacadas/blob/main/plano-de-trabalho/gantt.md)

## 1. Levantamento e Definição dos Recursos

   Os recursos serão definidos com base, inicialmente, em seu papel central e, posteriormente, com base nas demandas realizadas na Oficina de Demanda do MMA/DESP.

   Foram selecionados préviamente as seguintes fontes de recursos:

   ---

   ### 1.1. [CNCFlora](http://cncflora.jbrj.gov.br)

   O CNCFlora tem publicado seus dados usando o IPT institucional, via _Web Service_ e também enviando conjuntos de dados ao sistema [SIS Connect](https://connect.iucnredlist.org) da IUCN.

   #### Mecanismos de Publicação:

   * ##### [IPT e Darwin Core](http://ipt.jbrj.gov.br/jbrj/resource?r=redlist\_2013\_taxons)

        O CNCFlora publicou seus dados relativos ao Livro Vermelho (2013) no IPT da instituição. Entretanto, novas atualizações não estão previstas.
        
   * ##### [_Web Service_](http://cncflora.jbrj.gov.br/services/index.html)
        
        Os dados relativos ao Livro Vermelho (2013) também foram publicados via Web Service juntamente com os dados de ocorrência que deram subsídio às avaliações de cada espécie. 

   * ##### [Conjuntos de dados para IUCN](https://drive.google.com/file/d/1idSHoHEM51Qxu3CY10ke10lrJ7wnYU8o/view?usp=sharing)

        Os conjuntos de dados enviados para a IUCN são os dados mais recentes ofertados pelo CNCFlora.


   ---

   ### 1.2. Salve

   #### Mecanismos de Publicação:
   
   O Salve não possui mecanismos de publicação de dados abertos ao público. O acesso deve ser requerido diretamente à equipe técnica responsável.

   ---

   ### 1.3. [Flora e Funga do Brasil](http://floradobrasil.jbrj.gov.br/reflora/listaBrasil/PrincipalUC/PrincipalUC.do)

   #### Mecanismos de Publicação:

   * ##### [IPT e Darwin Core](http://ipt.jbrj.gov.br/jbrj/resource?r=lista\_especies\_flora\_brasil)
         
        Os dados presentes no sistema da Flora e Funga do Brasil são exportados via IPT com versões atualizadas automaticamente.

   * ##### [_Web Service_](https://servicos.jbrj.gov.br/v2/flora/)
   
        Os dados exportados via Web Sevice também estão no padrão Darwin Core e são consumidos diretamente dos bancos de dados, sem versionamento.
         
   
   ---

   ### 1.4. [Catálogo da Fauna](http://fauna.jbrj.gov.br/fauna/listaBrasil/ConsultaPublicaUC/ConsultaPublicaUC.do)

   #### Mecanismos de Publicação:

   * ##### [_Web Service_](https://drive.google.com/file/d/1Vy2\_-xTOF3JC992dlivp9oQYTCKLzVXe/view?usp=sharing)
   
        Os dados exportados via Web Service do Catálogo da Fauna não estão mapeados em Darwin Core.

## 2. Sistematização dos Termos Presentes nos Recursos

   Os termos e classes presentes nestes recursos serão sistematizados, gerando uma [Lista de Termos dos Recursos](https://github.com/edalcin/MMA-Ameacadas/tree/main/recursos).


## 3. Realização da Oficina de Demandas do MMA/DESP

   A oficina de demandas do MMA/DESP será onde o "estudo de caso de interoperabilidade" será definido.

   As demandas por dados e informações são motivadas, na maioria das vezes, como por exemplo, pela elaboração de [relatórios periódicos contendo informações acerca da implementação da Convenção sobre Diversidade Biológica (CDB)](https://antigo.mma.gov.br/biodiversidade/conven%C3%A7%C3%A3o-da-diversidade-biol%C3%B3gica/relatorios-brasileiros.html), que é um compromisso assumido pelo Brasil como membro da Convenção previsto no Artigo 26 da CDB (ratificada e promulgada pelo Decreto Federal nº 2.519/1998).

   Outras atividades que demandam dados e informações sobre espécies ameaçadas, como por exermplo, a elaboração da [Estratégia e Plano de Ação Nacionais para a Biodiversidade – EPANB](https://antigo.mma.gov.br/biodiversidade/conven%C3%A7%C3%A3o-da-diversidade-biol%C3%B3gica/estrat%C3%A9gia-e-plano-de-a%C3%A7%C3%A3o-nacionais-para-a-biodiversidade-epanb.html), e dos Indicadores das Metas Nacionais de Biodiversidade.

   Neste contexto, **a oficina irá definir o foco do estudo de caso, e com base neste foco, as demandas por dados e informações**. Estas demandas, por sua vez, possibilitarão a construção de uma lista de termos e classes demandados pelo MMA/DESP. Esta lista, juntamente com a lista de termos e classes geradas a partir da [Sistematização dos Termos Presentes nos Recursos](https://github.com/edalcin/MMA-Ameacadas/blob/main/plano-de-trabalho/plano-de-trabalho.md#2-sistematiza%C3%A7%C3%A3o-dos-termos-presentes-nos-recursos), servirá de subsídio para a realização da [Oficina de Consolidação dos Termos Demandados e Presentes nos Recursos](https://github.com/edalcin/MMA-Ameacadas/blob/main/plano-de-trabalho/plano-de-trabalho.md#4-realiza%C3%A7%C3%A3o-da-oficina-de-consolida%C3%A7%C3%A3o-dos-termos-demandados-e-presentes-nos-recursos)
 
 ## 4. Realização da Oficina de Consolidação dos Termos Demandados e Presentes nos Recursos

   A oficina de consolidação de demandas das vinculadas ao MMA terá a participação de, além dos membros do MMA/DESP participantes da primeira oficina, membros do CNFlora/JBRJ e SALVE/ICMBio responsáveis pelo desenvolvimento dos sistemas e pela gestão de informação sobre biodiversidade. 
   
   As demandas compiladas na primeira oficina geraram listas de termos que agora são encaminhadas para consolidação e consulta de ofertas "ocultas" nas bases de dados de cada sistema. Serão considerados ajustes nas ofertas dos sistemas de informação.
  

  ### 4.1. Compilação de termos da Oficina de Consolidação
   
   #### Elaboração da **Lista de Termos Preliminar** e da **Lista de Termos que Necessitam de Sistematização**

   Como resultado da [*Oficina de Demandas do MMA/DESP*](https://github.com/edalcin/MMA-Ameacadas/blob/main/plano-de-trabalho/plano-de-trabalho.md#realiza%C3%A7%C3%A3o-da-oficina-de-demandas-do-mmadesp) e da [Sistematização dos Termos Presentes nos Recursos](https://github.com/edalcin/MMA-Ameacadas/blob/main/plano-de-trabalho/plano-de-trabalho.md#2-sistematiza%C3%A7%C3%A3o-dos-termos-presentes-nos-recursos), uma **Lista de Termos Preliminar** será elaborada. Esta lista conterá os termos demandados, organizados em "classes", representando conjuntos de dados que hoje estão sendo tratados pelos recursos - sistemas de informação - existentes.

   A **Lista de Termos que Necessitam de Sistematização** representa conjuntos de dados, levantados na oficina, que não estão sendo tratados nem ofertados pelor sistemas de informação atualmente.
   
   
 ## 5. Definição dos padrões de dados e metadados

   Padrões de dados e metadados relacionados a dados sobre biodiversidade e espécies ameaçadas seão levantados e suas classes e termos compiladas.
   
 ## 6. Harmonização das listas de termos com os padrões de dados existentes

   As listas preliminar e de termos que necessitam de sistematização serão comparadas com os padrões de dados e metadados existentes para que possam gerar uma **Lista de Termos Harmonizados e Consolidados** e uma **Lista de Classes e Termos que não estão nos Padrões Considerados**. A **Lista de Termos Harmonizados e Consolidados**, representando a demanda por dados de espécies ameaçadas associada aos padrões de dados existentes e a **Lista de Classes e Termos que não estão nos Padrões Considerados**, representando a demanda por criação de um vocabulário que inclua classes e termos essenciais às demandas do MMA/DESP. Estas listas harmonizadas serão usadas como subsídios da Oficina para elaboração da **Lista de Termos Acordada**.

## 7. Realização da Oficina para elaboração da **Lista de Termos Acordada**

   Esta oficina irá avaliar e validar a lista de termos harmonizada com os padrões existentes.

 ### 7.1. Elaboração da **Proposta de Padrão de Dados para Espécies Ameaçadas**
 
   Considerando a validação da **Lista de Termos Acordada**, será elaborada um **Proposta de Padrão de Dados para Espécies Ameaçadas**, representando o **Produto 1** deste conjunto de oficinas.  
   

## 8. Definição das ferramentas e protocolos para publicação de dados

   De acordo com levantamento prévio presente no *Diagnóstico Nacional de Gestão de Dados de Biodiversidade*, um conjunto de mecanismos de publicação de dados já encontra-se em produção em diferentes instituições responsáveis pelos sistemas de informação que gereciam os recursos de informação sobre espécies ameaçadas. Este conjunto será revisado para atualização quanto a alterações e serão também apresentados eventuais novas ferramentas e protocolos para publicação de dados de biodiversidade adequadas ao contexto desta abordagem.

## 9. Realização da Oficina de definição dos mecanismos de publicação

   Esta oficina irá decidir os mecanismos comuns de publicação de dados sobre espécies ameaçadas para todas as instituições vinculadas ao MMA participantes.

 ### 9.1. Elaboração da **Proposta de Mecanismos para Publicação Dados sobre Espécies Ameaçadas**
 
   Considerando a decisão de um conjunto de ferramentas e protocolos para publicação de dados de biodiversidade, esta Proposta representará o **Produto 2** deste conjunto de oficinas.  

## 10. Reunião de apresentação dos produtos e fechamento

Esta reunião final pode ter dois momentos diferentes:
* Manhã
  * Grupo técnico para definição de encaminhamentos e próximos passos;
* Tarde
  * Apresentação dos produtos para todos os participantes do Projeto GEF Pró-espécies.


## Cronograma

|  | Mês 1 | Mes 2 |
|--|:--:|--|
| Tarefa1 | X |  |
