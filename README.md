from weasyprint import HTML

html_content = <!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Guía Maestra: Pre y Postoperatorio</title>
<style>
    @page {
        size: A4;
        margin: 18mm 15mm 18mm 15mm;
        @bottom-right {
            content: "Página " counter(page) " de " counter(pages);
            font-size: 8.5pt;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            color: #718096;
        }
        @bottom-left {
            content: "Cirugía I — Guía Maestra para Sacar 20";
            font-size: 8.5pt;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            color: #718096;
        }
    }

    body {
        font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
        color: #2d3748;
        line-height: 1.5;
        font-size: 10pt;
    }

    .header-box {
        background-color: #1a365d;
        color: white;
        padding: 20px 25px;
        border-radius: 8px;
        margin-bottom: 25px;
    }

    .header-box h1 {
        margin: 0 0 8px 0;
        font-size: 20pt;
        text-transform: uppercase;
        letter-spacing: 0.5px;
        color: #ffffff;
    }

    .header-box p {
        margin: 4px 0;
        font-size: 10pt;
        color: #e2e8f0;
    }

    h2 {
        color: #1a365d;
        border-bottom: 2px solid #2b6cb0;
        padding-bottom: 5px;
        margin-top: 25px;
        margin-bottom: 12px;
        font-size: 13.5pt;
        text-transform: uppercase;
        page-break-after: avoid;
    }

    h3 {
        color: #2b6cb0;
        margin-top: 18px;
        margin-bottom: 8px;
        font-size: 11.5pt;
        page-break-after: avoid;
    }

    h4 {
        color: #2c5282;
        margin-top: 12px;
        margin-bottom: 6px;
        font-size: 10.5pt;
        page-break-after: avoid;
    }

    p {
        margin: 6px 0;
        text-align: justify;
    }

    ul, ol {
        margin: 6px 0;
        padding-left: 20px;
    }

    li {
        margin-bottom: 4px;
    }

    table {
        width: 100%;
        border-collapse: collapse;
        margin: 14px 0;
        font-size: 9pt;
        page-break-inside: avoid;
    }

    th {
        background-color: #2b6cb0;
        color: white;
        text-align: left;
        padding: 7px 9px;
        font-weight: bold;
    }

    td {
        border-bottom: 1px solid #e2e8f0;
        padding: 7px 9px;
        vertical-align: top;
    }

    tr:nth-child(even) {
        background-color: #f7fafc;
    }

    .pepas-box {
        background-color: #fffaf0;
        border-left: 5px solid #dd6b20;
        border-right: 1px solid #feebc8;
        border-top: 1px solid #feebc8;
        border-bottom: 1px solid #feebc8;
        padding: 15px 18px;
        margin: 20px 0;
        border-radius: 0 8px 8px 0;
        page-break-inside: avoid;
    }

    .pepas-box h3 {
        color: #c05621;
        margin-top: 0;
        font-size: 12pt;
    }

    .badge {
        background-color: #e53e3e;
        color: white;
        padding: 2px 6px;
        border-radius: 4px;
        font-size: 7.5pt;
        font-weight: bold;
        vertical-align: middle;
    }

    .question-card {
        background-color: #ffffff;
        border: 1px solid #cbd5e0;
        border-left: 4px solid #3182ce;
        border-radius: 6px;
        padding: 12px 15px;
        margin-bottom: 15px;
        page-break-inside: avoid;
    }

    .question-title {
        font-weight: bold;
        color: #1a365d;
        margin-bottom: 6px;
    }

    .options {
        margin: 6px 0;
        padding-left: 15px;
        list-style-type: none;
    }

    .options li {
        margin-bottom: 3px;
    }

    .answer-box {
        background-color: #f0fff4;
        border: 1px solid #c6f6d5;
        color: #22543d;
        padding: 8px 12px;
        border-radius: 4px;
        margin-top: 8px;
        font-size: 9pt;
    }

    .flashcard-grid {
        display: block;
        page-break-inside: avoid;
    }

    .flashcard {
        border: 1px solid #e2e8f0;
        background-color: #f7fafc;
        border-radius: 6px;
        padding: 10px 14px;
        margin-bottom: 10px;
        page-break-inside: avoid;
    }

    .flashcard-q {
        font-weight: bold;
        color: #2b6cb0;
        margin-bottom: 4px;
    }

    .flashcard-a {
        color: #2f855a;
        font-weight: 500;
    }

    .diagram {
        background-color: #edf2f7;
        border: 1px solid #cbd5e0;
        padding: 12px;
        font-family: monospace;
        font-size: 8.5pt;
        border-radius: 6px;
        white-space: pre-wrap;
        margin: 15px 0;
        page-break-inside: avoid;
    }
</style>
</head>
<body>

<div class="header-box">
    <h1>GUÍA MAESTRA DE ESTUDIO: PRE Y POSTOPERATORIO</h1>
    <p><strong>Asignatura:</strong> Cirugía I — Unidad 5: Cirugía General</p>
    <p><strong>Docente / Sede:</strong> yo :v (mi casa)</p>
    <p><strong>Objetivo de Rendimiento:</strong> Nota Máxima (20/20) en Evaluaciones Teóricas y Prácticas</p>
</div>

<h2>1. 📌 Ficha Técnica y Objetivos de Aprendizaje</h2>
<h3>Ficha Técnica</h3>
<ul>
    <li><strong>Materia:</strong> Cirugía I — Unidad 5: Cirugía General.</li>
    <li><strong>Tema Principal:</strong> Manejo Perioperatorio (Evaluación Preoperatoria y Complicaciones Postoperatorias).</li>
    <li><strong>Meta Académica:</strong> Dominar la fisiopatología, estratificación de riesgo, diagnóstico oportuno y manejo integral para obtener la calificación máxima (20 de nota) en evaluaciones teóricas y prácticas.</li>
</ul>

