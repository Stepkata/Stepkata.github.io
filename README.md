## Strona internetowa stworzona na narzędzia informatyczne

Projekt na przedmiot Narzędzia Informatyczne w roku akademickim 2021/2022 na kierunku Informatyka i Systemy Inteligentne

### Obecne projekty

- Studentka Informatyki i Systemów inteligentnych
- Członek zespołu _DeadPxlz_

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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Stepkata/Stepkata.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
