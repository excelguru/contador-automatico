# contador-automatico

Contador automático em abela pré-formatada

Fórmula utilizada (célula A2):

    =SE(ÉNÚM(DESLOC(A2;-1;0));DESLOC(A2;-1;0)+1;1)
