# factor_partial
Partial factorisation of (univariate) polynomials. 

This algorithm can quickly rewrite polynomials like 

$x^{24}+12 x^{23}+78 x^{22}+352 x^{21}+1221 x^{20}+3432 x^{19}+8074
   x^{18}+16236 x^{17}+28314 x^{16}+43252 x^{15}+58278
   x^{14}+69576 x^{13}+73789 x^{12}+69576 x^{11}+58278
   x^{10}+43252 x^9+28314 x^8+16236 x^7+8065 x^6+3432 x^5+1221
   x^4+364 x^3+78 x^2+12 x-3$

as 

$(x^2+x+1)^12-(3 x^3-2)^2$

which I think it kind of neat. 
