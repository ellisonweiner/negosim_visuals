
    A[Artificial Intelligence (AI)] --> B(Machine Learning);
    A --> C(Natural Language Processing);
    A --> D(Computer Vision);
    A --> E(Robotics);
    A --> F(Expert Systems);
    A --> G(Planning and Reasoning);
    A --> H(AI Ethics & Safety);

    B --> B1[Supervised Learning];
    B --> B2[Unsupervised Learning];
    B --> B3[Reinforcement Learning];
    B --> B4[Deep Learning];

    C --> C1[Text Analysis];
    C --> C2[Speech Recognition];
    C --> C3[Machine Translation];
    C --> C4[Sentiment Analysis];
    C --> C5[Question Answering];

    D --> D1[Image Recognition];
    D --> D2[Object Detection];
    D --> D3[Image Segmentation];
    D --> D4[Video Analysis];
    D --> D5[Facial Recognition];

    E --> E1[Industrial Automation];
    E --> E2[Autonomous Vehicles];
    E --> E3[Service Robots];
    E --> E4[Human-Robot Interaction];
    E --> E5[Medical Robotics];

    F --> F1[Rule-Based Systems];
    F --> F2[Knowledge Representation];
    F --> F3[Inference Engines];
    F --> F4[Decision Support];

    G --> G1[Automated Planning];
    G --> G2[Logical Reasoning];
    G --> G3[Knowledge-Based Systems];
    G --> G4[Constraint Satisfaction];

    H --> H1[Bias and Fairness];
    H --> H2[Transparency and Explainability];
    H --> H3[Privacy and Security];
    H --> H4[Autonomous Weapons];
    H --> H5[Job Displacement];
    H --> H6[Value Alignment];

    style A fill:#f9f,stroke:#333,stroke-width:2px;
    style B,C,D,E,F,G,H fill:#ccf,stroke:#333;
    style B1,B2,B3,B4,C1,C2,C3,C4,C5,D1,D2,D3,D4,D5,E1,E2,E3,E4,E5,F1,F2,F3,F4,G1,G2,G3,G4,H1,H2,H3,H4,H5,H6 fill:#eef,stroke:#333;

    subgraph Machine Learning
        B1; B2; B3; B4;
    end

    subgraph Natural Language Processing
        C1; C2; C3; C4; C5;
    end

    subgraph Computer Vision
        D1; D2; D3; D4; D5;
    end

    subgraph Robotics
        E1; E2; E3; E4; E5;
    end

    subgraph Expert Systems
        F1; F2; F3; F4;
    end

    subgraph Planning and Reasoning
        G1; G2; G3; G4;
    end

    subgraph AI Ethics & Safety
        H1; H2; H3; H4; H5; H6;
    end
