# Coding Standards for ApiElecciones

Este documento describe los estándares de codificación utilizados en la aplicación ApiElecciones. Seguir estas convenciones ayuda a mantener el código legible, consistente y fácil de mantener.

## 1. Nombramiento de Variables
- Utilizar **camelCase** para variables locales y propiedades de objetos.
- Los nombres deben ser descriptivos y en inglés (ejemplo: `userName`, `candidateList`).

## 2. Nombramiento de Constantes
- Utilizar **MAYÚSCULAS_CON_GUIONES_BAJO** para constantes globales (ejemplo: `MAX_ATTEMPTS`).
- Para constantes de solo uso local, se puede usar camelCase.

## 3. Nombramiento de Métodos o Funciones
- Utilizar **camelCase**.
- El nombre debe describir claramente la acción que realiza (ejemplo: `getCandidates()`, `validateLogin()`).

## 4. Nombramiento de Clases
- Utilizar **PascalCase** (primera letra de cada palabra en mayúscula).
- El nombre debe ser un sustantivo singular (ejemplo: `User`, `CandidateManager`).

## 5. Nombramiento de Paquetes (Carpetas)
- Utilizar **minúsculas** y, si es necesario, separar palabras con guiones (ejemplo: `js/`, `css/`, `pages/`).

## 6. Documentación de Métodos o Funciones
- Documentar cada función o método con un comentario JSDoc antes de su declaración.
- Incluir descripción, parámetros y valor de retorno.

Ejemplo:
```js
/**
 * Valida las credenciales del usuario.
 * @param {string} username - Nombre de usuario.
 * @param {string} password - Contraseña del usuario.
 * @returns {boolean} True si las credenciales son válidas, false en caso contrario.
 */
function validateLogin(username, password) {
  // ...
}
```

## 7. Otros Estándares
- Indentación de 2 espacios.
- Evitar variables globales innecesarias.
- Usar comentarios para explicar lógica compleja.

---

Cumplir con estos estándares asegura un código más limpio y profesional en ApiElecciones.
