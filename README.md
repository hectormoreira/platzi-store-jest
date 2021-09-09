# platzi-store
Curso de Pruebas unitarias con Jest


## mount / shallow de `enzine`
- usas `mount` cuando necesitas el DOM
- usas `shallow` solo necesitas algo particular del componente. No ocupas todo el DOM

> Shallow permite traer elementos y probarlos como una unidad. Es útil cuando solo necesito algo particular de ese componente y no necesito toda su estructura y elementos del DOM

## Snapshots
- `jest --update` para actualizar

### Dependencias
- `npm i react-test-renderer -D` Convertir componente a un objeto `json`
- `npm i jest-fetch-mock -D` mock para trabajar con fetch
