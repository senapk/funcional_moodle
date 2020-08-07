## 41. vetFib
[](solver.hs)
Gere os n primeiros termos da série de Fibonacci

```hs
vetFib 2 == [0,1]
vetFib 6 == [0,1,1,2,3,5]
vetFib 9 == [0,1,1,2,3,5,8,13,21]
```

## Guia
- Faça os casos base para 0, 1 e 2
- Para n use o `let` ou `where` para calcular o vetor que os precede.
    - depois concatene com o valor atual que é a posição dos índices (n - 3) e (n - 2) do vetor.

<!--MAIN_BEGIN-->
### Main
```hs
main = do
    a <- readLn :: IO Int
    print $ vetFib a

```
<!--MAIN_END-->
