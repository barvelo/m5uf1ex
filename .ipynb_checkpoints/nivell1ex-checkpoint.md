# Spring framework


![texto_alternativo](./logo.png)

**L'Spring framework** (abreviant, Spring), és un marc de treball de codi obert per la plataforma Java. La primera versió va ser escrita per Rod Johnson, que inicialment va **_llençar el producte juntament amb el llibre One-on-One Java EE Design and Development._**[1] També hi ha un port disponible per la plataforma .NET, Spring.NET.

## Història de Spring Framework

Les primeres parts del que ha esdevingut **Spring Framework** van ser escrites per **_Rod Johnson el 2000_**, mentre treballava com a consultor independent per clients de la indústria financera a Londres. Mentre escrivia el seu llibre Expert One-on-one J2EE Design And Development (Programmer to programmer) **(2002)**, va anar més enllà del seu codi per expressar la seva perspectiva de com les aplicacions amb diferents parts de la plataforma J2EE hauria d'esdevenir més simple i més consistent del que els desenvolupadors i les empreses ho estaven fent en aquell moment.

## Funcionalitats clau

- Gestió de la configuració basada en JavaBeans, aplicant-hi principis d'Inversió de Control, més específicament usant la tècnica d'Injecció de Dependència. Això ajuda a reduir les dependències de components, en implementacions específiques, sobre altres components.

  - Una factoria de Beans central, que és usada globalment.

       - Capa genèrica d'abstracció per la gestió de transaccions de la base de dades.

  - Estratègies preincorporades per la JTA i un sol DataSource de JDBC. Això elimina la dependència en un entorn Java EE pel suport a les transaccions
  
- Integració amb entorns de persistència com Hibernate, JDO, iBatis i db4o.
  - Entorn d'aplicació web MVC, construït al nucli de la funcionalitat de Spring. suportant moltes tecnologies per generar vistes,     incloent-hi JSP, FreeMaker, Velocity, Tiles, iText i POI.
  
- Entorn extensiu de programació orientada a aspectes per proveir serveis, com ara gestió de les transaccions. Amb això es millora la modularitat dels sistemes.

## Introducció a Spring Framework

Aquest entorn proveeix solucions per diversos reptes tècnics encarats per desenvolupadors Java i organitzacions que volen crear aplicacions basades en la Plataforma Java. Donada la clara amplitud de la funcionalitat que s'hi ofereix, pot fer-se complicat distingir entre els blocs principals que componen el marc de treball. Spring Framework no està lligat exclusivament a Java EE, encara que la seva prou aconseguida integració en aquesta àrea és una raó important per la seva popularitat.

### Mòduls de l'Spring Framework

> Spring Framework pot ser considerat com una col·lecció d'entorns més petits, o entorns dintre d'entorns. La majoria d'aquests estan dissenyats per treballar independentment uns dels altres, tot i que se suposa que junts, milloren les funcionalitats. Aquests mòduls estan dividits en blocs de construcció típics d'aplicacions complexes:

```java

package com.tc.service;
/**
   * La interfaz de servicio (capa empresarial) del módulo de empleados
 */
public interface EmpService {
	/ ** Agregar información del empleado * /
	public void addEmp();
}

```  

# Enlaces externos

[Harrop, Rob; Jan Machahek. Pro Spring. APress, 2005. ISBN 1-59059-461-4.](#)

[Johnson, Rod; Jürgen Höller. J2EE Development without EJB. Wiley, 2004. ISBN 0-7645-5831-5.](#)

[Johnson, Rod. Expert One-on-on J2EE Design and Development. Wiley, 2002. ISBN 0-7645-4385-7.](#)

[Walls, Craig; Ryan Breidenbach. Spring in Action. Manning, 2005. ISBN 1-932394-35-4.](#)
