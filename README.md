# 🚀 Sinclair QL Planet

A static news aggregator bringing together posts, articles, and news from the **Sinclair QL** retro scene and community.

🌐 **Live Website:** [https://JavGuerra.github.io/Sinclair-QL-planet/](https://JavGuerra.github.io/Sinclair-QL-planet/)

---

## 📌 How does it work?

This site is automatically compiled every hour using **GitHub Actions** and the static site generator [Pluto](https://github.com/feedreader/pluto). It fetches the RSS/Atom feeds from community blogs and merges them into a single timeline.

---

## ➕ Want to add your Sinclair QL blog or website?

### Via repository

Contributions are more than welcome! If you run a blog, news channel, or website with an RSS/Atom feed dedicated to the Sinclair QL or Motorola 68000 retro computing:

1. **Fork** this repository.
2. Edit the `planet.ini` file by adding your site at the end:

```ini
[your-blog]
  title = Your Site Title
  link  = [https://yoursite.com](https://yoursite.com)
  feed  = [https://yoursite.com/feed.xml](https://yoursite.com/feed.xml)
```

3. Open a Pull Request. Once merged, your posts will automatically appear on the planet.

### Even simpler

Contact the author through another medium to share your link.

## 📄 License

This project is dedicated to the public domain under the Creative Commons Zero v1.0 Universal (CC0 1.0) license. See the [LICENSE](LICENSE.md) file for details.

---
Español

---

# 🚀 Planeta Sinclair QL

Un agregador de noticias estático que reúne publicaciones, artículos y novedades de la comunidad y la escena retro del **Sinclair QL**.

🌐 **Sitio web en vivo:** [https://JavGuerra.github.io/Sinclair-QL-planet/](https://JavGuerra.github.io/Sinclair-QL-planet/)

---

## 📌 ¿Cómo funciona?

Este sitio se compila de forma automática cada hora mediante **GitHub Actions** utilizando el generador estático [Pluto](https://github.com/feedreader/pluto). Lee los canales RSS/Atom de los blogs de la comunidad y los unifica en un único feed.

---

## ➕ ¿Quieres añadir tu blog o sitio web del Sinclair QL?

### Vía repositorio

¡Las contribuciones son más que bienvenidas! Si tienes un blog, un canal de noticias o una web con feed RSS/Atom sobre el Sinclair QL o la arquitectura Motorola 68000 en computación retro:

1. Haz un **Fork** de este repositorio.
2. Edita el archivo `planet.ini` añadiendo tu sitio al final:

```ini
[tu-blog]
  title = Nombre de tu sitio
  link  = [https://tusitio.com](https://tusitio.com)
  feed  = [https://tusitio.com/feed.xml](https://tusitio.com/feed.xml)
```
3. Abre un Pull Request. Una vez aprobado, tu contenido aparecerá automáticamente en el planeta.

### Más sencillo aún

Contacta con el autor por otro medio para comunicar tu enlace.

## 📄 Licencia

Este proyecto está dedicado al dominio público bajo la licencia Creative Commons Zero v1.0 Universal (CC0 1.0). Consulta el archivo [LICENSE](LICENSE.md) para más detalles.