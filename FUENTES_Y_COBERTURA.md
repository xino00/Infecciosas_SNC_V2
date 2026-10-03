# Fuentes, cobertura y discrepancias

[Volver al índice](README.md)

## Jerarquía de las fuentes

**INFURG-SEMES 2012 estructura la actuación; SEN 2025 gobierna el contenido clínico.** Es la prioridad acordada para estos apuntes. Si hay diferencias entre documentos, se mantiene SEN; si SEN tiene contradicciones internas, omisiones o posibles erratas, se conservan señaladas. La ausencia de un dato en SEN no autoriza a completar una pauta con INFURG.

INFURG también aporta la organización del destino asistencial, siempre atribuida expresamente. No se importan por esa vía sus dosis, umbrales de gravedad, observaciones temporizadas, procedimientos de derivaciones ni reglas de alta. No se han consultado otras fuentes clínicas.

## SEN: fuente clínica prioritaria

**Fuente clínica prioritaria:** `Infecciones_del_sistema_nervioso_SEN_2025.pdf`, aportado por el usuario y conservado localmente. El fragmento contiene los capítulos 40–44 del bloque «Patologías neurológicas. Infecciones del sistema nervioso». No incluye portada ni créditos generales; «SEN 2025» identifica el nombre del archivo, sin certificar aquí la edición bibliográfica completa.

- Extensión: **68 páginas del PDF**, intervalo impreso **619–686**.
- Correspondencia: **página impresa = página del PDF + 618**. Las páginas PDF 14, 40 y 60 son separadores sin texto extraído.
- Tamaño del original: **4 949 070 bytes**.
- SHA-256: `2b8e7dbc7ba0fc023016e93e36ce6d2bfe8b0cef61e4d05f226dc75616eb7842`.
- Elaboración y revisión de fidelidad inicial: **2 de octubre de 2026**.
- Reorganización y contraste con INFURG: **3 de octubre de 2026**.

| Capítulo | Autoría que figura en el fragmento | Páginas impresas | Páginas PDF |
| --- | --- | --- | --- |
| 40. Infecciones bacterianas | Juan Carlos García-Moncó Carra, Patricia Rodrigo Armenteros y Markel Erburu Iriarte | 619–631 | 1–13 |
| 41. Absceso cerebral, empiemas epidural y subdural (cerebral y medular) | José Ramón Ara Callizo | 633–642 | 15–24 |
| 42. Infecciones víricas | Francisco Javier Carod Artal | 643–657 | 25–39 |
| 43. Infecciones fúngicas y parasitarias del sistema nervioso | Alberto Sáez Marín, Erik Stiauren Fernández e Íñigo Corral Corral | 659–677 | 41–59 |
| 44. Prionopatías | Silvia Enríquez Calzada y Alejandro Durán Lozano | 679–686 | 61–68 |

Las bibliografías de los capítulos se han identificado dentro del PDF: pp. 630–631, 640–642, 655–657, 674–677 y 686, respectivamente. Sus artículos y guías **no se han consultado directamente**. Cuando una nota menciona un estudio, guía o recomendación, describe lo que cuenta el manual, sin atribuirle una verificación externa.

## INFURG: esqueleto de actuación

**Archivo consultado:** `SNC INFURG_SEMES2012.pdf`, aportado por el usuario y conservado en su ubicación local. El fragmento lleva el título interior *Manejo de Infecciones en Urgencias* y comprende los capítulos 18–23; la identificación «INFURG-SEMES 2012» procede del archivo aportado. No incluye la portada o los créditos generales completos.

- Extensión: **48 páginas del PDF**, intervalo impreso **145–192**.
- Correspondencia de las páginas con contenido: **impresa = PDF + 144**. PDF 14, 20 y 36 son separadores sin contenido clínico.
- Tamaño: **1 103 960 bytes**.
- SHA-256: `363ca6b2b81cb2874880f2c5aa390ccc0a88cdac48b36c81f3ff242972b70ea2`.
- Lectura completa y contraste: **3 de octubre de 2026**.

| Capítulo | Autoría en el fragmento | Impresa / PDF |
| --- | --- | --- |
| 18. Meningitis | Agustín Julián Jiménez, Raquel Parejo Míguez e Irene López Ramos | 145–157 / 1–13 |
| 19. Encefalitis | Agustín Julián Jiménez, Santiago Estébanez Seco y Raquel Parejo Míguez | 159–163 / 15–19 |
| 20. Absceso cerebral | Rafael Rubio Díaz, M.ª Paz García Butenegro y Agustín Julián Jiménez | 165–170 / 21–26 |
| 21. Infecciones parameníngeas | Pablo Franquelo Morales y Félix González Martínez | 171–179 / 27–35 |
| 22. Mielitis transversa. Infecciones medulares | Ana Huete Hurtado y Félix González Martínez | 181–186 / 37–42 |
| 23. Infecciones en enfermos con derivaciones de LCR | María Rosario Solano Vera y Félix González Martínez | 187–192 / 43–48 |

Se han leído las bibliografías incluidas en pp. 157, 163, 170, 179, 186 y 192 (PDF 13, 19, 26, 35, 42 y 48), sin consultar directamente las publicaciones que enumeran.

## Cobertura del esqueleto INFURG

INFURG no sustituye el contenido de los cinco capítulos SEN. Aporta una **secuencia asistencial y entradas por presentación**; los bloques de diagnóstico y tratamiento se han movido físicamente para que aparezcan antes de los desarrollos etiológicos extensos. Las dosis, tablas y citas clínicas previas se conservan.

