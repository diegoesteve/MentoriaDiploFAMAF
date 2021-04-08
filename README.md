# MentoriaDiploFAMAF

Los archivos tienen información de aquellos interesados que hicieron alguna búsqueda de entrenamientos/capacitaciones

El objetivo sería, hacer recomendaciones del tipo:
Si buscaste el entrenamiento A también puede interesarte el entrenamiento B

contacts.csv contiene el ID de lead y su ubicación geográfica
trainings tiene el nombre de la capacitación, el tipo y los tags (la forma en que un potencial interesado puede buscar la capacitación)
InfoRequest se dividió en 6 archivos debido al tamaño (para poder compartirlo por acá)

contacts se une con InfoRequests por _id y contacts_id
InfoRequest se une a trainings con el tag: name y training_name
