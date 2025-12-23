# GlobalSmart
Arquitectura por features combinada con Clean Architecture y Hexagonal

## Bugs
- Implementar DictionaryLabel en todos los sitios posibles. Posible implementacion futura (i8n)?

### Login

- Mejorar separación de elementos: useCase -> service -> Adapter (si fuese posible) para un mejor uso de la arquitectura.
- LoginContainer usa demasiados elementos Redux, useCases, cuando solo es un componente, en vez de un page habitual.

#### ResetPassword
- nombres poco entendibles metodos de service.
- Misma problematica separacion elementos, el adapter no hace nada.
- SendEmail buen componente, NewPassword revisar

#### ChallengeNewPassword y challenge2FA
- Puedo acceder sin problema a esta URL introduciendola desde el navegador /login/...


### Main (Cuadro de mando)
- No tiene diseño responsive, cuando hago un poco más pequeño el navegador (mitad de una pantalla 16:9, no se aprecia el navbar)

#### Navbar
##### Enviroment
- Renombrar variables (innecesario poner Service y Adapter)
- Mal uso arquitectura separación elementos

##### UserBlock
- Usar DictionaryLabel

#### HorizontalBar
- Visualmente, le meteria un margin top (mt-5)
- 

- UseCases:
	+ Brand: no se usa
	

### Verticales
A nivel visual es muy mejorable, se puede aprovechar mucho mejor el espacio

Componentes(xxxGraphs):
- Se puede cambiar el tamaño, y los detalles y el boton, mas aprovechable
- Usar solo un componente, no crear tres componentes similares
- Usar DictionaryLabel

#### FullScreenMap
Componente enorme que se ira viendo más tarde


### Inventario (dispositivos)
- Bastante refactorización se puede hacer
- UseCases mejorable a nivel de nombres de variables, metodos que se pueden movera otros archivos

#### Añadir dispositivos (addDevices)
- Formulario enorme, necesita una buena refactorización (aislar formulario?)
- Separacion de elementos (usecases, service, adapter)


## Mejoras
### Visuales