| Capítulo o recurso de INFURG | Elementos usados para organizar | Ubicación y límite |
| --- | --- | --- |
| 18. Meningitis, pp. 145–156 / PDF 1–12 | Sospecha y estabilidad → pruebas/LCR → tratamiento → vigilancia, contactos; vía subaguda | [Actuación meníngea](apuntes/00_actuacion_inicial.md#síndrome-meníngeo-agudo) y [bacterianas](apuntes/01_infecciones_bacterianas.md); criterios, dosis y matices de SEN |
| Algoritmo 1, p. 156 / PDF 12 | Coordinar muestras, tratamiento, imagen y PL; interpretar LCR antes de ajustar | Interpretado en texto en la ruta inicial. No se copia «TC normal → PL» como autorización universal, ni «linfocitario/glucosa normal → vírica» como diagnóstico cerrado |
| 19. Encefalitis, pp. 159–163 / PDF 15–19 | Reconocimiento → LCR/RM/EEG → tratamiento empírico → ingreso/seguimiento | [Ruta encefalitis](apuntes/00_actuacion_inicial.md#sospecha-de-encefalitis) y [víricas](apuntes/03_infecciones_viricas.md); no corticoides rutinarios de 2012 |
| 20. Absceso cerebral, pp. 165–170 / PDF 21–26 | Localizar, imagen, foco y muestras, decisión neuroquirúrgica y antimicrobiana | [Colección intracraneal](apuntes/00_actuacion_inicial.md#colección-intracraneal) y [abscesos](apuntes/02_abscesos_y_empiemas.md#absceso-cerebral); excepciones y duraciones SEN |
| 21. Infecciones parameníngeas, pp. 171–178 / PDF 27–34 | Diferenciar colecciones intracraneales y espinales; reconocer complicación vascular | [Colecciones intracraneales](apuntes/02_abscesos_y_empiemas.md#empiema-subdural-y-absceso-epidural-intracraneales) y rutas espinales. SEN no desarrolla un protocolo completo de anticoagulación de tromboflebitis séptica; no se incorpora el de INFURG |
| 22. Mielitis e infecciones medulares, pp. 181–186 / PDF 37–42 | Síndrome medular → imagen → compresivo/no compresivo → etiología | [Ruta medular](apuntes/00_actuacion_inicial.md#síndrome-medular-o-radicular); conecta colecciones, mielitis víricas, bacterianas y parasitarias sin pauta empírica universal |
| Figura 1, p. 184 / PDF 40 | Imagen antes de decidir la vía compresiva o no compresiva | Revisión visual: el gráfico enlaza «no inflamatoria» con mielitis transversa, en tensión con el texto. No se adopta esa flecha ni la PL «obligada» como regla |
| 23. Derivaciones de LCR, pp. 187–191 / PDF 43–47 | Contexto del dispositivo, infección/disfunción, valoración hospitalaria/neuroquirúrgica y control del foco | [Derivaciones](apuntes/00_actuacion_inicial.md#derivación-de-lcr-o-neurocirugía) y [nosocomial](apuntes/01_infecciones_bacterianas.md#particularidades-de-la-meningitis-nosocomial); no se reconstruye un protocolo de punción del reservorio o recambio ausente en SEN |
| Destino asistencial, pp. 155, 163, 170, 178, 186 y 191 / PDF 11, 19, 26, 34, 42 y 47 | Ingreso y nivel de vigilancia por síndrome/gravedad | Identificado como organización INFURG en cada recorrido; sin sus cortes de Glasgow, plazos de observación o reglas temporales de alta |

Los **22 cuadros numerados** de INFURG se distribuyen en meningitis (10), absceso (3), parameníngeas (2), mielitis (5) y derivaciones (2). Se han usado para reconocer cómo agrupa etiologías, riesgo, pruebas y tratamiento, **sin reproducir sus tablas posológicas**. Los dos algoritmos anteriores se han interpretado visualmente; las tablas terapéuticas implicadas en las discrepancias se han cotejado también con la imagen del PDF.

Hongos y parásitos conservan su desarrollo SEN, con una entrada por síndrome y decisiones previas al tratamiento. Prionopatías carece de equivalente en INFURG: se ha ordenado como reconocimiento → diferencial tratable → pruebas → interpretación → cuidados; su contenido sigue procediendo íntegramente de SEN.

## Criterio de síntesis

Los apuntes reorganizan el texto por reconocimiento, diagnóstico, decisiones terapéuticas y seguimiento. La cobertura se refiere a **todos los apartados clínicos**, no a una transcripción de cada frase, referencia o dato epidemiológico histórico. Se conservan los elementos epidemiológicos y fisiopatológicos que explican el riesgo, la sospecha o la conducta. Se han resumido las enumeraciones repetidas y los antecedentes históricos sin convertirlos en recomendaciones nuevas.

Cada bloque clínico termina con capítulo, página impresa y página del PDF. En las cinco notas, las citas «Fuente: cap.» corresponden a SEN; INFURG se identifica por su nombre en cada aportación. En la ruta transversal se distingue siempre la fuente de estructura de la fuente clínica. Las figuras se interpretan en palabras; no se han incrustado capturas. Las tablas se han reorganizado sin completar dosis, vías, intervalos, duraciones o criterios que no desarrolla la fuente. Las pautas pediátricas, del embarazo y de inmunodepresión se mantienen con su población identificada.

## Cobertura de los apartados clínicos de SEN

### Capítulo 40: bacterianas

| Apartado original | Impresa / PDF | Ubicación de la síntesis |
| --- | --- | --- |
| 1.1–1.4. Introducción, epidemiología, fisiopatología y clínica de meningitis aguda | 619–622 / 1–4 | [Meningitis aguda](apuntes/01_infecciones_bacterianas.md#meningitis-aguda) y [etiología por contexto](apuntes/01_infecciones_bacterianas.md#etiología-orientada-por-contexto) |
| 1.5. Diagnóstico | 622 / 4 | [Diagnóstico y LCR](apuntes/01_infecciones_bacterianas.md#diagnóstico-y-lcr) |
| 1.6. Complicaciones y factores pronósticos | 622–623 / 4–5 | [Complicaciones y pronóstico](apuntes/01_infecciones_bacterianas.md#complicaciones-y-pronóstico) |
| 1.7. Diagnóstico diferencial | 623 / 5 | [Diferencial](apuntes/01_infecciones_bacterianas.md#diagnóstico-diferencial) |
| 1.8.1–1.8.3. Soporte, antibióticos y glucocorticoides | 623–625 / 5–7 | [Tratamiento de la meningitis aguda](apuntes/01_infecciones_bacterianas.md#tratamiento-de-la-meningitis-aguda) |
| 1.8.4–1.8.5. Quimioprofilaxis y vacunación | 625–626 / 7–8 | [Profilaxis y vacunación](apuntes/01_infecciones_bacterianas.md#profilaxis-y-vacunación) |
| 2. Introducción a meningitis crónicas | 626 / 8 | [Meningitis crónicas](apuntes/01_infecciones_bacterianas.md#meningitis-crónicas) |
| 2.1. Tuberculosis | 626–627 / 8–9 | [Tuberculosis](apuntes/01_infecciones_bacterianas.md#tuberculosis) |
| 2.2. Brucella | 627–628 / 9–10 | [Neurobrucelosis](apuntes/01_infecciones_bacterianas.md#neurobrucelosis) |
| 2.3. Treponema | 628 / 10 | [Neurosífilis](apuntes/01_infecciones_bacterianas.md#neurosífilis) |
| 2.4. Borrelia | 628–629 / 10–11 | [Lyme](apuntes/01_infecciones_bacterianas.md#neuroborreliosis-de-lyme) |
| 2.5. Leptospira | 629–630 / 11–12 | [Leptospirosis](apuntes/01_infecciones_bacterianas.md#leptospirosis) |
| 2.6. Puntos clave | 630 / 12 | Integrados en los bloques previos y en [Puntos de decisión](apuntes/01_infecciones_bacterianas.md#puntos-de-decisión) |

### Capítulo 41: abscesos y empiemas

| Apartado original | Impresa / PDF | Ubicación de la síntesis |
| --- | --- | --- |
| 1. Introducción | 633 / 15 | [Localizar la infección](apuntes/02_abscesos_y_empiemas.md#localizar-la-infección) |
| 2.1–2.4. Definición, epidemiología, etiopatogenia y clínica del absceso cerebral | 633–634 / 15–16 | [Absceso cerebral](apuntes/02_abscesos_y_empiemas.md#absceso-cerebral) y [origen/etiología](apuntes/02_abscesos_y_empiemas.md#origen-y-etiología-del-absceso-cerebral) |
| 2.5–2.6. Diagnóstico y diferencial | 635–636 / 17–18 | [Diagnóstico del absceso cerebral](apuntes/02_abscesos_y_empiemas.md#diagnóstico-del-absceso-cerebral) |
| 2.7–2.8. Tratamiento y pronóstico | 636–638 / 18–20 | [Tratamiento del absceso cerebral](apuntes/02_abscesos_y_empiemas.md#tratamiento-del-absceso-cerebral) |
| 3.1–3.5. Empiema subdural y absceso epidural intracraneales | 638–639 / 20–21 | [Colecciones intracraneales](apuntes/02_abscesos_y_empiemas.md#empiema-subdural-y-absceso-epidural-intracraneales) |
| 4.1–4.8. Absceso epidural espinal: epidemiología, causas, clínica, diagnóstico, diferencial, tratamiento y pronóstico | 639–640 / 21–22 | [Absceso epidural espinal](apuntes/02_abscesos_y_empiemas.md#absceso-epidural-espinal) |
| 5. Absceso medular y subdural espinal | 640 / 22 | [Absceso intramedular y subdural espinal](apuntes/02_abscesos_y_empiemas.md#absceso-intramedular-y-subdural-espinal) |

### Capítulo 42: víricas

| Apartado original | Impresa / PDF | Ubicación de la síntesis |
| --- | --- | --- |
| 1–2. Introducción y epidemiología | 643–645 / 25–27 | [Epidemiología](apuntes/03_infecciones_viricas.md#epidemiología-y-mecanismos) y [Virus y exposiciones](apuntes/03_infecciones_viricas.md#virus-y-exposiciones) |
| 3.1. Mecanismos de entrada y daño | 645–646 / 27–28 | [Mecanismos](apuntes/03_infecciones_viricas.md#cómo-alcanza-el-snc) y [SARS-CoV-2](apuntes/03_infecciones_viricas.md#sars-cov-2-y-síndromes-relacionados) |
| 3.2. Infecciones congénitas | 646–647 / 28–29 | [Infecciones congénitas](apuntes/03_infecciones_viricas.md#infecciones-congénitas) |
| 4.1. Manifestaciones en inmunocompetentes | 647–649 / 29–31 | [Síndromes](apuntes/03_infecciones_viricas.md#del-síndrome-a-la-sospecha) y [Manifestaciones clínicas](apuntes/03_infecciones_viricas.md#manifestaciones-clínicas) |
| 4.2. Inmunocomprometidos | 649–651 / 31–33 | [Inmunodepresión y VIH](apuntes/03_infecciones_viricas.md#inmunodepresión-y-vih) |
| 4.2.1. Infecciones crónicas | 650 / 32 | [LMP y otras infecciones crónicas](apuntes/03_infecciones_viricas.md#lmp-y-otras-infecciones-crónicas) |
| 4.2.2. Infección por virus JC | 650–651 / 32–33 | [LMP](apuntes/03_infecciones_viricas.md#leucoencefalopatía-multifocal-progresiva) |
| 5.1. Laboratorio y LCR | 651–652 / 33–34 | [Diagnóstico](apuntes/03_infecciones_viricas.md#diagnóstico) |
| 5.2. Neuroimagen y EEG | 652–653 / 34–35 | [RM y EEG](apuntes/03_infecciones_viricas.md#rm-y-eeg) |
| 6. Diagnóstico | 653–654 / 35–36 | [Síndrome de sospecha](apuntes/03_infecciones_viricas.md#del-síndrome-a-la-sospecha) e [integración diagnóstica](apuntes/03_infecciones_viricas.md#integración-y-diferencial) |
| 7. Diagnóstico diferencial | 654 / 36 | [Integración y diferencial](apuntes/03_infecciones_viricas.md#integración-y-diferencial) |
| 8. Tratamiento y terapias adyuvantes | 654–655 / 36–37 | [Tratamiento](apuntes/03_infecciones_viricas.md#tratamiento) |
| 9. Puntos clave | 655 / 37 | [Seguimiento y puntos clave](apuntes/03_infecciones_viricas.md#seguimiento-y-puntos-clave) |

### Capítulo 43: hongos y parásitos

| Apartado original | Impresa / PDF | Ubicación de la síntesis |
| --- | --- | --- |
| 1. Introducción y clasificación fúngica | 659 / 41 | [Orientación inicial](apuntes/04_hongos_y_parasitos.md#orientación-inicial) |
| 1.1. Criptococo | 659–661 / 41–43 | [Criptococosis](apuntes/04_hongos_y_parasitos.md#criptococosis) |
| 1.2. Candida | 661–662 / 43–44 | [Candidiasis](apuntes/04_hongos_y_parasitos.md#candidiasis-del-snc) |
| 1.3. Aspergillus | 662–664 / 44–46 | [Aspergilosis](apuntes/04_hongos_y_parasitos.md#aspergilosis) |
| 1.4. Mucorales | 664–665 / 46–47 | [Mucormicosis](apuntes/04_hongos_y_parasitos.md#mucormicosis) |
| 1.5. Hongos dimórficos y dematiáceos mencionados en el apartado | 665–666 / 47–48 | [Otras micosis](apuntes/04_hongos_y_parasitos.md#otras-micosis) |
| 2. Introducción y clasificación parasitaria | 666 / 48 | [Orientación inicial](apuntes/04_hongos_y_parasitos.md#orientación-inicial) y las secciones por organismo |
| 2.1.1. Malaria cerebral | 666–667 / 48–49 | [Malaria cerebral](apuntes/04_hongos_y_parasitos.md#malaria-cerebral) |
| 2.1.2. Toxoplasmosis | 667–668 / 49–50 | [Toxoplasmosis](apuntes/04_hongos_y_parasitos.md#toxoplasmosis) |
| 2.1.3. Tripanosomiasis africana y americana | 668–669 / 50–51 | [Tripanosomiasis](apuntes/04_hongos_y_parasitos.md#tripanosomiasis) |
| 2.1.4. Amebiasis | 669 / 51 | [Amebiasis](apuntes/04_hongos_y_parasitos.md#amebiasis) |
| 2.2.1. Neurocisticercosis | 669–671 / 51–53 | [Neurocisticercosis](apuntes/04_hongos_y_parasitos.md#neurocisticercosis) |
| 2.2.2. Equinococosis, esparganosis y cenurosis | 671–672 / 53–54 | [Otros cestodos](apuntes/04_hongos_y_parasitos.md#otros-cestodos) |
| 2.2.3. Esquistosomiasis | 672–673 / 54–55 | [Esquistosomiasis](apuntes/04_hongos_y_parasitos.md#esquistosomiasis) |
| 2.2.4. Triquinosis | 673 / 55 | [Triquinosis](apuntes/04_hongos_y_parasitos.md#triquinosis) |
| 2.2.5. Otros helmintos y meningitis eosinofílica | 673–674 / 55–56 | [Otros helmintos](apuntes/04_hongos_y_parasitos.md#meningitis-eosinofílica) |

### Capítulo 44: prionopatías

| Apartado original | Impresa / PDF | Ubicación de la síntesis |
| --- | --- | --- |
| 1–3. Introducción, epidemiología y etiología/fisiopatología | 679–680 / 61–62 | [Concepto y mecanismos](apuntes/05_prionopatias.md#concepto-y-mecanismos) |
| 4. Clínica y variantes | 680–681 / 62–63 | [Reconocimiento clínico](apuntes/05_prionopatias.md#reconocimiento-clínico) |
| 5. Pruebas complementarias | 681–683 / 63–65 | [Estudio inicial](apuntes/05_prionopatias.md#estudio-de-una-demencia-rápidamente-progresiva) y [Biomarcadores](apuntes/05_prionopatias.md#biomarcadores) |
| 6. Diagnóstico y esquema | 683–684 / 65–66 | [Esquema diagnóstico del manual](apuntes/05_prionopatias.md#esquema-diagnóstico-del-manual) |
| 7. Diagnóstico diferencial | 683–684 / 65–66 | [Diagnóstico diferencial](apuntes/05_prionopatias.md#diagnóstico-diferencial) |
| 8. Tratamiento, precauciones y comunicación | 684 y 686 / 66 y 68 | [Tratamiento y precauciones](apuntes/05_prionopatias.md#tratamiento-y-precauciones) |
| 9. Puntos clave | 686 / 68 | [Puntos de decisión](apuntes/05_prionopatias.md#puntos-de-decisión) |

## Tablas, figuras y esquema

En SEN se revisaron visualmente **29 tablas numeradas, 17 figuras numeradas y el esquema diagnóstico adicional de la p. 684**. La tabla siguiente indica dónde se ha interpretado su contenido; no implica que se reproduzcan sus diseños o todas sus leyendas.

| Original | Impresa / PDF | Tratamiento en los apuntes |
| --- | --- | --- |
| Cap. 40, tablas 1–2 | 620 / 2 | Etiología, factores de riesgo y tratamiento empírico |
| Cap. 40, tablas 3–6 | 623–625 / 5–7 | Tratamiento dirigido, dosis y penetración, nosocomial y profilaxis |
| Cap. 40, tablas 7–8 | 626 / 8 | Diferencial y exposiciones de meningitis crónica |
| Cap. 41, tablas 1–2 | 634 y 637 / 16 y 19 | Foco, microorganismos y esquemas empíricos |
| Cap. 41, tablas 3–4 | 638 y 640 / 20 y 22 | Reconocimiento, imagen y decisiones de absceso cerebral y espinal |
| Cap. 41, figura 1 | 635 / 17 | Lectura textual de TC/RM del absceso |
| Cap. 42, tablas 1–3 | 644–645 / 26–27 | Virus, exposiciones y mecanismos de acceso |
| Cap. 42, tablas 4–5 | 646–647 / 28–29 | SARS-CoV-2 e infección congénita |
| Cap. 42, tablas 6–8 | 648–649 / 30–31 | Presentaciones por agente y rabia |
| Cap. 42, tablas 9–11 | 650–651 / 32–33 | VIH, sarampión y fármacos inmunosupresores |
| Cap. 42, figuras 1–2 | 653 / 35 | Lectura de RM en herpes y LMP |
| Cap. 43, tabla 1 y tabla 3 | 659 y 664 / 41 y 46 | Grupos de hongos y comparación clínica/diagnóstica/terapéutica |
| Cap. 43, tabla 2 | 661 / 43 | Fases y alternativas del tratamiento criptocócico en VIH |
| Cap. 43, tablas 4–6 | 666 y 673–674 / 48 y 55–56 | Clasificación parasitaria, meningitis eosinofílica y otros helmintos |
| Cap. 43, figuras 1–4 | 661, 664–665 y 668 / 43, 46–47 y 50 | Imagen de criptococo, Aspergillus, mucor y toxoplasma |
| Cap. 43, figuras 5–7 | 670–671 / 52–53 | Localizaciones y fases de neurocisticercosis |
| Cap. 43, figuras 8–9 | 672 / 54 | Hidatidosis vertebral y esquistosomiasis medular |
| Cap. 44, figuras 1–2 | 680–681 / 62–63 | Conversión de PrP y variantes clínicas |
| Cap. 44, figuras 3–5 | 682–683 y 685 / 64–65 y 67 | RM, EEG, funcionamiento de RT-QuIC y límites de biomarcadores |
| Cap. 44, esquema diagnóstico sin número | 684 / 66 | Descripción de las categorías impresas, con sus discrepancias explícitas |

## Discrepancias entre INFURG y SEN

INFURG-SEMES 2012 aporta la organización de la actuación; ante diferencias de contenido clínico prevalece SEN 2025. Esta prioridad no resuelve las ambigüedades internas de SEN ni autoriza completar sus pautas incompletas con datos de 2012. La ausencia de un detalle en SEN se señala como límite de cobertura, no como demostración de que el dato antiguo sea incorrecto.

| Aspecto | INFURG: dato que no se traslada automáticamente | Criterio aplicado desde SEN | Referencias de ambas fuentes |
| --- | --- | --- | --- |
| D01. Tiempo hasta antibiótico y aciclovir | Alterna dos objetivos numéricos para la primera dosis antibiótica. | Inicio precoz sin demora por TC o PL. La ventana para aciclovir cuando no se dispone de pruebas no es una indicación de esperar si ya existe sospecha o deterioro. | INFURG cap. 18, pp. 151 y 155 (PDF 7 y 11); cap. 19, p. 162 (PDF 18). SEN cap. 40, pp. 622–624 (PDF 4–6); cap. 42, p. 654 (PDF 36). |
| D02. TC previa, Glasgow y seguridad de PL | Añade umbral numérico de Glasgow, edad, foco ORL y dificultad para realizar fondo de ojo entre las indicaciones. | Se usa la lista clínica de SEN y se conserva su duda B02: mezcla indicaciones de neuroimagen con coagulopatía y sospecha de absceso epidural. Una TC normal no convierte por sí sola la PL en segura. | INFURG cap. 18, p. 149 y pp. 155–156 (PDF 5 y 11–12). SEN cap. 40, p. 622 (PDF 4); cap. 41, p. 640 (PDF 22). |
| D03. Rangos del LCR | Los rangos celulares y de proteínas de las tablas bacteriana y vírica difieren de SEN. | Se mantienen los rangos y excepciones de SEN, sin unir ambos intervalos ni convertirlos en criterios excluyentes. | INFURG cap. 18, pp. 149–150 (PDF 5–6); cap. 19, p. 161 (PDF 17). SEN cap. 40, p. 622 (PDF 4); cap. 42, pp. 651–652 (PDF 33–34). |
| D04. Alta, observación y repetición de PL | Fija horas de observación y decúbito tras PL, así como distintos intervalos de repetición según capítulo o algoritmo. | SEN no desarrolla un protocolo equivalente de alta u observación ni valida esos tiempos; además admite LCR inicial normal. Se conserva el apartado de destino como organización INFURG, sin convertir sus plazos o umbrales en autorización de alta ni repetición universal. | INFURG cap. 18, pp. 149 y 155–156 (PDF 5 y 11–12); cap. 19, p. 163 (PDF 19). SEN cap. 40, pp. 622–623 (PDF 4–5); cap. 42, pp. 651–652 y 654 (PDF 33–34 y 36). |
| D05. Ceftriaxona pediátrica y neonato | La tabla expresa una pauta pediátrica por administración y contempla ceftriaxona en neonatos. | SEN expresa la ceftriaxona pediátrica como total diario repartido y recoge cefotaxima más ampicilina en el esquema neonatal. No se importa ni convierte la pauta de 2012. | INFURG cap. 18, p. 151, tabla 6 (PDF 7). SEN cap. 40, pp. 620 y 624, tablas 1 y 4 (PDF 2 y 6). |
| D06. Dexametasona en meningitis bacteriana | Utiliza pauta ponderal, duración variable y exclusión si ya recibía antibiótico parenteral; vincula además corticoide a añadir rifampicina. | Se conserva la pauta fija adulta, duración y matices temporales/etiológicos de SEN. No se añaden prohibición absoluta ni rifampicina obligatoria a partir de INFURG. | INFURG cap. 18, pp. 151–153 (PDF 7–9). SEN cap. 40, pp. 624–625 y 630 (PDF 6–7 y 12). |
| D07. Profilaxis meningocócica | Cambian límites de edad, opciones de dosis y formulaciones sobre embarazo. | Se conserva la tabla de SEN junto a B06, incluidos sus huecos en edades exactas y la ambigüedad sobre rifampicina en embarazo. No se reparan con los límites de INFURG. | INFURG cap. 18, p. 154, tabla 9 (PDF 10). SEN cap. 40, p. 625, tabla 6 (PDF 7). |
| D08. Tuberculosis y neurobrucelosis | Difieren la dosis/condición de añadir etambutol y las pautas de rifampicina y gentamicina en Brucella. | Se mantienen indicaciones, dosis, fases y duración de SEN; no se añade sistemáticamente el cuarto fármaco de INFURG ni se sustituyen dosis ponderales por las fijas antiguas. | INFURG cap. 18, pp. 154–155, tabla 10 (PDF 10–11); cap. 22, p. 185 (PDF 41). SEN cap. 40, pp. 627–628 (PDF 9–10). |
| D09. Neuroborreliosis | La ceftriaxona se presenta con un intervalo diferente y sin la separación clínica que desarrolla SEN. | Prevalecen la pauta SEN y su distinción entre formas menos graves y graves, conservando el matiz sobre eficacia comparable de doxiciclina en estudios europeos. | INFURG cap. 18, p. 154 (PDF 10); cap. 22, p. 185 (PDF 41). SEN cap. 40, p. 629 (PDF 11). |
| D10. Corticoides en encefalitis | Propone dexametasona si no está contraindicada. | SEN no recomienda corticoides ni inmunoglobulinas rutinarios; se conserva la indicación específica de corticoides con aciclovir en vasculitis VVZ. | INFURG cap. 19, p. 162 (PDF 18). SEN cap. 42, pp. 654–655 (PDF 36–37). |
| D11. CMV y foscarnet | Presenta una pauta de foscarnet con intervalo para CMV y una cobertura amplia en inmunodepresión. | Se conserva la pauta de CMV de SEN con su intervalo ausente señalado; no se rellena con INFURG ni con la pauta SEN de HHV-6. Las indicaciones se separan por agente y síndrome. | INFURG cap. 19, p. 163 (PDF 19); cap. 22, p. 185 (PDF 41). SEN cap. 42, p. 654 (PDF 36). |
| D12. Toxoplasmosis y VIH | El pie de tabla utiliza «SIDA o serología positiva» y aporta dosis y duración completas que no coinciden con el desarrollo de SEN. | SEN exige interpretar inmunidad, clínica, imagen y serología conjuntamente. No se convierte seropositividad aislada en infección activa ni se rellenan las dosis ausentes del capítulo específico con INFURG. | INFURG cap. 20, p. 169, tabla 2 (PDF 25). SEN cap. 41, p. 637, tabla 2 (PDF 19); cap. 43, pp. 667–668 (PDF 49–50). |
| D13. Esquema empírico del absceso cerebral | Agrupa endocarditis con trauma/neurocirugía; cambia la combinación para foco desconocido y desarrolla ajustes otógenos. | Se utilizan las filas diferenciadas de SEN. La cobertura otógena incompleta permanece señalada como A03; la nota antigua no se incorpora como corrección implícita de SEN. | INFURG cap. 20, p. 169, tabla 2 (PDF 25). SEN cap. 41, p. 637, tabla 2 (PDF 19). |
| D14. Duración y adyuvantes del absceso | Presenta una duración general y pautas numéricas de corticoide/fenitoína. | SEN diferencia aspiración, manejo médico y exéresis, y condiciona las pautas cortas. La profilaxis antiepiléptica primaria se mantiene como propuesta de algunos autores sin guías claras, no como obligación; no se importan dosis adyuvantes. | INFURG cap. 20, pp. 169–170 (PDF 25–26). SEN cap. 41, pp. 636–638 (PDF 18–20). |
| D15. Parálisis y cirugía del absceso epidural espinal | Desestima cirugía con para/tetraplejía establecida y establece un corte pronóstico más restrictivo. | SEN conserva drenaje y antibióticos como estándar, incluso plantea intervención temprana ante paraplejía completa. No se transforma la parálisis en contraindicación ni el límite temporal de SEN en una espera programada. | INFURG cap. 21, p. 178 (PDF 34). SEN cap. 41, p. 640 (PDF 22). |
| D16. Algoritmo de mielopatía | Tras excluir compresión plantea PL obligada y ofrece regímenes empíricos extensos para mielitis, inmunodepresión y absceso intramedular. | Se conserva la bifurcación anatómica mediante imagen como orientación organizativa; no se copia la PL como regla universal ni un protocolo farmacológico completo. SEN distingue colecciones, causas víricas e inmunomediadas y mantiene la PL generalmente contraindicada en absceso epidural. | INFURG cap. 22, pp. 184–186 (PDF 40–42). SEN cap. 41, pp. 639–640 (PDF 21–22); cap. 42, pp. 647–648 y 654–655 (PDF 29–30 y 36–37). |
| D17. Retirada del catéter y colocación de uno nuevo | Describe demoras desde el inicio antibiótico hasta retirar el sistema, con variantes según dependencia y tipo de drenaje. | SEN indica retirada del catéter infectado y condiciona la colocación del nuevo a cultivos de LCR negativos durante el período señalado. Son decisiones distintas: no se importa una demora programada de retirada ni se usa el plazo de recambio como protocolo completo. | INFURG cap. 23, pp. 190–191 (PDF 46–47). SEN cap. 40, pp. 623–625 (PDF 5–7). |
| D18. Tratamiento genérico de «hongos» | La tabla medular reúne antifúngicos como alternativas de un mismo grupo sin desarrollar etiología. | El capítulo específico SEN separa criptococo, Candida, Aspergillus y mucorales. Tampoco se extiende a cualquier hongo la mención general de voriconazol del capítulo de abscesos; se conserva A02 y se remite a la micosis concreta. | INFURG cap. 22, p. 185, tabla 5 (PDF 41). SEN cap. 41, p. 637 (PDF 19); cap. 43, pp. 659–665 (PDF 41–47). |

Los protocolos de tromboflebitis séptica intracraneal y de mielitis transversa de INFURG exceden el desarrollo específico del fragmento SEN disponible. Sus encabezados pueden orientar la búsqueda y la valoración especializada, pero no se presentan como protocolos actualizados por SEN.

## Registro de dudas y limitaciones de la fuente

**Ninguna de estas observaciones se ha resuelto con otra guía.** Se han evitado correcciones clínicas silenciosas. Las siguientes entradas remiten a la nota donde aparece la advertencia y sus consecuencias para la lectura.

| ID | Impresa / PDF | Problema y tratamiento editorial |
| --- | --- | --- |
| B01 | 621 y 630 / 3 y 12 | [Tríada y lista de cuatro síntomas](apuntes/01_infecciones_bacterianas.md#reconocimiento-y-prioridad): no convertir el 95 % en regla de exclusión |
| B02 | 622 / 4 | [Neuroimagen y seguridad de PL](apuntes/01_infecciones_bacterianas.md#secuencia-inicial): la lista mezcla indicaciones de imagen con contraindicaciones; faltan umbrales |
| B03 | 622 / 4 | [Rentabilidad microbiológica tras antibióticos](apuntes/01_infecciones_bacterianas.md#interpretación-del-líquido): afirmaciones discordantes en la misma página |
| B04 | 623 / 5 | [Tratamiento dirigido](apuntes/01_infecciones_bacterianas.md#tratamiento-dirigido-que-recoge-la-tabla-3): combinación/alternativa de TMP-SMX en Listeria poco clara; H. influenzae sin desarrollo de sensibilidad |
| B05 | 624 / 6 | [Tabla de dosis](apuntes/01_infecciones_bacterianas.md#dosis-de-la-tabla-4): nota farmacológica posiblemente errónea; se mantienen cifras de cloxacilina y cefepima pediátrica, y se separan totales diarios de dosis por administración |
| B06 | 625 / 7 | [Profilaxis](apuntes/01_infecciones_bacterianas.md#contactos): límites exactos de edad y trimestre del embarazo no resueltos |
| B07 | 626 / 8 | [Vacunación](apuntes/01_infecciones_bacterianas.md#vacunación-descrita-en-el-manual): duplicidad aparente de dosis/refuerzo de 4CMenB; calendario no actualizado |
| B08 | 627 / 9 | [Brucelosis](apuntes/01_infecciones_bacterianas.md#neurobrucelosis): discordancia entre «leve-moderada» y proteínas de 400 mg/dL |
| B09 | 628 / 10 | [Neurosífilis](apuntes/01_infecciones_bacterianas.md#neurosífilis): denominación temporal confusa, resolución espontánea descrita y ausencia de intervalo para penicilina procaína |
| B10 | 630 / 12 | [Leptospirosis](apuntes/01_infecciones_bacterianas.md#leptospirosis): vía de cefotaxima impresa como «in»; no se interpreta como una vía inequívoca |
| A01 | 634 / 16 | [Absceso y neurocisticercosis](apuntes/02_abscesos_y_empiemas.md#cómo-se-forma-y-qué-buscar): no equiparar automáticamente quiste parasitario y absceso piógeno |
| A02 | 637 / 19 | [Inmunodepresión y hongos](apuntes/02_abscesos_y_empiemas.md#esquemas-empíricos-según-el-foco): la mención genérica de voriconazol no se extiende a cualquier micosis |
| A03 | 637 / 19 | [Origen otógeno](apuntes/02_abscesos_y_empiemas.md#esquemas-empíricos-según-el-foco): Pseudomonas figura entre los agentes sin adaptación específica de la pauta |
| V01 | 648 / 30 | [Virus del Nilo occidental](apuntes/03_infecciones_viricas.md#síndromes-y-agentes-concretos): porcentaje impreso como «-2 %», sin reconstruirlo |
| V02 | 651 / 33 | [Inmunosupresores](apuntes/03_infecciones_viricas.md#tratamientos-asociados-a-riesgo-vírico-en-la-tabla-11): clasificación de everolimus posiblemente errónea |
| V03 | 647 / 29 | [Infección congénita](apuntes/03_infecciones_viricas.md#infecciones-congénitas): «tercer trimestre» para CMV/rubéola no distingue transmisión de daño fetal |
| V04 | 654 / 36 | [Antivirales](apuntes/03_infecciones_viricas.md#pautas-tal-como-las-desarrolla-el-manual): alternancia de meningitis, encefalitis y meningoencefalitis; no fusionar todas las duraciones |
| V05 | 654 / 36 | [CMV](apuntes/03_infecciones_viricas.md#pautas-tal-como-las-desarrolla-el-manual): foscarnet y cidofovir sin intervalo completo |
| H01 | 661 / 43 | [Criptococo](apuntes/04_hongos_y_parasitos.md#tratamiento-por-fases-en-pacientes-con-vih): numeración bibliográfica discordante en la tabla; se cita la tabla del manual |
| H02 | 659 y 665–666 / 41 y 47–48 | [Otras micosis](apuntes/04_hongos_y_parasitos.md#otras-micosis): agrupación de dematiáceos junto a dimórficos no adoptada como equivalencia taxonómica |
| H03 | 667 / 49 | [Malaria](apuntes/04_hongos_y_parasitos.md#tratamiento-del-fragmento): artesunato sin dosis ponderal ni frecuencia después de las 24 h |
| H04 | 668 / 50 | [Toxoplasma](apuntes/04_hongos_y_parasitos.md#tratamiento-de-la-toxoplasmosis): duración de 3–6 semanas y mantenimiento sin todas las condiciones de retirada; faltan dosis |
| H05 | 669 / 51 | [Chagas](apuntes/04_hongos_y_parasitos.md#americana): benznidazol «y» nifurtimox sin aclarar combinación o alternativas |
| H06 | 673 / 55 | [Esquistosoma](apuntes/04_hongos_y_parasitos.md#confirmación-diferencial-y-tratamiento): praziquantel 60 mg/kg/día seguido de «cada 8 h»; no presentarlo como 60 mg/kg por toma |
| H07 | 673 / 55 | [Meningitis eosinofílica](apuntes/04_hongos_y_parasitos.md#meningitis-eosinofílica): afirmación categórica sobre T. cati no contrastada ni usada para excluirlo clínicamente |
| H08 | 667–668 / 49–50 | [Serología de toxoplasma](apuntes/04_hongos_y_parasitos.md#imagen-y-diagnóstico): expresión «seroconversión de IgM a IgG» sin un algoritmo serológico completo; no se interpreta más allá del texto |
| P01 | 682 / 64 | [Genética](apuntes/05_prionopatias.md#subtipos-y-genética): asociación textual de D178N y codón 129 confusa |
| P02 | 682 / 64 | [RT-QuIC](apuntes/05_prionopatias.md#lcr-y-rt-quic): sensibilidad/especificidad agregadas y condiciones preanalíticas incompletas |
| P03 | 682–685 / 64–67 | [Biomarcadores](apuntes/05_prionopatias.md#lcr-y-rt-quic): texto y figura difieren en el desarrollo clínico de algunas muestras; no intercambiar matrices |
| P04 | 683–684 / 65–66 | [Esquema diagnóstico](apuntes/05_prionopatias.md#esquema-diagnóstico-del-manual): referencia CDC 2018 frente a pie OMS 1998; requisitos clínicos y conjunción en RM conservados como lectura del esquema, sin validarlos como clasificador |

También se conservan, junto a su contexto, diferencias de énfasis que no se han convertido en una pauta única: vancomicina empírica según resistencia local frente a uso general en el adulto; suspensión o continuación de dexametasona según agente; excepciones a aspiración diagnóstica frente a criterios de manejo médico del absceso; serología de Lyme dirigida frente al listado amplio del estudio de demencia rápidamente progresiva.

## Comprobaciones y límites

- Lectura íntegra de SEN antes de la redacción inicial, con extracción de texto y contraste visual de tablas, figuras y esquema. Lectura íntegra de INFURG antes de la reorganización, con revisión visual de sus algoritmos y tablas terapéuticas comparadas.
- Segunda pasada de cada dosis incluida: **fármaco, indicación, población, unidad, total diario o cantidad por administración, intervalo, vía y duración**. Cuando un campo falta o es ambiguo se indica; no se completa por memoria.
- Revisión de cifras, unidades y tablas frente al original, y coherencia entre las cinco notas. No se trasladan dosis de meningitis a abscesos ni pautas de una formulación de anfotericina a otra.
- Comprobación de correspondencia de páginas, estructura de tablas, destinos de enlaces e índices de Markdown.
- En la reorganización se comparan las tablas, líneas numéricas, bloques clínicos y avisos de SEN con la versión previa, para detectar pérdidas o cambios involuntarios. Las adiciones se revisan contra su fuente y no introducen dosis de INFURG.
- Publicación limitada a `README.md`, este registro, `apuntes/00_actuacion_inicial.md` y las cinco notas. Los dos PDF y los materiales temporales de extracción/revisión quedan fuera del repositorio remoto.

La revisión es de **fidelidad documental**, realizada durante la elaboración de los apuntes; no equivale a una revisión clínica independiente, una actualización terapéutica ni una resolución de las dudas enumeradas. Las recomendaciones sobre vacunas, fármacos, prevención o declaración de enfermedades mantienen el contexto del manual.
