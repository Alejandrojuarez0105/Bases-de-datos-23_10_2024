# Clase pasada

#Utiliza el Álgebra Relacional para las consultas
#Pregunta_1 : Se requieren todos los registros de la relación Actor cuyo primer nombre sea DAN y el apellido TORN.

relational_response_1="σ_firstname='DAN'^lastname='TORN'_(Actor)"

#Pregunta_2 : Se requieren todos los apellidos, sin duplicados de la relación Actor.

relational_response_2="∏lastname_(Actor)"

#Pregunta_3 : Se requiere renombrar la relación Actor a Instructor

relational_response_3="pInstructor(Actor)"


---
Todas las relaciones van con letra inicial mayúscula

Al incluir el nombre de la base de datos en un predicado se debe utilizar el punto y todo el predicado en minúsculas.

Ej r.campoid y no R.campoid

---
Todos los predicados de la selección se colocan entre guiones bajos.

Ej σ_campoid=valor_(R)

---
Si el campo en cuestión, tiene guiones bajos originalmente, estos se eliminaran en el momento de hacer la consulta.

Ej En la relación original: campo_id;en la consulta se sustituye por campoid

---

Todos los predicados de la selección se separan por operadores.

Ej σ_campoid>valor^campoid<=valor_(R)

Entre el último atributo de la selección y la relación hay un guión bajo.

---
Proyección
Entre una proyección y una selección hay un espacio en blanco.

Ej ∏v.id,pr.nombre,v.cantidad σ_v.cantidad>9_(R)

La proyección no incluye espacios en blanco entre sus atributos

Ej ∏v.id,pr.nombre,v.cantidad

Los atributos de la proyección se separan por comas

Ej ∏v.id,pr.nombre,v.cantidad

Entre los atributos de una proyección y un renombramiento hay un espacio en blanco

Ej ∏proveedores.nombre_pR3(R1)

---
Notaciones
σ
∏
⋈
p
:

---