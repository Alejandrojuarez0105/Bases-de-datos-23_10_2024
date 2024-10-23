# Bases-de-datos-23_10_2024


#Utiliza el Álgebra Relacional para las consultas
# Pregunta_1 : Se requieren todos los registros de la relación Actor cuyo primer nombre sea DAN y el apellido TORN.

relational_response_1="σ_firstname='DAN'^lastname='TORN'_(Actor)"

#Pregunta_2 : Se requieren todos los apellidos, sin duplicados de la relación Actor.

relational_response_2="∏lastname_(Actor)"

#Pregunta_3 : Se requiere renombrar la relación Actor a Instructor

relational_response_3="pInstructor(Actor)"

