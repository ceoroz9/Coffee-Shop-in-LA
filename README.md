# Coffee-Shop-in-LA

## Introducción
He decidido abrir un pequeño café atendido por robots en Los Ángeles. El proyecto es prometedor pero caro, así que con mis compañeros hemos decidido intentar atraer inversionistas. Estamos interesados en las condiciones actuales del mercado, ¿seremos capaces de mantener tu éxito cuando la novedad de los camareros robot desaparezca?

Para la preparación de un estudio de mercado, poseo datos procedentes de fuentes abiertas sobre restaurantes en LA.

## Descripción de datos
Tabla rest_data:

- object_name — nombre del establecimiento
- chain — establecimiento que pertenece a una cadena (TRUE/FALSE)
- object_type — tipo de establecimiento
- address — dirección
- number — número de asientos

Voy a extraer las calles de la direcciones, por lo que necesitaré instalar este módulo: !pip install -q usaddress
