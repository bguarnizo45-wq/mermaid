graph TD
    A[Inicio] --> B[Contacto Inicial]
    B --> C{Modalidad de Atención?}
    C -->|Presencial| D[Agendamiento en sede física]
    C -->|Virtual| E[Registro en plataforma digital]
    D & E --> F[Triaje inicial (cuestionario clínico)]
    F --> G{¿Urgencia detectada?}
    G -->|Sí| H[Atención prioritaria en 24h]
    G -->|No| I[Sesión diagnóstica en 72h]
    H & I --> J[Elaboración de plan terapéutico]
    J --> K{Intervención}
    K -->|Individual| L[Terapia CBT/EMDR según caso]
    K -->|Grupal| M[Talleres en hospitales aliados]
    L & M --> N[Seguimiento mensual]
    N --> O{¿Meta alcanzada?}
    O -->|Sí| P[Alta con recomendaciones]
    O -->|No| Q[Reevaluar plan]
    P --> R[Encuesta de satisfacción]
    Q --> K
    R --> Z[Fin del proceso]
