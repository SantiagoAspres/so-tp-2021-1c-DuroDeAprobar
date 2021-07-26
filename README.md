# so-tp-2021-1c-DuroDeAprobar

Trabajo práctico cuatrimestral de la cátedra de Sistemas Operativos (1c2021) UTN FRBA. [Enunciado](https://docs.google.com/document/d/1u54jk7uKaa6BOAXgLuNVfeYN_mwPBje94iX_6KqvqJo/edit#) / [Pruebas](https://docs.google.com/document/d/1rorLRNnwpM9kKxeuHAwM0mmNN20X0Mb20Q-I66y6sdc/edit).

Integrantes: 
<a href="https://github.com/andresbulgheroni" target="_blank" rel="noopener noreferrer">andresbulgheroni</a> - 
<a href="https://github.com/celeslvp" target="_blank" rel="noopener noreferrer">celeslvp</a> - 
<a href="https://github.com/SantiagoAspres" target="_blank" rel="noopener noreferrer">SantiagoAspres</a> - 
<a href="https://github.com/smchejolan" target="_blank" rel="noopener noreferrer">smchejolan</a> - 
<a href="https://github.com/snouthill" target="_blank" rel="noopener noreferrer">snouthill</a>.

---
 
<p align="center">
  <img src="https://user-images.githubusercontent.com/62316777/125995719-436fd46a-9d69-4689-8611-d01ee7fc1bee.png" alt="Duro de Aprobar"/>
</p>

---

## Guía de deploy

```sh
git clone https://github.com/snouthill/so-tp-2021-1c-DuroDeAprobar.git
cd tp-2021-1c-DuroDeAprobar
./install.sh -f
```

El script `install.sh` también acepta los siguientes parámetros:

| `./install.sh -f` | Instalar las dependencias requeridas y compilar todos los módulos |
| -------- | -------- |
| `./install.sh -d` | Instalar las dependencias requeridas|
| `./install.sh -c` | Compilar todos los módulos |

---

## Iniciando módulos

Los módulos podrán iniciarse corriendo los scripts `i_Mongo_Store.sh`, `mi_Ram_Hq.sh` y `discordiador.sh`, en ese orden, con el parámetro correspondiente:

| `./<módulo> -i` | Iniciar módulo normalmente|
| -------- | -------- |
| `./<módulo> -v` | Ejecutar módulo con chequeo de memoria de Valgrind|
| `./<módulo> -c` | Compilar módulo y luego ejecutarlo |


