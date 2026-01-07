```mermaid
flowchart TD

    A[Total Sessions<br/>1,082,718]
    A --> B[COHORT<br/>New User + Landing Page = Product page<br/>465,497]

    %% ATC vs Non-ATC
    B --> C[ATC Sessions<br/>38,311]
    B --> D[Non-ATC Sessions<br/>407,634]

    %% ATC breakdown
    C --> C1[Single-page sessions<br/>17,589]
    C --> C2[Multi-page sessions<br/>20,722]

    %% Non-ATC -> Bounce vs No-Bounce
    D --> E[Bounce sessions<br/>173,716]
    D --> F[No-Bounce sessions<br/>253,316]

    %% =========================
    %% Parallel categorizations
    %% =========================

    %% View 1: Page depth classification
    F --> P[View 1: Page depth]
    P --> F1[Single-page sessions<br/>194,246]
    P --> F2[Multi-page sessions<br/>59,070]

    %% View 2: Return behavior classification
    F --> R[View 2: Return behavior]
    R --> G[Return user sessions<br/>7,965]
    R --> H[No return user sessions<br/>245,351]

    %% Return users -> ATC outcome
    G --> G1[ATC on return session<br/>398 users]
    G --> G2[No ATC on return session<br/>7,573 users]

