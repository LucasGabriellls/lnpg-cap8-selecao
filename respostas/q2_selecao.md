// Implementação em C
switch (k) {
    case 1:
    case 2:
        j = 2 * k - 1;
        break;
    case 3:
    case 5:
        j = 3 * k + 1;
        break;
    case 4:
        j = 4 * k - 1;
        break;
    case 6:
    case 7:
    case 8:
        j = k - 2;
        break;
}

// Implementação em Ruby
case k
when 1, 2
  j = 2 * k - 1
when 3, 5
  j = 3 * k + 1
when 4
  j = 4 * k - 1
when 6, 7, 8
  j = k - 2
end

// Implementação em Erlang
case K of
    K when K =:= 1; K =:= 2 -> J = 2 * K - 1;
    K when K =:= 3; K =:= 5 -> J = 3 * K + 1;
    K =:= 4 -> J = 4 * K - 1;
    K when K >= 6, K =< 8 -> J = K - 2
end.

Discuta os méritos relativos do uso dessas linguagens para esse código em particular.

C: O mérito é a velocidade. Por lidar direto com inteiros no baixo nível, é a mais rápida na execução, mas o código fica "sujo" com tanto case e break.

Ruby: O mérito é a escrita. É a mais simples e limpa de todas, permitindo agrupar valores por vírgula ou faixas (6..8), o que economiza muito tempo.

Erlang: O mérito é a segurança. O sistema de "guards" (os when) garante que a lógica seja seguida à risca, embora a sintaxe seja bem mais burocrática e difícil de ler.