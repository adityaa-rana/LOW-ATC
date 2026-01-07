flowchart TD

    A[Total Sessions<br/>1,082,718]

    A --> B[New User + Landing Page = Product<br/>465,497]

    %% ATC vs Non-ATC
    B --> C[ATC Sessions<br/>38,311 (8.59%)]
    B --> D[Non-ATC Sessions<br/>407,634 (91.41%)]

    %% ATC breakdown
    C --> C1[Single-page<br/>17,589]
    C --> C2[Multi-page<br/>20,722]

    %% Non-ATC → Bounce vs No-Bounce
    D --> E[Bounce<br/>173,716 (40.6%)]
    D --> F[No-Bounce<br/>253,316 (59.3%)]

    %% Non-ATC Bounce (page depth view)
    E --> E1[Single-page]
    E --> E2[Multi-page]

    %% Non-ATC No-Bounce → Page depth
    F --> F1[Single-page<br/>194,246]
    F --> F2[Multi-page<br/>59,070]

    %% Non-ATC No-Bounce → Return behavior
    F --> G[Return Users<br/>7,965 users]
    F --> H[No Return<br/>245,351 sessions<br/>(Same page = Landing page)]

    %% Return users → ATC outcome
    G --> G1[ATC on Return Session<br/>398 users]
    G --> G2[No ATC<br/>7,573 users]