<h3>Objetivos Clave para el Examen</h3>
<ul>
    <li>Definir con precisión el periodo preoperatorio y establecer los componentes de una historia clínica rigurosa.</li>
    <li>Dominar las escalas de evaluación de riesgo quirúrgico, cardiovascular, respiratorio y tromboembólico (ASA, Lee/RCRI, Goldman, METs, Caprini).</li>
    <li>Identificar la cronología exacta y etiología de la <strong>fiebre postoperatoria</strong>.</li>
    <li>Clasificar las <strong>Infecciones del Sitio Quirúrgico (ISQ)</strong> según la CDC y las <strong>Complicaciones Quirúrgicas</strong> según la escala de <strong>Clavien-Dindo</strong>.</li>
    <li>Reconocer y manejar las principales complicaciones respiratorias, digestivas y renales del postoperatorio.</li>
</ul>

<h2>2. 📚 Desarrollo Exhaustivo del Contenido</h2>

<div class="diagram">
                        PERIODO PERIOPERATORIO
                                │
        ┌───────────────────────┴───────────────────────┐
        ▼                                               ▼
  PREOPERATORIO                                   POSTOPERATORIO
  ├── Historia Clínica                            ├── Control de FV y Drenajes
  ├── Estratificación de Riesgo                   ├── Cronología de la Fiebre
  │   ├── ASA (I - VI)                            │   ├── Precoz (PO1-2): Atelectasia
  │   ├── Lee / RCRI                              │   ├── Temprana (PO3-4): ITU / TVP
  │   ├── Goldman (I - IV)                        │   └── Tardía (PO5-8): ISQ / Absceso
  │   └── Caprini (TVP/TEP)                       ├── Complicaciones Sistémicas
  └── Consentimiento e Inmediato                  └── Clasificación Clavien-Dindo
</div>

<h3>A. PREOPERATORIO Y EVALUACIÓN PREQUIRÚRGICA</h3>

<h4>1. Definición y Objetivos</h4>
<ul>
    <li><strong>Definición:</strong> Es el periodo que transcurre desde el momento en que se decide la intervención quirúrgica hasta el comienzo de la anestesia.</li>
    <li><strong>El mejor predictor de morbi-mortalidad:</strong> La condición clínica preoperatoria del paciente.</li>
    <li><strong>Objetivos Principales:</strong> Reducir morbi-mortalidad, facilitar la recuperación, acelerar la reincorporación laboral/familiar y optimizar costos/eficiencia.</li>
    <li><strong>Multidisciplinaridad:</strong> Es realizado por el cirujano, anestesiólogo, internista, cardiólogo y otros especialistas según la comorbilidad.</li>
</ul>

<h4>2. Componentes de la Evaluación Preoperatoria</h4>
<ol>
    <li>Definir si la cirugía es de <strong>Emergencia</strong> o <strong>Electiva</strong>.</li>
    <li><strong>Historia Clínica Completa:</strong> Antecedentes patológicos, alergias a fármacos/anestésicos, medicación actual, hábitos nocivos (tabaco, alcohol, drogas), posibilidad de embarazo o anemia.</li>
    <li><strong>Exámenes Auxiliares:</strong> Laboratorio e imágenes orientados según historia clínica, riesgo y complejidad de la cirugía (evitar análisis de rutina indiscriminados).</li>
    <li><strong>Planeamiento Quirúrgico:</strong> Estrategia, técnica, logística instrumental (p. ej., ligasure, armónico, radiofrecuencia).</li>
    <li><strong>Evaluación Anestésica (Riesgo Quirúrgico - RQ):</strong> Elección de la técnica anestésica (general, epidural, espinal).</li>
    <li><strong>Soporte Social y Familiar:</strong> Evaluación de cuidados posoperatorios en casa.</li>
    <li><strong>Consentimiento Informado:</strong> Consolidación de la relación médico-paciente-familiar y firma legal.</li>
    <li><strong>Preoperatorio Inmediato:</strong> Marcación de la zona quirúrgica, verificación de suspensión/recepción de fármacos y estado óptimo para SOP.</li>
</ol>

<h4>3. Escalas de Valoración del Riesgo Quirúrgico</h4>

<h5>a) Clasificación del Estado Físico ASA (American Society of Anesthesiologists)</h5>
<table>
    <thead>
        <tr>
            <th>Clasificación</th>
            <th>Descripción</th>
            <th>Ejemplos Clínicos</th>
            <th>Mortalidad</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>ASA I</strong></td>
            <td>Paciente sano, sin enfermedad sistémica.</td>
            <td>Hernia inguinal en paciente joven, mioma uterino en mujer sana.</td>
            <td>0.06 – 0.08%</td>
        </tr>
        <tr>
            <td><strong>ASA II</strong></td>
            <td>Enfermedad sistémica leve o moderada, controlada y no incapacitante.</td>
            <td>Diabetes controlada con dieta, hipertensión moderada, obesidad moderada, edades extremas.</td>
            <td>0.27 – 0.4%</td>
        </tr>
        <tr>
            <td><strong>ASA III</strong></td>
            <td>Enfermedad sistémica grave con limitación funcional definida, pero no incapacitante.</td>
            <td>Cardiopatía severa, DM no compensada con vasculopatía, EPOC, infarto antiguo, obesidad mórbida.</td>
            <td>1.8 – 4.3%</td>
        </tr>
        <tr>
            <td><strong>ASA IV</strong></td>
            <td>Enfermedad sistémica grave e incapacitante, amenaza constante para la vida.</td>
            <td>ICC descompensada, angina persistente, insuficiencia renal o respiratoria severa.</td>
            <td>7.8 – 23%</td>
        </tr>
        <tr>
            <td><strong>ASA V</strong></td>
            <td>Paciente moribundo con expectativa de vida &lt; 24 h con o sin cirugía.</td>
            <td>Ruptura de aneurisma aórtico en shock, TEC severo con edema cerebral, embolismo pulmonar masivo.</td>
            <td>9.4 – 51%</td>
        </tr>
        <tr>
            <td><strong>ASA VI</strong></td>
            <td>Paciente con muerte cerebral diagnosticada (donante de órganos).</td>
            <td>Donante cadavérico.</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td><strong>Sufijo "E"</strong></td>
            <td>Se añade a cualquier categoría si la cirugía es de <strong>emergencia</strong>.</td>
            <td>Apendicitis aguda en ASA I ➔ ASA I-E.</td>
            <td>Mayor riesgo</td>
        </tr>
    </tbody>
