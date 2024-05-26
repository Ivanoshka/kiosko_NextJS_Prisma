This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Registro de Progreso

25/05/2024

## Actualizacion 1

Configuración del Proyecto - 10:30 am

Creación del Proyecto con npx-next.app@latest

TypeScript: Sí

ESLint: Sí

Tailwind CSS: Sí

Directorio src/: No

Router de la Aplicación: Sí

Alias de Importación (@/\*): No

## Actualizacion 2 - 11:00 am

Creación de carpetas ProductPage y CreateProductPage

Creación de los contenedores principales

## Actualizacion 3 - 11:50 am

Instalación de Prisma y generación del schema

npm i @prisma/client

npm i -D prisma

npx prisma init

Creación de la base de datos en render

## Actualizacion 4 - 12:15 pm

Modelos en Prisma

Comenzar a crear la base de datos

Migrar los productos cada vez que se hagan cambios

npx prisma migrate dev

## Actualizacion 5 Seeding - 12:30

Agregar datos

instalar la dependencia de ts-node
npm i -D ts-node

ya configurado todo se obtuvieron los datos con el comando:

npx prisma db seed

## Hasta aqui la app tiene base de datos y Contenedores principales- 13:00

## Actualizacion 6 Data Fetching en Next.js - 13:00

Hasta aqui la app obtiene datos de manera correcta
y los muestra en consola

## Actualizacion 7 iterando sobre las categorias 13:30

Hasta aqui la aplicacion muestra ya en el servidor las categorias de la base de datos

## Actualizacion 8 Mostrando las Categorias y los iconos 13:50

Hasta aqui la aplicacion muestra el icono junto con su nombre en el servidor

## Actualizacion 9 Routing dinamico- 14:00

Hasta aqui la aplicacion detecta el click en categoria

## Actualizacion 10 Detectar la categoria actual y obtener los productos 15:00

La aplicacion al dar click en la categoria muestra una consulta a la base de datos de los productos en existencia

## Actualizacion 11 iterando sobre productos 15:20

La aplicacion ya muestra los paquetes y sus precios en el servidor

## Actualizacion 12 Finalizando los Card de productos 15:30

Muestra los componentes de los productos, imagen y boton para agregar al pedido

## Actualizacion 13 Resaltando la categoria actual 15:40

Resalta la categoria en la cual nos encontramos

## Actualizacion 14 Se creo el Store de Zustand 15:50

npm i zustand

## Actualizacion 15 consume el state de orden 16:00

La aplicacion consume el store, la orden aparece en pedido por el momento muestra el texto carrito esta vacio

## Actualizacion 16 Comunica el boton con la store 16:10

Agrega elementos a nuestra orden pero lo muestra en consola

## Actualizacion 17 Agrega articulas a la orden 16:25

La aplicacion ya agrega elementos a la orden visualmente por el momento muestra el mensaje si hay o no hay algo en el carrito

## Actualizacion 18 Mostrando los articulos a la orden 16:35

La aplicacion ya muestra mi pedido con la descripcion cantidad, precio y subtotal.
Visualmente en el servidor

## Actualizacion 19 Evita duplicados 16:50

Al presionar multiples veces en el articulo ya no añade el mismo solucionado

Ademas si presionas el boton agregar se actualiza la cantidad de producto y el subtotal

## Actualizacion 20 Incremntando la Cantidad de un articulo 17:05

SE hizo funcionar el boton de + para incrementar las cantidades
