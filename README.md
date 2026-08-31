# hola-mundo

Contiene un archivo de saludo que sirve de prueba mínima del flujo de trabajo
descrito en [lineamientos-github](https://github.com/fycls-ingenieria/lineamientos-github):
rama, commit convencional, pull request y squash merge.

## Qué necesito instalado

Solo `git`. El repositorio no tiene código que compilar ni dependencias que instalar.

```bash
git --version
```

## Cómo lo levanto

```bash
git clone https://github.com/andros-sierra/hola-mundo.git
cd hola-mundo
```

## Cómo lo pruebo

El contenido del archivo debe ser exactamente `Hola mundo`:

```bash
cat hola-mundo.txt
```

Salida esperada:

```
Hola mundo
```

## Estructura

```
.
├── README.md        # este archivo
├── .gitignore       # exclusiones base de la organización
└── hola-mundo.txt   # el saludo
```

No usa variables de entorno, por lo que no incluye `.env.example`.
