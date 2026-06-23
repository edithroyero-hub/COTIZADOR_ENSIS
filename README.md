# COTIZADOR ENSIS Security 2026

Cotizador interactivo HTML para servicios de vigilancia y seguridad privada en Colombia, conforme a la normativa vigente 2026.

## Características

- **Multi-servicio**: cotiza varios servicios al mismo cliente con modalidades, sectores y armamento independientes
- **27 modalidades estándar** del tarifario Supervigilancia + opción personalizada (horas/días no estándar)
- **3 tarifarios 2026**: Ene-Jun (jornada 44h), Jul 1-14 y Jul 15-Dic (jornada 42h por Ley 2101 + Circular 0040)
- **Cotización por meses o por días** (eventos cortos)
- **Adicionales por turno**: guardia extra diurno ($80.000) o nocturno ($100.000) configurables
- **Parámetros editables en vivo**: % Reinversión, % Comisión, % Administrativo, % IVA, % Renta
- **Auditoría automática** con veredicto en vivo (OK / ATENCIÓN / ALERTA / FALLO según margen neto)
- **Entregable cliente limpio** (solo lo cotizado + compromiso de reinversión)
- **Exportar / Importar Excel** (.xlsx) e **Importar/Exportar JSON** para iteración con cliente
- **Guardado automático** en navegador (localStorage)

## Cómo usarlo

1. Descarga el archivo `index.html`
2. Doble-click para abrir en cualquier navegador moderno (Chrome, Edge, Firefox)
3. Llena los datos del cliente, periodo y configura los servicios cotizados
4. Genera el entregable cliente o exporta a Excel

## Normativa aplicada (Colombia 2026)

- **Circular Externa 20251300000115CS** — Supervigilancia (tarifas mínimas 2026)
- **Decreto 0159 de 2026** — MinTrabajo (SMMLV transitorio $1.750.905)
- **Circular 0040 MinTrabajo** (16-abr-2026): jornada 42h/sem sector vigilancia desde 15-jul-2026
- **Ley 2466 de 2025** — recargo dominical 80% en 2026
- **Ley 1819 de 2016 art. 65** — exoneración aportes parafiscales para trabajadores < 10 SMLV
- **Art. 462-1 ET** — IVA con base gravable AIU
- **Ley 2101 de 2021** — reducción progresiva de jornada laboral

## Requisitos técnicos

- Navegador moderno con JavaScript habilitado
- Conexión a internet la primera vez (carga librería SheetJS para Export/Import Excel)
- Funciona offline después de la primera carga

## Estructura del archivo

`index.html` es un archivo HTML autocontenido con:
- HTML para la UI
- CSS embebido para los estilos
- JavaScript embebido para la lógica de cálculo y persistencia
- Datos de los 3 tarifarios 2026 embebidos como objetos JS

## Licencia

Material confidencial de ENSIS Security Ltda. Uso interno autorizado únicamente.

---

**Edith Royero | Financiera**
ENSIS Security Ltda.
