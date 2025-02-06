
```c
/* ************************************************************************** */
/*                                                                            */
/*                                                        :::      ::::::::   */
/*   whoami.c                                           :+:      :+:    :+:   */
/*                                                    +:+ +:+         +:+     */
/*   By: mortiz-d <mortizdelburgo@gmail.com>        +#+  +:+       +#+        */
/*                                                +#+#+#+#+#+   +#+           */
/*   Created: 2021/10/01 10:05:24 by mortiz-d          #+#    #+#             */
/*   Updated: always by mortiz-d                      ###   ########.fr       */
/*                                                                            */
/* ************************************************************************** */

#include <stdio.h>

struct persona {
    char nombre[50];
    char pais[50];
    char trabajo[50];
    char objetivo[50];
    char aficion[50];
    char universidad[50];
    char titulacion[10];
    char estudios[50];
} s_persona;

void introduccion (struct persona yo)
{
    printf("Soy %s y actualmente resido en %s, en mi tiempo libre he sido voluntario como %s.\n" \
        "Soy una persona que ha completado los estudios troncales de %s y actualmente estoy consiguiendo el %s de %s.\n" \
        "Actualmente soy un %s aunque me estoy desarrollando para convertirme en un %s.\n",yo.nombre, yo.pais,yo.aficion ,yo.universidad,yo.titulacion, yo.estudios, yo.trabajo , yo.objetivo);
    return;
}

int main(void) {
    struct persona yo = {"Miguel Angel", "Madrid / España","Programador","Analista de Datos","⚜️ Monitor Scout ⚜️","42School Madrid","RNCP 6","Software Engineer"};
    introduccion(yo);
    return 0;
}
```

```output
Soy Miguel Angel y actualmente resido en Madrid / España, en mi tiempo libre he sido voluntario como ⚜️ Monitor Scout ⚜️.
Soy una persona que ha completado los estudios troncales de 42School Madrid y actualmente estoy consiguiendo el RNCP 6 de Software Engineer.
Actualmente soy un Programador aunque me estoy desarrollando para convertirme en un Analista de Datos.
```
<div>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mortiz-d&exclude_repo=Other_Projects&theme=dark&langs_count=4">
    <img src="https://github-readme-stats.vercel.app/api?username=mortiz-d&count_private=true&show_icons=true&theme=dark">
</div>

### <p>Lenguajes de programacion que uso:<br></p>
<p>
    <strong>C:</strong>     ★★★★☆<br>
    <strong>C++:</strong>   ★★★☆☆<br>
    <strong>Java:</strong>  ★★★☆☆<br>
    <strong>Python:</strong>★★★☆☆<br>
</p>

### <p>Bases de Datos que he utilizado:<br></p>
<p>
    <strong>MySQL:</strong>     ★★★☆☆<br>
    <strong>MongoDB:</strong>   ★★★☆☆<br>
</p>

### <p>Contenedores y Virtualización:<br></p>
<p>
    <strong>Docker:</strong>         ★★★☆☆<br>
    <strong>Vagrant:</strong>★★★☆☆<br>
    <strong>Virtual Machine:</strong>★★★☆☆<br>
</p>

### <p>Big Data<br></p>
<p>
    <strong>Power BI:</strong>★★☆☆☆<br>
    <strong>Pandas:</strong>★★☆☆☆<br>
    <strong>Excel:</strong>★★★☆☆<br>
</p>