</table>

<h5>b) Índice de Riesgo Cardíaco Corregido / Modificado de Lee (RCRI)</h5>
<p>Calcula el riesgo de eventos cardíacos mayor (muerte cardíaca, infarto no fatal, paro cardíaco) a los 30 días post-cirugía no cardíaca.</p>
<ul>
    <li><strong>Variables (1 punto cada una):</strong>
        <ol>
            <li>Historia de enfermedad cardíaca isquémica (angina o IM reciente).</li>
            <li>Historia de insuficiencia cardíaca congestiva.</li>
            <li>Historia de enfermedad cerebrovascular (ACV / AIT).</li>
            <li>Insuficiencia renal crónica (Creatinina sérica &gt; 2 mg/dL o ClCr &lt; 60 mL/min/1.73m²).</li>
            <li>Diabetes mellitus que requiere uso de insulina.</li>
            <li>Cirugía de alto riesgo (intraperitoneal, intratorácica o vascular suprainguinal).</li>
        </ol>
    </li>
</ul>

<table>
    <thead>
        <tr>
            <th>Puntos RCRI</th>
            <th>Riesgo Estimado de Evento Cardíaco</th>
        </tr>
    </thead>
    <tbody>
        <tr><td><strong>0 puntos</strong></td><td>3.9% (muy bajo riesgo, ~0.4–1.0%)</td></tr>
        <tr><td><strong>1 punto</strong></td><td>6.0% (~1.0%)</td></tr>
        <tr><td><strong>2 puntos</strong></td><td>10.1% (~2.4%)</td></tr>
        <tr><td><strong>≥ 3 puntos</strong></td><td>15.0% (&gt; 5.4 – 9.0%)</td></tr>
    </tbody>
</table>

<h5>c) Valoración del Riesgo Cardíaco de Goldman</h5>
<ul>
    <li><strong>Criterios y Puntuación:</strong>
        <ul>
            <li>S3, ritmo de galope o distensión venosa yugular: <strong>11 puntos</strong>.</li>
            <li>Infarto de miocardio reciente (&lt; 6 meses): <strong>10 puntos</strong>.</li>
            <li>Ritmo no sinusal o extrasístoles supraventriculares en ECG: <strong>7 puntos</strong>.</li>
            <li>&gt; 7 extrasístoles ventriculares/minuto: <strong>7 puntos</strong>.</li>
            <li>Edad &gt; 70 años: <strong>5 puntos</strong>.</li>
            <li>Cirugía de urgencia: <strong>4 puntos</strong>.</li>
            <li>Estenosis aórtica severa: <strong>3 puntos</strong>.</li>
            <li>Cirugía intraperitoneal, aórtica o torácica: <strong>3 puntos</strong>.</li>
            <li>Mal estado general (PaO₂ &lt; 60, PaCO₂ &gt; 50, K⁺ &lt; 3, Creatinina &gt; 3 mg/dL, enfermedad hepática crónica): <strong>3 puntos</strong>.</li>
        </ul>
    </li>
    <li><strong>Estratificación por Clases:</strong>
        <ul>
            <li><strong>Clase I (0–5 pts):</strong> Riesgo muy bajo (Muerte cardíaca 0.2%).</li>
            <li><strong>Clase II (6–12 pts):</strong> Riesgo bajo (Muerte cardíaca 2%).</li>
            <li><strong>Clase III (13–25 pts):</strong> Riesgo alto (Muerte cardíaca 11%).</li>
            <li><strong>Clase IV (≥ 26 pts):</strong> Riesgo muy alto (Muerte cardíaca 56%).</li>
        </ul>
    </li>
</ul>

<h5>d) Capacidad Funcional (METs - Equivalente Metabólico)</h5>
<ul>
    <li><strong>&lt; 4 METs (Pobre):</strong> Incapaz de subir dos pisos de escaleras, caminar 100 m a paso ligero o realizar tareas domésticas pesadas. Correlaciona con un incremento sustancial de morbimortalidad.</li>
    <li><strong>≥ 4 METs (Buena / Excelente):</strong> Subir dos tramos de escaleras, correr, realizar deportes o trabajo pesado. Permite proceder a la cirugía con menor riesgo.</li>
</ul>

<h5>e) Estimación del Riesgo Quirúrgico por Tipo de Cirugía (ESC/ESA &amp; ACC/AHA)</h5>
<ul>
    <li><strong>Bajo Riesgo (&lt; 1%):</strong> Cirugía superficial, mama, dental, endocrina (tiroides), ocular, reconstructiva, ginecológica menor, urológica menor.</li>
    <li><strong>Riesgo Intermedio (1 – 5%):</strong> Intraperitoneal (colecistectomía, esplenectomía, hernia hiatal), carótida sintomática/asintomática, angioplastia periférica, cabeza y cuello, ortopedia mayor (cadera/columna), trasplante renal.</li>
    <li><strong>Alto Riesgo (&gt; 5%):</strong> Cirugía aórtica y vascular mayor, revascularización/amputación de miembro inferior, cirugía duodeno-pancreática, resección hepática / vía biliar, esofagectomía, reparación de víscera perforada, cistectomía total, neumonectomía, trasplante pulmonar/hepático.</li>
</ul>

<h3>B. POSTOPERATORIO Y MANEJO DE COMPLICACIONES</h3>

