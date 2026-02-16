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

<div style="background:#ffffff; border:2px solid #154481; border-radius:12px; box-shadow:0 4px 12px rgba(21,68,129,0.15); margin:2rem 0; overflow:hidden;">

  <div style="background:linear-gradient(135deg, #072142 0%, #154481 100%); color:#ffffff; padding:1.5rem 2rem; text-align:center;">
    <h2 style="margin:0; font-size:1.6em; font-weight:700; font-family:'Montserrat', sans-serif;">Datos abiertos: conceptos básicos y beneficios</h2>
  </div>

  <table role="presentation" style="width:100%; border-collapse:collapse; table-layout:fixed; border-bottom:2px solid #154481;">
    <tr style="border-bottom:1px solid #e0e7ef;">
      <td style="width:80px; text-align:center; vertical-align:middle; background:#f8fafc; border-right:1px solid #e0e7ef; padding:1rem; font-size:1.8em;">📋</td>
      <td style="padding:1rem 1.25rem; vertical-align:middle; line-height:1.6;"><strong style="color:#154481;">Descripción:</strong> La unidad ofrece una visión general de qué son los datos abiertos, cómo se usan y qué beneficios aportan en términos de accesibilidad, reutilización, transparencia y valor social y económico.</td>
    </tr>
    <tr style="border-bottom:1px solid #e0e7ef;">
      <td style="width:80px; text-align:center; vertical-align:middle; background:#f8fafc; border-right:1px solid #e0e7ef; padding:1rem; font-size:1.8em;">👥</td>
      <td style="padding:1rem 1.25rem; vertical-align:middle; line-height:1.6;"><strong style="color:#154481;">Público objetivo:</strong> publicadores y <u>reutilizadores</u> de datos abiertos, así como cualquier persona interesada en esta materia.</td>
    </tr>
    <tr>
      <td style="width:80px; text-align:center; vertical-align:middle; background:#f8fafc; border-right:1px solid #e0e7ef; padding:1rem; font-size:1.8em;">🎓</td>
      <td style="padding:1rem 1.25rem; vertical-align:middle; line-height:1.6;"><strong style="color:#154481;">Conocimientos previos:</strong> no se precisan</td>
    </tr>
  </table>

  <div style="display:flex; flex-wrap:wrap; border-bottom:2px solid #154481;">
    <div style="flex:1; min-width:300px; border-right:2px solid #154481;">
      <div style="display:flex; border-bottom:1px solid #e0e7ef;">
        <div style="width:80px; display:flex; align-items:center; justify-content:center; background:#f8fafc; border-right:1px solid #e0e7ef; padding:0.75rem; flex-shrink:0;">
          <span style="font-size:1.5em;">🎯</span>
        </div>
        <div style="padding:0.75rem 1rem; flex:1;">
          <strong style="color:#154481; font-size:1.1em;">Objetivos</strong>
        </div>
      </div>
      <div style="padding:1rem 1.25rem;">
        <ul style="margin:0; padding-left:1.25rem; line-height:1.7;">
          <li>Establecer <strong>conceptos básicos</strong> relacionados con los datos abiertos tomando como referencia el marco legislativo vigente en España.</li>
          <li>Reconocer los <strong>principios generales</strong> a tener en cuenta para asegurar que los datos abiertos son fácilmente reutilizables.</li>
          <li>Descubrir los principales <strong>beneficios económicos y sociales</strong> que supone la apertura de datos públicos.</li>
          <li>Conocer los <strong>aspectos clave ligados al ecosistema de los datos</strong> de cara a asegurar la generación de los beneficios apuntados.</li>
        </ul>
      </div>
    </div>
    <div style="flex:1; min-width:300px;">
      <div style="display:flex; border-bottom:1px solid #e0e7ef;">
        <div style="width:80px; display:flex; align-items:center; justify-content:center; background:#f8fafc; border-right:1px solid #e0e7ef; padding:0.75rem; flex-shrink:0;">
          <span style="font-size:1.5em;">📑</span>
        </div>
        <div style="padding:0.75rem 1rem; flex:1;">
          <strong style="color:#154481; font-size:1.1em;">Contenidos</strong>
        </div>
      </div>
      <div style="padding:1rem 1.25rem;">
        <ol style="margin:0; padding-left:1.25rem; line-height:1.7;">
          <li>Introducción</li>
          <li>Conceptos clave
            <ul style="margin:0.25rem 0; padding-left:1.25rem;">
              <li>Bloque I: conceptos básicos</li>
              <li>Bloque II: conceptos relacionados con la publicación</li>
              <li>Bloque III: conceptos relacionados con la reutilización</li>
            </ul>
          </li>
          <li>Principios generales de los datos abiertos</li>
          <li>Beneficios de los datos abiertos
            <ul style="margin:0.25rem 0; padding-left:1.25rem;">
              <li>Beneficios económicos</li>
              <li>Beneficios sociales</li>
              <li>Beneficios para las Administraciones</li>
            </ul>
          </li>
        </ol>
      </div>
    </div>
  </div>
<table role="presentation" style="width:100%; border-collapse:collapse; table-layout:fixed;">
<tr style="border-bottom:1px solid #e0e7ef;">
<td style="width:80px; text-align:center; vertical-align:middle; background:#f8fafc; border-right:1px solid #e0e7ef; padding:1rem; font-size:1.8em;">💡</td>
<td style="padding:1rem 1.25rem; vertical-align:middle; line-height:1.6;"><strong style="color:#154481;">Guía de uso:</strong> en el <a href="https://liascript.github.io/course/?https://raw.githubusercontent.com/datosgobes/unidad-formativa-00/refs/heads/main/CURSO.md#tutorial" style="font-weight:600;">Tutorial del curso</a> encontrarás información sobre los recursos disponibles, la estructura global, etc.</td>
</tr>
<tr style="border-bottom:1px solid #e0e7ef;">
<td style="width:80px; text-align:center; vertical-align:middle; background:#f8fafc; border-right:1px solid #e0e7ef; padding:1rem; font-size:1.8em;">🏷️</td>
<td style="padding:1rem 1.25rem; vertical-align:middle; line-height:1.6;"><strong style="color:#154481;">Versión:</strong> v1.0.1</td>
</tr>
</table>
<div style="background:#f8fafc; border-top:2px solid #154481; padding:1.5rem; text-align:center;">
<div style="display:flex; justify-content:center; gap:1rem; flex-wrap:wrap; margin-bottom:0.75rem;">
<a href="https://liascript.github.io/course/?https://raw.githubusercontent.com/datosgobes/unidad-formativa-01/refs/heads/main/CURSO.md#3" class="pdf-download-btn" style="font-size:1.75em; padding:1rem 1.6rem; font-weight:800;">
▶️ Empezar curso
</a>
</div>
<div style="display:flex; justify-content:center; gap:0.75rem; flex-wrap:wrap; margin-bottom:0.5rem;border:none;">
<a href="https://github.com/datosgobes/unidad-formativa-01/releases/download/latest/documentation-unidad-formativa-01.pdf" target="_blank" rel="noopener" style="display:inline-block; background:#6b7280; color:#ffffff; font-size:0.9em; padding:0.5rem 1rem; border-radius:6px; text-decoration:none;" onmouseover="this.style.background='#4b5563';" onmouseout="this.style.background='#6b7280';">
📄 PDF
</a>
<a href="https://github.com/datosgobes/unidad-formativa-01/releases/download/latest/scorm-unidad-formativa-01.zip" target="_blank" rel="noopener" style="display:inline-block; background:#6b7280; color:#ffffff; font-size:0.9em; padding:0.5rem 1rem; border-radius:6px; text-decoration:none;" onmouseover="this.style.background='#4b5563';" onmouseout="this.style.background='#6b7280';">
📦 SCORM
</a>
<a href="https://github.com/datosgobes/unidad-formativa-01/releases/download/latest/ims-unidad-formativa-01.zip" target="_blank" rel="noopener" style="display:inline-block; background:#6b7280; color:#ffffff; font-size:0.9em; padding:0.5rem 1rem; border-radius:6px; text-decoration:none;" onmouseover="this.style.background='#4b5563';" onmouseout="this.style.background='#6b7280';">
📚 IMS
</a>
</div>
<div style="font-size:0.85em; color:#666;">Empezar el curso o descargar documentación</div>
</div>
  
</div>

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

*************************************************************************************************************

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

*************************************************************************************************************

<!-- id="conceptos-clave" -->
## CONCEPTOS CLAVE

{{|>}}
*************************************************************************************************************

Como punto de partida se definen los conceptos básicos que se manejan al hablar de datos en general y de datos abiertos en particular. Se toma como referencia el marco legislativo vigente en España.

*************************************************************************************************************

### Bloque I: Conceptos básicos

{{|>}}
*************************************************************************************************************

