# Organization Chart
graph TB
ES[Executive Sponsor]
PD[Program Director]
DPM[Deputy PM]
PMO[PMO Lead]
FL[Functional Lead]
TL[Technical Lead]
QL[QA Lead]
OL[Operations Lead]
ES --> PD
PD --> DPM
PD --> PMO
PD --> FL
PD --> TL
PD --> QL
PD --> OL
PMO --> PCA[Project Control Analyst]
PMO --> FCA[Financial Analyst]
FL --> BA[Business Analysts]
FL --> CM[Change Management Lead]
TL --> ERPL[ERP Lead]
TL --> IL[Integration Lead]
TL --> DL[Data Lead]
TL --> DEV[Developers]
QL --> TA[Test Analysts]
OL --> SA[Support Analysts]
OL --> CI[Continuous Improvement]
