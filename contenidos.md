---
layout: default
title: Ruta de sesiones
---

<h1>Ruta de sesiones</h1>
<p class="lede">6 encuentros · {{ site.data.curso.horario_general }} · {{ site.data.curso.salon }}</p>

<div class="callout">
  Las sesiones 1 y 6 son <strong>plenarias completas</strong> (diagnóstico inicial e integración final). Las sesiones 2 a 5 combinan un bloque plenario breve con <strong>rutas paralelas</strong> — cuantitativa y cualitativa — donde cada estudiante trabaja sobre su propio proyecto.
</div>

<div class="timeline-strip">
  <a href="#sesion-1"><span class="tl-icon">1</span><span class="tl-label">Diagnóstico<br>de proyectos</span></a>
  <a href="#sesion-2"><span class="tl-icon">2</span><span class="tl-label">Validación de<br>instrumentos</span></a>
  <a href="#sesion-3" class="highlight"><span class="tl-icon">3</span><span class="tl-label">Entrega 1<br>🎯</span></a>
  <a href="#sesion-4"><span class="tl-icon">4</span><span class="tl-label">Análisis<br>en curso</span></a>
  <a href="#sesion-5" class="highlight"><span class="tl-icon">5</span><span class="tl-label">Entrega 2<br>🎯</span></a>
  <a href="#sesion-6" class="highlight"><span class="tl-icon">6</span><span class="tl-label">Entrega 3<br>🎯</span></a>
</div>

{% for s in site.data.curso.sesiones %}
<div class="unit-card" id="sesion-{{ s.numero }}">
  <h3>Sesión {{ s.numero }} · {{ s.dia }} {{ s.fecha }}</h3>

  {% case s.numero %}

  {% when 1 %}
  <div class="route-col plenary">
    <h4>🟢 Bloque plenario completo</h4>
    <p>Encuadre del seminario. Diagnóstico y tipificación de proyectos (cuantitativo / cualitativo / mixto). Estándares internacionales de reporte (STROBE, COREQ/SRQR) y ética de la recolección de datos.</p>
    <p style="margin-top:8px;"><strong>Actividad común:</strong> ficha de proyecto — tipo de estudio, pregunta, población, técnica de recolección propuesta. Base para autodiagnóstico con la herramienta MMAT (ver <a href="{{ '/herramientas/caja-herramientas.html' | relative_url }}">Caja de herramientas</a>).</p>
  </div>

  {% when 2 %}
  <div class="route-col plenary">
    <h4>🟢 Bloque plenario breve</h4>
    <p>Validez y confiabilidad de instrumentos.</p>
  </div>
  <div class="dual-route">
    <div class="route-col quant">
      <h4>Ruta cuantitativa</h4>
      <p><strong>1.1</strong> Técnicas de recolección cuantitativa. <strong>1.2</strong> Validación de encuestas y prueba piloto — diseño del instrumento propio, uso de CVI/COSMIN.</p>
    </div>
    <div class="route-col qual">
      <h4>Ruta cualitativa</h4>
      <p><strong>2.1</strong> Entrevista semiestructurada y a profundidad — diseño de guion propio, checklist COREQ/CASP.</p>
    </div>
  </div>

  {% when 3 %}
  <div class="dual-route">
    <div class="route-col quant">
      <h4>Ruta cuantitativa</h4>
      <p><strong>1.2 (cont.)</strong> Ajuste post-piloto. <strong>1.3</strong> Análisis descriptivo e inferencial — fundamentos aplicados a su diseño.</p>
    </div>
    <div class="route-col qual">
      <h4>Ruta cualitativa</h4>
      <p><strong>2.2</strong> Observación participante: guías de observación y diario de campo.</p>
    </div>
  </div>
  <div class="update-block">
    <h3>🎯 Entrega 1 — Diseño y validación del instrumento de recolección (30%)</h3>
    <p style="margin-bottom:0;">Se presenta al cierre de esta sesión. Corresponde a los temas 1.1-1.2 (cuantitativa) y 2.1-2.4 (cualitativa). Ver <a href="{{ '/proyecto.html' | relative_url }}">Entregas</a> y <a href="{{ '/rubricas.html' | relative_url }}">Rúbrica SOLO — Entrega 1</a>.</p>
  </div>

  {% when 4 %}
  <div class="route-col plenary">
    <h4>🟢 Check-in cruzado</h4>
    <p>Dudas comunes de recolección entre ambos grupos.</p>
  </div>
  <div class="dual-route">
    <div class="route-col quant">
      <h4>Ruta cuantitativa</h4>
      <p><strong>1.3 (cont.)</strong> Análisis inferencial aplicado con datos reales o simulados del proyecto.</p>
    </div>
    <div class="route-col qual">
      <h4>Ruta cualitativa</h4>
      <p><strong>2.3</strong> Grupos focales y grupos de discusión. <strong>2.4</strong> Otras fuentes (fotografías, infografías, video).</p>
    </div>
  </div>

  {% when 5 %}
  <div class="dual-route">
    <div class="route-col quant">
      <h4>Ruta cuantitativa</h4>
      <p><strong>1.4</strong> Software para análisis cuantitativo — taller práctico: SPSS / R / Jamovi con datos propios.</p>
    </div>
    <div class="route-col qual">
      <h4>Ruta cualitativa</h4>
      <p><strong>3.1</strong> Transcripción de registros. <strong>3.2</strong> Análisis de contenido vs. análisis de discurso — tipos de codificación.</p>
    </div>
  </div>
  <div class="update-block">
    <h3>🎯 Entrega 2 — Procesamiento y primer análisis de datos (30%)</h3>
    <p style="margin-bottom:0;">Se presenta al cierre de esta sesión. Corresponde a los temas 1.3-1.4 (cuantitativa) y 3.1-3.3 (cualitativa). Ver <a href="{{ '/proyecto.html' | relative_url }}">Entregas</a> y <a href="{{ '/rubricas.html' | relative_url }}">Rúbrica SOLO — Entrega 2</a>.</p>
  </div>

  {% when 6 %}
  <div class="route-col plenary">
    <h4>🟢 Plenaria integradora</h4>
    <p>Cada estudiante presenta su avance (5-7 min); retroalimentación cruzada cuanti↔cuali. Cierre con <strong>1.5</strong> interpretación de resultados cuantitativos y <strong>3.3-3.4</strong> software cualitativo + identificación de patrones (modo demostrativo para ambos grupos).</p>
  </div>
  <div class="update-block">
    <h3>🎯 Entrega 3 — Interpretación de resultados y construcción de hallazgos (40%)</h3>
    <p style="margin-bottom:0;">Se presenta y sustenta en esta sesión plenaria. Corresponde a los temas 1.5 (cuantitativa) y 3.4 (cualitativa). Ver <a href="{{ '/proyecto.html' | relative_url }}">Entregas</a> y <a href="{{ '/rubricas.html' | relative_url }}">Rúbrica SOLO — Entrega 3</a>.</p>
  </div>

  {% endcase %}
</div>
{% endfor %}
