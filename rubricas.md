---
layout: default
title: Rúbricas SOLO
---

<h1>Rúbricas de evaluación — estilo SOLO</h1>
<p class="lede">Structure of Observed Learning Outcomes (Biggs &amp; Collis, 1982) — una rúbrica por entrega, con indicador diferenciado Cuant./Cual.</p>

<div class="card">
<p>Las tres rúbricas comparten la misma taxonomía de niveles, lo que permite calificar con el mismo rasero de exigencia proyectos cuantitativos y cualitativos. Cada criterio se describe con un <strong>indicador diferenciado</strong> (Cuant./Cual.) y se valora según el nivel de complejidad estructural demostrado en el trabajo entregado, no según una lista de tareas cumplidas.</p>
<div class="solo-scale-4">
  <div><span>1</span>Inicial<br><span style="font-size:9.5px; font-weight:400;">Pre + Uniestructural</span></div>
  <div><span>2</span>En desarrollo<br><span style="font-size:9.5px; font-weight:400;">Multiestructural</span></div>
  <div><span>3</span>Logrado<br><span style="font-size:9.5px; font-weight:400;">Relacional</span></div>
  <div><span>4</span>Destacado<br><span style="font-size:9.5px; font-weight:400;">Abstracto ampliado</span></div>
</div>
<p style="margin:10px 0 0; font-size:13px; color:var(--muted);">Un estudiante de metodología mixta es evaluado con los indicadores de ambas rutas en los criterios que correspondan a cada componente de su estudio.</p>
</div>

<div class="grading-panel" data-site-key="seminario3">
  <div class="gp-row">
    <label class="gp-label" for="gp-name">👤 Estudiante / grupo</label>
    <input type="text" id="gp-name" class="gp-input" placeholder="Nombre del estudiante o grupo">
  </div>
  <div class="gp-scores">
    <div class="gp-score-item"><span class="gp-score-label">Entrega 1 (30%)</span><span class="gp-score-value" id="gp-score-0">—</span></div>
    <div class="gp-score-item"><span class="gp-score-label">Entrega 2 (30%)</span><span class="gp-score-value" id="gp-score-1">—</span></div>
    <div class="gp-score-item"><span class="gp-score-label">Entrega 3 (40%)</span><span class="gp-score-value" id="gp-score-2">—</span></div>
    <div class="gp-score-item gp-final"><span class="gp-score-label">Nota final</span><span class="gp-score-value" id="gp-final">—</span></div>
  </div>
  <div class="gp-actions">
    <button type="button" id="gp-save" class="gp-btn gp-btn-primary">💾 Guardar y calificar siguiente</button>
    <button type="button" id="gp-reset" class="gp-btn">↺ Limpiar selección</button>
  </div>
</div>
<div class="gp-toast" id="gp-toast"></div>

<div class="rubric-activity">
<h2>1. Entrega 1 · Diseño y validación del instrumento — Corte 1 (30%) · Sesión 3</h2>
<div class="weight-bar">
  <div class="w1" style="width:20%;">20%</div>
  <div class="w2" style="width:30%;">30%</div>
  <div class="w3" style="width:25%;">25%</div>
  <div class="w4" style="width:15%;">15%</div>
  <div class="w5" style="width:10%;">10%</div>
</div>
<div class="weight-legend">
  <span><span class="dot" style="background:var(--teal-500);"></span>Coherencia con la pregunta</span>
  <span><span class="dot" style="background:var(--teal-700);"></span>Validación del instrumento</span>
  <span><span class="dot" style="background:var(--amber);"></span>Prueba piloto y ajustes</span>
  <span><span class="dot" style="background:var(--navy-900);"></span>Consideraciones éticas</span>
  <span><span class="dot" style="background:#5eb3a8;"></span>Calidad del documento</span>
</div>
</div>

