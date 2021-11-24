## Strona internetowa stworzona na narzędzia informatyczne

Projekt na przedmiot Narzędzia Informatyczne w roku akademickim 2021/2022 na kierunku Informatyka i Systemy Inteligentne

### Obecne projekty

- Studentka Informatyki i Systemów inteligentnych
- Członek zespołu _DeadPxlz_
- [hobby artystyczne](https://drive.google.com/drive/folders/15ADb8wdDfpK6yUYaHwPKNJutCHW3Wk0-?usp=sharing)

### Snippet mojej częsci kodu projektu

```
def sortuj(name):
  dict = {}
  file = open(name, "r")
  for line in file:
    x, y = line.split(' ')
    dict[int(x)] = y #jeżeli wynik jest taki sam, zostanie zastąpiony w słowniku, ale nie w pliku
  x = 0
  for i in sorted(dict, reverse=True):
    print("%s " %i, dict[i])
    if (x==9):
      break
    x+=1
 
```

