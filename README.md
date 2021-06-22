# LaTeX
LaTeX related files

## Requirements
## [jlisting](https://osdn.net/projects/mytexpert/downloads/26068/jlisting.sty.bz2/)
### Setup
1. Download it from [here](https://osdn.net/projects/mytexpert/downloads/26068/jlisting.sty.bz2/).
2. Copy `jlisting.sty` to `texlive/[year]/texmf-dist/tex/latex`.
3. Run `mktexlsr` on your Terminal (with root / Administrator privileges).
### Insert
```
\begin{lstlisting}
#include <stdio.h>
int main(void){
    printf("Hello world!\n");
}
\end{lstlisting}
```

## License
This repository is licensed under the MIT License.
