# Prueba

## Requisitos

* [React](https://react.dev/)
* [NextJs](https://nextjs.org/)

## Requerimientos

dado el siguiente JSON

```json
[
  {
    "id": "6679ac2afe7a1ab59c331627",
    "isActive": false,
    "balance": "$3,987.51",
    "picture": "http://placehold.it/32x32",
    "name": "Esther Rice",
    "gender": "female",
    "email": "estherrice@gonkle.com",
    "address": "128 Beekman Place, Jeff, South Carolina, 9599",
    "about": "Ut incididunt anim do in eu adipisicing deserunt deserunt. Do sit magna non id fugiat labore irure in irure ipsum laborum. Culpa voluptate excepteur reprehenderit velit. Ut culpa aute velit velit cillum aliquip nulla minim irure labore voluptate reprehenderit. Commodo culpa tempor laborum nulla anim non.\r\n",
    "registered": "2016-03-22T04:56:52 -01:00"
  },
  {
    "id": "6679ac2a2c7673b872041588",
    "isActive": true,
    "balance": "$2,903.28",
    "picture": "http://placehold.it/32x32",
    "name": "Mendez Hood",
    "gender": "male",
    "email": "mendezhood@gonkle.com",
    "address": "586 Schweikerts Walk, Nash, Virginia, 1618",
    "about": "Velit cupidatat tempor ex Lorem occaecat eu do dolor excepteur duis consequat cupidatat. Exercitation sint adipisicing cillum qui enim adipisicing qui pariatur ut dolore sit aliquip reprehenderit occaecat. Nulla anim magna adipisicing minim do quis. Voluptate non nulla esse irure.\r\n",
    "registered": "2022-10-18T02:27:12 -02:00"
  },
  {
    "id": "6679ac2a90e3254a0f9a804b",
    "isActive": true,
    "balance": "$3,109.94",
    "picture": "http://placehold.it/32x32",
    "name": "Rosalinda Rowe",
    "gender": "female",
    "email": "rosalindarowe@gonkle.com",
    "address": "313 Eagle Street, Statenville, American Samoa, 4891",
    "about": "Eu deserunt qui pariatur deserunt adipisicing et adipisicing sint ut sit nulla voluptate. Officia cupidatat nisi veniam aute do irure eu. Eiusmod sunt irure dolore cillum mollit voluptate exercitation aute laboris sunt tempor nostrud. Aliquip sunt veniam elit esse esse duis ipsum dolor ea officia.\r\n",
    "registered": "2017-12-17T04:15:23 -01:00"
  },
  {
    "id": "6679ac2a7242ed8ea94dfd23",
    "isActive": false,
    "balance": "$3,604.51",
    "picture": "http://placehold.it/32x32",
    "name": "Jerri Calderon",
    "gender": "female",
    "email": "jerricalderon@gonkle.com",
    "address": "965 Brooklyn Avenue, Tedrow, Wisconsin, 425",
    "about": "Consequat nostrud quis et ad excepteur. Exercitation consectetur minim sint ipsum do commodo veniam eiusmod non esse qui irure. Non exercitation culpa mollit velit. Ex qui voluptate id exercitation labore minim anim laboris irure. Est cillum mollit ad ad eiusmod. Cupidatat commodo quis tempor esse sunt sint deserunt dolore officia esse ullamco fugiat sunt.\r\n",
    "registered": "2014-03-21T12:42:02 -01:00"
  },
  {
    "id": "6679ac2a7d53c720f456b766",
    "isActive": true,
    "balance": "$3,713.06",
    "picture": "http://placehold.it/32x32",
    "name": "Freeman Kinney",
    "gender": "male",
    "email": "freemankinney@gonkle.com",
    "address": "298 Wyckoff Street, Bonanza, Ohio, 8243",
    "about": "Aliqua cupidatat commodo velit aute veniam nostrud esse eiusmod ut sint id ut aute. Excepteur consequat ad ullamco incididunt do do esse. Est amet mollit esse in minim.\r\n",
    "registered": "2016-04-03T07:26:28 -02:00"
  }
]
```

Se requiere que se generen componentes de `react` mediante los cuales de maneje un `CRUD`. Como mínimo deben haber 2 compoentes

* Un componente que liste el contenido del `JSON` y permita editar un registro
* Un componente que muestre un registro para modificarlo

## Considearicions

* Se deben generar las columnas y los campos de manera dinámica no pueden estar fijas en el codigo

* El componente que liste se debe poder alojar en una pagina

* El componente que edite se debe poder Alojar en otra pagina de detalle

* Se deben poder crear nuevos elementos

* Se debe poder eliminar elementos

## Bonus track

* Los tipos de campos pudieran configurarse

* Abstracción de la capa de datos