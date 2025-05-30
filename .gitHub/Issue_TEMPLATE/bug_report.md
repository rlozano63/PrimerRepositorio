name: Bug report
description: Crea un informe para ayudarnos a mejorar
title: "[BUG] "
labels: ["bug"]
assignees: []

body:
  - type: markdown
    attributes:
      value: "Gracias por reportar un bug. Por favor completa la siguiente información:"
  - type: input
    id: environment
    attributes:
      label: Entorno
      description: Sistema operativo, navegador, versión, etc.
      placeholder: "Ejemplo: Windows 11, Chrome 123.0.1"
  - type: textarea
    id: what-happened
    attributes:
      label: ¿Qué ocurrió?
      description: Describe lo que ocurrió y qué esperabas que ocurriera.
  - type: textarea
    id: steps
    attributes:
      label: Pasos para reproducir el bug
      description: Detalla paso a paso cómo reproducir el error.
  - type: dropdown
    id: severity
    attributes:
      label: Severidad
      options:
        - Baja
        - Media
        - Alta
