# Math
## [Trigonometric Functions](https://en.wikipedia.org/wiki/Trigonometric_functions) in [Taylor Series](https://en.wikipedia.org/wiki/Taylor_series)

### 1. Formula

|$sin(x)$|$cos(x)$|$tan(x)$|
|---|---|---|
|$\displaystyle\sum_{n=0}^∞ \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$\displaystyle\sum_{n=0}^∞ \frac{(-1)^n}{(2n)!}x^{2n}$|$\displaystyle\sum_{n=1}^∞ \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$|


#### 1.1.

|$sin(x)$|
|---|

||Expansion|
|:---:|---|
|$\displaystyle\sum_{n=0}^0 \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x$|
|$\displaystyle\sum_{n=0}^1 \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}$|
|$\displaystyle\sum_{n=0}^2 \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}$|
|$\displaystyle\sum_{n=0}^3 \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}$|
|$\displaystyle\sum_{n=0}^4 \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\frac{x^9}{9!}$|
|$\displaystyle\sum_{n=0}^5 \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\frac{x^9}{9!}-\frac{x^{11}}{11!}$|
|$\displaystyle\sum_{n=0}^6 \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\frac{x^9}{9!}-\frac{x^{11}}{11!}+\frac{x^{13}}{13!}$|
|$\displaystyle\sum_{n=0}^7 \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\frac{x^9}{9!}-\frac{x^{11}}{11!}+\frac{x^{13}}{13!}-\frac{x^{15}}{15!}$|
|$\displaystyle\sum_{n=0}^8 \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\frac{x^9}{9!}-\frac{x^{11}}{11!}+\frac{x^{13}}{13!}-\frac{x^{15}}{15!}+\frac{x^{17}}{17!}$|
|$\displaystyle\sum_{n=0}^9 \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\frac{x^9}{9!}-\frac{x^{11}}{11!}+\frac{x^{13}}{13!}-\frac{x^{15}}{15!}+\frac{x^{17}}{17!}-\frac{x^{19}}{19!}$|
|$\displaystyle\sum_{n=0}^{10} \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\frac{x^9}{9!}-\frac{x^{11}}{11!}+\frac{x^{13}}{13!}-\frac{x^{15}}{15!}+\frac{x^{17}}{17!}-\frac{x^{19}}{19!}+\frac{x^{21}}{21!}$|
|$\displaystyle\sum_{n=0}^{11} \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\frac{x^9}{9!}-\frac{x^{11}}{11!}+\frac{x^{13}}{13!}-\frac{x^{15}}{15!}+\frac{x^{17}}{17!}-\frac{x^{19}}{19!}+\frac{x^{21}}{21!}-\frac{x^{23}}{23!}$|
|$\displaystyle\sum_{n=0}^{12} \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\frac{x^9}{9!}-\frac{x^{11}}{11!}+\frac{x^{13}}{13!}-\frac{x^{15}}{15!}+\frac{x^{17}}{17!}-\frac{x^{19}}{19!}+\frac{x^{21}}{21!}-\frac{x^{23}}{23!}+\frac{x^{25}}{25!}$|
|$\displaystyle\sum_{n=0}^{13} \frac{(-1)^n}{(2n + 1)!}x^{2n+1}$|$x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+\frac{x^9}{9!}-\frac{x^{11}}{11!}+\frac{x^{13}}{13!}-\frac{x^{15}}{15!}+\frac{x^{17}}{17!}-\frac{x^{19}}{19!}+\frac{x^{21}}{21!}-\frac{x^{23}}{23!}+\frac{x^{25}}{25!}-\frac{x^{27}}{27!}$|

#### 1.2.

|$cos(x)$|
|---|

||Expansion|
|:---:|---|
|$\displaystyle\sum_{n=0}^0 \frac{(-1)^n}{(2n)!}x^{2n}$|$1$|
|$\displaystyle\sum_{n=0}^1 \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}$|
|$\displaystyle\sum_{n=0}^2 \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}$|
|$\displaystyle\sum_{n=0}^3 \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}$|
|$\displaystyle\sum_{n=0}^4 \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\frac{x^8}{8!}$|
|$\displaystyle\sum_{n=0}^5 \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\frac{x^8}{8!}-\frac{x^{10}}{10!}$|
|$\displaystyle\sum_{n=0}^6 \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\frac{x^8}{8!}-\frac{x^{10}}{10!}+\frac{x^{12}}{12!}$|
|$\displaystyle\sum_{n=0}^7 \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\frac{x^8}{8!}-\frac{x^{10}}{10!}+\frac{x^{12}}{12!}-\frac{x^{14}}{14!}$|
|$\displaystyle\sum_{n=0}^8 \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\frac{x^8}{8!}-\frac{x^{10}}{10!}+\frac{x^{12}}{12!}-\frac{x^{14}}{14!}+\frac{x^{16}}{16!}$|
|$\displaystyle\sum_{n=0}^9 \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\frac{x^8}{8!}-\frac{x^{10}}{10!}+\frac{x^{12}}{12!}-\frac{x^{14}}{14!}+\frac{x^{16}}{16!}-\frac{x^{18}}{18!}$|
|$\displaystyle\sum_{n=0}^{10} \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\frac{x^8}{8!}-\frac{x^{10}}{10!}+\frac{x^{12}}{12!}-\frac{x^{14}}{14!}+\frac{x^{16}}{16!}-\frac{x^{18}}{18!}+\frac{x^{20}}{20!}$|
|$\displaystyle\sum_{n=0}^{11} \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\frac{x^8}{8!}-\frac{x^{10}}{10!}+\frac{x^{12}}{12!}-\frac{x^{14}}{14!}+\frac{x^{16}}{16!}-\frac{x^{18}}{18!}+\frac{x^{20}}{20!}-\frac{x^{22}}{22!}$|
|$\displaystyle\sum_{n=0}^{12} \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\frac{x^8}{8!}-\frac{x^{10}}{10!}+\frac{x^{12}}{12!}-\frac{x^{14}}{14!}+\frac{x^{16}}{16!}-\frac{x^{18}}{18!}+\frac{x^{20}}{20!}-\frac{x^{22}}{22!}+\frac{x^{24}}{24!}$|
|$\displaystyle\sum_{n=0}^{13} \frac{(-1)^n}{(2n)!}x^{2n}$|$1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+\frac{x^8}{8!}-\frac{x^{10}}{10!}+\frac{x^{12}}{12!}-\frac{x^{14}}{14!}+\frac{x^{16}}{16!}-\frac{x^{18}}{18!}+\frac{x^{20}}{20!}-\frac{x^{22}}{22!}+\frac{x^{24}}{24!}-\frac{x^{26}}{26!}$|

#### 1.3.

|$tan(x)$|
|---|

||Expansion|
|:---:|---|
|$\displaystyle\sum_{n=1}^1 \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^2 \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^3 \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^4 \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^5 \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^6 \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^7 \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^8 \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^9 \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{10} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{11} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{12} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{13} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{14} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{15} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{16} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{17} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{18} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{19} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
|$\displaystyle\sum_{n=1}^{20} \frac{(-1)^{n-1}2^{2n}(2^{2n}-1)B_{2n}}{(2n)!}x^{2n-1}$||
