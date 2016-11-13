# UDP Amplified M

Un script simplu UDP pentru a initia un atac DDoS. Simplu, dar eficient, mai puternic decat majoritatea script-urilor publice. De aici si denumirea de "Amplified".

Acest script este facut in /usr/bin/perl, deci aveti nevoie de perl instalat pe VPS-ul dumneavoastra.

Comanda ar fi asa: perl <denumirescript> <ip> <timp> <marime> <port>. 

Recomand: perl <denumirescript> <ip> 0 65500 0, unde "0" reprezinta random ports, respectiv timp infinit, desigur, pana cand il opriti voi cu CTRL+C, iar "65500" reprezinta marimea maxima.

[!] Nu folositi script-ul pe un VPS slab, se prea poate sa se inchida.
