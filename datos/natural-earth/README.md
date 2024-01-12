# Natural Earth

[Natural Earth](https://www.naturalearthdata.com/)

## Datos utilizados

### Países

```bash
# Archivos SHP comprimidos
wget -P datos/natural-earth \
  https://www.naturalearthdata.com/http//www.naturalearthdata.com/download/10m/cultural/ne_10m_admin_0_countries.zip

# Archivos SHP descomprimidos
unzip datos/natural-earth/ne_10m_admin_0_countries.zip -d datos/natural-earth
```