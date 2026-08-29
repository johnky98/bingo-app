Coloca aquí los archivos de logo de los patrocinadores (PNG/JPG, fondo transparente
recomendado, altura sugerida ~200px).

Luego, en modulo_balotera/index.html, agrega una línea por cada uno dentro del
arreglo PATROCINADORES (cerca del inicio del <script>), por ejemplo:

  const PATROCINADORES = [
    { nombre: 'Nombre del patrocinador', archivo: 'patrocinadores/logo1.png' },
  ];

El banner en la pantalla de la tómbola se actualiza solo, sin tocar nada más.