<div class="irubric" data-entrega="0" data-weight="30">
  <div class="irc" data-weight="20">
    <div class="irc-head"><span class="irc-name">Coherencia con la pregunta de investigación</span><span class="irc-weight">20%</span></div>
    <div class="irc-sub">Cuant.: el instrumento opera las variables definidas en el problema. Cual.: el guion/guía captura las categorías/ejes de indagación del problema.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c0" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">Instrumento desconectado de la pregunta.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c0" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Cubre variables/categorías de forma parcial o listada.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c0" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Todas las variables/categorías están operacionalizadas y conectadas.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c0" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Justifica y argumenta cada decisión de diseño frente a la literatura.</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="30">
    <div class="irc-head"><span class="irc-name">Validación del instrumento</span><span class="irc-weight">30%</span></div>
    <div class="irc-sub">Cuant.: aplica CVI/CVR con jueces expertos y/o checklist COSMIN. Cual.: aplica checklist COREQ o CASP en el diseño.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c1" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">No se valida el instrumento.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c1" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Se aplica el checklist parcialmente.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c1" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Checklist aplicado completo, con ajustes documentados.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c1" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Analiza críticamente los resultados de la validación y sus implicaciones.</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="25">
    <div class="irc-head"><span class="irc-name">Prueba piloto y ajustes</span><span class="irc-weight">25%</span></div>
    <div class="irc-sub">Cuant.: ejecuta piloto y calcula fiabilidad preliminar (ej. alfa de Cronbach). Cual.: realiza entrevista/observación piloto y ajusta el guion.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c2" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">No hay piloto.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c2" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Piloto ejecutado sin ajustes documentados.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c2" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Piloto ejecutado con ajustes justificados.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c2" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Compara versiones pre/post piloto y argumenta la mejora.</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="15">
    <div class="irc-head"><span class="irc-name">Consideraciones éticas</span><span class="irc-weight">15%</span></div>
    <div class="irc-sub">Cuant.: consentimiento informado y manejo de datos, según aplique. Cual.: consentimiento informado, anonimización y manejo de datos sensibles.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c3" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">No se documentan.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c3" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Se mencionan de forma genérica.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c3" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Se documentan de forma específica al proyecto.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c3" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Anticipa riesgos éticos particulares del contexto/población.</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="10">
    <div class="irc-head"><span class="irc-name">Calidad del documento</span><span class="irc-weight">10%</span></div>
    <div class="irc-sub">Cuant.: describe el instrumento según STROBE. Cual.: describe el instrumento según COREQ/SRQR.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c4" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">Documento incompleto o poco claro.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c4" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Documento claro pero sin seguir estándar de reporte.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c4" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Documento claro y alineado al estándar correspondiente.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e0-c4" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Documento listo para anexo de protocolo o publicación.</span>
      </label>
    </div>
  </div>
</div>
<div class="irc-result" id="irubric-result-0">Sin calificar aún</div>

<div class="rubric-activity">
<h2>2. Entrega 2 · Procesamiento y primer análisis de datos — Corte 2 (30%) · Sesión 5</h2>
<div class="weight-bar">
  <div class="w1" style="width:20%;">20%</div>
  <div class="w2" style="width:25%;">25%</div>
  <div class="w3" style="width:30%;">30%</div>
  <div class="w4" style="width:15%;">15%</div>
  <div class="w5" style="width:10%;">10%</div>
</div>
<div class="weight-legend">
  <span><span class="dot" style="background:var(--teal-500);"></span>Organización y limpieza de datos</span>
  <span><span class="dot" style="background:var(--teal-700);"></span>Uso de software</span>
  <span><span class="dot" style="background:var(--amber);"></span>Rigor del análisis</span>
  <span><span class="dot" style="background:var(--navy-900);"></span>Documentación del proceso</span>
  <span><span class="dot" style="background:#5eb3a8;"></span>Gestión autónoma del avance</span>
</div>
</div>

