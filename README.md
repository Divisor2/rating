# Сайт рейтинга


## Контент:

```mermaid
graph  TD

H[Content Flow]  -->  L( Articles)  &  N(News)  &  B(fa:fa-gift Bonus)  &  F(FAQ)  &  W(Reviews)  &  T(How Tos)

B  --->  N

subgraph  WWW

S[Home]  -->  R[Rating]

S  -->  G[Blog]

G  -.->  L  &  N

R  -.->  W

F  -.->  R

T  -.->  L
end
```