**Dato:** toda representación digital de actos, hechos o información, así como su recopilación, incluso como grabación sonora, visual o audiovisual. [📖 Fuente](https://www.boe.es/buscar/act.php?id=BOE-A-2010-1331)

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

**Datos abiertos:** cualquiera es libre de utilizar, reutilizar y redistribuir, con el único límite, en su caso, del requisito de atribución de su fuente o el reconocimiento de su autoría. [📖 Fuente](https://www.boe.es/buscar/act.php?id=BOE-A-2007-19814)

Esta definición identifica tres características esenciales:

- **Uso libre**: pueden emplearse para cualquier finalidad, incluida la comercial.
- **Reutilización**: posibilidad de transformar, combinar o enriquecer los datos.
- **Redistribución**: posibilidad de compartir datos originales o derivados.

<center>![Definición de datos abiertos](media/image_004-005.png "Definición de datos abiertos. Fuente: [datos.gob.es](https://datos.gob.es/)")</center>

**Lo que NO son datos abiertos**

- Datos publicados sin licencia clara (genera inseguridad jurídica).
- Datos accesibles solo previo registro o pago.
- Datos con restricciones de privacidad o seguridad (ej: datos personales).

<div style="background:#fdf8ec; border-left:4px solid #ff9800; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#fdf2e4; color:#ff9800; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
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

**Licencia abierta:** acuerdo legal que otorga permisos de libre uso, modificación y distribución de un recurso, exigiendo únicamente **el reconocimiento del autor** y la continuidad de la propia licencia abierta. Las licencias Creative Commons (CC) es el ejemplo más popular para contenidos y datos, y en concreto, las mostradas en este esquema, las más habituales en el contexto de los datos abiertos.

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

**Datos abiertos gubernamentales o del sector público:** son datos generados, creados, recolectados, procesados, preservados, mantenidos, diseminados o financiados por un gobierno o una institución pública, y que consideran los requerimientos y restricciones legales que permiten su reutilización -licencia abierta-. Son datos con un gran potencial. [📖 Fuente](https://ideas.repec.org/p/oec/govaaa/22-en.html).

**Las administraciones públicas son los principales proveedores de datos abiertos**. Por esta razón, cuando hablamos de datos abiertos, generalmente se hace referencia a datos oficinales gubernamentales disponibles como abiertos.


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

**Datos abiertos de alto valor (HVD** por sus siglas en inglés): datos cuya reutilización está asociada a considerables **beneficios para la sociedad, el medio ambiente y la economía**, en particular debido a su idoneidad para la creación de servicios de valor añadido, aplicaciones y puestos de trabajo nuevos, dignos y de calidad, y del número de beneficiarios potenciales de los servicios de valor añadido y aplicaciones basados en tales conjuntos de datos. [📖 Fuente](https://www.boe.es/buscar/act.php?id=BOE-A-2007-19814#:~:text=Subir-,%5BBloque%207%3A%20%23a3%2D3%5D,-Art%C3%ADculo%203.ter)

En enero de 2023, la Comisión Europea define seis categorías para diferenciar los datos de alto valor [📖 Fuente](https://datos.gob.es/es/catalogo/conjuntos-datos?is_hvd=true)


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

**Datos protegidos:** datos que obran en poder de organismos del sector público que estén protegidos por motivos de:

<ol type="a" style="list-style-type: lower-alpha; margin:0.25rem 0 0.5rem 0; padding-left: 1.5em;">
  <li>confidencialidad comercial, incluidos los secretos comerciales, profesionales o empresariales</li>
  <li>confidencialidad estadística</li>
  <li>protección de los derechos de propiedad intelectual de terceros, o</li>
  <li>protección de los datos personales</li>
</ol>

La Ley de Gobernanza de Datos (DGA) establece el marco para este tipo de datos. Norma complementaria de la Directiva de 2019, que rige el ámbito de los datos abiertos. [📖 Fuente](https://eur-lex.europa.eu/legal-content/ES/TXT/PDF/?uri=CELEX:32022R0868)


<div style="background:#fdf8ec; border-left:4px solid #ff9800; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#fdf2e4; color:#ff9800; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
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


*************************************************************************************************************

### Bloque II: conceptos relacionados con la publicación

{{|>}}
*************************************************************************************************************


**Conjunto de datos**: datos relacionados, convenientemente estructurados y organizados, de forma que puedan ser tratados (procesados) apropiadamente para obtener información. [📖 Fuente](https://administracionelectronica.gob.es/pae_Home/dam/jcr%3A86742046-a129-4c69-96de-9193f2a191c7/Guia_de_aplicacion_RD1495_Publicacion_oficial_2012.pdf)

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		🧭 Ejemplo
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			La Dirección General de Tráfico (DGT) publica un conjunto de datos en formato XLS con las series históricas de matriculaciones desde 1998 a 2024. [📖 Fuente](https://datos.gob.es/es/catalogo/e00130502-matriculaciones-series-historicas-2024) 
		</p>
	</div>
</div>

**Servicio de datos**: conjunto de operaciones que ofrecen acceso a uno o más conjuntos de datos o funciones de procesamiento permitiendo obtener datos en distintos formatos.
A los servicios de datos se accede principalmente mediante API (Interfaz de Programación de Aplicaciones), que actúa como un puente para acceder a los datos de un sistema sin necesidad de conocer su implementación interna.

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		🧭 Ejemplo
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			La Agencia Estatal de Meteorología (AEMET) publica una API de datos meteorológicos que permite que una aplicación consulte la temperatura actual mediante una llamada programada. [📖 Fuente](https://opendata.aemet.es/centrodedescargas/inicio) 
		</p>
	</div>
</div>

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#e4d7fb; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      [APIs para el acceso a datos abiertos](https://datos.gob.es/es/blog/apis-para-el-acceso-datos-abiertos)
    </p>
  </div>
</div>

<div style="background:#fdf8ec; border-left:4px solid #ff9800; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#fdf2e4; color:#ff9800; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		⚠️ Aviso
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			Es importante no confundir entre servicio de datos y API. El **servicio de datos** es el “repositorio” o fuente donde están los datos. La **API** es la “puerta de acceso programática” que permite interactuar con esos datos de forma dinámica y automatizada.
		</p>
	</div>
</div>

**Distribución:** información (datos) en un formato concreto, accesible desde un URL específica. Un conjunto de datos puede disponer de una o múltiples distribuciones. [📖 Fuente](https://www.boe.es/buscar/doc.php?id=BOE-A-2013-2380) 

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		🧭 Ejemplo
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			El Instituto Nacional de Estadística publica datos sobre residuos alimentarios por actividad económica. Los datos se sirven como [servicio API](https://datos.gob.es/es/catalogo/ea0010587-distribucion-porcentual-del-residuo-alimentario-por-actividad-economica-cnae-2009-identificador-api-67542) y como [ficheros con diferentes formatos](https://datos.gob.es/es/catalogo/ea0010587-distribucion-porcentual-del-residuo-alimentario-por-actividad-economica-cnae-2009-identificador-api-67542), lo que referimos como diferentes distribuciones: CSV, XLSX, JSON, PC-AXIS, entre otros.
      <br>
      Además del servicio API, que permite acceder mediante consultas dinámicas a los datos mencionados, el INE ofrece datasets en CSV y JSON, entre otros formatos.
		</p>
	</div>
</div>

<div style="background:#fffbeb; border-left:4px solid #fbbf24; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#fef3c7; color:#d97706; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    🔍 Saber más
  </div>
  <div style="padding:0 1rem 0 1rem;">
	  <p style="margin:0.25rem 0 0.5rem 0;">
      Cada formato tiene diferentes peculiaridades. Los más comunes son los siguientes:
	    <ul style="list-style-type: disc; margin-left: 1.5em;">
      <li>CSV: simple, universal y legible por máquina</li>
      <li>XLSX: familiar para usuarios de Excel</li>
      <li>JSON/JSON-LD: estructurado, ideal para su uso por API</li>
      <li>PC-AXIS: habitual para datos estadísticos </li>
    </ul>
    </p>
  </div>
</div>

<div style="background:#fdf8ec; border-left:4px solid #ff9800; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#fdf2e4; color:#ff9800; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ⚠️ Aviso
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      El concepto de distribución en ocasiones se refiere a la forma de ofrecer los datos para su descarga o uso. Es decir, se pueden diferenciar distribuciones no solo por formato del fichero sino también en base a otros criterios como puede ser el periodo temporal al que se refiere la información. De esta forma, cada fichero de datos correspondiente a un periodo es una distribución, siempre que ese fichero se publique como una unidad de acceso independiente. Ver ejemplo a continuación. 
    </p>
  </div>
</div>

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    🧭 Ejemplo
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      <strong>Población residente por municipio</strong>, que representa una serie temporal con periodicidad anual
    </p>
    <p style="margin:0.25rem 0 0.5rem 0;">
      <strong>Ficheros publicados:</strong>
    </p>
    <ul style="list-style-type: disc; margin-left: 1.5em; margin-bottom: 0.5rem;">
      <li>poblacion_2021.csv</li>
      <li>poblacion_2022.csv</li>
      <li>poblacion_2021.json</li>
      <li>poblacion_2022.json</li>
    </ul>
    <p style="margin:0.25rem 0 0.5rem 0;">
      <strong>Modelado correcto:</strong>
    </p>
    <ul style="list-style-type: disc; margin-left: 1.5em; margin-bottom: 0.5rem;">
      <li>1 dataset: describe la serie temporal completa en diferentes formatos</li>
      <li>4 distribuciones: cada una corresponde a un año concreto o a un formato</li>
    </ul>
  </div>
</div>

**Metadatos:** datos que definen y describen otros datos. Es información estructurada que describe, explica o localiza un conjunto de datos o un servicio de datos, haciendo más sencilla la recuperación de información, utilización o administración de dicho conjunto de datos [📖 Fuente](https://www.boe.es/buscar/act.php?id=BOE-A-2010-1331#:~:text=Subir-,%5BBloque%2056%3A%20%23an%5D,-ANEXO) 

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		🧭 Ejemplo
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			El Instituto Nacional de Estadística publica los consumos energéticos anualmente. El conjunto de datos cuenta, entre otros, con los siguientes metadatos:
      <br>
			<strong>Título:</strong> Consumos energéticos por año, comunidades y ciudades autónomas y producto consumido
			<br><strong>Descripción:</strong> tabla de INEbase Consumos energéticos por año, comunidades y ciudades autónomas y producto consumido. Encuesta de Consumos Energéticos
			<br><strong>Frecuencia de actualización:</strong> Anual
			<br><strong>Licencia:</strong> https://www.ine.es/aviso_legal
			<br><strong>Fecha de última actualización:</strong> 26/05/2025
			<br><strong>Otros recursos:</strong> https://www.ine.es/dyngs/IOE/es/operacion.htm?numinv=30070
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
        <li><a href="https://datos.gob.es/es/blog/importancia-de-la-catalogacion-de-datos">Importancia de la Catalogación de Datos</a></li>
        <li><a href="https://datos.gob.es/es/blog/metadatos-para-incrementar-la-reutilizacion-de-datos-abiertos-en-aprendizaje-automatico">Metadatos para incrementar la reutilización de datos abiertos en aprendizaje automático</a></li>
      </ul>
    </p>
  </div>
</div>


<center>![Definición de metadatos](media/image_007-001.png "Definición de metadatos. Fuente: [datos.gob.es](https://datos.gob.es/)")</center>

**Catálogo de datos abiertos:** repositorio electrónico donde se almacenan y administran datos abiertos y sus metadatos.

Estos catálogos generalmente se presentan en forma de páginas web que almacenan y administran tanto los **datos**como algunos **metadatos** que los describen. Podemos encontrar [catálogos con datos abiertos del sector público en todos los niveles administrativos](https://datos.gob.es/es/iniciativas), ya sea nacional, regional o local.

Dado que el número de portales y repositorios continúa creciendo día a día, para facilitarla localización de datos, estos catálogos se consolidan a través de **meta-catálogos y agregadores**, que ofrecen una visión consolidada y estable de los distintos conjuntos y servicios de datos a través de un único punto de acceso común. Es el caso del [Catálogo nacional,](https://datos.gob.es/es/catalogo/conjuntos-datos) albergado en el portal de datos abiertos nacional (datos.gob.es) o del [Catálogo del portal europeo de datos](https://data.europa.eu/data/combined?locale=es), o de repositorios temáticos como los referidos en la imagen siguiente.

<center>![Repositorios temáticos](media/image_008-002.jpg "Repositorios temáticos. Fuente: [datos.gob.es](https://datos.gob.es/)")</center>

<div style="background:#fdf8ec; border-left:4px solid #ff9800; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#fdf2e4; color:#ff9800; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		⚠️ Aviso
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			A menudo el término <strong>Catálogo de datos abiertos</strong> se utiliza como sinónimo de <strong>Portal de datos abiertos</strong>, si bien son términos diferentes. El portal de datos abiertos es el sitio web que aloja un Catálogo de datos pero que también incluye funcionalidades y contenidos complementarios.
		</p>
	</div>
</div>

**Espacio de datos:** es un ecosistema donde materializar la compartición voluntaria de los datos de sus participantes dentro de un entorno de soberanía, confianza y seguridad, establecido mediante mecanismos integrados de gobernanza y técnicos, habilitadores de la generación de valor. [📖 Fuente](https://gaiax-spain.com/espacios-de-datos/)

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		🧭 Ejemplo
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			El Ministerio de Sanidad de España pone en marcha en enero de 2026 el <strong>Espacio nacional de datos de salud</strong>. Se trata de una red de plataformas de organismos públicos y privados, para interactuar e intercambiar datos. Este entorno busca facilitar la personalización de la atención del paciente o impulsar la investigación médica mediante un uso responsable, seguro y útil de la inteligencia artificial.
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
        <li><a href="https://datos.gob.es/es/blog/por-que-espacios-de-datos">¿Por qué espacios de datos?</a></li>
        <li><a href="https://datos.gob.es/es/blog/cuales-son-los-principales-elementos-de-un-espacio-de-datos">¿Cuáles son los principales elementos de un espacio de datos?</a></li>
        <li><a href="https://datos.gob.es/es/blog/modelo-de-desarrollo-de-casos-de-uso-para-espacios-de-datos">Modelo de desarrollo de casos de uso para espacios de datos</a></li>
        <li><a href="https://datos.gob.es/es/conocimiento/caracteristicas-para-la-creacion-de-espacios-de-datos">Características para la creación de espacios de datos</a></li>
      </ul>
    </p>
  </div>
</div>


*************************************************************************************************************


### Bloque III: conceptos relacionados con la reutilización

{{|>}}
*************************************************************************************************************

**Reutilización de la información pública (RISP):** uso de documentos que obran en poder de las Administraciones y organismos del sector público, por personas físicas o jurídicas, con fines comerciales o no comerciales [📖 Fuente](https://www.boe.es/buscar/act.php?id=BOE-A-2007-19814#:~:text=Subir-,%5BBloque%2030%3A%20%23an%5D,-Anexo).

La RISP en España se rige por la [Ley 37/2007](https://www.boe.es/buscar/act.php?id=BOE-A-2007-19814) sobre la reutilización de la información del sector público en aplicación de la [Directiva Europea 2019/1024.](https://eur-lex.europa.eu/legal-content/ES/ALL/?uri=CELEX%3A32019L1024)

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#e4d7fb; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      <ul style="list-style-type: disc; margin-left: 1.5em;">
        <li><a href="https://datos.gob.es/es/blog/las-claves-de-la-ley-sobre-reutilizacion-de-la-informacion-del-sector-publico-en-espana">Las claves de la Ley sobre reutilización de la información del sector público en España</a></li>
      </ul>
    </p>
  </div>
</div>

**Calidad de datos:** se entiende como la idoneidad de los datos para servir para múltiples propósitos y para diferentes tipos de usuarios [📖 Fuente](https://datos.gob.es/sites/default/files/documentacion/files/guia_calidad_de_datos_abiertos_1_0.pdf).

[La norma ISO/IEC 25012](https://iso25000.com/index.php/normas-iso-25000/iso-25012) establece las características que deben cumplir los datos para considerarse de calidad, las cuales se recogen en la siguiente imagen.

<center>![Atributos de la calidad de los datos](media/image_009.png "Atributos de la calidad de los datos. Fuente: [datos.gob.es](https://datos.gob.es/)")</center>

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#e4d7fb; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      <ul style="list-style-type: disc; margin-left: 1.5em;">
        <li><a href="https://datos.gob.es/es/conocimiento/guia-practica-para-la-mejora-de-la-calidad-de-datos-abiertos">Guía práctica para la mejora de la calidad de datos abiertos</a></li>
      </ul>
    </p>
  </div>
</div>

**Gobierno abierto (*open Government*):** Es una doctrina que tiene como objetivo que la ciudadanía colabore en la creación y mejora de servicios públicos y en el robustecimiento de la transparencia y la rendición de cuentas [📖 Fuente](https://es.wikipedia.org/wiki/Gobierno_abierto).

Se sustenta en tres pilares básicos:

* **Transparencia:** publicación de datos como abiertos para asegurar el seguimiento de políticas públicas
* **Colaboración:** derribo de silos y estructuras piramidales con el fin de trabajar horizontalmente y favorecer la organización de las sociedades.
* **Participación:** co-diseño de políticas públicas, deliberación con ciudadanos y consulta ciudadana.

<center>![Definición de gobierno abierto](media/image_010.png "Definición de gobierno abierto. Fuente: [datos.gob.es](https://datos.gob.es/)")</center>

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#e4d7fb; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      <ul style="list-style-type: disc; margin-left: 1.5em;">
        <li><a href="https://datos.gob.es/es/noticias/el-v-plan-de-gobierno-abierto-incorpora-medidas-concretas-para-impulsar-los-datos-abiertos">El V Plan de Gobierno Abierto incorpora medidas concretas para impulsar los datos abiertos</a></li>
      </ul>
    </p>
  </div>
</div>

<div style="background:#fffbeb; border-left:4px solid #fbbf24; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#fef3c7; color:#d97706; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    🔍 Saber más
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      Se pueden encontrar listados de definiciones para ampliar los conceptos ligados a datos abiertos en los siguientes documentos oficiales:
      <br><br>
      <ol style="list-style-type: disc; margin-left: 1.5em;">
        <li>Glosario de términos del <a href="https://www.boe.es/buscar/act.php?id=BOE-A-2010-1331#:~:text=Subir-,%5BBloque%2056%3A%20%23an%5D,-ANEXO">Real Decreto 4/2010, de 8 de enero, por el que se regula el Esquema Nacional de Interoperabilidad en el ámbito de la Administración Electrónica</a>.</li>
        <li>Anexo - Definiciones de la <a href="https://www.boe.es/buscar/act.php?id=BOE-A-2007-19814#:~:text=Subir-,%5BBloque%2030%3A%20%23an%5D,-Anexo">Ley 37/2007, de 16 de noviembre, sobre reutilización de la información del sector público</a></li>
        <li>Anexo I - Glosario de terminología de la <a href="https://www.boe.es/buscar/doc.php?id=BOE-A-2013-2380">Norma Técnica de Interoperabilidad de reutilización de recursos de información (NTI-RISP)</a></li>
        <li>Capítulo 9 - Definiciones y Acrónimos de la <a href="https://administracionelectronica.gob.es/pae_Home/dam/jcr%3A86742046-a129-4c69-96de-9193f2a191c7/Guia_de_aplicacion_RD1495_Publicacion_oficial_2012.pdf">Guía de aplicación de la Norma Técnica de Interoperabilidad de reutilización de recursos de información</a>. Incluye un capítulo 9 de Definiciones y Acrónimos.</li>
        <li>Anexo V - Definiciones y acrónimos de la <a href="https://datos.gob.es/elearning/Unidades_Didacticas/Unidad_1/contenidos/descargas/04-ref.pdf">Guía de Aplicación del Real Decreto 1495/2011 por el que se desarrolla la Ley 37/2007</a>.</li>
        <li><a href="https://www.esmartcity.es/2025/10/17/diccionario-terminos-administracion-electronica-actualiza-11-edicion">Diccionario de conceptos y términos de la Administración Electrónica (edición 11ª)</a></li>
      </ol>
    </p>
  </div>
</div>

<div style="background:#fee2e2; border-left:4px solid #dc2626; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#fecaca; color:#dc2626; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    🧪 Caso de estudio
  </div>
  <div style="padding:0 1rem 0 1rem;">
      <p style="margin:0.25rem 0 0.5rem 0;">
      En la siguiente imagen se refieren los principales conceptos descritos anteriormente. Se aplican a una colección de datos publicado por el INE y referenciado en el Catálogo de datos abiertos nacional albergado en datos.gob.es en la siguiente url:
      <br><br>
      https://datos.gob.es/es/catalogo/ea0010587-empleo-por-ramas-de-actividad-cntr2010-identificador-api-67201
      <br><br>
      <strong>Datos</strong> sobre la evolución del empleo por ramas de actividad
      <br><br>
      Si descargamos el fichero <a href="https://www.ine.es/jaxiT3/Tabla.htm?t=67201">aquí</a> obtenemos un fichero xls que contiene los siguientes datos:
      <br><br>
      <center><img src="media/image_011.png"></center>
      <br><br>
      <strong>Datos abiertos</strong> dado que se publican asociados a una licencia abierta
      <br><br>
      <center><img src="media/image_012.png"></center>
      <br>
      [📖 Fuente](https://www.ine.es/dyngs/AYU/index.htm?cid=125)
      <br><br>
      <strong>Datos abiertos de alto valor</strong>. Se trata de datos estadísticos, esto es, pertenecen a una categoría de las fijadas por la Comisión Europea como de alto valor. En consecuencia, aparecen marcados como tales en el Catálogo nacional.
      <br><br>
      <center><img src="media/image_013.png"></center>
      <br><br>
      <strong>Conjunto de datos</strong>
      <br><br>
      Los datos que publica el INE con los datos sobre evolución de empleo, junto con sus correspondientes metadatos, constituye un conjunto de datos.
      <br><br>
      <center><img src="media/image_014.png"></center>
      <br><br>
      <strong>Distribuciones</strong>
      <br><br>
      La colección de ficheros en diferentes formatos: CSV, XLSX, JSON, etc. se corresponde con las distribuciones.
      <br><br>
      <center><img src="media/image_015.png"></center>
      <br><br>
      <strong>Metadatos</strong>
      <br><br>
      Los atributos que definen y describen los metadatos que facilitarán su comprensión y su localización a través de buscadores.
      <br><br>
      <center><img src="media/image_016.png"></center>
    </p>
  </div>
</div>

*************************************************************************************************************

### Ejercicio

{{|>}}
*************************************************************************************************************

<div style="background:#ffffff; border:2px solid #154481; border-radius:12px; box-shadow:0 2px 8px rgba(21,68,129,0.15); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #072142 0%, #154481 100%); color:#ffffff; padding:1rem 1.5rem; display:flex; align-items:center; gap:0.75rem;">
    <div style="font-size:1.5em;">✏️</div>
    <h4 style="margin:0; font-size:1.3em; font-weight:600; font-family:'Montserrat', sans-serif;">Ejercicio</h4>
  </div>
  <div style="padding:1.25rem 1.5rem; background:#f8fafc;">
    <p style="margin:0; font-size:1em; color:#333; line-height:1.6;">
      Consulta el enlace a continuación y empareja los conceptos de la zona inferior con los ejemplos de la columna izquierda: <a href="https://datos.gob.es/es/catalogo/l01280796-principales-parques-y-jardines-municipales1">Principales parques y jardines municipales</a>
      <br><br>
      <em>Publicador: Ayuntamiento de Madrid</em>
    </p>
  </div>
</div>

- [[Dato] [Conjunto de datos] [Distribución] [Licencia] [Metadatos]]
- [  ( )        ( )                 (X)          ( )         ( )    ]  **1)** Los datos de parques municipales del Ayuntamiento en CSV
- [  ( )        (X)                 ( )          ( )         ( )    ]  **2)** Colección descargable con listado de parques, ubicación y características en varios formatos
- [  (X)        ( )                 ( )          ( )         ( )    ]  **3)** Ubicación de los Jardines Gregorio Ordóñez
- [  ( )        ( )                 ( )          (X)         ( )    ]  **4)** Condiciones de uso, reutilización y redistribución
- [  ( )        ( )                 ( )          ( )         (X)    ]  **5)** Fecha de última actualización, creación u otros atributos descriptivos
***
<div style="background:#d1fae5; border-left:4px solid #10b981; padding:0.5rem 1rem; border-radius:6px; margin:0.5rem 0;">
  <div style="color:#065f46; font-weight:600; font-size:1.1em;">✅ ¡Excelente!</div>
  <div style="color:#047857; font-size:0.9em; margin-top:0.25rem;">Has comprendido correctamente los conceptos:</div>
  <ul style="color:#047857; font-size:0.9em; margin:0.5rem 0 0.5rem 1.5rem;">
    <li><strong>Dato:</strong> unidad básica de información (ej. ubicación de un jardín)</li>
    <li><strong>Conjunto de datos:</strong> colección de distribuciones sobre una misma temática</li>
    <li><strong>Distribución:</strong> datos en un formato específico (CSV, JSON, XML, etc.)</li>
    <li><strong>Licencia:</strong> términos legales de uso y reutilización</li>
    <li><strong>Metadatos:</strong> información descriptiva (fecha, autor, formato, etc.)</li>
  </ul>
</div>
***

*************************************************************************************************************

## PRINCIPIOS DE APERTURA DE DATOS

{{|>}}
*************************************************************************************************************

Para garantizar que los datos abiertos sean fácilmente utilizables, reutilizables y redistribuibles, es necesario cumplir con una serie de principios reconocidos internacionalmente. Estos principios constituyen el marco de referencia que orienta a las organizaciones en la publicación de datos abiertos.

Aunque en la literatura se identifican diversos enfoques, existen dos marcos de referencia considerados fundamentales, los cuales se presentan a continuación.

*************************************************************************************************************

### Principios *Open Government Data* (OGD)

{{|>}}
*************************************************************************************************************

En 2007, [una treintena de defensores del gobierno abierto](https://public.resource.org/open_government_meeting.html) se reunió en California (EE.UU.) para elaborar un documento que recogiera los principios [Open Government Data. Así nacieron los](https://opengovdata.org/) ocho **principios** de los datos abiertos gubernamentales, que son los siguientes:

* **Completos:** deben ofrecerse todos los datos disponibles, siempre que no estén sujetos a condiciones de privacidad o seguridad y que su apertura no suponga un riesgo de identificación o individualización de una persona física o de seguridad nacional.
* **Primarios:** los datos ofrecidos deben tener el más alto nivel de granularidad, evitando agregaciones o modificaciones.
* **Oportunos:** los datos tienen que estar disponibles tan rápido como sea necesario para preservar su valor.
* **Accesibles:** los datos deben estar a disposición de la más amplia gama de usuarios y de propósitos.
* **Procesables:** los datos deben estar razonablemente estructurados para permitir el procesamiento automatizado.
* **No discriminatorio:** los datos deben estar disponibles para cualquier persona y bajo las mismas condiciones.
* **No propietario:** los datos deben ofrecerse en un formato sobre el cual ninguna entidad tenga un control exclusivo.
* **De licencia libre:** los datos no deben estar sujetos a ninguna regulación sobre derechos de autor, patentes, marcas registradas o secretos comerciales. Sí se pueden permitir restricciones razonables de privacidad, seguridad y privilegios.

<div style="background:#ebf8ed; border-left:4px solid #3fb950; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
	<div style="background:#d8f1dc; color:#3fb950; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
		🧭 Ejemplo
	</div>
	<div style="padding:0 1rem 0 1rem;">
		<p style="margin:0.25rem 0 0.5rem 0;">
			En el siguiente esquema se presenta un ejemplo de cómo interpretar los principios básicos referidos, aplicados a <strong>datos sobre accidentes de tráfico</strong>:
		</p>
		<center><img src="media/image_019.jpg" alt="Principios Open Government Data" title="Principios Open Government Data. Fuente: datos.gob.es"></center>
	</div>
</div>

*************************************************************************************************************

### Principios *FAIR*

{{|>}}
*************************************************************************************************************

Otro enfoque distinto, aunque en línea con las condiciones que deben cumplir los datos para que resulten fácilmente utilizables, reutilizables y redistribuibles son los llamados Principios FAIR - **F**indable (Encontrables), **A**ccessible (Accesibles), **I**nteroperable (Interoperables) y **R**eusable (Reutilizables), **inicialmente aplicables al ámbito de la investigación, pero poco a poco extendidos a otros ámbitos**. Se presentan como un conjunto de directrices precisas y medibles que deben seguirse para la publicación de datos con la mayor calidad posible.

Estos principios hacen **hincapié en la capacidad de acción de los sistemas informáticos para encontrar, acceder, interoperar y reutilizar los datos con la mínima intervención humana. Esto resulta esencial** ya que los seres humanos dependen cada vez más del apoyo informático para tratar los datos como resultado del aumento del volumen, la complejidad y la velocidad de creación de los datos.

Los datos abiertos deben atender a principios FAIR, lo que se traduce en:

* **Datos encontrables (*Findable)*:** los datos y metadatos pueden ser localizados por el usuario de manera sencilla después de su publicación, mediante herramientas de búsqueda. Para ello es necesario:
  * Asignar un identificador único y persistente (URI).
  * Describir los datos con metadatos de manera prolija.
  * Indexar los datos y metadatos en el recurso de búsqueda.
  * En los metadatos, especificar el identificador de los datos que se describen.
* **Accesibles (*Accessible*):** los datos y metadatos deben estar disponibles sin barreras para todos los usuarios. Los datos y metadatos son recuperables por su identificador utilizando protocolos de comunicación estandarizados.
  * El protocolo es abierto, gratuito y de aplicación universal.
  * El protocolo permite un procedimiento de autenticación y autorización cuando sea necesario.
* **Interoperables (*Interoperable*):** los datos deben poder integrarse con otros datos. Además, los datos deben poder interoperar con aplicaciones o flujos de trabajo para su análisis, almacenamiento y procesamiento.
  * Los datos y metadatos deben utilizar un lenguaje formal, accesible, compartido y ampliamente aplicable.
  * Los datos y metadatos deben incluir referencias cualificadas a otros datos o metadatos.
* **Reutilizables (*Reusable*):** los datos y metadatos deben estar bien descritos para que puedan ser replicados y/o combinados en diferentes entornos.
  * Los datos y metadatos deben estar bien descritos con una pluralidad de atributos precisos y relevantes.
  * Los datos y metadatos deben estar asociados a una procedencia detallada.
  * Los datos y metadatos deben cumplir con las normas de la comunidad pertinentes para el sector.

<center>![Calidad del dato | datos.gob.es](media/image_020.jpg "Principios FAIR. Fuente: [datos.gob.es](https://datos.gob.es/)")</center>

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#e4d7fb; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      <ul style="list-style-type: disc; margin-left: 1.5em;">
        <li><a href="https://datos.gob.es/es/blog/principios-fair-el-secreto-de-los-magos-de-los-datos">Principios FAIR: el secreto de los magos de los datos</a></li>
        <li><a href="https://www.nature.com/articles/sdata201618">The FAIR Guiding Principles for scientific data management and stewardship</a></li>
        <li><a href="https://www.go-fair.org/">Comunidad GO FAIR</a></li>
      </ul>
    </p>
  </div>
</div>

<div style="background:#fffbeb; border-left:4px solid #fbbf24; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#fef3c7; color:#d97706; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    🔍 Saber más
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      Además de los dos marcos de referencia mencionados, existen otros que también son relevantes. Cabe mencionar los siguientes:
      <br><br>
      <ol style="list-style-type: decimal; margin-left: 1.5em;">
        <li>Los principios definidos por la <a href="https://opendatacharter.org/wp-content/uploads/2025/09/Carta_Internacional_de_Datos_Abiertos2015.pdf">Carta internacional de los Datos Abiertos</a> (Open Data Charter) que establecen que los datos deben ser:</li>
        <li>Abiertos por defecto.</li>
        <li>Oportunos y exhaustivos.</li>
        <li>Accesibles y utilizables.</li>
        <li>Comparables e interoperables.</li>
        <li>Para mejorar la gobernanza y la participación ciudadana.</li>
        <li>Para el desarrollo incluyente y la innovación.</li>
        <li>Las siete dimensiones relativas a la calidad, incluidas en el informe <strong>Marco de calidad y directrices para las actividades estadísticas de la OCDE</strong> publicado en 2011: pertinencia, precisión, credibilidad, actualidad, accesibilidad, interpretabilidad y coherencia. Este documento, además, establece que la calidad está ampliamente vinculada con las perspectivas, necesidades y prioridades de los reutilizadores.</li>
      </ol>
    </p>
  </div>
</div>

*************************************************************************************************************

### Ejercicio

{{|>}}
*************************************************************************************************************

<div style="background:#ffffff; border:2px solid #154481; border-radius:12px; box-shadow:0 2px 8px rgba(21,68,129,0.15); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #072142 0%, #154481 100%); color:#ffffff; padding:1rem 1.5rem; display:flex; align-items:center; gap:0.75rem;">
    <div style="font-size:1.5em;">✏️</div>
    <h4 style="margin:0; font-size:1.3em; font-weight:600; font-family:'Montserrat', sans-serif;">Ejercicio</h4>
  </div>
  <div style="padding:1.25rem 1.5rem; background:#f8fafc;">
    <p style="margin:0; font-size:1em; color:#333; line-height:1.6;">
      A continuación, tienes definiciones de algunos principios de los datos abiertos. Empareja cada definición con su concepto correcto:
    </p>
  </div>
</div>

- [[Accesibles] [Completos] [Procesables] [No propietarios]]
- [    (X)         ( )          ( )             ( )        ]  Los datos deben estar disponibles de tal manera que cualquiera sin discriminación pueda usarlos, modificarlos y compartirlos para cualquier fin.
- [    ( )         (X)          ( )             ( )        ]  Todos los datos públicos deben estar disponibles, siempre que no estén sujetos a restricciones de privacidad o seguridad.
- [    ( )         ( )          (X)             ( )        ]  Los datos disponibles deben estar estructurados de tal forma que permitan ser procesados de forma automatizada.
- [    ( )         ( )          ( )             (X)        ]  Los datos deben estar disponibles en un formato que no sea de uso exclusivo de ninguna entidad para evitar restricciones de uso.
***
<div style="background:#d1fae5; border-left:4px solid #10b981; padding:0.5rem 1rem; border-radius:6px; margin:0.5rem 0;">
  <div style="color:#065f46; font-weight:600; font-size:1.1em;">✅ ¡Perfecto!</div>
  <div style="color:#047857; font-size:0.9em; margin-top:0.25rem;">Has identificado correctamente los principios OGD:</div>
  <ul style="color:#047857; font-size:0.9em; margin:0.5rem 0 0.5rem 1.5rem;">
    <li><strong>Accesibles:</strong> disponibles para todos sin discriminación</li>
    <li><strong>Completos:</strong> publicar toda la información salvo restricciones legales</li>
    <li><strong>Procesables:</strong> estructurados para que las máquinas puedan procesarlos</li>
    <li><strong>No propietarios:</strong> formatos sin control exclusivo de ninguna entidad</li>
  </ul>
</div>
***

*************************************************************************************************************

## BENEFICIOS DE LA REUTILIZACIÓN DE DATOS ABIERTOS

{{|>}}
*************************************************************************************************************

La apertura de datos que están en manos de las Administraciones públicas tienen un gran potencial para la generación de **beneficios económicos y sociales, así como ventajas para las propias administraciones** que apuestan por la apertura.

La [**Carta Internacional de Datos Abiertos**](https://opendatacharter.org/wp-content/uploads/2025/09/Carta_Internacional_de_Datos_Abiertos2015.pdf), presentada en 2015 y adoptada por numerosos gobiernos y organizaciones, entre ellos, el Gobierno de España, destaca los datos abiertos como un **elemento clave de la transformación global** impulsada por la tecnología y los medios digitales.

El destacado documento refiere cómo el acceso libre a los datos **permite a los actores públicos y privados generar innovación**, desarrollar **nuevos productos** y servicios, y **mejorar la eficiencia económica** mediante decisiones basadas en evidencia. Así mismo, presenta los datos abiertos como un activo clave por su capacidad para **fortalecer gobiernos más transparentes**, responsables, eficientes y receptivos, así como para **apoyar el diseño, la implementación y la evaluación de políticas públicas** y de los Objetivos de Desarrollo Sostenible a escala global.

Además, los datos abiertos se constituyen en pieza clave para **nuevos nichos de valor** como son la **inteligencia artificial o los espacios de datos.** Por una parte, la **combinación de los datos abiertos y la inteligencia artificial abre nuevas y valiosas oportunidades** para afrontar los grandes retos globales de una forma más informada y con mayor impacto. Tal y como señalan las [directrices de la UNESCO en 2023](https://unesdoc.unesco.org/ark%3A/48223/pf0000385841.locale%3Den), los datos abiertos no son solo un recurso útil, sino una base imprescindible para desarrollar una inteligencia artificial responsable y eficaz. Por otro lado, **los datos abiertos se constituyen en un activo básico de los espacios de datos**. Los usuarios que acceden a este tipo de nuevos ecosistemas digitales pueden combinar datos abiertos y datos de espacios de datos para crear casos de reutilización innovadores que no serían posibles con datos de una única fuente.

Tanto mediante un uso más tradicional como utilizando tecnologías más novedosas, los beneficios de los datos abiertos son incuestionables. Esta realidad se pone de manifiesto a través no solo de diversos **informes que tratan de cuantificar el impacto de los datos abiertos**, sino también, y de forma más tangible, mediante **recopilatorios de ejemplos y casos de uso que presentan una visión más cualitativa** del valor que aporta la reutilización de los datos abiertos. Estos últimos se recogen en fuentes de información de diversa naturaleza, como medios de comunicación generalistas y especializados, informes de organismos nacionales e internacionales, y repositorios de casos de uso disponibles en múltiples portales de datos abiertos, entre otros.

A continuación se presentan ejemplos concretos que dejan de manifiesto el potencial creciente de esta materia prima.

*************************************************************************************************************

### Beneficios económicos

{{|>}}
*************************************************************************************************************

Los datos que las administraciones disponen como datos abiertos permiten **optimizar los procesos empresariales**, encontrar soluciones a los retos corporativos a través del análisis de la información, además de favorecer la **generación de nuevos productos, servicios e incluso modelos de negocio.**

Los datos abiertos son especialmente valiosos para las pequeñas y medianas empresas, así como para las empresas de nueva creación que no disponen de suficiente cantidad de datos por sí mismas.

Ejemplos relevantes del potencial económico de los datos abiertos para el tejido empresarial se traducen en casos como los presentados a continuación.

<div style="background:#ffffff; border:1px solid #ddd; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #ac2624 0%, #333334 100%); color:#ffffff; padding:1.5rem; text-align:center;">
    <h3 style="margin:0; font-size:1.75em; font-weight:700; font-family:'Montserrat', sans-serif;">Meteogrid</h3>
  </div>
  <div style="display:flex; flex-wrap:wrap; padding:1.5rem;">
    <div style="flex:1; min-width:300px; padding-right:1.5rem;">
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿A qué se dedican?</h4>
        <p style="margin:0; line-height:1.6;">
          <strong>Meteogrid</strong> nace en 2004, una SME especializados en la <strong>lucha contra incendios y protección civil.</strong> Entre otras actividades, la compañía ofrece <strong>servicios de asesoría diaria a los</strong> cuerpos de protección civil y bomberos en incendios forestales sobre <strong>comportamiento del fuego en base a las condiciones meteorológicas.</strong>
        </p>
        <p style="margin:1rem 0 0 0; line-height:1.6;">
          Dispone de índices y aplicaciones específicas para la <strong>asesoría del comportamiento de incendio en las zonas de interfaz</strong>, y para la <strong>identificación del riesgo</strong> sobre personas, viviendas, propiedades y medio natural.
        </p>
      </div>
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿Qué datos abiertos utilizan?</h4>
        <ul style="margin:0; padding-left:1.5rem; line-height:1.8;">
          <li>Telemetría LIDAR vuelo PNOA (Plan Nacional de Ortofotografía Aérea)</li>
          <li>Inventario Forestal Nacional (IFN3)</li>
          <li>Datos del Catastro</li>
        </ul>
      </div>
      <div>
        <p style="margin:0; font-size:0.95em;">
          <strong>Más información:</strong> <a href="https://datos.gob.es/es/empresas/meteogrid" target="_blank" rel="noopener" style="font-weight:600;">datos.gob.es/es/empresas/meteogrid</a>
        </p>
      </div>
    </div>
    <div style="flex:0 0 200px; display:flex; align-items:center; justify-content:center; padding:1rem;">
      <img src="https://datos.gob.es/sites/default/files/success/images/meteogrid_0.png" alt="Meteogrid" style="max-width:180px; max-height:180px; width:auto; height:auto;">
    </div>
  </div>
</div>

<div style="background:#ffffff; border:1px solid #ddd; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #84c7cc 0%, #02828d 100%); color:#ffffff; padding:1.5rem; text-align:center;">
    <h3 style="margin:0; font-size:1.75em; font-weight:700; font-family:'Montserrat', sans-serif;">Hispatec Agrointeligencia</h3>
  </div>
  <div style="display:flex; flex-wrap:wrap; padding:1.5rem;">
    <div style="flex:1; min-width:300px; padding-right:1.5rem;">
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿A qué se dedican?</h4>
        <p style="margin:0; line-height:1.6;">
          <strong>Hispatec Agrointeligencia</strong> es una compañía que trabaja en pro de sacar la inteligencia de los datos para el <strong>sector agro.</strong>
        </p>
        <p style="margin:1rem 0 0 0; line-height:1.6;">
          Desde Hispatec Agrointeligencia analizan el <strong>flujo de datos desde la producción hasta el mercado y viceversa.</strong> Desarrollan productos que mejoran la <strong>eficiencia de empresas del sector agro</strong> y soluciones que aseguran la <strong>conservación del medio ambiente</strong> (uso del agua, suelo, fertilizantes,…).
        </p>
      </div>
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿Qué datos abiertos utilizan?</h4>
        <ul style="margin:0; padding-left:1.5rem; line-height:1.8;">
          <li>Datos del proyecto Copérnico</li>
          <li>Precios coyunturales de productos agrícolas y ganaderos</li>
          <li>Red de Alerta e Información Fitosanitaria</li>
        </ul>
      </div>
      <div>
        <p style="margin:0; font-size:0.95em;">
          <strong>Más información:</strong> <a href="https://datos.gob.es/es/empresas/hispatec" target="_blank" rel="noopener" style="font-weight:600;">datos.gob.es/es/empresas/hispatec</a>
        </p>
      </div>
    </div>
    <div style="flex:0 0 200px; display:flex; align-items:center; justify-content:center; padding:1rem;">
      <img src="https://datos.gob.es/sites/default/files/success/images/hispatec_logo.jpg" alt="Hispatec" style="max-width:180px; max-height:180px; width:auto; height:auto;">
    </div>
  </div>
</div>

<div style="background:#ffffff; border:1px solid #ddd; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #e1f56f 0%, #010900 100%); color:#ffff; padding:1.5rem; text-align:center;">
    <h3 style="margin:0; font-size:1.75em; font-weight:700; font-family:'Montserrat', sans-serif;">Idealista</h3>
  </div>
  <div style="display:flex; flex-wrap:wrap; padding:1.5rem;">
    <div style="flex:1; min-width:300px; padding-right:1.5rem;">
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿A qué se dedican?</h4>
        <p style="margin:0; line-height:1.6;">
          <strong>Idealista</strong> facilita un <strong>espacio para que los usuarios puedan publicar, o buscar, anuncios de venta o alquiler de inmuebles</strong>. También ofrecen otros servicios relacionados con el sector inmobiliario, como <strong>valoraciones de viviendas</strong> o el <strong>servicio de certificación energética</strong>.
        </p>
        <p style="margin:1rem 0 0 0; line-height:1.6;">
          Su misión es poner al alcance de cualquier profesional del sector <strong>información inmobiliaria estructurada, ordenada, homogénea y en tiempo real</strong>.
        </p>
      </div>
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿Qué datos abiertos utilizan?</h4>
        <ul style="margin:0; padding-left:1.5rem; line-height:1.8;">
          <li>Datos del Catastro</li>
          <li>Datos del Instituto Nacional de Estadística</li>
          <li>Telemetría LIDAR vuelo PNOA (Plan Nacional de Ortofotografía Aérea)</li>
        </ul>
      </div>
      <div>
        <p style="margin:0; font-size:0.95em;">
          <strong>Más información:</strong> <a href="https://datos.gob.es/es/empresas/idealista" target="_blank" rel="noopener" style="font-weight:600;">datos.gob.es/es/empresas/idealista</a>
        </p>
      </div>
    </div>
    <div style="flex:0 0 200px; display:flex; align-items:center; justify-content:center; padding:1rem;">
      <img src="https://datos.gob.es/sites/default/files/success/images/idealista.jpg" alt="Idealista" style="max-width:180px; max-height:180px; width:auto; height:auto;">
    </div>
  </div>
</div>

Estas realidades avalan las cifras que refleja el último Informe de la Asociación Multisectorial de la Información (ASEDIE), que analiza y describe la situación del **sector reutilizador en España**, y establece un **beneficio neto de 146 millones de euros en 2023** para las empresas que reutilizan datos -generalmente datos abiertos procedentes del sector público, pero también de fuentes privadas- [📖 Fuente](https://www.asedie.es/es/informes-anuales).

El siguiente visual resume algunas de las cifras más relevantes con las que concluye el estudio.

<center>![Informe del Sector Infomediario de Asedie](media/image_021.jpg "Informe del Sector Infomediario de Asedie. Economía del Dato en su ámbito infomediario (2025)")</center>

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#ede9fe; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <ul style="margin:0.5rem 0 0.5rem 0;">
      <li><a href="https://datos.gob.es/es/noticias/disponible-la-13a-edicion-del-informe-del-sector-infomediario-de-asedie" target="_blank" rel="noopener">Disponible la 13ª edición del Informe del Sector Infomediario de ASEDIE</a></li>
      <li><a href="https://datos.gob.es/es/empresas" target="_blank" rel="noopener">Ejemplos reales de empresas que basan su actividad en los datos abiertos</a></li>
    </ul>
  </div>
</div>

La Comisión Europea, a través del Portal europeo de datos, ofrece varios ejemplos de los **beneficios económicos indirectos** derivados del uso de los datos abiertos y advierte que, sin embargo, en la actualidad no se están explotando todas estas posibilidades y oportunidades, para lo cual sería necesario disponer de más datos abiertos en toda Europa. Fuente [El impacto económico de los datos abiertos: oportunidades de creación de valor en Europa](https://www.europeandataportal.eu/en/doc/economic-impact-open-data-opportunities-value-creation-europe) (2020). Se refieren, entre otros, los siguientes:

* **Contribuyen a salvar entre 54.000 y 202.000 vidas al disminuir el tiempo de respuesta de las emergencias à** Los datos abiertos pueden ayudar a los servicios de emergencia a alcanzar la ubicación de un incidente más rápido, lo que, a su vez, ayuda a salvar más vidas.
* **Optimizan en 27 millones de horas el transporte público à** Las aplicaciones basadas en datos abiertos ligados a la movilidad hacen posible optimizar la ruta, facilitar la conducción en tiempo real de cara a evitar atascos, etc.
* **Disminuyen la necesidad del equivalente a 5,8 millones de toneladas de petróleo à** Las aplicaciones basadas en datos abiertos sirven como una herramienta para ayudar a los hogares a reducir su consumo de energía proporcionándoles informes y sugerencias sobre cómo disminuir su uso.
* **Ahorran 1.100 millones de euros en gastos de traducción por parte de las Administraciones públicas** Los datos abiertos permiten optimizar los sistemas de traducción automática.

En resumen, los datos abiertos, **impulsan el crecimiento y la eficiencia en todos los sectores**. Contribuyen a la **creación de empleo**, tanto de forma directa como indirecta, facilitan procesos de contratación más inteligentes y **estimulan la innovación** en ámbitos como la planificación urbana y los servicios digitales, tal y como refiere el “Tercer volumen del Observatorio de Casos de Uso” [📖 Fuente](https://data.europa.eu/en/publications/reports/use-case-observatory-0)

<div style="background:#fdf8ec; border-left:4px solid #ff9800; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#fdf2e4; color:#ff9800; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ⚠️ Aviso
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <p style="margin:0.25rem 0 0.5rem 0;">
      Los datos abiertos son la materia prima esencial para la economía del dato que Europa pretende desarrollar y se constituyen en elemento de los <a href="https://digital-strategy.ec.europa.eu/en/policies/data-spaces" target="_blank" rel="noopener">espacios europeos de datos sectoriales</a>: salud, movilidad, turismo, agricultura, energía, finanzas, clima, administración pública, entre otros.
    </p>
  </div>
</div>

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#ede9fe; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <ul style="margin:0.5rem 0 0.5rem 0;">
      <li><a href="https://datos.gob.es/es/empresas" target="_blank" rel="noopener">Catálogo de empresas de datos.gob.es</a></li>
      <li><a href="https://datos.gob.es/es/noticias/transformando-los-datos-abiertos-en-valor-socioeconomico" target="_blank" rel="noopener">Transformando los datos abiertos en valor socioeconómico</a></li>
      <li><a href="https://datos.gob.es/es/noticias/los-datos-abiertos-especialmente-valiosos-para-la-pequena-y-mediana-empresa" target="_blank" rel="noopener">Los datos abiertos, especialmente valiosos para la pequeña y mediana empresa</a></li>
    </ul>
  </div>
</div>

*************************************************************************************************************

### Beneficios sociales

{{|>}}
*************************************************************************************************************

Los datos abiertos poseen un importante potencial para generar beneficios sociales al promover **una sociedad más informada, participativa y equitativa**.

Tal y como señala la Carta Internacional de Datos Abiertos, el acceso libre y oportuno a los datos permite a ciudadanos, gobiernos y organizaciones de la sociedad civil **comprender mejor la realidad social, identificar desigualdades, evaluar el impacto de las políticas públicas y diseñar soluciones más ajustadas a las necesidades** reales de la población.

Además, los datos abiertos **favorecen la mejora de los servicios públicos** en ámbitos clave como la salud, la educación, la protección del medio ambiente, la seguridad o los derechos humanos, al **facilitar decisiones basadas en evidencia** y una colaboración más efectiva entre los distintos actores sociales.

Ejemplos relevantes del valor social de los datos abiertos se traducen en ejemplos impulsados tanto por organizaciones públicas, privada o del tercer sector, tales como los presentados a continuación.

<div style="background:#ffffff; border:1px solid #ddd; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #f9ec45 0%, #1e3c85 100%); color:#ffffff; padding:1.5rem; text-align:center;">
    <h3 style="margin:0; font-size:1.75em; font-weight:700; font-family:'Montserrat', sans-serif;">Park4Dis</h3>
  </div>
  <div style="display:flex; flex-wrap:wrap; padding:1.5rem;">
    <div style="flex:1; min-width:300px; padding-right:1.5rem;">
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿A qué se dedican?</h4>
        <p style="margin:0; line-height:1.6;">
          Proyecto para <strong>ayudar a conductores con movilidad reducida</strong> en Europa y a todas las familias de personas con discapacidad, para tener mayor autonomía y poder desplazarse sin barreras añadidas.
        </p>
        <p style="margin:1rem 0 0 0; line-height:1.6;">
          Ofrece una aplicación en la que refiere más de 75.000 plazas en más de 1.000 municipios. La plataforma se nutre de su <strong>red de voluntarios</strong> en colaboración con empresas socialmente responsables.
        </p>
      </div>
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿Qué datos abiertos utilizan?</h4>
        <ul style="margin:0; padding-left:1.5rem; line-height:1.8;">
          <li>Datos proporcionados por ayuntamientos para mapear y localizar plazas de aparcamiento para personas con movilidad reducida</li>
          <li>Datos de normativas locales de tráfico</li>
        </ul>
      </div>
      <div>
        <p style="margin:0; font-size:0.95em;">
          <strong>Más información:</strong> <a href="https://datos.gob.es/es/aplicaciones/park4dis" target="_blank" rel="noopener" style="font-weight:600;">datos.gob.es/es/aplicaciones/park4dis</a>
        </p>
      </div>
    </div>
    <div style="flex:0 0 200px; display:flex; align-items:center; justify-content:center; padding:1rem;">
      <img src="https://datos.gob.es/sites/default/files/app/logo/25-logo-park-dis_2.jpg" alt="Logo Park4Dis" style="max-width:180px; max-height:180px; width:auto; height:auto;">
    </div>
  </div>
</div>

<div style="background:#ffffff; border:1px solid #ddd; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #00266f 0%, #00ffa6 100%); color:#ffffff; padding:1.5rem; text-align:center;">
    <h3 style="margin:0; font-size:1.75em; font-weight:700; font-family:'Montserrat', sans-serif;">Civio</h3>
  </div>
  <div style="display:flex; flex-wrap:wrap; padding:1.5rem;">
    <div style="flex:1; min-width:300px; padding-right:1.5rem;">
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿A qué se dedican?</h4>
        <p style="margin:0; line-height:1.6;">
          Organización sin ánimo de lucro que <strong>promueve la transparencia de las instituciones y el fácil acceso a la información pública mediante la tecnología y el periodismo</strong>.
        </p>
        <p style="margin:1rem 0 0 0; line-height:1.6;">
          Para ello cuentan con tres líneas de actuación: periodismo, incidencia pública y servicios de transparencia para las AA.PP.
        </p>
      </div>
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿Qué datos abiertos utilizan?</h4>
        <ul style="margin:0; padding-left:1.5rem; line-height:1.8;">
          <li>Sistema Nacional de Publicidad de Subvenciones y Ayudas Públicas</li>
          <li>Datos del proyecto Copérnico</li>
          <li>Datos del Boletín Oficial del Estado</li>
        </ul>
      </div>
      <div>
        <p style="margin:0; font-size:0.95em;">
          <strong>Más información:</strong> <a href="https://datos.gob.es/es/empresas/civio" target="_blank" rel="noopener" style="font-weight:600;">datos.gob.es/es/empresas/civio</a>
        </p>
      </div>
    </div>
    <div style="flex:0 0 200px; display:flex; align-items:center; justify-content:center; padding:1rem;">
      <img src="https://datos.gob.es/sites/default/files/success/images/civio-fundacion.png" alt="Civio" style="max-width:180px; max-height:180px; width:auto; height:auto;">
    </div>
  </div>
</div>

<div style="background:#ffffff; border:1px solid #ddd; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #f7f7f7 0%, #000000 100%); color:#ffffff; padding:1.5rem; text-align:center;">
    <h3 style="margin:0; font-size:1.75em; font-weight:700; font-family:'Montserrat', sans-serif;">Datadista</h3>
  </div>
  <div style="display:flex; flex-wrap:wrap; padding:1.5rem;">
    <div style="flex:1; min-width:300px; padding-right:1.5rem;">
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿A qué se dedican?</h4>
        <p style="margin:0; line-height:1.6;">
          <strong>Datadista</strong> es un medio de comunicación digital español especializado en <strong>periodismo de investigación, periodismo de datos y nuevas narrativas</strong>.
        </p>
        <p style="margin:1rem 0 0 0; line-height:1.6;">
          Fue creado en 2016 con el objetivo de <strong>explicar temas complejos</strong> como la corrupción, el uso de los recursos públicos y cuestiones sociales, medioambientales y económicas <strong>mediante análisis de datos, visualizaciones interactivas, vídeos explicativos e investigaciones en profundidad.</strong>
        </p>
      </div>
      <div style="margin-bottom:1.5rem;">
        <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿Qué datos abiertos utilizan?</h4>
        <ul style="margin:0; padding-left:1.5rem; line-height:1.8;">
          <li>Datos del Instituto Nacional de Estadística</li>
          <li>Boletín Oficial del Estado</li>
          <li>Registro Mercantil</li>
        </ul>
      </div>
      <div>
        <p style="margin:0; font-size:0.95em;">
          <strong>Más información:</strong> <a href="https://datos.gob.es/es/empresas/datadista" target="_blank" rel="noopener" style="font-weight:600;">datos.gob.es/es/empresas/datadista</a>
        </p>
      </div>
    </div>
    <div style="flex:0 0 200px; display:flex; align-items:center; justify-content:center; padding:1rem;">
      <img src="https://datos.gob.es/sites/default/files/success/images/logo_datadista_tamano_ok.jpg" alt="Datadista" style="max-width:180px; max-height:180px; width:auto; height:auto;">
    </div>
  </div>
</div>

En resumen, los beneficios sociales de los **datos abiertos** se traducen en la democratización del acceso a la información, permiten realidades como el **periodismo de datos** e impulsan la participación activa de la sociedad en la toma de decisiones y en la mejora de su entorno, asegurando un **control social distribuido,** esto es, comunidades organizadas pueden monitorizar la calidad del aire, el nivel de ruido o el estado del mantenimiento urbano, promoviendo entornos más saludables y sostenibles.

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#ede9fe; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <ul style="margin:0.5rem 0 0.5rem 0;">
      <li><a href="https://datos.gob.es/es/blog/la-reutilizacion-de-datos-abiertos-en-el-periodismo-una-ventana-abierta-nuevos-modelos-de-negocio" target="_blank" rel="noopener">La reutilización de datos abiertos en el periodismo: una ventana abierta a nuevos modelos de negocio y comunidades</a></li>
      <li><a href="https://datos.gob.es/es/noticias/transformando-los-datos-abiertos-en-valor-socioeconomico" target="_blank" rel="noopener">Transformando los datos abiertos en valor socioeconómico</a></li>
      <li><a href="https://datos.gob.es/es/conocimiento/datos-abiertos-para-cumplir-con-los-objetivos-de-desarrollo-sostenible" target="_blank" rel="noopener">Datos abiertos para cumplir con los Objetivos de Desarrollo Sostenible</a></li>
      <li><a href="https://datos.gob.es/es/blog/datos-abiertos-inteligencia-artificial-y-medio-ambiente" target="_blank" rel="noopener">Datos abiertos, inteligencia artificial y medio ambiente</a></li>
    </ul>
  </div>
</div>

*************************************************************************************************************

### Beneficios para la propia Administración

{{|>}}
*************************************************************************************************************

En el ámbito de las administraciones públicas, la reutilización de la información del sector público facilita la optimización y creación de servicios, contribuyendo a la mejora de la reputación institucional y al fomento de la innovación, lo cual se traduce en un ahorro económico en la actividad pública.

* **Mejora de la reputación institucional** à la apertura de datos mejora la reputación de las administraciones al aumentar la transparencia, y en consecuencia, fortalecer la confianza y la participación ciudadana en la gestión pública.
* **Ahorro en el desarrollo de la actividad pública** à La reutilización de datos abiertos por parte de las administraciones, especialmente en colaboración del sector público, favorece la innovación, lo cual se traduce en productos y servicios que mejoran la eficiencia, accesibilidad y sostenibilidad de los servicios mediante soluciones replicables. Esto se traduce en ahorros económicos directos e indirectos.

A continuación se presentan ejemplos que dejan de manifiesto los beneficios que la apertura de datos supone para la Administración.

<div style="background:#ffffff; border:1px solid #ddd; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #ba283b 0%, #ce9aca 100%); color:#ffff; padding:1.5rem; text-align:center;">
    <h3 style="margin:0; font-size:1.75em; font-weight:700; font-family:'Montserrat', sans-serif;">Datahub energético de Castilla y León</h3>
  </div>
  <div style="padding:1.5rem;">
    <div style="margin-bottom:1.5rem;">
      <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿En qué consiste y qué beneficios aporta?</h4>
      <p style="margin:0; line-height:1.6;">
        El Datahub energético de la Junta es un <strong>ejercicio de transparencia</strong> de la Administración de Castilla y León. Consiste en un compendio de información energética informatizada a través de una herramienta para la <strong>optimización energética</strong> de edificios de la administración autónoma.
      </p>
      <p style="margin:1rem 0 0 0; line-height:1.6;">
        A través de esta herramienta se racionalizan anualmente los contratos energéticos y se realizan las compras energéticas de los diferentes Organismos de la Junta de Castilla y León. <strong>Los ahorros cuantificados desde el año 2015 han sido de 2M€ anuales</strong> únicamente en el coste fijo de electricidad.
      </p>
    </div>
    <div style="margin-bottom:1.5rem;">
      <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿Qué datos abiertos utilizan?</h4>
      <ul style="margin:0; padding-left:1.5rem; line-height:1.8;">
        <li>Sistema de Información de Puntos de Suministros (SIPS) de electricidad y el SIPS de gas natural canalizado</li>
        <li>Relación de edificios e instalaciones de la comunidad autónoma con su ubicación y coordenadas GPS, superficie, etc.</li>
        <li>Referencias catastrales de los edificios</li>
      </ul>
    </div>
    <div>
      <p style="margin:0; font-size:0.95em;">
        <a href="https://energia.jcyl.es/web/es/ahorro-eficiencia-energetica/datahub-energetico-junta-castilla.html" target="_blank" rel="noopener" style="text-decoration:none; font-weight:600;">📖 Fuente</a>
      </p>
    </div>
  </div>
</div>

<div style="background:#ffffff; border:1px solid #ddd; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #8b9523 0%, #203b03 100%); color:#ffff; padding:1.5rem; text-align:center;">
    <h3 style="margin:0; font-size:1.75em; font-weight:700; font-family:'Montserrat', sans-serif;">Smart Agro-Recomendaciones de Riego</h3>
  </div>
  <div style="padding:1.5rem;">
    <div style="margin-bottom:1.5rem;">
      <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿En qué consiste y qué beneficios aporta?</h4>
      <p style="margin:0; line-height:1.6;">
        Smart Agro-Recomendaciones de Riego es una herramienta digital desarrollada por el Cabildo de La Palma con el objetivo es mejorar la <strong>eficiencia del uso del agua</strong> en la agricultura local, especialmente para cultivos de plátano y aguacate.
      </p>
      <p style="margin:1rem 0 0 0; line-height:1.6;">
        La aplicación proporciona información detallada al seleccionar el cultivo y la zona de explotación para facilitar decisiones hídricas más eficientes, representando un paso importante hacia una agricultura más inteligente.
      </p>
      <p style="margin:1rem 0 0 0; line-height:1.6;">
        Contribuye de forma notable a la <strong>mejora de la reputación institucional</strong> al posicionar al Cabildo como una entidad innovadora, comprometida con la sostenibilidad y orientada a las necesidades reales del territorio.
      </p>
    </div>
    <div style="margin-bottom:1.5rem;">
      <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿Qué datos abiertos utilizan?</h4>
      <ul style="margin:0; padding-left:1.5rem; line-height:1.8;">
        <li>Datos de la red insular de estaciones meteorológicas</li>
        <li>Datos de evapotranspiración (ETo)</li>
        <li>Datos de calidad del aire</li>
      </ul>
    </div>
    <div>
      <p style="margin:0; font-size:0.95em;">
        <a href="https://datos.gob.es/es/aplicaciones/smart-agro-recomendaciones-de-riego" target="_blank" rel="noopener" style="text-decoration:none; font-weight:600;">📖 Fuente</a>
      </p>
    </div>
  </div>
</div>

<div style="background:#ffffff; border:1px solid #ddd; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,0.1); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #5e605f 0%, #fdd100 100%); color:#ffff; padding:1.5rem; text-align:center;">
    <h3 style="margin:0; font-size:1.75em; font-weight:700; font-family:'Montserrat', sans-serif;">Spain By Bike</h3>
  </div>
  <div style="padding:1.5rem;">
    <div style="margin-bottom:1.5rem;">
      <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿En qué consiste y qué beneficios aporta?</h4>
      <p style="margin:0; line-height:1.6;">
        Spain By Bike es una plataforma especializada en <strong>turismo ciclista por España</strong> desarrollada Instituto Geográfico Nacional (IGN) y el Centro Nacional de Información Geográfica (CNIG). Presenta una amplia variedad de rutas ciclistas por regiones, adaptadas a distintos niveles y estilos: desde recorridos tranquilos por vías verdes hasta desafíos de montaña. A través de una herramienta interactiva, los usuarios pueden ver el itinerario, la ubicación, la dificultad, la distancia, etc. Además, ofrece servicios complementarios como alquiler de bicicletas, transporte de equipaje, alojamiento y asistencia técnica.
      </p>
      <p style="margin:1rem 0 0 0; line-height:1.6;">
        Esta herramienta contribuye a reforzar la imagen de las administraciones como <strong>instituciones innovadoras</strong>, y alineadas con las políticas públicas de sostenibilidad y reutilización de la información pública.
      </p>
      <p style="margin:1rem 0 0 0; line-height:1.6;">
        La aplicación está basada en datos abiertos con licencia CC BY 4.0, lo cual refuerza el <strong>compromiso de la administración con la transparencia y la reutilización de la información del sector público.</strong>
      </p>
    </div>
    <div style="margin-bottom:1.5rem;">
      <h4 style="color:#446DA2; margin:0 0 0.75rem 0; font-size:1.1em; border-bottom:2px solid #e0e0e0; padding-bottom:0.5rem; font-family:'Montserrat', sans-serif;">¿Qué datos abiertos utilizan?</h4>
      <ul style="margin:0; padding-left:1.5rem; line-height:1.8;">
        <li>Geoespaciales y cartográficos</li>
        <li>Rutas ciclistas e itinerario</li>
        <li>Datos turísticos y de puntos de interés</li>
      </ul>
    </div>
    <div>
      <p style="margin:0; font-size:0.95em;">
        <a href="https://datos.gob.es/es/aplicaciones/rutas-ciclistas-por-espana" target="_blank" rel="noopener" style="text-decoration:none; font-weight:600;">📖 Fuente</a>
      </p>
    </div>
  </div>
</div>

<div style="background:#f3e8ff; border-left:4px solid #7c3aed; padding:0; border-radius:8px; overflow:hidden; margin-top:1.5rem; margin-bottom:1.5rem;">
  <div style="background:#ede9fe; color:#7c3aed; padding:0.6rem 1rem; font-weight:600; font-size:1.05em;">
    ℹ️ Más información
  </div>
  <div style="padding:0 1rem 0 1rem;">
    <ul style="margin:0.5rem 0 0.5rem 0;">
      <li><a href="https://datos.gob.es/es/conocimiento/innovacion-municipal-traves-de-datos-abiertos-soluciones-para-hacer-mas-accesibles-los" target="_blank" rel="noopener">Innovación municipal a través de datos abiertos: soluciones para hacer más accesibles los servicios municipales</a></li>
      <li><a href="https://datos.gob.es/es/blog/aplicaciones-de-datos-geograficos-abiertos-del-centro-nacional-de-informacion-geografica" target="_blank" rel="noopener">Aplicaciones de datos geográficos abiertos del Centro Nacional de Información Geográfica</a></li>
      <li><a href="https://datos.gob.es/es/conocimiento/las-administraciones-publicas-ante-la-reutilizacion-de-la-informacion-publica" target="_blank" rel="noopener">Las Administraciones Públicas ante la reutilización de la información pública</a></li>
    </ul>
  </div>
</div>

*************************************************************************************************************

### Ejercicio

{{|>}}
*************************************************************************************************************

<div style="background:#ffffff; border:2px solid #154481; border-radius:12px; box-shadow:0 2px 8px rgba(21,68,129,0.15); margin:1.5rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #072142 0%, #154481 100%); color:#ffffff; padding:1rem 1.5rem; display:flex; align-items:center; gap:0.75rem;">
    <div style="font-size:1.5em;">✏️</div>
    <h4 style="margin:0; font-size:1.3em; font-weight:600; font-family:'Montserrat', sans-serif;">Ejercicio</h4>
  </div>
  <div style="padding:1.25rem 1.5rem; background:#f8fafc;">
    <p style="margin:0; font-size:1em; color:#333; line-height:1.6;">
      Indica cuáles de las siguientes afirmaciones sobre los beneficios de los datos abiertos son verdaderas y cuáles falsas.
    </p>
  </div>
</div>

**1) Los datos abiertos pueden contribuir a que los Gobiernos sean más transparentes**

- [(X)] Verdadero
- [( )] Falso
***
> La transparencia y rendición de cuentas es uno de los principales beneficios de los datos abiertos.
***

**2) Los datos abiertos estimulan la innovación**

- [(X)] Verdadero
- [( )] Falso
***
> Los datos abiertos favorecen la generación de nuevos productos, servicios e incluso modelos de negocio.
***

**3) Los datos abiertos pueden ayudar a demostrar que los fondos públicos se están empleando adecuadamente y que las políticas se están aplicando**

- [(X)] Verdadero
- [( )] Falso
***
> La apertura de datos permite verificar el uso adecuado de recursos públicos y evaluar políticas.
***

**4) Los datos abiertos pueden generar nuevas oportunidades de negocio**

- [(X)] Verdadero
- [( )] Falso
***
> Son especialmente valiosos para PYMEs y startups que no disponen de datos propios suficientes.
***

**5) Los datos abiertos pueden ayudar a proteger nuestro planeta**

- [(X)] Verdadero
- [( )] Falso
***
> Facilitan decisiones basadas en evidencia sobre medio ambiente, clima y sostenibilidad.
***

*************************************************************************************************************

<!-- id="cuestionario-final" -->
## CUESTIONARIO FINAL

{{|>}}
*************************************************************************************************************

<div style="background:#ffffff; border:2px solid #154481; border-radius:16px; box-shadow:0 4px 12px rgba(147,51,234,0.2); margin:2rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #072142 0%, #154481 100%); color:#ffffff; padding:2rem; text-align:center;">
    <div style="font-size:3em; margin-bottom:0.5rem;">📋</div>
    <h3 style="margin:0; font-size:2em; font-weight:700; text-transform:uppercase; letter-spacing:1px; font-family:'Montserrat', sans-serif;">Cuestionario Final</h3>
    <p style="margin:0.75rem 0 0 0; font-size:1.1em; opacity:0.95;">Evalúa tus conocimientos sobre datos abiertos</p>
  </div>
  <div style="padding:1.5rem 2rem; background:linear-gradient(to bottom, #faf5ff 0%, #ffffff 100%);">
    <p style="margin:0; font-size:1.05em; color:#333; text-align:center;">
      <strong>Instrucciones:</strong> Indica si cada afirmación es <strong>verdadera</strong> o <strong>falsa</strong>
    </p>
  </div>
</div>

**1) Es conveniente que los datos abiertos tengan limitaciones de uso comercial con licencias específicas**

- [( )] Verdadero
- [(X)] Falso
***
> Las licencias abiertas deben permitir uso y reutilización, también comercial.
***

**2) Los datos sujetos a confidencialidad estadística deben ser publicados como datos abiertos**

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

**7) Un beneficio importante de los datos abiertos es el hecho de que su publicación favorece la transparencia**

- [(X)] Verdadero
- [( )] Falso
***
> Transparencia y rendición de cuentas.
***

**8) Ofrecer datos primarios significa publicarlos con el mayor nivel de granularidad, evitando agregaciones o modificaciones**

- [(X)] Verdadero
- [( )] Falso
***
> Datos primarios permiten máxima reutilización.
***

**9) Cualquier restricción que se imponga sobre el uso de datos abiertos incrementa su potencial para generar nuevo valor**

- [( )] Verdadero
- [(X)] Falso
***
> Las restricciones reducen la reutilización.
***

**10) Aspectos como el formato, la estructura y la posibilidad de ser leídos por las máquinas reducen la usabilidad de los datos abiertos**

- [( )] Verdadero
- [(X)] Falso
***
> Procesables por máquina = mayor reutilización.
***

*************************************************************************************************************

<!-- id="resumen" -->
## RESUMEN

{{|>}}
*************************************************************************************************************

> * Los datos se han convertido en un **activo fundamental** para personas, organizaciones y administraciones públicas, siendo el factor diferencial de la revolución tecnológica actual.
> * Los **datos abiertos** son aquellos que cualquiera puede utilizar, reutilizar y redistribuir libremente, con el único requisito de atribución de la fuente.
> * Las administraciones públicas están **impulsando políticas de "datos abiertos"** para apoyar el **nuevo modelo de relación administración-ciudadanía** que favorezca a esta última su participación en la toma de decisiones de una forma más directa.
> * Existen **conceptos clave** diferenciados: dato, conjunto de datos, distribución, metadatos, catálogo, servicio de datos (API) y espacio de datos, cada uno con un rol específico en el ecosistema de datos abiertos.
> * Los **datos de alto valor (HVD)** abarcan seis categorías definidas por la Comisión Europea: geoespaciales, observación de la Tierra y medio ambiente, meteorológicos, estadísticos, empresariales y movilidad.
> * Los datos abiertos deben tener en cuenta unos **principios generales** que aseguren que los datos pueden ser fácilmente utilizables, reutilizables y redistribuibles:
>   * **Principios OGD**: completos, primarios, oportunos, accesibles, procesables, no discriminatorios, no propietarios y de licencia libre.
>   * **Principios FAIR**: encontrables, accesibles, interoperables y reutilizables.
> * Las políticas de datos abiertos tienen **beneficios** para las propias administraciones, para la economía y la ciudadanía:
>   * **Económicos**: impulsan la innovación, crean empleo, generan nuevos productos y servicios, y son especialmente valiosos para PYMEs y startups.
>   * **Sociales**: promueven la transparencia, facilitan el periodismo de datos, mejoran servicios públicos y fomentan la participación ciudadana.
>   * **Para la Administración**: mejoran la reputación institucional, optimizan recursos, generan ahorros económicos y favorecen la colaboración público-privada.
> * Los datos abiertos son **pieza clave** para nuevos nichos de valor como la **inteligencia artificial** y los **espacios de datos** europeos sectoriales.

*************************************************************************************************************

<!-- id="contacto" -->
## CONTACTO

{{|>}}
*************************************************************************************************************

<div style="background:#ffffff; border:2px solid #154481; border-radius:16px; box-shadow:0 4px 12px rgba(21,68,129,0.2); margin:2rem 0; overflow:hidden;">
  <div style="background:linear-gradient(135deg, #072142 0%, #154481 100%); color:#ffffff; padding:2rem; text-align:center;">
    <img src="https://raw.githubusercontent.com/datosgobes/materiales-formativos/refs/heads/main/assets/img/logo_iniciativa-aporta.svg" alt="Iniciativa Aporta" style="height:60px; margin-bottom:1rem; filter:brightness(0) invert(1);">
    <h3 style="margin:0; font-size:1.75em; font-weight:700; font-family:'Montserrat', sans-serif;">¿Quieres saber más sobre la Iniciativa Aporta?</h3>
    <p style="margin:0.75rem 0 0 0; font-size:1.05em; opacity:0.9;">Descubre todo el potencial de los datos abiertos en España</p>
  </div>
  <div style="padding:1.5rem 2rem; background:linear-gradient(to bottom, #f0f7ff 0%, #ffffff 100%);">
    <div style="display:flex; flex-direction:column; gap:1rem;">
      <a href="https://datos.gob.es/" target="_blank" rel="noopener" style="display:flex; align-items:center; gap:1rem; padding:1rem 1.25rem; background:#ffffff; border:2px solid #e0e7ef; border-radius:12px; text-decoration:none; color:#333; box-shadow:0 2px 4px rgba(0,0,0,0.05); cursor:pointer;" onmouseover="this.style.borderColor='#154481'; this.style.boxShadow='0 6px 16px rgba(21,68,129,0.2)'; this.style.transform='translateY(-2px)';" onmouseout="this.style.borderColor='#e0e7ef'; this.style.boxShadow='0 2px 4px rgba(0,0,0,0.05)'; this.style.transform='translateY(0)';">
        <div style="background:#154481; color:#fff; width:50px; height:50px; border-radius:10px; display:flex; align-items:center; justify-content:center; font-size:1.5em; flex-shrink:0;">🌐</div>
        <div>
          <div style="font-weight:700; font-size:1.1em; color:#154481;">Visita datos.gob.es</div>
          <div style="font-size:0.9em; color:#666; margin-top:0.25rem;">Portal nacional de datos abiertos de España</div>
        </div>
      </a>
      <a href="http://bit.ly/2IY8JgV" target="_blank" rel="noopener" style="display:flex; align-items:center; gap:1rem; padding:1rem 1.25rem; background:#ffffff; border:2px solid #e0e7ef; border-radius:12px; text-decoration:none; color:#333; box-shadow:0 2px 4px rgba(0,0,0,0.05); cursor:pointer;" onmouseover="this.style.borderColor='#10b981'; this.style.boxShadow='0 6px 16px rgba(16,185,129,0.2)'; this.style.transform='translateY(-2px)';" onmouseout="this.style.borderColor='#e0e7ef'; this.style.boxShadow='0 2px 4px rgba(0,0,0,0.05)'; this.style.transform='translateY(0)';">
        <div style="background:#10b981; color:#fff; width:50px; height:50px; border-radius:10px; display:flex; align-items:center; justify-content:center; font-size:1.5em; flex-shrink:0;">📬</div>
        <div>
          <div style="font-weight:700; font-size:1.1em; color:#10b981;">Suscríbete al boletín</div>
          <div style="font-size:0.9em; color:#666; margin-top:0.25rem;">Recibe las últimas novedades en tu correo</div>
        </div>
      </a>
      <a href="https://datos.gob.es/es/form/contact" target="_blank" rel="noopener" style="display:flex; align-items:center; gap:1rem; padding:1rem 1.25rem; background:#ffffff; border:2px solid #e0e7ef; border-radius:12px; text-decoration:none; color:#333; box-shadow:0 2px 4px rgba(0,0,0,0.05); cursor:pointer;" onmouseover="this.style.borderColor='#f59e0b'; this.style.boxShadow='0 6px 16px rgba(245,158,11,0.2)'; this.style.transform='translateY(-2px)';" onmouseout="this.style.borderColor='#e0e7ef'; this.style.boxShadow='0 2px 4px rgba(0,0,0,0.05)'; this.style.transform='translateY(0)';">
        <div style="background:#f59e0b; color:#fff; width:50px; height:50px; border-radius:10px; display:flex; align-items:center; justify-content:center; font-size:1.5em; flex-shrink:0;">💬</div>
        <div>
          <div style="font-weight:700; font-size:1.1em; color:#d97706;">Contacta con nosotros</div>
          <div style="font-size:0.9em; color:#666; margin-top:0.25rem;">Sugerencias, mejoras o incidencias</div>
        </div>
      </a>
    </div>
  </div>
</div>

*************************************************************************************************************