<div class="irubric" data-entrega="1" data-weight="30">
  <div class="irc" data-weight="20">
    <div class="irc-head"><span class="irc-name">Organización y limpieza de datos</span><span class="irc-weight">20%</span></div>
    <div class="irc-sub">Cuant.: base de datos depurada y variables codificadas. Cual.: transcripciones completas y corpus documental organizado.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c0" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">Datos crudos, sin organizar.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c0" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Datos organizados parcialmente.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c0" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Base/corpus limpio, documentado y listo para analizar.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c0" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Incluye control de calidad del dato (doble verificación, auditoría de transcripción).</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="25">
    <div class="irc-head"><span class="irc-name">Uso de software</span><span class="irc-weight">25%</span></div>
    <div class="irc-sub">Cuant.: manejo de SPSS/R/Jamovi para análisis descriptivo/inferencial. Cual.: manejo de Atlas.ti/NVivo/Taguette para primer ciclo de codificación.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c1" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">No usa el software o lo usa de forma incorrecta.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c1" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Usa el software para tareas básicas.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c1" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Usa el software de forma pertinente al diseño del proyecto.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c1" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Optimiza el flujo de trabajo (sintaxis, macros, libros de códigos reutilizables).</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="30">
    <div class="irc-head"><span class="irc-name">Rigor del análisis</span><span class="irc-weight">30%</span></div>
    <div class="irc-sub">Cuant.: selección adecuada de pruebas estadísticas según tipo de variable y diseño. Cual.: coherencia entre tipo de codificación (contenido vs. discurso) y pregunta de investigación.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c2" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">Análisis no pertinente al diseño.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c2" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Análisis pertinente pero con errores técnicos.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c2" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Análisis correctamente seleccionado y ejecutado.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c2" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Contrasta o triangula más de una técnica de análisis.</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="15">
    <div class="irc-head"><span class="irc-name">Documentación del proceso</span><span class="irc-weight">15%</span></div>
    <div class="irc-sub">Cuant.: bitácora de decisiones de análisis. Cual.: diario metodológico de decisiones de codificación.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c3" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">No hay registro del proceso.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c3" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Registro incompleto.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c3" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Registro completo y trazable.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c3" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">El registro permite replicar el análisis paso a paso.</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="10">
    <div class="irc-head"><span class="irc-name">Gestión autónoma del avance</span><span class="irc-weight">10%</span></div>
    <div class="irc-sub">Cuant.: cumplimiento del cronograma de análisis propio. Cual.: cumplimiento del cronograma de codificación propio.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c4" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">Avance nulo o muy por debajo de lo planeado.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c4" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Avance parcial frente a lo planeado.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c4" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Avance conforme a lo planeado.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e1-c4" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Avance adelantado con espacio para profundizar.</span>
      </label>
    </div>
  </div>
</div>
<div class="irc-result" id="irubric-result-1">Sin calificar aún</div>

<div class="rubric-activity">
<h2>3. Entrega 3 · Interpretación de resultados y construcción de hallazgos — Corte 3 (40%) · Sesión 6</h2>
<div class="weight-bar">
  <div class="w1" style="width:30%;">30%</div>
  <div class="w2" style="width:20%;">20%</div>
  <div class="w3" style="width:20%;">20%</div>
  <div class="w4" style="width:15%;">15%</div>
  <div class="w5" style="width:15%;">15%</div>
</div>
<div class="weight-legend">
  <span><span class="dot" style="background:var(--teal-500);"></span>Interpretación y pregunta de investigación</span>
  <span><span class="dot" style="background:var(--teal-700);"></span>Contextualización de hallazgos</span>
  <span><span class="dot" style="background:var(--amber);"></span>Comunicación de resultados</span>
  <span><span class="dot" style="background:var(--navy-900);"></span>Diálogo interparadigmático</span>
  <span><span class="dot" style="background:#5eb3a8;"></span>Proyección al documento de grado</span>
</div>
</div>

