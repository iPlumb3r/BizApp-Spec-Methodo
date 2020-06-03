# Activity ID : Déclarer et caractériser une organisation

## Involved Roles
Activité métier réalisée par :
* @finalCustomer (=> eux-même, @serviceProvider ou @hostingCompany)
* @serviceProvider (=> eux-même)
* @hostedConsultant (=> @hostingCompany)

# WHY ?

## Finality
Permet d’identifier de manière unique chaque @Organization de l’écosystème et de disposer des informations utiles à son propos.

# WHAT ?
## Description
Les différents utilisateurs sus-cités doivent pouvoir référencer et caractériser une @Organization dans la plateforme “HRC”, que ce soit : 
* Leur propre @Organization : C’est le cas des #finalCustomer et des @serviceProvider qui doivent se déclarer eux-même au moment de l’inscription
* Une autre #Organization que la leur :
  * C’est le cas des @hostedConsultant qui doivent déclarer leur @hostingCompany lors de leur inscription
  * C’est le cas des @finalCustomer qui peuvent déclarer des @serviceProvider ou des @hostingCompany dans le cadre des leur processus de référencement 

## Trigger Event
Une @Organization doit / peut être déclarée : 
* à l’inscription
* au référencement

## Manipulated Concept(s)

@Organization
* @finalCustomer
* @serviceProvider
* @hostingCompany

## Associated Requirements
Le système doit pouvoir alerter l’utilisateur sur des critères à définir que la société présente des risques

Cas des @finalCustomer ou des @serviceProvider : Par défaut, l’@Organization est défini comme étant une @subsidiary.
S’il s’agit d’une @headquarter alors il faut le déclarer explicitement et le système doit alors permettre de sélectionner les @subsidiary existantes ou d’en définir de nouvelle.

# How ?
## Comment(s)
Voir s’il existe un service “open data” pour faciliter la saisie des @Organization dans la plateforme (Infogreffe ou autre)

## Question(s)
Question A ...

