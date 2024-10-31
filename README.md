<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diagrama de Fontanellas</title>
    <script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
    <script>
        mermaid.initialize({ startOnLoad: true });
    </script>
</head>
<body>
    <div class="mermaid">
        flowchart TD
            classDef mainNode fill:none,stroke:#000000,stroke-width:2px,font-size:18px,font-weight:bold,color:#000000;
            classDef subNode fill:none,stroke:#000000,stroke-width:1.5px,font-size:16px,color:#000000;

            ConceptosGenerales["Avanzarse, innovar, ser líder.<br>Con la fidelidad y confianza de sus clientes, van evolucionando e invirtiendo para adaptarse a sus necesidades y a las exigencias del mercado."]:::mainNode

            ConceptosGenerales --> Evolution["Aspectos destacados de la evolución"]:::mainNode

            Evolution --> A["Compromiso firme con el medio ambiente y la sostenibilidad."]:::subNode
            A --> A1["De su especialidad con la marca Tani-Flex de curtición vegetal pasan a cromo y ahora están invirtiendo en el desarrollo de nuevas técnicas exentas de cromo."]:::subNode
            A --> A2["Sistema de placas fotovoltaicas"]:::subNode

            Evolution --> B["Diversidad de materiales, diferentes posicionamientos e internacionalización."]:::subNode
            B --> B1["Vidal Bosch: Complementar su catálogo de oferta de pieles; mejorar la presencia en los mercados en los que ambas marcas operan."]:::subNode
            B --> B2["Líderes con productos competitivos y de alta calidad en piel de serraje de poliuretano y presencia internacional."]:::subNode
            B --> B3["Con dos plantas productivas en España; últimos avances tecnológicos necesarios; amplia experiencia en curtición, diseño y acabados para marroquinería y cinturones."]:::subNode
            B --> B4["Referente en el desarrollo de nuevos productos; diseño exclusivo; acabados transfer de poliuretano."]:::subNode
            B --> B5["Fast Response Unit (FRU)."]:::subNode
    </div>
</body>
</html>
