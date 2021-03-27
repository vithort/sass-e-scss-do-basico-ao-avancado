# sass-e-scss-do-basico-ao-avancado
 SASS e SCSS do Básico ao Avançado

## Comandos

- Build do Arquivo

```
sass sass/styles.sass css/styles.css
```

- Build da Pasta em Tempo de Execução

```
sass --watch sass:css
```

# Comentários

// => não é incluso no CSS

/* => é incluso no CSS

/*! => é incluso no CSS, inclusive no modo compressed

é possível interpolar valores nos comentários, ex: #{1 + 3}


## Formatos de Saída CSS

- nested
- expanded
- compact
- compressed

```
sass style.scss style.css --style compact
sass --watch scss:css --style compressed
```
