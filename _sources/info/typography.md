---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Типографские соглашения

## Программный код

Пример кода внутри строки, обозначается так: `echo "Hello, World!"`.

Команда вводимая в терминал Unix подобных систем:
:::bash
echo "Hello, World!"
:::
Символ **$** является приглашением командной строки. Его вводить не нужно.

Команда вводимая в командной строке Windows подобных систем:
```shell
echo "Hello, World!"
```
Символы **C:\\>** являются приглашением командной строки. Их вводить не нужно.

Команда вводимая в терминал Unix подобных систем вместе с выводом:
```bash
echo "Hello, World!"
```
```{code-cell} ipython3
:tags: ["remove-input"]
%%bash
echo "Hello, World!"
```

Python код выглядит
```python
message = "Hello, World!"
print(message)
```
А так — python код и результат его исполнения

```{code-cell} ipython3
message = "Hello, World!"
print(message)
```

```{code-cell} python
%%bash
message="Hello, World!"
echo $message
```

```console
echo "Hello, World!"
echo "Hello, World!"
echo "Hello, World!"
echo "Hello, World!"
echo "Hello, World!"
echo "Hello, World!"
```

```{code-cell} python
! message="Hello, World!"
! echo $message
! pwd
```

```{code-cell} python
! message="Hello, World!"
! echo $message
! pwd
```


+++

## Графические выделения

<!--
```{admonition} This is a title
:class: note
:class: warning
:class: tip
:class: caution
:class: attention
:class: danger
:class: error
:class: hint
:class: important
:class: seealso
An example of an admonition with a title.
```
-->

```{note}
Так обозначаются замечания общего характера.
```

```{admonition} Совет
Так обозначаются советы и рекомендации,
```

```{hint}
Так обозначаются подсказки.
```

```{admonition} Смотрите также
:class: seealso
Так обозначаются ссылки на материал по теме.
```

```{attention}
Материал, требующий особого внимания обозначается так.
```

```{warning}
Так обозначаются предупреждения и предостережения.
```

```{error}
Так обозначаются действия, которые могут привести к ошибке.
```

```{danger}
Потенциально опасные действия, обозначаются так.
```



+++

## Математика

````{prf:theorem} Теорема Пифагора
:label: thm-pythagor

В прямоугольном треугольнике, длины катетов которого равны $a$ и $b$, а длина гипотенузы — $c$, выполнено соотношение
$a^2 + b^2 = c^2$.
````
