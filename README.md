# Programar Digispark Attiny85 Como RubberDucky
En esta guía en español te enseñaré como programar tu Rubber Ducky por menos de 3 euros. ATENCIÓN: Esta pagina solo proporciona los códigos con fines educativos o probar los códigos en espacios controlados, no hacerlo sin el consentimiento de las personas involucradas o las victimas


# Materiales
# Digispark Attiny85

<img width="334" height="283" alt="image" src="https://github.com/user-attachments/assets/6eadce0c-4fe6-4d12-8e2c-e314e75d9472" />

# Pc con Arduino IDE

<img width="293" height="345" alt="image" src="https://github.com/user-attachments/assets/a23099a1-ae15-4e64-99b7-d6584fad371d" />


# Instalacion de Drivers para que podamos programar nuestro rubber ducky
Tendremos que ir a los archivos adjuntados a este repositorio(para ir directamente pincha aquí -->https://github.com/rodriiii99/programar-DigisparkAttiny85-como-RubberDucky/blob/main/DPinst64.exe) o buscar el archivo llamado "DPinst64" que esta adjuntado en los archivos de este repositorio, y seguidamente lo descargaremos en nuestro PC pinchandole al boton/dibujo de descarga <img width="948" height="403" alt="image" src="https://github.com/user-attachments/assets/9a26cc75-7215-45df-a38d-99383e2ad48a" />


Una vez instalado lo abrimos y nos aparecerá una nueva pestaña (que servirá para instalar los drivers) le daremos a instalar y esperaremos a q se descargue, cuando acabe pondrá un botón de finalizar, le damos y se cerrará la pestaña.<img width="959" height="479" alt="image" src="https://github.com/user-attachments/assets/dfec3a02-a4a2-4d5f-9700-9048bac60e0f" />


Con esto ya tendriamos finalizado el apartado de drivers ahora solo hay que hacer que reconozca el Attiny85 el Arduino IDE.Que es la app que utilizaremos para programar nuestro Attiny85

# Hacer que reconozca nuestro Digispark Attiny 85 el Arduino IDE
Como no hay una libreria especifica para que nuestro Attiny85 sea reconocido por este programa, tendremos que ponerle una libreria no oficial.Para ello haremos lo siguiente: 
Abrir Arduino IDE ir al apartado Archivo>Preferiencias y donde pone Gestor de URLs Adicionales de Tarjetas en el recuadro de la derecha pondremos la siguiente url:       [http://digistump.com/package_digistump_index.json](https://raw.githubusercontent.com/digistump/arduino-boards-index/master/package_digistump_index.json)<img width="959" height="503" alt="image" src="https://github.com/user-attachments/assets/8ec44e9d-4798-4269-9a47-d6825f531f80" />

Y le daremos Ok y ya estaría configurado.(El siguiente paso se necesita hacer todas las veces que lo programemos)Ahora para ponerlo en funcionamiento, iremos a Herramientas>Placa>Digistump AVR Boards>Digispark(Default-16.5mhz)<img width="959" height="503" alt="image" src="https://github.com/user-attachments/assets/e5ffd309-ff02-4ced-9d60-40e0d88b97f1" />
Y luego el puerto por el que saldrá la información para que se cargue en el Attiny85 Herramientas>Puerto y seleccionaremos el COM al que tengamos conectado nuestro dispositivo.<img width="959" height="504" alt="image" src="https://github.com/user-attachments/assets/078b73bd-737e-4de3-9235-3b38effeed63" />

# Funcionamiento
Copiar los scripts de algunos de los archivos que os dejo adjuntados (más abajo estan explicados todos) y ponerlo en el Arduino IDE.
<img width="951" height="362" alt="image" src="https://github.com/user-attachments/assets/9fa48638-4f87-4704-b93e-5b7a02b86814" />
<img width="976" height="501" alt="image" src="https://github.com/user-attachments/assets/3deaffb5-dc14-4b9f-94e0-6893c963d30a" />

# Scripts
1. [Cierre de todas las ventanas abiertas en el PC](https://github.com/rodriiii99/programar-DigisparkAttiny85-como-RubberDucky/blob/main/Cierre%20de%20todas%20las%20ventanas%20abiertas%20en%20el%20PC): Este script empezará a cerrar todas las pestañas del pc sin parar hasta que sea desconectado, basicamente en 10 segundos te puede llegar a cerrar todas las pestañas abiertas en tu PC
2. [Broma de hackeo](https://github.com/rodriiii99/programar-DigisparkAttiny85-como-RubberDucky/blob/main/Broma%20de%20hackeo): Este script pondra un mensaje de accediendo al sistema y seguidamente empezara a llenar 20 lineas de código binario, cuando acabe pondra la frase "es una broma" al final de todo el texto.
3. [Teclado loco](https://github.com/rodriiii99/programar-DigisparkAttiny85-como-RubberDucky/blob/main/Teclado%20Loco): Este script empezara a poner las letras de la a a la z y seguidamnete tocara enter,espacio y las 4 flechas de abajo, arriba, derecha e izquierda.Y lo hará en bucle hasta que se desconecte el dispositivo.
4. [Spam del texto que tú quieras](): Este scrip pone el texto que tengas copiado en el portapapeles y lo pone de manera infinita hasta que tú lo desconectes el Digispark. Funciona poniendo el atajo Cntrl + V y Enter dos veces y luego espera 1 segundo hasta ponerlo otra vez.

MÁS PROXIMAMENTE!!!!HAGO TAMBIEN LOS SCRIPTS QUE ME PIDAIS DEJADMELO EN EL APARTADO DE [ISSUES](https://github.com/rodriiii99/programar-DigisparkAttiny85-como-RubberDucky/issues) OS ESTARÉ LEYENDO!!!
   
