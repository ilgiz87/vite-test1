# Изучение Vite

по урокам на [YouTube](https://www.youtube.com/watch?v=SBtNHd7ZBn4&list=PL-FhWbGlJPfZg649Ukk5vPa4nUjHhQ6o3 "Курс по разработке современных frontend проектов с помощью сборщика нового поколения Vite.")

Официальный [гайд Vite](https://vite.dev/guide/)

## Установка Vite
```shell
npm create vite@latest
```
### Vite Plugin Inspect

**Vite Plugin Inspect** — это плагин для Vite, который позволяет инспектировать промежуточные преобразования кода в процессе сборки. 
Станица на [NPMJS.com](https://www.npmjs.com/package/vite-plugin-inspect)
#### Установка 
```bash
npm i -D vite-plugin-inspect
```
Добавьте плагин в свой `vite.config.js`:
```javascript
// vite.config.js
import Inspect from 'vite-plugin-inspect'

export default {
  plugins: [
    Inspect()
  ],
}
```
