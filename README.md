## Description
<b> <h4> STEM Classification of CBO-2002 Occupations and Brazillian HEC Fields of Education </h4> </b>

We provide .csv tables classifying CBO-2002 occupations (Classificação Brasileira de Ocupações) into STEM and non-STEM occupations, as well as INEP’s
HEC's(Higher Education Census) fields of education classification of STEM degrees in Brazil. In addition to the tables, we also provide reports in .pdf format with a guide and full disclosure of the classification processes. 

In Brazil, there is no official taxonomy of STEM jobs or educational fields. As a result, the few existing analysis of STEM jobs and education in Brazil use their own, generally vague, classifications and are not transparent about the classification criteria. We seek to fill this gap in the STEM taxonomy and literature by providing unprecedented classification of STEM occupations and higher-education degrees in Brazil. 

## Files

| **Name** | **Description** | **Type**  | **File** |
|----------|-----------------|-----------|----------|
| STEM Classification of CBO-2002 Occupations | Four Digit CBO-2002 Occupational Codes STEM Classification. Dummy <code>stem</code> equals 1 if occupation is STEM and 0 otherwise.   | .csv Table  | [stem_cbo2002.csv](tables/stem_cbo2002.csv) |
| STEM Classification INEP’s HEC's Fields of Education | INEP’s Higher Education Census (HEC) fields of education classification of STEM degrees.    Dummy <code>stem</code> equals 1 if educational degree is STEM and 0 otherwise.                                          |  .csv Table |  insert file |
| STEM Classification of Household CBO Occupations     |  Household CBO Occupational Codes STEM Classification. Dummy <code>stem</code> equals 1 if occupation is STEM and 0 otherwise.                                                                                                                                        |  .csv Table | [stem_cbo_household.csv](tables/stem_cbo_household.csv)  |
| STEM Classification in the Formal Labor Market in Brazil |    Report containing a guide and full disclosure of the classification criteria for CBO-2002 definitions of STEM occupations. It also contains the proposed classification applied to 2017 RAIS (Relação Anual de Informações Sociais), an administrative data set from the Ministry of Labor in which occupations are identified by a CBO-2002 code, to provide preliminary statistics of the STEM formal labor market in Brazil. | .pdf Report | [stem_occupations_classification.pdf](reports/stem_occupations_classification.pdf)  |
|  STEM Classification for Brazilian Higher Education | Report with a STEM field classification proposal tailored to the Brazilian Higher-Education Censuses (HEC), consistent across multiple years of the HEC. It contains preliminary statistics of the classification applied to HEC/INEP data, from 2010 to 2019. |   .pdf Report    | [stem_education_classification.pdf](reports/stem_education_classification.pdf) |

## How to use

Import the .csv files into <code>R</code>, <code>STATA</code>, or your preferred statistical software and merge by occupational or degree identification code. 

## Credits

If you benefit from our classification tables and/or reports in this repository, please cite it in your work as:

Machado, C., Rachter, L., Schanaider, F., & Stussi, M. (2022) STEM Classification for the Brazilian Formal Labor Market and the Brazillian Higher Education. Github repository - [https://github.com/mstussi/stem_brazil](https://github.com/mstussi/stem_brazil)

## More About the Occcupational Standards and Educational Degrees in Brazil

<h4> Occupational Standards </h4>  

The [CBO](https://concla.ibge.gov.br/classificacoes/por-tema/ocupacao/classificacao-brasileira-de-ocupacoes.html) (Classificação Brasileira de Ocupações)  is the Brazilian statistical standard to classify workers into occupational categories. It describes and orders occupations within a hierarchical structure that makes it possible to aggregate information regarding the workforce, according to occupational characteristics that concern the nature of the workforce and the content of the work. We classify STEM occupations based on [a definition](https://www.bls.gov/soc/attachment_c_stem.pdf) proposed by the United States Bureau of Labor Statistics (USBLS) for the [2010-SOC](https://www.bls.gov/soc/2010/home.htm) (Standard Occupational Classification). For each of the 622 CBO-2002 four-digit occupational codes, a correspondence was sought among the SOC-2010 set of 97 STEM occupations listed by USBLS. 
FALAR DA CBO DOMILICIAR.

The 'Household CBO' ([CBO-Domiciliar](https://concla.ibge.gov.br/images/concla/estrutura/CBODomicilar.xls)) presents small differences in relation to the CBO-2002. It was used in the 2000's Demographic Census as a provisional version of the CBO, available at the time it was carried out, called CBO-Domiciliar. The CBO-Domiciliar was later implemented in the other IBGE household surveys from 2002 onwards, such as [PNAD](https://www.ibge.gov.br/estatisticas/sociais/populacao/9127-pesquisa-nacional-por-amostra-de-domicilios.html?=&t=o-que-e) (the National Survey by Household Sample). 


<h4> Educational Degrees in the Brazillian Superior Education Censuses </h4>  

The [HEC](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-da-educacao-superior) (Brazillian Higher-Education Censuses) is collected by INEP and contains data from every registered higher education institution in the country, on a yearly basis. Each data-set contains nation-wide, individual-level, identified data, with student, institution and degree characteristics. HEC contain [ISCED](http://uis.unesco.org/en/topic/international-standard-classification-education-isced) degree identification codes, developed by UNESCO and adopted by many other international organizations such as the OECD and EUROSTAT. ISCED codes are useful when classifying STEM fields because [SAGA](https://en.unesco.org/saga) (STEM and Gender Advancement), a global policy initiative created by UNESCO, has already developed an educational STEM field classification, compatible with ISCED codes, which are available in INEP’s data-sets. Combining SAGA’s STEM classification with ISCED codes, available for Brazilian data, provides a starting point for identifying STEM degrees, modifying it to better suit to the context of Brazilian higher education.




