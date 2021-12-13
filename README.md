# BaBoost6AnkHelloGitHub
## BaBoost6AnkHelloGitHub
### BaBoost6AnkHelloGitHub
#### BaBoost6AnkHelloGitHub
##### BaBoost6AnkHelloGitHub
###### BaBoost6AnkHelloGitHub

----
**Markdown cheatsheet:** soldaki bold yazı [CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

----
 
![](https://cdn-icons-png.flaticon.com/512/25/25231.png)

![Kırık Resim](Link)

![](https://camo.githubusercontent.com/a433273b618d7b8c2569ba6013774adf910ae8e3da45eaff176f64781bfd53fc/68747470733a2f2f72617069646170692e636f6d2f626c6f672f77702d636f6e74656e742f75706c6f6164732f323031372f30312f6f63746f6361742e676966)


""Not:""

- CTRL + A : imlecin bulunduğu tüm sayfayı seçer.
  - 1.deneme
    - 2.deneme
     - 3.deneme
      - 4.deneme
- CTRL + C : imlecin bulunduğu satırı kopyalar.
- CTRL + V : kopyalananı yapıştırır.
- CTRL + X : imlecin bulunduğu satırı keser.(Yapıştırılabilir!)
- CTRL + Z : Geri alır.
- CRTL + Y : ileri alır.
- Home tuşu satırın başına gider.
- End tuşu satırın sonuna gider.
- SHIFT + HOME satır başına kadar hepsini seçer.
- SHIFT + END satır sonuna kadar hepsini seçer.
- SHIFT + yön tuşları ile belirli aralık seçer .
- try.dot.net sitesi browser editör...
- alttaki semböl altgr + ; ile yapılıyor!!!
```cs

using System;
using System.Collections.Generic;
using System.Linq;

public class Program
{
  public static void Main()
  {
    foreach (var i in Fibonacci().Take(20))
    {
      Console.WriteLine(i);
    }
  }

  private static IEnumerable<int> Fibonacci()
  {
    int current = 1, next = 1;

    while (true) 
    {
      yield return current;
      next = current + (current = next);
    }
  }
}

```
