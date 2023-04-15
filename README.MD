
# RLE

[Rle](https://pt.wikipedia.org/wiki/Codifica%C3%A7%C3%A3o_run-length) é um modo de compressão de texto.



## Apêndice

Esse é um código que fiz a 6 anos atrás na linguagem de script KiXtart.
Essa é um linguagem que aprendi um pouco antes de 2017, eu aprendi ela sem querer, e ela foi a primeira linguagem que aprendi que fazia manipulação de objeto(isso porque ela não cria objetos)


## Funcionalidades

- Comprimir texto
- Descomprimir texto

 
## Uso/Exemplos

```kixtart
include "rle.udf" // call "rle.udf"

"ORIGINAL   : KiiiiiXXXtarttttt"?
"COMPRESS   : " RLE("KiiiiiXXXtarttttt", 1,'*')?
"DECOMPRESS : " RLE("Ki*5XXXtart*5",0,'*')?
get$
```

```
> kixtart temp.kix
ORIGINAL   : KiiiiiXXXtarttttt
COMPRESS   : Ki*5XXXtart*5
DECOMPRESS : KiiiiiXXXtarttttt
```


## Licença

[MIT](https://choosealicense.com/licenses/mit/)