<div class="diagram">
               CRONOLOGÍA DE LA FIEBRE POSTOPERATORIA
 ┌─────────────────────────────────────────────────────────────────┐
 │ PO 1 - 2 (Precoz)     ──► Atelectasia, Estrés Quirúrgico,      │
 │                           Transfusiones, Fármacos.             │
 │ PO 3 - 4 (Temprana)   ──► ITU (Catéter), Flebitis (CVC), TVP.   │
 │ PO 5 - 8 (Tardía)     ──► ISQ, Absceso Intraabdominal,         │
 │                           Dehiscencia de Anastomosis, Neumonía.│
 └─────────────────────────────────────────────────────────────────┘
</div>

<h4>1. Evaluación General y Monitoreo Postoperatorio</h4>
<ul>
    <li><strong>Objetivo:</strong> Detección precoz y corrección de anormalidades antes de que evolucionen a falla multiorgánica o paro.</li>
    <li><strong>Parámetros Fundamentales:</strong> Funciones Vitales (PA, FC, FR, T°, SatO₂), Diuresis y Balance Hídrico estricto, Drenajes y Sondajes, Estado neurológico (Glasgow), Examen abdominal y de herida, Examen de extremidades y deambulación precoz.</li>
</ul>

<h4>2. Criterios de Sepsis-3 y SOFA en el Postoperatorio</h4>
<ul>
    <li><strong>Sepsis:</strong> Disfunción orgánica potencialmente mortal causada por una respuesta desregulada del huésped a la infección.</li>
    <li><strong>qSOFA (Quick SOFA) - Despistaje Rápido en Cama del Paciente (≥ 2 puntos es positivo):</strong>
        <ol>
            <li>Frecuencia Respiratoria ≥ 22 rpm.</li>
            <li>Alteración del estado mental (Glasgow &lt; 15).</li>
            <li>Presión Arterial Sistólica ≤ 100 mmHg.</li>
        </ol>
    </li>
    <li><strong>Escala SOFA (Sequential Organ Failure Assessment):</strong> Evalúa 6 sistemas (Respiratorio PaO₂/FiO₂, Coagulación/Plaquetas, Hígado/Bilirrubinas, Cardiovascular/PAM o vasopresores, SNC/Glasgow, Renal/Creatinina o diuresis). Un incremento de ≥ 2 puntos identifica disfunción orgánica.</li>
</ul>

<h4>3. Diagnóstico Diferencial de la Fiebre Postoperatoria según Cronología</h4>

<h5>a) Fiebre Precoz e Inmediata (PO1 – PO2)</h5>
<ol>
    <li><strong>Atelectasia y Neumonitis:</strong> La causa más frecuente de fiebre en las primeras 48 horas. Anestésicos aumentan viscosidad de secreciones, abolición del reflejo tusígeno y de la actividad ciliar, tapones mucosos con colapso alveolar distal. Clínica: T° habitualmente &lt; 38.9 °C.</li>
    <li><strong>Estrés Quirúrgico / Respuesta Inflamatoria:</strong> Liberación fisiológica de citoquinas proinflamatorias (IL-1, IL-6, TNF-α) inducida por la agresión tisular.</li>
    <li><strong>Reacciones Transfusionales o Farmacológicas:</strong> Incompatibilidad o alergias a antibióticos u otros fármacos.</li>
    <li><strong>Hipertermia Maligna:</strong> Emergencia anestésica rara desencadenada por halogenados (sevoflurano, isoflurano) o succinilcolina. Mutación en receptores RyR1 ➔ liberación masiva de calcio intracelular, rigidez muscular, acidosis láctica, hipercapnia severa, rabdomiólisis e hipertermia extrema.</li>
</ol>

<h5>b) Fiebre Temprana (PO3 – PO4)</h5>
<ol>
    <li><strong>Infección del Tracto Urinario (ITU):</strong> La infección nosocomial más frecuente en cirugía. &gt; 90% asociado a catéter vesical (Foley) colocado por &gt; 48 horas. Etiología: <em>E. coli</em>, <em>Pseudomonas aeruginosa</em>, <em>Enterococcus faecalis</em>, <em>Proteus mirabilis</em>. Fiebre: Puede alcanzar 39.4 – 40 °C.</li>
    <li><strong>Infección de Catéter Venoso Central (CVC) y Flebitis:</strong> Por técnica no aséptica, paso de soluciones hipertónicas o manipulaciones de la vía.</li>
    <li><strong>Trombosis Venosa Profunda (TVP) / Tromboembolismo Pulmonar (TEP):</strong> Signo de Homans positivo, dolor e hinchazón asimétrica en miembros inferiores.</li>
</ol>

<h5>c) Fiebre Tardía (PO5 – PO8)</h5>
<ol>
    <li><strong>Infección del Sitio Quirúrgico (ISQ):</strong> Infección de herida o plano profundo.</li>
    <li><strong>Colección o Absceso Intraabdominal:</strong> Común tras peritonitis o perforación visceral previa.</li>
    <li><strong>Dehiscencia de Anastomosis:</strong> Fuga de contenido intestinal/biliar, peritonitis secundaria y sepsis.</li>
    <li><strong>Neumonía Nosocomial:</strong> Fiebre, infiltrados pulmonares nuevos, secreción purulenta y leucocitosis.</li>
</ol>

<h4>4. Clasificación de la Infección del Sitio Quirúrgico (CDC)</h4>
<p>Se considera ISQ a toda infección relacionada con la intervención que ocurre dentro de los <strong>30 días</strong> postquirúrgicos (o hasta <strong>1 año</strong> si se colocó material protésico/implante).</p>

