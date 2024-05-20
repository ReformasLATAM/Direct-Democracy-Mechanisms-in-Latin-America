# Direct Democracy Mechanisms in Latin America

Welcome to the GitHub repository of the database "Direct Democracy Mechanisms in Latin America," maintained by members of the Political Reform Observatory in Latin America.

## Contents

- [Summary](#summary)
- [Description](#description)
- [Citation](#citation)

## Summary

The database contains information on the regulations concerning the governing mechanisms of direct democracy, (citizens' initiative, mandate, recall, and public consultation) of 17 Latin American countries between 1979 and 2021. 

The information was coded based on the following variables: country (name, cowcode and acronym), year in which the reform was established, consecutive country reforms, regulation  to direct democracy mechanisms, citizens' initiative existence, percentage of support to promote the citizens' initiative, demand for additional requirements to promote the citizens' initiative, existence of a presidential recall, percentage of citizen support to the presidential recall, demand for additional requirements to endorse the presidential recall, existence of legislative recall, percentage of citizen support to endorse the legislative recall, additional requirements to endorse legislative recall, support of popular consultation from public authorities, support of public consultation from the executive, support of public  consultation from the legislature, support of popular consultation from the citizens and percentage of citizen support to activate public consultation.

Members of the Observatory of Political Reforms in Latin America collected and coded the information. The information collection managers are Mariana Ramírez Bustamante (University of Salamanca), Adrián Porras Flores (University of Salamanca) and María de Guadalupe Salmorán Villar (Institute for Legal Research, UNAM); the coding managers are Carlos Guadarrama Cruz (Faculty of Higher Studies Acatlán, UNAM) and Elliot Román Almaraz (Faculty of Higher Studies Acatlán, UNAM).

## Description

The directory `./Data/` contains the file `./Data/DD_DirectDemocracy` where all relevant information regarding the database linked to the direct democracy mechanisms in Latin America and its reforms is located. Specifically, the database consists of the following variables:

-   `country`: name of the country in which the reform of direct democratic mechanisms in Latin America was implemented.

-   `cowcode`: country code according to the coding of“Correlates of War” https://correlatesofwar.org/data-sets/cow-country-codes.

-   `reform_year`: calendar year corresponding to the reform of the direct democracy mechanisms in each Latin American country between 1979-2021. 

-   `consec_country_reform`: records the consecutive number of the reforms to the direct democracy mechanisms in each Latin American country. e.g. Peru_1 Peru_2, Peru_3, Peru_4.

-   `regulation`: indicates the legal status of the regulations establishing the direct democracy mechanisms. Constitution [1]: Mechanisms are regulated in the constitutional framework. Law [2]: mechanisms are regulated in electoral laws. 

-   `citizens'_initiative`: indicates whether the reform establishes the citizens' initiative mechanism. No [0]: the reform does not mention the citizens' initiative mechanism. Yes [1]: the reform regulates the initiative mechanism.

-   `percentage_iniciative`: indicates the percentage of support on the electoral roll (or electoral roll, depending on the country) required by law to promote a citizens' initiative.

-   `additional_requi_initiative`: indicates whether the reform establishes additional requirements to the percentage of support for promoting a citizens' initiative for a law. No [0]: the reform does not establish additional requirements to promote this direct democracy mechanism.Yes [1]: the reform establishes additional requirements to promote this mechanism of direct democracy.

-   `president_recall`: indicates whether the reform establishes the recall mechanism for the executive branch. No [0]: the reform does not establish the recall mechanism to the executive branch. Yes [1]: the reform establishes the recall mechanism to the executive branch.

-   `percentage_president_recall`: indicates the percentage of support on the electoral roll (or electoral roll, depending on the country) established by the law to promote the recall of the executive power.

-   `additional_requi_president_recall`: indicates whether the reform establishes additional requirements to the percentage of support to promote the recall of the executive power. No [0]: the reform does not establish additional requirements to promote this mechanism. Yes [1]: the reform establishes additional requirements to promote this mechanism.

-   `legislative_recall`: indicates whether the reform provides  a recall mechanism for any person in the legislative branch. No [0]: the reform does not provide the recall of any representative in the legislative branch.Yes [1]: the reform establishes the recall of any representative belonging to the legislative branch.

-   `percentage_legislative_recall`: indicates the percentage of support on the electoral roll (or electoral roll, depending on the country) established by law to promote the recall of a member of the legislature.

-   `additional_requi_legislative_recall`: indicates whether the reform establishes additional requirements to the percentage of support to promote the recall of a person belonging to the legislative branch. No [0]: the reform does not establish additional requirements to support the recall of any representative belonging to the legislative branch. Yes [1]: the reform establishes additional requirements to support  the recall of a representative belonging to the legislative branch.

-   `authorities_consult`: indicates whether the reform establishes the possibility for public authorities to support the popular consultation mechanism. No [0]: the reform does not establish the possibility for public authorities to support the public consultation mechanism.Yes [1]: the reform establishes the possibility for public authorities to support the public consultation mechanism.

-   `executive_consult`: indicates whether the reform mentions that the executive branch may endorse the public consultation mechanism. No [0]: the reform does not mention that the executive branch is the one to endorse the public consultation mechanism. Yes [1]: the reform mentions that the executive branch is the one to endorse the public consultation mechanism.

-   `legislative_consult`: indicates whether the reform mentions that the legislature may endorse the public consultation mechanism. No [0]: the reform does not mention that the legislative branch is the one to endorse the public consultation mechanism. Yes [1]: the reform mentions that the legislative branch is the one to endorse the public consultation mechanism.

-   `public_consult`: indicates whether the reform mentions that citizens will be able to endorse the popular consultation mechanism. No [0]: the reform does not mention that citizens should be the ones to endorse the public consultation mechanism. Yes [1]: the reform mentions that the citizens should be the ones to endorse the public consultation mechanism.

-   `percentage_public_consultation`: indicates the percentage of support from the electoral roll (or electoral census, depending on the country) established by law to support the consultation.

## Citation

``` r
Freidenberg, Flavia. Dir., 2022,  “Direct Democracy Mechanisms in Latin America", Observatory of Political Reforms in Latin America (1978-2022). Mexico City: Institute for Legal Research (IIJ-UNAM) and Washington, D.C.: Secretariat for Strengthening Democracy of the Organization of American States (SSD/OAS), V2. DOI:
https://doi.org/10.6084/m9.figshare.19078358.v2.
```