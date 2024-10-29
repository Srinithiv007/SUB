module fs(a,b,c,diff,borr);
input a,b,c;
output diff,borr;
assign diff=a^b^c;
assign borr=~a&(b^c)|b&c;
endmodule