<table>
    <thead>
        <tr>
            <th>Tipo de ISQ</th>
            <th>Capas Anatómicas Comprometidas</th>
            <th>Criterios Diagnósticos Clave</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Superficial</strong></td>
            <td>Piel y tejido celular subcutáneo únicamente.</td>
            <td>Secreción purulenta por la incisión, aislamiento de microorganismo en cultivo, o presencia de signos inflamatorios localizados (dolor, eritema, calor, tumefacción).</td>
        </tr>
        <tr>
            <td><strong>Profunda</strong></td>
            <td>Tejidos blandos profundos (fascia aponeurótica y músculo).</td>
            <td>Drenaje purulento profundo, dehiscencia espontánea de la sutura o apertura por el cirujano ante fiebre &gt; 38 °C y dolor localizado, o absceso en imagen/reintervención.</td>
        </tr>
        <tr>
            <td><strong>Órgano / Espacio</strong></td>
            <td>Cualquier cavidad u órgano manipulado o abierto durante la cirugía.</td>
            <td>Drenaje purulento a través de dren colocado en cavidad, aislamiento de patógeno en muestra aséptica de cavidad, o absceso intraabdominal/visceral detectado en imágenes (TAC/Eco).</td>
        </tr>
    </tbody>
</table>

<h5>Fascitis Necrotizante</h5>
<ul>
    <li>Infección de partes blandas grave y fulminante.</li>
    <li><strong>Clínica:</strong> Eritema de rápida progresión, induración, vesículas/bulas, piel morada o pálida que pierde turgencia, crepitación (gas en tejidos) y dolor severo desproporcionado a los hallazgos físicos. Típicamente el paciente presenta estado tóxico/séptico.</li>
</ul>

<h4>5. Clasificación de Complicaciones Quirúrgicas de Clavien-Dindo</h4>

<table>
    <thead>
        <tr>
            <th>Grado</th>
            <th>Definición / Criterio de Tratamiento</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Grado I</strong></td>
            <td>Desviación del curso normal que <strong>no requiere</strong> tratamiento farmacológico adicional (salvo antieméticos, antipiréticos, analgésicos, electrolitos) ni intervenciones. Incluye infección de herida superficial tratable en la cama.</td>
        </tr>
        <tr>
            <td><strong>Grado II</strong></td>
            <td>Requiere tratamiento farmacológico con medicamentos diferentes a los del Grado I (p. ej., <strong>antibióticos</strong>, anticoagulantes, hemoderivados o nutrición parenteral total).</td>
        </tr>
        <tr>
            <td><strong>Grado III</strong></td>
            <td>Requiere intervención quirúrgica, endoscópica o de radiología intervencionista.</td>
        </tr>
        <tr>
            <td><em>Grado IIIa</em></td>
            <td>Intervención <strong>sin</strong> anestesia general (local o sedación).</td>
        </tr>
        <tr>
            <td><em>Grado IIIb</em></td>
            <td>Intervención <strong>con</strong> anestesia general.</td>
        </tr>
        <tr>
            <td><strong>Grado IV</strong></td>
            <td>Complicación que amenaza la vida y requiere manejo en UCI / UCIN.</td>
        </tr>
        <tr>
            <td><em>Grado IVa</em></td>
            <td>Disfunción de un solo órgano (incluye diálisis).</td>
        </tr>
        <tr>
            <td><em>Grado IVb</em></td>
            <td>Disfunción multiorgánica.</td>
        </tr>
        <tr>
            <td><strong>Grado V</strong></td>
            <td>Muerte del paciente.</td>
        </tr>
        <tr>
            <td><strong>Sufijo "d"</strong></td>
            <td>Se agrega si el paciente padece una discapacidad (<em>disability</em>) al momento del alta.</td>
        </tr>
    </tbody>
</table>

<h4>6. Complicaciones Específicas por Sistemas</h4>

<h5>a) Complicaciones Respiratorias (Primera causa de muerte postoperatoria: 25%)</h5>
<ul>
    <li><strong>Atelectasia:</strong> La complicación pulmonar más precoz e inespecífica. Prevenible mediante incentivador respiratorio, estimulación de la tos y deambulación precoz.</li>
    <li><strong>Neumonía Nosocomial / AVM:</strong> Fiebre, esputo purulento e infiltrados pulmonares.</li>
    <li><strong>Broncoaspiración / Neumonitis por Aspiración:</strong> Especialmente en emergencias con estómago lleno.</li>
    <li><strong>SDRA (Distrés Respiratorio Agudo):</strong> Requiere ventilación mecánica precoz con PEEP.</li>
</ul>

<h5>b) Complicaciones Digestivas</h5>
<ul>
    <li><strong>Íleo Adinámico (Fisiológico / Paralítico):</strong> Atonía gastrointestinal posquirúrgica normal por 24 a 72 horas. Manejo: NPO, hidratación EV, corrección de electrolitos (hipopotasemia), procinéticos (metoclopramida), deambulación precoz y SNG si hay distensión severa.</li>
    <li><strong>Obstrucción Mecánica:</strong> Por bridas/adherencias, vólvulos, herniación interna o estenosis anastomótica. Suele requerir reoperación.</li>
    <li><strong>Diarrea por <em>Clostridium difficile</em> (Colitis Pseudomembranosa):</strong> Secundaria a antibióticos de amplio espectro (clindamicina, ampicilina, cefalosporinas, fluoroquinolonas). Manejo: Suspender ATB desencadenante; Metronidazol VO (cuadros leves) o Vancomicina VO / Fidaxomicina (cuadros severos).</li>
    <li><strong>Hemorragia Digestiva Alta (Úlcera de Estrés):</strong> Prevenible con inhibidores de bomba de protones (Omeprazol EV).</li>
</ul>

<h5>c) Complicaciones Renales</h5>
<ul>
    <li><strong>Oliguria Postoperatoria:</strong> Volumen urinario &lt; 0.5 mL/kg/h o &lt; 35 mL/h.</li>
    <li><strong>Etiología de la Insuficiencia Renal Aguda (IRA):</strong>
        <ul>
            <li><em>Prerrenal (Más frecuente):</em> Hipovolemia, deshidratación, hemorragia, hipotensión o baja perfusión.</li>
            <li><em>Renal (Parenquimatosa):</em> Necrosis Tubular Aguda (NTA) por isquemia prolongada, fármacos nefrotóxicos (aminoglucósidos, AINEs), mioglobinuria o hemoglobinuria.</li>
            <li><em>Postrenal (Obstructiva):</em> Retención aguda de orina por prostatismo, bloqueo por coágulos o ligadura accidental de uréteres.</li>
        </ul>
    </li>
