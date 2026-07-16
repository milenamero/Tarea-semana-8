# Restaurante App

## Nombre del estudiante

Milena Mayerli Mero Loor

---

## Descripción

Sistema desarrollado en Python utilizando Programación Orientada a Objetos para administrar productos, bebidas y clientes mediante un menú interactivo por consola.

---

## Estructura

```
restaurante_app/
│
├── modelos/
│   ├── producto.py
│   ├── bebida.py
│   └── cliente.py
│
├── servicios/
│   └── restaurante.py
│
└── main.py
```

---

## Responsabilidad de cada clase

**Producto**

Representa un producto general del restaurante.

**Bebida**

Hereda de Producto y agrega el atributo tamaño.

**Cliente**

Representa la información de un cliente.

**Restaurante**

Administra el registro y listado de productos y clientes.

**main.py**

Gestiona el menú e interacción con el usuario.

---

## Relación entre Producto y Bebida

La clase Bebida hereda de Producto porque una bebida es un tipo de producto. Esto permite almacenar ambos objetos en una sola colección y utilizar polimorfismo mediante el método mostrar_informacion().

---

## Principios SOLID aplicados

### SRP

Cada clase tiene una única responsabilidad.

### OCP

El sistema puede ampliarse mediante la clase Bebida sin modificar la lógica principal.

### LSP

Los objetos Bebida pueden utilizarse donde se espera un Producto.

---

## Ejecución

Abrir una terminal dentro de la carpeta restaurante_app y ejecutar:

```
python main.py
```

---

## Reflexión

La Programación Orientada a Objetos permite desarrollar aplicaciones organizadas, fáciles de mantener y ampliar, separando correctamente las responsabilidades de cada clase.