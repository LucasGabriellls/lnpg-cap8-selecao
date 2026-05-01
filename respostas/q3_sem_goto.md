// Implementação em Java
int j = -3;
for (int i = 0; i < 3 && j <= 0; i++) {
    int condicao = j + 2;
    
    if (condicao == 3 || condicao == 2) {
        j--;
    } else if (condicao == 0) {
        j += 2;
    } else {
        j = 0;
    }

    if (j <= 0) {
        j = 3 - i;
    }
}

// Implementação em GO
j := -3
for i := 0; i < 3 && j <= 0; i++ {
    condicao := j + 2
    
    if condicao == 3 || condicao == 2 {
        j--
    } else if condicao == 0 {
        j += 2
    } else {
        j = 0
    }

    if j <= 0 {
        j = 3 - i
    }
}

// Implementação em Php
$j = -3;
for ($i = 0; $i < 3 && $j <= 0; $i++) {
    $condicao = $j + 2;

    if ($condicao == 3 || $condicao == 2) {
        $j--;
    } elseif ($condicao == 0) {
        $j += 2;
    } else {
        $j = 0;
    }

    if ($j <= 0) {
        $j = 3 - $i;
    }
}