</ul>

<h5>d) Enfermedad Tromboembólica (TVP / TEP) y Escala de Caprini</h5>
<ul>
    <li><strong>Escala de Caprini:</strong> Estratifica el riesgo tromboembólico.</li>
    <li><strong>Profilaxis:</strong>
        <ul>
            <li><em>Riesgo Muy Bajo (0 pts):</em> Deambulación precoz.</li>
            <li><em>Riesgo Bajo (1–2 pts):</em> Compresión neumática intermitente o medias.</li>
            <li><em>Riesgo Moderado (3–4 pts):</em> Enoxaparina 20 mg/24h SC ± compresión neumática.</li>
            <li><em>Riesgo Alto (≥ 5 pts):</em> Enoxaparina 40 mg/24h SC + compresión neumática intermitente.</li>
        </ul>
    </li>
</ul>

<div class="pepas-box">
    <h3>🎯 🔥 LAS FIJAS / PEPAS DEL EXAMEN (HIGH-YIELD)</h3>
    <ol>
        <li><span class="badge">FIJA 1</span> <strong>Definición de Preoperatorio:</strong> Inicia al decidir la operación y termina al iniciar la anestesia.</li>
        <li><span class="badge">FIJA 2</span> <strong>Mejor predictor de morbi-mortalidad:</strong> La condición clínica preoperatoria del paciente.</li>
        <li><span class="badge">FIJA 3</span> <strong>Puntuación de Lee (RCRI):</strong> A partir de <strong>≥ 3 factores</strong>, el riesgo de evento cardíaco supera el 15%.</li>
        <li><span class="badge">FIJA 4</span> <strong>Criterios de Goldman:</strong> El hallazgo físico con mayor puntaje es el <strong>S3 / Ritmo de galope o distensión venosa yugular (11 puntos)</strong>. El IMA reciente &lt; 6 meses otorga 10 puntos.</li>
        <li><span class="badge">FIJA 5</span> <strong>Capacidad Funcional:</strong> Punto de corte crítico = <strong>4 METs</strong> (subir 2 tramos de escaleras). &lt; 4 METs incrementa sustancialmente el riesgo.</li>
        <li><span class="badge">FIJA 6</span> <strong>Las 5 "W" de la Fiebre:</strong> Wind (Atelectasia PO1-2), Water (ITU PO3-5), Wound (ISQ PO5-7), Walking (TVP PO5-7), Wonder drugs (Fármacos).</li>
        <li><span class="badge">FIJA 7</span> <strong>Tiempo Límite ISQ (CDC):</strong> Hasta <strong>30 días</strong> sin prótesis, hasta <strong>1 año</strong> con prótesis o implante.</li>
        <li><span class="badge">FIJA 8</span> <strong>Hipertermia Maligna:</strong> Causa: Succinilcolina / Sevoflurano en mutación de receptor <strong>RyR1</strong>. Antídoto: <strong>Dantroleno sódico</strong>.</li>
        <li><span class="badge">FIJA 9</span> <strong>Clavien-Dindo IIIa vs IIIb:</strong> Reintervención sin anestesia general (IIIa) vs con anestesia general (IIIb). Fármacos como antibióticos son Grado II.</li>
        <li><span class="badge">FIJA 10</span> <strong>Íleo Fisiológico:</strong> Dura 24 a 72 horas. Si persiste con vómitos y ruidos metálicos pasadas las 72h ➔ sospechar obstrucción mecánica.</li>
    </ol>
</div>

<h2>4. 🧠 Sección Active Recall y Banqueo</h2>

<h3>A. Banqueo Tipo Examen (10 Preguntas Exigentes)</h3>

<div class="question-card">
    <div class="question-title">Pregunta 1</div>
    <p>Varón de 68 años con antecedente de infarto agudo de miocardio hace 4 meses y diabetes mellitus tipo 2 insulinodependiente. Es programado para una colectomía subtotal electiva. Al examen físico se aprecia capacidad funcional de 3 METs. ¿En qué clase de Goldman y puntaje RCRI de Lee se clasifica respectivamente?</p>
    <ul class="options">
        <li>A) Goldman I / RCRI 1 punto</li>
        <li>B) Goldman III / RCRI 3 puntos</li>
        <li>C) Goldman IV / RCRI 4 puntos</li>
        <li>D) Goldman II / RCRI 2 puntos</li>
        <li>E) Goldman III / RCRI 2 puntos</li>
    </ul>
    <div class="answer-box">
        <strong>Respuesta Correcta: B</strong><br>
        <em>Justificación:</em> Goldman: IMA &lt; 6 meses (10 pts) + cirugía intraperitoneal (3 pts) = 13 pts ➔ Clase III (riesgo alto). RCRI de Lee: Cardiopatía isquémica (1 pt) + DM con insulina (1 pt) + cirugía de alto riesgo (1 pt) = 3 puntos.
    </div>
</div>

<div class="question-card">
    <div class="question-title">Pregunta 2</div>
    <p>Paciente mujer de 45 años en su 2° día postoperatorio de colecistectomía laparoscópica presenta un pico febril de 38.4 °C, taquipnea ligera y disminución del murmullo vesicular en base pulmonar derecha. No presenta síntomas urinarios y la herida está limpia. ¿Cuál es el diagnóstico y manejo más adecuado?</p>
    <ul class="options">
        <li>A) Infección del sitio quirúrgico / Abrir puntos de sutura</li>
        <li>B) Atelectasia / Incentivador respiratorio y deambulación precoz</li>
        <li>C) Neumonía nosocomial / Iniciar Ceftriaxona EV</li>
        <li>D) Infección urinaria / Solicitud de urocultivo</li>
        <li>E) Fuga biliar / Tomografía de abdomen</li>
    </ul>
    <div class="answer-box">
        <strong>Respuesta Correcta: B</strong><br>
        <em>Justificación:</em> La causa más frecuente de fiebre precoz (PO1-2) es la atelectasia. El pilar del tratamiento es el espirómetro de incentivo y la movilidad precoz.
    </div>
