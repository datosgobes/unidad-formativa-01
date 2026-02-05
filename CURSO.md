<!--
module_id: unidad-formativa-01
author: Equipo gestor de la plataforma datos.gob.es
email: contacto@datos.gob.es
date: 26/01/2026
version: 1.0.0
language: es
narrator: Spanish Female
mode: Textbook
title: Unidad 01 - Datos abiertos: conceptos básicos y beneficios
comment: Esta unidad presenta los conceptos básicos, principios y beneficios de los datos abiertos.
long_description: Unidades didácticas. Unidad 01 - Datos abiertos: conceptos básicos y beneficios. Más información en [datos.gob.es](https://datos.gob.es/)

edit: true

repository: https://github.com/datosgobes/unidad-formativa-01

logo:     https://cdn.jsdelivr.net/gh/datosgobes/materiales-formativos@main/assets/img/logo_dge_square.svg

icon:     https://cdn.jsdelivr.net/gh/datosgobes/materiales-formativos@main/assets/img/logo_dge_normal.svg

dark:   false

script: https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

link: https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap
      https://cdn.jsdelivr.net/gh/datosgobes/materiales-formativos@main/assets/css/dge-styles.css

font: Montserrat

import: https://raw.githubusercontent.com/liaScript/mermaid_template/master/README.md

import: https://raw.githubusercontent.com/LiaTemplates/Communica/0.0.2/README.md

attribute: Iniciativa de datos abiertos del Gobierno de España [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
-->

# Unidad 01 - Datos abiertos: conceptos básicos y beneficios

<ul class="logo-list primary-logos">
  <li><a href="https://digital.gob.es/ministerio/organigrama_organos/SEDIA.html"><img alt="Secretaría de Estado de Digitalización e Inteligencia Artificial" src="https://raw.githubusercontent.com/datosgobes/materiales-formativos/refs/heads/main/assets/img/logo_sedia_red-es.jpg"></a></li>
  <li><a href="https://datos.gob.es"><img alt="datos.gob.es" src="https://raw.githubusercontent.com/datosgobes/materiales-formativos/refs/heads/main/assets/img/logo_dge_normal.svg"></a></li>
  <li><a href="https://datos.gob.es/acerca-de-la-iniciativa-aporta"><img alt="Iniciativa Aporta" src="https://raw.githubusercontent.com/datosgobes/materiales-formativos/refs/heads/main/assets/img/logo_iniciativa-aporta.svg"></a></li>
</ul>

[preview-lia](https://raw.githubusercontent.com/datosgobes/unidad-formativa-01/refs/heads/main/README.md)

<div style="text-align:center; margin: 1.5em 0 1em 0;">
	<div style="display:flex; justify-content:center; gap:1rem; flex-wrap:wrap; margin-bottom:0.75rem;">
		<a href="https://liascript.github.io/course/?https://raw.githubusercontent.com/datosgobes/unidad-formativa-01/refs/heads/main/CURSO.md#3" class="pdf-download-btn" style="font-size:1.75em; padding:1rem 1.6rem; font-weight:800;">
      ▶️ Empezar curso
    </a>
  </div>
  <div style="display:flex; justify-content:center; gap:1rem; flex-wrap:wrap; margin-bottom:0.5rem;">
    <a href="https://github.com/datosgobes/unidad-formativa-01/releases/download/latest/documentation-unidad-formativa-01.pdf" target="_blank" rel="noopener" class="pdf-download-btn" style="font-size:0.95em; padding:0.55rem 0.9rem; background:#6b7280; color:#ffffff;">
      📄 PDF
    </a>
    <a href="https://github.com/datosgobes/unidad-formativa-01/releases/download/latest/scorm-unidad-formativa-01.zip" target="_blank" rel="noopener" class="pdf-download-btn" style="font-size:0.95em; padding:0.55rem 0.9rem; background:#6b7280; color:#ffffff;">
      📦 SCORM
    </a>
    <a href="https://github.com/datosgobes/unidad-formativa-01/releases/download/latest/ims-unidad-formativa-01.zip" target="_blank" rel="noopener" class="pdf-download-btn" style="font-size:0.95em; padding:0.55rem 0.9rem; background:#6b7280; color:#ffffff;">
      📚 IMS
    </a>
  </div>
  <div style="font-size:0.95em; color:#446DA2;">Empezar el curso o descargar documentación</div>
</div>

<div style="background:#ebf3ff; border-left:4px solid rgb(var(--color-highlight)); padding:1rem 1rem; border-radius:8px; color:var(--color-highlight);">
  <p style="margin:0.5rem 0 0.25rem 0;text-align:center;">
    Esta unidad ha sido elaborada en el marco de la <a href="https://datos.gob.es/es/que-hacemos" target="_blank" rel="noopener">Iniciativa Aporta (datos.gob.es)</a>, desarrollada por el <a href="https://digital.gob.es/" target="_blank" rel="noopener">Ministerio para la Transformación Digital y de la Función Pública</a> a través de la <a href="https://www.red.es/" target="_blank" rel="noopener">Entidad Pública Empresarial Red.es</a>
  </p>
  <br>
  <div style="text-align:center;">
    <strong style="font-size:1.05em;">📝 Aviso legal</strong>
  </div>
  <p style="margin:0.5rem 0 0.25rem 0;text-align:center;">
    Esta obra está sujeta a una licencia Atribución 4.0 de Creative Commons (CC BY 4.0). Está permitida su reproducción, distribución, comunicación pública y transformación para generar una obra derivada, sin ninguna restricción, siempre que se cite al titular de los derechos (<i>Ministerio para la Transformación Digital y de la Función Pública a través de la Entidad Pública Empresarial Red.es</i>). La licencia completa se puede consultar en: <a href="https://creativecommons.org/licenses/by/4.0" target="_blank" rel="noopener">Attribution 4.0 International</a>
  </p>
</div>

![](media/image_001.jpg)

**05/01/2026**

![](media/image_002.png)

## TUTORIAL

{{|>}}
*************************************************************************************************************


<div style="background:#fdf8ec; border-left:4px solid rgb(var(--lia-warning)); padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#fdf2e4; color:rgb(var(--lia-warning)); padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		⚠️ Aviso
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			Este curso está diseñado en <a href="https://liascript.github.io/" target="_blank" rel="noopener">LiaScript</a>. Para disfrutarlo con todas sus funcionalidades, accede a <a href="https://liascript.github.io/course/?https://raw.githubusercontent.com/datosgobes/unidad-formativa-01/refs/heads/main/CURSO.md" target="_blank" rel="noopener">este enlace</a>.
			</p>
			<p style="margin:0;">
			Para conocer más sobre el formato Markdown utilizado por LiaScript, consulta la <a href="https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md" target="_blank" rel="noopener">documentación oficial</a>.
		</p>
	</div>
</div>

{{1}}
Puedes navegar el curso a través del índice de la parte izquierda o usando las flechas de navegación del teclado o de la parte inferior de la web.

![Navegación del curso](https://raw.githubusercontent.com/datosgobes/materiales-formativos/refs/heads/main/media/tutorial_dge_sections.png)

{{2}}
Al finalizar cada sección, tendrás la oportunidad de responder preguntas para comprobar tu aprendizaje. Estas actividades solo están disponibles en la versión LiaScript, no en Markdown estándar.

??[Cuestionario](https://liascript.github.io/course/?https://raw.githubusercontent.com/datosgobes/unidad-formativa-01/refs/heads/main/CURSO.md#cuestionario-final)

{{3}}

Recursos disponibles:

- <span class="res res-fuente">📖 <strong>Fuente</strong></span>: origen de la definición o de la información que respalda el concepto o información que se está presentando.
- <span class="res res-ejemplo">🧭 <strong>Ejemplo</strong></span>: casos concretos que facilitan la comprensión.
- <span class="res res-aviso">⚠️ <strong>Aviso</strong></span>: consejo o dato práctico para entender lo presentado.
- <span class="res res-mas-info">ℹ️ <strong>Más información</strong></span>: material de relevancia que complementa lo explicado.
- <span class="res res-saber">🔍 <strong>Saber más</strong></span>: referencias y documentos adicionales.
- <span class="res res-caso">🧪 <strong>Caso de estudio</strong></span>: casos reales para afianzar conocimientos.
- <span class="res res-ejercicio">🏋️ <strong>Ejercicio</strong></span>: actividades para aplicar los conocimientos adquiridos.

{{4}}
Existe la opción de seleccionar otro idioma para el curso usando la traducción -si existe aparecen listados- o seleccionando el servicio de traducción automática con un solo clic. Ten presente que la traducción automática puede contener errores o interpretaciones incorrectas de algunos conceptos.

![Botón para traducir el contenido](https://raw.githubusercontent.com/datosgobes/materiales-formativos/refs/heads/main/media/tutorial_dge_translate.png)

{{5}}
El curso incluye secciones con narración de audio. Puedes activar o desactivar la narración utilizando el botón situado en la parte superior de cada página.

![Ejemplo de narración de una página](https://raw.githubusercontent.com/datosgobes/materiales-formativos/refs/heads/main/media/tutorial_dge_audio.png)

*************************************************************************************************************>

## INFORMACIÓN INICIAL

{{|>}}
*************************************************************************************************************

<center>
__Título de la unidad__

¿Qué son los datos abiertos? Conceptos básicos, principios y beneficios.

__Descripción de la unidad__

La unidad ofrece una visión general de qué son los datos abiertos, cómo se usan y qué beneficios aportan en términos de accesibilidad, reutilización, transparencia y valor social y económico.
</center>

---

!?[Vídeo descriptivo de la unidad](https://www.youtube.com/watch?v=UM9aGVdHuyU)

*************************************************************************************************************>

## OBJETIVOS DIDÁCTICOS

{{|>}}
*************************************************************************************************************

Comenzamos presentando los **objetivos didácticos** de esta unidad:

> - Establecer **conceptos básicos** relacionados con los datos abiertos tomando como referencia el marco legislativo vigente en España.
> - Reconocer los **principios generales** a tener en cuenta para asegurar que los datos abiertos son fácilmente reutilizables.
> - Descubrir los principales **beneficios económicos y sociales** que supone la apertura de datos públicos.
> - Conocer los **aspectos clave ligados al ecosistema de los datos** de cara a asegurar la generación de los beneficios apuntados.

*************************************************************************************************************>

## CONTENIDOS

{{|>}}
*************************************************************************************************************

>{{1}} **[INTRODUCCIÓN](#introducción)**  
>
>{{2}} **[CONCEPTOS CLAVE](#conceptos-clave)** 
>
>{{3}} **[PRINCIPIOS DE APERTURA DE DATOS](#principios)**  
>
>{{4}} **[BENEFICIOS DE LA REUTILIZACIÓN DE DATOS ABIERTOS](#beneficios)** 
>
>{{5}} **[CUESTIONARIO FINAL](#cuestionario-final)**  
>
>{{6}} **[RESUMEN](#resumen)**

*************************************************************************************************************>

## PÚBLICO OBJETIVO

{{|>}}
*************************************************************************************************************

Esta unidad formativa está dirigida a:

> - [x] Publicadores de datos abiertos y reutilizadores de los mismos.

*************************************************************************************************************>

## CONOCIMIENTOS PREVIOS NECESARIOS

{{|>}}
*************************************************************************************************************

Para poder asimilar los conceptos que vamos a desarrollar en la unidad:

> - [x] No se precisan conocimientos previos.

*************************************************************************************************************>

<!-- id="introduccion" -->
## INTRODUCCIÓN

{{|>}}
*************************************************************************************************************

En la sociedad actual **los datos se han convertido en un activo fundamental**, tanto para las personas como para las organizaciones. El dato, y su papel esencial en el desarrollo de tecnologías disruptivas como la inteligencia artificial, supone el factor diferencial de la revolución industrial y tecnológica en la que nos encontramos inmersos.

Los datos generados por las administraciones públicas fruto de su actividad —los **datos del sector público**— despiertan un gran interés:

- Para la ciudadanía, porque son una herramienta clave para la **transparencia y la participación democrática**.
- Para las empresas, porque representan una fuente valiosa para **mejorar la competitividad** en distintos sectores.
- Para las propias administraciones, porque facilitan la **definición y optimización de políticas públicas**.

Los datos producidos por las administraciones en el ejercicio de sus funciones deben ponerse a disposición de la sociedad como **datos abiertos**: **accesibles y disponibles para todos, sin restricciones legales ni técnicas**.

Los datos procedentes de múltiples ámbitos —geográfico, medioambiental, meteorológico, turístico, empresarial, educativo, entre otros— conforman un conjunto amplio, diverso y valioso. Publicados como datos abiertos, pueden y deben generar beneficios para toda la sociedad.

*************************************************************************************************************>

<!-- id="conceptos-clave" -->
## CONCEPTOS CLAVE

{{|>}}
*************************************************************************************************************

Como punto de partida se definen los conceptos básicos que se manejan al hablar de datos en general y de datos abiertos en particular. Se toma como referencia el marco legislativo vigente en España.

*************************************************************************************************************>

### 2.1. Bloque I: Conceptos básicos

{{|>}}
*************************************************************************************************************

> **Dato:** toda representación digital de actos, hechos o información, así como su recopilación, incluso como grabación sonora, visual o audiovisual. [📖 Fuente](https://www.boe.es/buscar/act.php?id=BOE-A-2010-1331)

Los datos pueden ser **estructurados** y **no estructurados**:

- **Estructurados**: tienen bien definidos su longitud y su formato, como las fechas, los números o las cadenas de caracteres. Se almacenan en tablas.
- **No estructurados**: carecen de un formato específico. No se pueden almacenar dentro de una tabla.


<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		🧭 Ejemplo
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<ul style="margin:0.25rem 0 0.5rem 0;">
			<li><strong>Dato:</strong> 15°C.
			<br>- Es un valor aislado, sin contexto. Solo sabemos que es una temperatura.</li>
			<li><strong>Información:</strong> la temperatura en Valladolid hoy es de 15°C.
			<br>- El dato se contextualiza: sabemos dónde y cúando se aplica.</li>
			<li><strong>Conocimiento:</strong> si la temperatura en Valladolid es de 15°C en enero, es inusualmente alta.
			<br>- Se interpreta la información, se relaciona con experiencia y se extraen conclusiones útiles.</li>
		</ul>
	</div>
</div>

<center>![Datos, información y conocimiento](media/image_003.png "Datos, información y conocimiento. Fuente: Shutterstock. Créditos: Anna Frajtova")</center>

> **Datos abiertos:** cualquiera es libre de utilizar, reutilizar y redistribuir, con el único límite, en su caso, del requisito de atribución de su fuente o el reconocimiento de su autoría. [📖 Fuente](https://www.boe.es/buscar/act.php?id=BOE-A-2007-19814)

Esta definición identifica tres características esenciales:

- **Uso libre**: pueden emplearse para cualquier finalidad, incluida la comercial.
- **Reutilización**: posibilidad de transformar, combinar o enriquecer los datos.
- **Redistribución**: posibilidad de compartir datos originales o derivados.

<center>![Definición de datos abiertos](media/image_004-005.png "Definición de datos abiertos. Fuente: [datos.gob.es](https://datos.gob.es/)")</center>

**Lo que NO son datos abiertos**

- Datos publicados sin licencia clara (genera inseguridad jurídica).
- Datos accesibles solo previo registro o pago.
- Datos con restricciones de privacidad o seguridad (ej: datos personales).

<div style="background:#fdf8ec; border-left:4px solid rgb(var(--lia-warning)); padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#fdf2e4; color:rgb(var(--lia-warning)); padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		⚠️ Aviso
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			En la práctica, esto significa que:
		<ul style="list-style-type: disc; margin-left: 1.5em;">
			<li>Un ayuntamiento publica sus presupuestos anuales como datos abiertos: ciudadanos y periodistas pueden analizarlos.</li>
			<li>El Ministerio de Transportes ofrece datos de tráfico en tiempo real: desarrolladores crean aplicaciones de movilidad.</li>
			<li>El Instituto Nacional de Estadística publica datos demográficos: investigadores los usan para estudios socioeconómicos.</li>
		</ul>
		</p>
	</div>
</div>

> **Licencia abierta:** acuerdo legal que otorga permisos de libre uso, modificación y distribución de un recurso, exigiendo únicamente **el reconocimiento del autor** y la continuidad de la propia licencia abierta. Las licencias Creative Commons (CC) es el ejemplo más popular para contenidos y datos, y en concreto, las mostradas en este esquema, las más habituales en el contexto de los datos abiertos.

<center>![Licencias](media/image_006-1.jpg "Licencias predefinidas más populares para datos abiertos. Fuente: [datos.gob.es](https://datos.gob.es/)")</center>

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		🧭 Ejemplo
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			El Instituto Geográfico Nacional ofrece información geográfica digital de España reutilizable y gratuita bajo una licencia **CC-BY 4.0.** [📖 Fuente](https://centrodedescargas.cnig.es/CentroDescargas/politica-datos) 
		</p>
	</div>
</div>

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#e4d7fb; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      [La importancia de las licencias en el entorno digital: un enfoque accesible para todos](https://datos.gob.es/es/noticias/licencias-de-uso-asociadas-las-iniciativas-de-datos-abiertos-en-espana)
    </p>
  </div>
</div>

> **Datos abiertos gubernamentales o del sector público:** son datos generados, creados, recolectados, procesados, preservados, mantenidos, diseminados o financiados por un gobierno o una institución pública, y que consideran los requerimientos y restricciones legales que permiten su reutilización -licencia abierta-. Son datos con un gran potencial. [📖 Fuente](https://ideas.repec.org/p/oec/govaaa/22-en.html).
>
> **Las administraciones públicas son los principales proveedores de datos abiertos**. Por esta razón, cuando hablamos de datos abiertos, generalmente se hace referencia a datos oficinales gubernamentales disponibles como abiertos.


<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		🧭 Ejemplo
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			El Instituto Nacional de Estadística (INE) publica datos de población, que actualiza periódicamente. [📖 Fuente](https://www.ine.es/dyngs/INEbase/categoria.htm?c=Estadistica_P&cid=1254735572981/)
		</p>
	</div>
</div>

> **Datos abiertos de alto valor (HVD** por sus siglas en inglés): datos cuya reutilización está asociada a considerables **beneficios para la sociedad, el medio ambiente y la economía**, en particular debido a su idoneidad para la creación de servicios de valor añadido, aplicaciones y puestos de trabajo nuevos, dignos y de calidad, y del número de beneficiarios potenciales de los servicios de valor añadido y aplicaciones basados en tales conjuntos de datos. [📖 Fuente](https://www.boe.es/buscar/act.php?id=BOE-A-2007-19814#:~:text=Subir-,%5BBloque%207%3A%20%23a3%2D3%5D,-Art%C3%ADculo%203.ter)
>
> En enero de 2023, la Comisión Europea define seis categorías para diferenciar los datos de alto valor [📖 Fuente](https://datos.gob.es/es/catalogo/conjuntos-datos?is_hvd=true)


<center> ![Categorías temáticas de conjuntos de alto valor](media/image_006.jpg "Categorías temáticas de conjuntos de alto valor. Fuente: [datos.gob.es](https://datos.gob.es/)") </center>

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#e4d7fb; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      [Europa define los conjuntos de datos de alto valor que el sector público tendrá que abrir como máximo en 2024](https://datos.gob.es/es/noticias/europa-define-los-conjuntos-de-datos-de-alto-valor-que-el-sector-publico-tendra-que-abrir)
    </p>
  </div>
</div>

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		🧭 Ejemplo
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			A través del Cátalogo Nacional diferentes organismos publican datos de alto valor (HVD) [📖 Fuente](https://datos.gob.es/es/catalogo/conjuntos-datos?is_hvd=true) 
		</p>
	</div>
</div>

> **Datos protegidos:** datos que obran en poder de organismos del sector público que estén protegidos por motivos de:
> a) confidencialidad comercial, incluidos los secretos comerciales, profesionales o empresariales
> b) confidencialidad estadística
> c) protección de los derechos de propiedad intelectual de terceros, o
> d) protección de los datos personales
>
> La Ley de Gobernanza de Datos (DGA) establece el marco para este tipo de datos. Norma complementaria de la Directiva de 2019, que rige el ámbito de los datos abiertos. [📖 Fuente](https://eur-lex.europa.eu/legal-content/ES/TXT/PDF/?uri=CELEX:32022R0868)


<div style="background:#fdf8ec; border-left:4px solid rgb(var(--lia-warning)); padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#fdf2e4; color:rgb(var(--lia-warning)); padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		⚠️ Aviso
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			Los datos protegidos son aquellos datos que las administraciones no pueden disponer como datos abiertos pues en ellos concurren derechos de terceros que dificultan su reutilización: datos de carácter personal, datos con derechos de propiedad intelectual, entre otros. 
		</p>
	</div>
</div>


<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#e4d7fb; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
	<p style="margin:0.25rem 0 0.5rem 0;">
	<ul style="list-style-type: disc; margin-left: 1.5em;">
		<li>[La aplicación del Reglamento UE sobre Gobernanza de Datos en las Administraciones Públicas](https://datos.gob.es/es/blog/la-aplicacion-del-reglamento-ue-sobre-gobernanza-de-datos-en-las-administraciones-publicas)</li>
		<li>[Infografía: Reglamento Europeo de Gobernanza de Datos](https://datos.gob.es/sites/default/files/blog/file/infografia-doble-reglamento-europeo-es_0.pdf)</li>
		<li>[La protección de datos personales en el borrador del Reglamento de Gobernanza de los Datos (Data Governance Act)](https://datos.gob.es/es/blog/la-proteccion-de-datos-personales-en-el-borrador-del-reglamento-de-gobernanza-de-los-datos-data)</li>
		<li>[Las salas seguras en España: ¿A qué tipo de datos pueden acceder los investigadores?](https://datos.gob.es/es/blog/las-salas-seguras-en-espana-que-tipo-de-datos-pueden-acceder-los-investigadores)</li>
	</ul>
	</p>
  </div>
</div>


*************************************************************************************************************>

### 2.2. Bloque II: conceptos relacionados con la publicación

- [📖 Fuente](https://administracionelectronica.gob.es/pae_Home/dam/jcr%3A86742046-a129-4c69-96de-9193f2a191c7/Guia_de_aplicacion_RD1495_Publicacion_oficial_2012.pdf)

> **Conjunto de datos:** datos relacionados, estructurados y organizados para poder ser tratados y obtener información.

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    🧭 Ejemplo
  </div>
    </p>
  </div>
</div>

> **Servicio de datos:** conjunto de operaciones que ofrecen acceso a uno o más conjuntos de datos o funciones de procesamiento. El acceso suele ser mediante API.

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    🧭 Ejemplo
  </div>
    </p>
  </div>
</div>

- <span class="res res-aviso">⚠️ Aviso</span> El servicio de datos es la fuente; la API es la puerta de acceso programática.

> **Distribución:** información en un formato concreto, accesible desde una URL específica. Un dataset puede tener múltiples distribuciones.

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    🧭 Ejemplo
  </div>
    </p>
  </div>
</div>

> **Metadatos:** datos que describen otros datos (título, descripción, licencia, fechas...). Facilitan recuperación y uso.

![Definición de metadatos](media/image_009.png)

> **Catálogo de datos abiertos:** repositorio electrónico donde se almacenan datos abiertos y sus metadatos. Puede agregarse en meta-catálogos.

![Catálogos y repositorios](media/image_010.png)

> **Espacio de datos:** ecosistema para compartir datos entre participantes con soberanía, confianza y seguridad (gobernanza + mecanismos técnicos).

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    🧭 Ejemplo
  </div>
    </p>
  </div>
</div>

### 2.3. Bloque III: conceptos relacionados con la reutilización

- [📖 Fuente](https://www.boe.es/buscar/act.php?id=BOE-A-2007-19814)

> **Reutilización de la información pública (RISP):** uso de documentos en poder del sector público por personas físicas o jurídicas, con fines comerciales o no comerciales.

- <span class="res res-saber">🔍 Saber más</span> https://datos.gob.es/es/blog/las-claves-de-la-ley-sobre-reutilizacion-de-la-informacion-del-sector-publico-en-espana

> **Calidad de datos:** idoneidad de los datos para múltiples propósitos y usuarios. Referencia: ISO/IEC 25012.

![Atributos de la calidad de los datos](media/image_011.png)

> **Gobierno abierto (Open Government):** doctrina orientada a transparencia, colaboración y participación.

![Gobierno abierto](media/image_012.png)

**Saber más**

- <span class="res res-saber">🔍 Saber más</span> Glosario ENI (RD 4/2010), Ley 37/2007, NTI-RISP, guías ENI, diccionario de Administración Electrónica.

**Caso de estudio**

- <span class="res res-caso">🧪 Caso de estudio</span> INE: empleo por ramas de actividad. Dataset, distribuciones (CSV/XLSX/JSON), metadatos y licencia abiertos.  
  https://datos.gob.es/es/catalogo/ea0010587-empleo-por-ramas-de-actividad-cntr2010-identificador-api-67201

![Ejemplo de distribuciones y metadatos](media/image_017.png)

**Ejercicio**

Consulta y empareja conceptos con el recurso [Principales parques y jardines municipales](https://datos.gob.es/es/catalogo/l01280796-principales-parques-y-jardines-municipales1):

{{|>}}
*************************************************************************************************************

**1) Los datos de parques municipales del Ayuntamiento en CSV**

- [( )] Dato
- [( )] Conjunto de datos
- [(X)] Distribución
- [( )] Licencia
- [( )] Metadatos
***
> ✅ Correcto.
***

**2) Colección descargable con listado de parques, ubicación y características en varios formatos**

- [( )] Dato
- [(X)] Conjunto de datos
- [( )] Distribución
- [( )] Licencia
- [( )] Metadatos
***
> ✅ Correcto.
***

**3) Ubicación de los Jardines Gregorio Ordóñez**

- [(X)] Dato
- [( )] Conjunto de datos
- [( )] Distribución
- [( )] Licencia
- [( )] Metadatos
***
> ✅ Correcto.
***

**4) Condiciones de uso, reutilización y redistribución**

- [( )] Dato
- [( )] Conjunto de datos
- [( )] Distribución
- [(X)] Licencia
- [( )] Metadatos
***
> ✅ Correcto.
***

**5) Fecha de última actualización, creación u otros atributos descriptivos**

- [( )] Dato
- [( )] Conjunto de datos
- [( )] Distribución
- [( )] Licencia
- [(X)] Metadatos
***
> ✅ Correcto.
***

*************************************************************************************************************>

<!-- id="principios" -->
## PRINCIPIOS DE APERTURA DE DATOS

Para garantizar que los datos abiertos sean fácilmente utilizables, reutilizables y redistribuibles, es necesario cumplir con principios reconocidos internacionalmente.

### 3.1. Principios Open Government Data (OGD)

En 2007 se definieron los **8 principios** OGD:

- **Completos**
- **Primarios**
- **Oportunos**
- **Accesibles**
- **Procesables**
- **No discriminatorios**
- **No propietarios**
- **De licencia libre**

![Principios Open Government Data](media/image_021.png)

### 3.2. Principios FAIR

Principios **FAIR** (Findable, Accessible, Interoperable, Reusable) con foco en acción por sistemas informáticos:

- **Encontrables:** URI persistentes, metadatos ricos, indexación.
- **Accesibles:** protocolos abiertos; autenticación si procede.
- **Interoperables:** lenguajes formales y referencias cualificadas.
- **Reutilizables:** descripciones detalladas, procedencia, normas sectoriales.

![Principios FAIR](media/image_022.jpg)

**Saber más**

- <span class="res res-saber">🔍 Saber más</span> Open Data Charter, Informe OCDE de calidad estadística (2011), comunidad GO FAIR.

**Ejercicio**

Relaciona definición con el principio:

{{|>}}
*************************************************************************************************************

**1) Disponibles para cualquiera, sin discriminación**

- [(X)] Accesibles
- [( )] Completos
- [( )] Procesables
- [( )] No propietarios
***
> Correcto.
***

**2) Publicar todo salvo restricciones legítimas**

- [( )] Accesibles
- [(X)] Completos
- [( )] Procesables
- [( )] No propietarios
***
> Correcto.
***

**3) Estructurados para procesamiento automatizado**

- [( )] Accesibles
- [( )] Completos
- [(X)] Procesables
- [( )] No propietarios
***
> Correcto.
***

**4) Formatos sin control exclusivo**

- [( )] Accesibles
- [( )] Completos
- [( )] Procesables
- [(X)] No propietarios
***
> Correcto.
***

*************************************************************************************************************>

<!-- id="beneficios" -->
## BENEFICIOS DE LA REUTILIZACIÓN DE DATOS ABIERTOS

La apertura de datos tiene potencial para generar **beneficios económicos, sociales y para la propia Administración**, y es materia prima clave para inteligencia artificial y espacios de datos.

### 4.1. Beneficios económicos

Los datos abiertos permiten optimizar procesos empresariales, resolver retos mediante análisis y crear nuevos productos o modelos de negocio (especialmente útiles para pymes y startups).

- <span class="res res-caso">🧪 Caso de estudio</span> **Meteogrid**: asesoría en incendios forestales con LIDAR PNOA, Inventario Forestal Nacional, Catastro.  
  Más info: datos.gob.es/es/empresas/meteogrid  
  ![](media/image_023.png)
- <span class="res res-caso">🧪 Caso de estudio</span> **Hispatec Agrointeligencia**: inteligencia de datos para el sector agro con Copernicus, precios agrícolas y Red Fitosanitaria.  
  Más info: datos.gob.es/es/empresas/hispatec  
  ![](media/image_024.jpg)
- <span class="res res-caso">🧪 Caso de estudio</span> **Idealista**: portal inmobiliario con datos de Catastro, INE y LIDAR PNOA.  
  Más info: datos.gob.es/es/empresas/idealista  
  ![Idealista](media/image_025.jpg)

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden;">
  <div style="background:#ede9fe; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      Informe ASEDIE (2025): beneficio neto de 146M€ en 2023 para empresas reutilizadoras.
    </p>
  </div>
</div>

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden;">
  <div style="background:#ede9fe; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      Impacto económico europeo (aplicaciones de emergencias, movilidad, energía, traducción automática).
    </p>
  </div>
</div>

### 4.2. Beneficios sociales

Los datos abiertos fomentan sociedades más informadas, participativas y equitativas; mejoran servicios públicos basados en evidencia.

- <span class="res res-caso">🧪 Caso de estudio</span> **Park4Dis**: mapea plazas accesibles para PMR con datos municipales y normativas.  
  Más info: datos.gob.es/es/aplicaciones/park4dis  
  ![Logo Park4Dis](media/image_027.jpg)
- <span class="res res-caso">🧪 Caso de estudio</span> **Civio**: transparencia y periodismo de datos (BOE, subvenciones, Copernicus).  
  Más info: datos.gob.es/es/empresas/civio  
  ![Civio](media/image_028.png)
- <span class="res res-caso">🧪 Caso de estudio</span> **Datadista**: periodismo de investigación con datos INE, BOE, Registro Mercantil.  
  Más info: datos.gob.es/es/empresas/datadista  
  ![](media/image_029.jpg)

### 4.3. Beneficios para la propia Administración

La reutilización mejora reputación institucional, impulsa innovación y genera ahorros.

- <span class="res res-caso">🧪 Caso de estudio</span> **Datahub energético de Castilla y León**: optimización energética y contratos; ahorros de 2M€/año desde 2015.  
  Fuente: https://energia.jcyl.es/web/es/ahorro-eficiencia-energetica/datahub-energetico-junta-castilla.html
- <span class="res res-caso">🧪 Caso de estudio</span> **Smart Agro – Recomendaciones de Riego (La Palma)**: uso eficiente de agua con datos meteorológicos y ETo.  
  Fuente: https://datos.gob.es/es/aplicaciones/smart-agro-recomendaciones-de-riego
- <span class="res res-caso">🧪 Caso de estudio</span> **Spain By Bike (IGN/CNIG)**: rutas ciclistas con geodatos y datos turísticos abiertos.  
  Fuente: https://datos.gob.es/es/aplicaciones/rutas-ciclistas-por-espana

- <span class="res res-aviso">⚠️ Aviso</span> Los datos abiertos son materia prima para la economía del dato y para los espacios europeos de datos sectoriales (salud, movilidad, turismo, agricultura, energía, finanzas, clima, administración pública...).

### Ejercicio (beneficios)

Indica si las siguientes afirmaciones son verdaderas o falsas:

{{|>}}
*************************************************************************************************************

**1) Pueden contribuir a que los Gobiernos sean más transparentes**

- [(X)] Verdadero
- [( )] Falso
***
> Transparencia y rendición de cuentas.
***

**2) Estimulan la innovación**

- [(X)] Verdadero
- [( )] Falso
***
> Nuevos productos y servicios basados en datos.
***

**3) Pueden ayudar a demostrar que los fondos públicos se emplean adecuadamente**

- [(X)] Verdadero
- [( )] Falso
***
> Facilitan evaluación y control social.
***

**4) Pueden generar nuevas oportunidades de negocio**

- [(X)] Verdadero
- [( )] Falso
***
> Empresas reutilizadoras crean valor añadido.
***

**5) Pueden ayudar a proteger nuestro planeta**

- [(X)] Verdadero
- [( )] Falso
***
> Datos ambientales abiertos permiten monitorizar y actuar.
***

*************************************************************************************************************>

<!-- id="cuestionario-final" -->
## CUESTIONARIO FINAL

Indica si cada afirmación es verdadera o falsa:

{{|>}}
*************************************************************************************************************

**1) Es conveniente que los datos abiertos tengan limitaciones de uso comercial con licencias específicas**

- [( )] Verdadero
- [(X)] Falso
***
> Las licencias abiertas deben permitir uso y reutilización, también comercial.
***

**2) Los datos sujetos a confidencialidad estadística deben publicarse como datos abiertos**

- [( )] Verdadero
- [(X)] Falso
***
> Datos protegidos no pueden abrirse sin salvaguardas.
***

**3) Los principios FAIR se crearon específicamente para datos gubernamentales**

- [( )] Verdadero
- [(X)] Falso
***
> Nacieron en el ámbito científico y se extendieron a otros dominios.
***

**4) Los datos relacionados con el medio ambiente están considerados de alto valor (HVD)**

- [(X)] Verdadero
- [( )] Falso
***
> Medio ambiente es una de las seis categorías HVD.
***

**5) Un mismo conjunto de datos puede tener múltiples distribuciones**

- [(X)] Verdadero
- [( )] Falso
***
> Puede publicarse en varios formatos o periodos.
***

**6) La publicación de metadatos es clave en la publicación de datos abiertos**

- [(X)] Verdadero
- [( )] Falso
***
> Sin metadatos no es posible localizar o reutilizar los datos.
***

**7) Publicar datos primarios implica máxima granularidad, evitando agregaciones**

- [(X)] Verdadero
- [( )] Falso
***
> Permite mayor reutilización y evita pérdidas de detalle.
***

**8) Cualquier restricción sobre el uso de datos abiertos incrementa su potencial de valor**

- [( )] Verdadero
- [(X)] Falso
***
> Las restricciones reducen la reutilización.
***

**9) Formato, estructura y legibilidad por máquina mejoran la usabilidad de los datos abiertos**

- [(X)] Verdadero
- [( )] Falso
***
> Procesables por máquina = mayor reutilización.
***

*************************************************************************************************************>

<!-- id="resumen" -->
## RESUMEN

- Las administraciones públicas impulsan **políticas de datos abiertos** para un modelo de relación administración–ciudadanía más transparente y participativo.
- Los datos abiertos deben cumplir **principios generales** (OGD, FAIR, licencias abiertas) para ser utilizables, reutilizables y redistribuibles.
- La apertura aporta **beneficios** a economía (innovación, nuevos negocios), sociedad (servicios basados en evidencia, periodismo de datos, sostenibilidad) y administraciones (eficiencia, reputación, ahorro).

![](media/image_030.jpg)

![](media/image_031.png)

Puedes identificar los espacios de **datos abiertos** gracias a este logo.

**¿QUIERES SABER MÁS SOBRE LA INICIATIVA APORTA?** Visita https://datos.gob.es/ — suscríbete al boletín o escribe a contacto@datos.gob.es.
