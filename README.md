# Shannon-Entropy-with-matlab

p = 0:0.001:0.999999;
H = p.*log2(1./p) + (1-p) .*log2(1./(1-p));

plot(p,H);
title ('Entropia binaria');
xlabel('P');
ylabel('H(P)');
grid on;