</div>

<div class="question-card">
    <div class="question-title">Pregunta 3</div>
    <p>En relación a la Infección del Sitio Quirúrgico (ISQ) según los criterios de la CDC, señale la afirmación CORRECTA:</p>
    <ul class="options">
        <li>A) La ISQ superficial compromete piel, tejido subcutáneo y fascia aponeurótica.</li>
        <li>B) El periodo de vigilancia postoperatoria para definir ISQ sin implante es de 60 días.</li>
        <li>C) La presencia de secreción purulenta por un dren intraabdominal se clasifica como ISQ Profunda.</li>
        <li>D) El aislamiento de microorganismos en un cultivo obtenido asépticamente de la cavidad peritoneal se clasifica como ISQ Órgano/Espacio.</li>
        <li>E) Toda infección de herida requiere apertura inmediata e inicio de vancomicina sistémica.</li>
    </ul>
    <div class="answer-box">
        <strong>Respuesta Correcta: D</strong><br>
        <em>Justificación:</em> La ISQ de Órgano/Espacio afecta cualquier cavidad u órgano manipulado y se confirma por drenaje purulento del dren intracavitario o aislamiento en muestra aséptica de dicha cavidad.
    </div>
</div>

<div class="question-card">
    <div class="question-title">Pregunta 4</div>
    <p>Un paciente de 52 años sometido a una gastrectomía radical por cáncer gástrico presenta en el PO6 dehiscencia parcial de la anastomosis gastro-yeyunal demostrada por tomografía con colección líquida. Es llevado a sala de operaciones bajo anestesia general para lavado cavitario y colocación de drenes. Según la clasificación de Clavien-Dindo, ¿cómo se gradúa esta complicación?</p>
    <ul class="options">
        <li>A) Grado II</li>
        <li>B) Grado IIIa</li>
        <li>C) Grado IIIb</li>
        <li>D) Grado IVa</li>
        <li>E) Grado IVb</li>
    </ul>
    <div class="answer-box">
        <strong>Respuesta Correcta: C</strong><br>
        <em>Justificación:</em> Al requerir reintervención quirúrgica en quirófano bajo anestesia general, corresponde exactamente a Clavien-Dindo Grado IIIb.
    </div>
</div>

<div class="question-card">
    <div class="question-title">Pregunta 5</div>
    <p>¿Cuál de los siguientes hallazgos exploratorios tiene el MAYOR puntaje individual en la escala de riesgo cardíaco de Goldman?</p>
    <ul class="options">
        <li>A) Infarto de miocardio reciente (&lt; 6 meses)</li>
        <li>B) Edad mayor a 70 años</li>
        <li>C) Presencia de tercer ruido (S3) o ingurgitación yugular</li>
        <li>D) Estenosis aórtica severa</li>
        <li>E) Cirugía de emergencia</li>
    </ul>
    <div class="answer-box">
        <strong>Respuesta Correcta: C</strong><br>
        <em>Justificación:</em> El S3 / ritmo de galope o distensión venosa yugular otorga 11 puntos (el puntaje individual más alto de la escala). El IMA reciente otorga 10 puntos.
    </div>
</div>

<div class="question-card">
    <div class="question-title">Pregunta 6</div>
    <p>Paciente varón de 70 años con antecedente de HBP en su PO1 presenta diuresis de 180 mL en 12 horas. Creatinina se eleva a 1.8 mg/dL. Al examen: dolor suprapúbico y matidez. ¿Cuál es el tipo de IRA y el primer paso en su manejo?</p>
    <ul class="options">
        <li>A) Prerrenal / Administrar bolo de NaCl 0.9% 1000 mL</li>
        <li>B) Renal parenquimatosa / Iniciar Furosemida</li>
        <li>C) Postrenal / Colocación de sonda vesical</li>
        <li>D) Prerrenal / Iniciar Dobutamina</li>
        <li>E) Renal parenquimatosa / Hemodiálisis urgente</li>
    </ul>
    <div class="answer-box">
        <strong>Respuesta Correcta: C</strong><br>
        <em>Justificación:</em> El globo vesical (retención aguda de orina) ocasiona IRA Postrenal. La descompresión mediante sonda vesical resuelve el cuadro.
    </div>
</div>

<div class="question-card">
    <div class="question-title">Pregunta 7</div>
    <p>Durante una cirugía con sevoflurano y succinilcolina, el paciente presenta rigidez muscular generalizada, EtCO₂ elevado y temperatura corporal de 40 °C. ¿Cuál es la fisiopatología subyacente?</p>
    <ul class="options">
        <li>A) Reacción anafiláctica severa por histamina</li>
        <li>B) Mutación en el receptor RyR1 con liberación masiva de Calcio del retículo sarcoplásmico</li>
        <li>C) Liberación excesiva de catecolaminas por feocromocitoma</li>
        <li>D) Tormenta tiroidea desencadenada por estrés</li>
        <li>E) Sepsis severa por bacteriemia masiva</li>
    </ul>
    <div class="answer-box">
        <strong>Respuesta Correcta: B</strong><br>
        <em>Justificación:</em> Hipertermia Maligna por mutación del receptor RyR1 desencadenada por anestésicos halogenados o succinilcolina.
    </div>
</div>

<div class="question-card">
    <div class="question-title">Pregunta 8</div>
    <p>¿Cuál es la escala recomendada para evaluar el riesgo de Trombosis Venosa Profunda (TVP) en pacientes quirúrgicos y determinar la profilaxis con Enoxaparina?</p>
    <ul class="options">
        <li>A) Escala de Glasgow</li>
        <li>B) Escala de Caprini</li>
        <li>C) Criterios de qSOFA</li>
        <li>D) Clasificación de Clavien-Dindo</li>
        <li>E) Índice de Lee</li>
    </ul>
    <div class="answer-box">
        <strong>Respuesta Correcta: B</strong><br>
        <em>Justificación:</em> La Escala de Caprini estratifica el riesgo de tromboembolismo venoso en pacientes quirúrgicos.
    </div>
