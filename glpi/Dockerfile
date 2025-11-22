# Imagen base ya preparada para GLPI
FROM diouxx/glpi:latest

# Copia tu código GLPI al contenedor
COPY glpi /var/www/html

# Ajusta permisos
RUN chown -R www-data:www-data /var/www/html