<div class="irubric" data-entrega="2" data-weight="40">
  <div class="irc" data-weight="30">
    <div class="irc-head"><span class="irc-name">Interpretación en relación con la pregunta</span><span class="irc-weight">30%</span></div>
    <div class="irc-sub">Cuant.: interpreta significancia estadística y relevancia práctica/clínica. Cual.: construye categorías/patrones y los relaciona con el problema.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c0" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">Describe datos sin interpretarlos.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c0" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Interpreta resultados de forma aislada, sin conectar con la pregunta.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c0" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Interpreta y conecta explícitamente con la pregunta de investigación.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c0" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Discute alcances y límites de la interpretación propuesta.</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="20">
    <div class="irc-head"><span class="irc-name">Contextualización de los hallazgos</span><span class="irc-weight">20%</span></div>
    <div class="irc-sub">Cuant. y Cual.: relaciona resultados/hallazgos con literatura y contexto de salud pública.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c1" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">No hay referencia a literatura o contexto.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c1" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Referencia genérica a literatura.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c1" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Contextualización específica y pertinente.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c1" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Identifica aportes o vacíos frente al estado del arte.</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="20">
    <div class="irc-head"><span class="irc-name">Comunicación de resultados</span><span class="irc-weight">20%</span></div>
    <div class="irc-sub">Cuant.: claridad de tablas y gráficos estadísticos. Cual.: claridad de matrices o mapas de códigos/categorías.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c2" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">Comunicación confusa o incompleta.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c2" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Comunicación clara pero básica.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c2" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Comunicación clara, completa y bien diseñada visualmente.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c2" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Comunicación de calidad para publicación o presentación externa.</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="15">
    <div class="irc-head"><span class="irc-name">Diálogo interparadigmático — sesión 6</span><span class="irc-weight">15%</span></div>
    <div class="irc-sub">Cuant.: explica sus hallazgos a compañeros cualitativos y comprende los de ellos. Cual.: explica sus hallazgos a compañeros cuantitativos y comprende los de ellos.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c3" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">No participa o no logra explicarse a la otra audiencia.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c3" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Explica su proyecto pero con dificultad para el otro enfoque.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c3" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Comunica con claridad a una audiencia del otro paradigma.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c3" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Establece puentes o complementariedades entre ambos enfoques.</span>
      </label>
    </div>
  </div>
  <div class="irc" data-weight="15">
    <div class="irc-head"><span class="irc-name">Proyección hacia el documento de grado</span><span class="irc-weight">15%</span></div>
    <div class="irc-sub">Cuant. y Cual.: identifica implicaciones para la discusión y conclusiones de la tesis.</div>
    <div class="irc-levels">
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c4" data-level="1" data-score="1.25">
        <span class="irc-opt-top">1 · Inicial</span>
        <span class="irc-opt-desc">No proyecta implicaciones.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c4" data-level="2" data-score="2.5">
        <span class="irc-opt-top">2 · En desarrollo</span>
        <span class="irc-opt-desc">Proyecta implicaciones de forma general.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c4" data-level="3" data-score="3.75">
        <span class="irc-opt-top">3 · Logrado</span>
        <span class="irc-opt-desc">Proyecta implicaciones específicas y aplicables.</span>
      </label>
      <label class="irc-opt">
        <input type="radio" name="seminario3-e2-c4" data-level="4" data-score="5.0">
        <span class="irc-opt-top">4 · Destacado</span>
        <span class="irc-opt-desc">Plantea una hoja de ruta clara para el cierre del trabajo de grado.</span>
      </label>
    </div>
  </div>
</div>
<div class="irc-result" id="irubric-result-2">Sin calificar aún</div>

<div class="gp-savedlist-wrap">
<h2>📋 Calificaciones guardadas en este navegador</h2>
<p class="muted" style="font-size:13px; margin-top:-6px;">Se guardan localmente en este navegador (no se suben a ningún servidor). Usa "Copiar todo" para pegarlas en Excel u otra planilla.</p>
<div class="gp-savedlist-actions">
  <button type="button" id="gp-copy" class="gp-btn">📋 Copiar todo (para Excel)</button>
  <button type="button" id="gp-clearall" class="gp-btn gp-btn-danger">🗑 Borrar todas</button>
</div>
<div class="gp-table-wrap">
<table class="gp-table">
<thead><tr><th>Estudiante</th><th>Entrega 1 (30%)</th><th>Entrega 2 (30%)</th><th>Entrega 3 (40%)</th><th>Nota final</th><th></th></tr></thead>
<tbody id="gp-table-body"></tbody>
</table>
</div>
</div>

<div class="criteria-block">
<h3>🎯 Criterios transversales</h3>
<dl>
  <dt>Nivel SOLO, no checklist de tareas:</dt> <dd>en cada criterio se valora cómo se integra y conecta el trabajo con la pregunta de investigación, no si se completaron pasos aislados.</dd>
  <dt>Metodología mixta:</dt> <dd>se evalúa con los indicadores de ambas rutas en los criterios que correspondan a cada componente del estudio.</dd>
</dl>
</div>
