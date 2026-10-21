• La tabla de controles: cada Input Action con su tecla y su botón del controlador arcade.
  Ñ la bola re-spawnea en un punto determinado
  Q la palanca izq del pinball se mueve
  E la palanca drch del pinball se mueve
  WASD para moverse en el escenario
  Espacio para saltar

• Los valores físicos finales de la bola y del material físico.
Bola:
Simulate Physics = true
Mass (Kg) = 0,1
Linear Damping = 0
Angular Damping = 0
Enable Graviti = true

Material:
  Friction = 0.7
  Static friction = 0
  Restituition = 0,3
  Density = 1 g/cm³
  Sleep linear velocity Threshold = 1
  Sleep Angular velocity Threshold = 0,05
  Sleep counter Threshold = 4


• La lista de mejoras implementadas (efectos, game feel, escenario, nuevos elementos…)
  - he decorado el escenario añadiendo una barrera fisica y unos coches de policia para impedir que el jugador salga de la zona del pinball
