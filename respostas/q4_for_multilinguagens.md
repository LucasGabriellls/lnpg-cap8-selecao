// Implementação em Php
$n = 100;
$sum = 0;
for ($i = 0, $j = 17; $i < $n; $i++, $j--) {
    $sum += $i * $j + 3;
}

// Implementação em Go
n := 100
sum := 0
j := 17
for i := 0; i < n; i, j = i+1, j-1 {
    sum += i * j + 3
}

// Implementação em Swift
let n = 100
var sum = 0
var j = 17
for i in 0..<n {
    sum += i * j + 3
    j -= 1
}

// Implementação em Lua
local n = 100
local sum = 0
local j = 17
for i = 0, n - 1 do
    sum = sum + (i * j + 3)
    j = j - 1
end

// Implementação em C++
int n = 100;
int sum = 0;
for (int i = 0, j = 17; i < n; i++, j--) {
    sum += i * j + 3;
}