</div>

<div class="question-card">
    <div class="question-title">Pregunta 9</div>
    <p>Paciente operado en el PO5 presenta fiebre de 39 °C, deposiciones líquidas abundantes y leucocitosis tras recibir Clindamicina. ¿Cuál es el agente etiológico y tratamiento oral de elección en casos severos?</p>
    <ul class="options">
        <li>A) <em>Escherichia coli</em> / Ciprofloxacino</li>
        <li>B) <em>Clostridium difficile</em> / Vancomicina VO</li>
        <li>C) <em>Entamoeba histolytica</em> / Metronidazol EV</li>
        <li>D) <em>Pseudomonas aeruginosa</em> / Piperacilina-Tazobactam</li>
        <li>E) <em>Staphylococcus aureus</em> / Oxacilina</li>
    </ul>
    <div class="answer-box">
        <strong>Respuesta Correcta: B</strong><br>
        <em>Justificación:</em> La colitis pseudomembranosa por <em>C. difficile</em> secundaria a antibióticos se trata en formas severas con Vancomicina oral.
    </div>
</div>

<div class="question-card">
    <div class="question-title">Pregunta 10</div>
    <p>De acuerdo a los criterios de quick SOFA (qSOFA) para la identificación rápida de sepsis postoperatoria, ¿cuál de los siguientes parámetros NO forma parte de la escala?</p>
    <ul class="options">
        <li>A) Frecuencia Respiratoria ≥ 22 rpm</li>
        <li>B) Presión Arterial Sistólica ≤ 100 mmHg</li>
        <li>C) Alteración del nivel de conciencia (Glasgow &lt; 15)</li>
        <li>D) Recuento de leucocitos &gt; 12,000 / μL</li>
        <li>E) Todos forman parte de qSOFA</li>
    </ul>
    <div class="answer-box">
        <strong>Respuesta Correcta: D</strong><br>
        <em>Justificación:</em> El qSOFA evalúa únicamente 3 parámetros clínicos: FR ≥ 22, PAS ≤ 100 mmHg y Glasgow &lt; 15.
    </div>
</div>

<h3>B. Flashcards de Repaso Activo (Active Recall)</h3>

<div class="flashcard-grid">
    <div class="flashcard">
        <div class="flashcard-q">P: ¿Qué es el periodo preoperatorio y cuál es su límite final?</div>
        <div class="flashcard-a">R: Es el tiempo desde que se decide la operación hasta el inicio de la anestesia.</div>
    </div>
    <div class="flashcard">
        <div class="flashcard-q">P: ¿Cuál es el mejor predictor de morbi-mortalidad perioperatoria?</div>
        <div class="flashcard-a">R: La condición clínica preoperatoria del paciente.</div>
    </div>
    <div class="flashcard">
        <div class="flashcard-q">P: Paciente con HTN y DM controlada con dieta sin limitación. ¿Qué categoría ASA le corresponde?</div>
        <div class="flashcard-a">R: ASA II.</div>
    </div>
    <div class="flashcard">
        <div class="flashcard-q">P: ¿Cuáles son las 5 variables del Índice de Riesgo Cardíaco Corregido de Lee (RCRI)?</div>
        <div class="flashcard-a">R: 1. Enfermedad cardíaca isquémica. 2. Insuficiencia cardíaca. 3. Enfermedad cerebrovascular. 4. IRC (Creatinina &gt; 2 mg/dL). 5. DM con insulina (más el tipo de cirugía de alto riesgo).</div>
    </div>
    <div class="flashcard">
        <div class="flashcard-q">P: Causa más frecuente de fiebre en el PO1 - PO2 y su manejo.</div>
        <div class="flashcard-a">R: Atelectasia. Manejo: Espirómetro de incentivo y deambulación precoz.</div>
    </div>
    <div class="flashcard">
        <div class="flashcard-q">P: Causa de fiebre postoperatoria en PO3 - PO4 frecuentemente asociada a catéteres colocados por &gt; 48 horas.</div>
        <div class="flashcard-a">R: Infección del Tracto Urinario (ITU) por sonda Foley.</div>
    </div>
    <div class="flashcard">
        <div class="flashcard-q">P: Definición temporal de Infección del Sitio Quirúrgico (ISQ).</div>
        <div class="flashcard-a">R: Infección dentro de los 30 días post-cirugía o hasta 1 año si se colocó material extraño/prótesis.</div>
    </div>
    <div class="flashcard">
        <div class="flashcard-q">P: Diferencia entre Clavien-Dindo Grado IIIa y IIIb.</div>
        <div class="flashcard-a">R: Grado IIIa requiere intervención SIN anestesia general. Grado IIIb requiere intervención CON anestesia general.</div>
    </div>
    <div class="flashcard">
        <div class="flashcard-q">P: Etiología y tratamiento oral severo de la colitis pseudomembranosa post-antibióticos.</div>
        <div class="flashcard-a">R: Causa: Clostridium difficile. Tratamiento severo: Vancomicina vía oral.</div>
    </div>
    <div class="flashcard">
        <div class="flashcard-q">P: ¿Cuáles son los 3 parámetros de la escala qSOFA?</div>
        <div class="flashcard-a">R: 1. Frecuencia Respiratoria ≥ 22 rpm. 2. Alteración del sensorio (Glasgow &lt; 15). 3. Presión Arterial Sistólica ≤ 100 mmHg.</div>
    </div>
</div>

</body>
</html>

# Generar el PDF
output_filename = "Guia_Maestra_Pre_y_Postoperatorio.pdf"
HTML(string=html_content).write_pdf(output_filename)
print(f"¡PDF generado con éxito como '{output_filename}'!")
