## 30. merge
```hs
--IN : Duas listas ordenadas
--OUT: A união de ambas em uma única lista ordenada
--OBS: Percorra cada lista uma única vez na recursão
merge [1,3] [7,7,9] == [1,3,7,7,9]
merge [7,7,9] [1,3] == [1,3,7,7,9]
merge [1,3,5] [4,4,6,7] == [1,3,4,4,5,6,7]
merge [4,4,5,6,7] [1,3] == [1,3,4,4,5,6,7]
```


<!--MAIN_BEGIN-->
### Main
```hs
main = do
    a <- readLn :: IO [Int]
    b <- readLn :: IO [Int]
    print $ merge a b

```
<!--MAIN_END-->
