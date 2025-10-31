# A01646802 and A01645224-Evidencia de proyecto
Generador de RFC a partir de foto del pasaporte

La función de este código es leer un pasaporte a manera de imagen, para posterior procesar mrz, limpiarlo y generar un RFC. Para esto fue necesario la implementación de distintas librerías como:

cv2: Carga la imagen.

matplotlib: Muestre la imagen en pantalla.

passporteye: Es la encargada del proceso de filtrado de la imagen y captura del mrz a manera de diccionario.

random: Genera la homoclave.

string: Almacane caracteres para la creación de la homoclave.

unicodedata: Elimina los acentos.

google.colab: Tiene una función visual donde el usuario tiene un botón para subir el archivo.
