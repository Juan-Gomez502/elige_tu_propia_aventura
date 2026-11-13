# elige_tu_propia_aventura
Un repositorio para que los estudiantes de cuarto, completen el punto dos de un codigo para elegir tu propia aventura

Clases,	No define ninguna clase.
Objetos propios,	No crea objetos de clases propias.
Archivos separados,	Todo está en un único archivo Python.
Organización,	Mezcla menús, historia y consultas SQL. Las funciones no reemplazan el requisito de clases.


Además:
1. Al reiniciar una aventura terminada, puede sobrescribir otro nombre de jugador. Pide un nombre nuevo, pero mantiene el jugador_id anterior y borra sus decisiones e inventario. Comprobé que, al continuar como Ana y reiniciar como Beto, Ana desaparece y quedan dos registros llamados Beto.
2. La llave se puede recoger repetidamente. Cada regreso a la cueva permite agregar otra «Llave antigua». Lo comprobé: el inventario termina con dos copias del mismo objeto.
3. No guarda explícitamente el resultado final. Tanto ganar el tesoro como terminar sin llave guardan terminado. Las estadísticas no distinguen directamente entre ambos desenlaces.
4. Falta una opción general para salir. El menú inicial no ofrece salir y, durante la aventura, esa opción solo aparece en el refugio.
5. El README está incompleto. No explica cómo ejecutar el programa, cómo continuar partidas ni cómo está organizado.

La corrección principal sería reorganizarlo en clases con responsabilidades claras, por ejemplo Jugador, Aventura y BaseDatos, cada una en su archivo, y un main.py que las utilice.
