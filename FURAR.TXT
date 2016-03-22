# Mitsubishi
Programas Mitsubishi

/ Furação G83

G17 G21 G54 G80 G90 ;
G0 G43 H1 Z200 ;
S850 M3 ;
/ L0 G83 X0 Y0 Z-1 (PROFUNDIDADE FURO) R1 Q2 F100 ;
/ L0 G85 Z-1 X0 Y0 R2 F50 ;
X0 Y0 ;
G80 ;
G0 Z100 ; 
M30 ;
%
