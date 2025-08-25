<h1>Práctica #PROYECTO_M21 de mi curso de FrontEnd de EBAC</h1>
<h2>Descripción del proyecto</h2>
Este proyecto es una tienda web de comida típica poblana. El usuario puede visualizar una lista de platillos (con imagen, nombre y precio), y agregar productos a un carrito de compras dinámico. El sistema permite aumentar o disminuir la cantidad de productos, eliminar productos individuales, vaciar el carrito por completo y confirmar una compra.
<br>
El diseño es responsivo, con comportamiento ajustado para pantallas pequeñas (como laptops y móviles). Además, el sistema muestra visualmente el número de productos añadidos al carrito con un indicador en el botón del carrito.
<h2>Tecnologías utilizadas</h2>
<ul>
  <li><b>HTML5</b></li>
  <ul>
    <li>Archivo: <b>index.html</b>.</li>
    <li>Estructura base del sitio web.</li>
    <li>Uso de etiquetas semánticas como <b>&lt;header&gt;</b>, <b>&lt;main&gt;</b>, <b>&lt;section&gt;</b>, <b>&lt;article&gt;</b>, <b>&lt;aside&gt;</b>.</li>
    <li>Accesibilidad a través de <b><em>alt</em></b> en imágenes.</li>
    <li>Diseño responsivo mediante <b><em>meta viewport</em></b>.</li>
  </ul>
  <li><b>SASS</b></li>
  <ul>
    <li>Archivo: <b>main.scss</b> (compilado a <b>main.css</b>).</li>
    <li>Utiliza la sintaxis <b>SASS</b> para una mejor organización:</li>
    <ul>
      <li><b>Mixins</b> para media queries (<b><em>@mixin laptops</em></b>).</li>  
      <li><b>Anidación de selectores</b> para mejor legibilidad.</li>
    </ul>
  <li>Estilización de:</li>
  <ul>
    <li>Encabezado.</li>
    <li>Productos.</li>
    <li>Carrito (estilo tipo sidebar deslizante).</li>
    <li>Botones, precios, títulos.</li>
  </ul>
  </ul>
  <li><b>CSS (compilado desde SCSS)</b></li>
  <ul>
    <li>Archivo vinculado en el <b>HTML</b>: <b><em>css/main.css</em></b>.</li>
    <li>Es el <b>CSS</b> generado a partir de <b><em>main.scss</em></b> y cargado en el navegador.</li>
  </ul>
  <li><b>JavaScript</b></li>
  <ul>
    <li>Archivo: <b><em>scripts.js</em></b>.</li>
    <li>Funcionalidades implementadas:</li>
    <ul>
      <li>Agregar productos al carrito.</li>
      <li>Mostrar y ocultar carrito.</li>
      <li>Calcular total.</li>
      <li>Vaciar carrito.</li>
      <li>Eliminar artículos individualmente.</li>
      <li>Confirmar compra.</li>
      <li>Mostrar cantidad de artículos en un indicador visual.</li>
    </ul>
    <li>Gestión dinámica del <b>DOM</b> (crear, actualizar y eliminar elementos <b>HTML</b>).</li>
  </ul>
  <li><b>Recursos Estáticos</b></li>
  <ul>
    <li><b>Imágenes</b> ubicadas en <b><em>assets/img/</em></b>, utilizadas en las tarjetas de productos.</li>
    <li><b>Fuente estándar</b> (Arial).</li>
  </ul>
</ul>
<h2>Instrucciones de instalación y uso</h2>
<ul>
  <li>Hay que asegurarse de tener Node.js y npm instalados en el sistema los cuales pueden ser descargados desde: https://nodejs.org/.</li>
  <li>Después de ejecutar el paso anterior, instala <b>SASS</b> globalmente utilizando la línea de comandos: npm install -g sass.</li>
  <li>Para usar este código hay que ir a la pestaña Code | Download ZIP.</li>
  <li>Descomprimir el archivo zipeado, entrar a la carpeta creada y buscar el archivo <b>index.html</b>.</li>
  <li>Una vez localizado el archivo <b>index.html</b> le damos doble click a dicho archivo y se nos abrirá el proyecto HTML en nuestro navegador de Internet predeterminado.</li>
  <li>Explora los productos disponibles.</li>
  <li>Da clic en el botón <b>Agregar al carrito</b> para añadir productos.</li>
  <li>En la parte superior, da clic en <b>Ver Carrito</b> para desplegar el carrito.</li>
  <li>Dentro del carrito puedes:</li>
  <ul>
    <li>Ver el total actualizado.</li>
    <li>Eliminar productos individualmente.</li>
    <li>Vaciar todo el carrito.</li>
    <li>Confirmar la compra.</li>
  </ul>
  <li>Da clic en <b>Cerrar Carrito</b> para ocultarlo.</li>
  <li>Cuando cambiamos el diseño de tamaño los elementos que conforman el diseño web se ajustan de tal manera que se adaptan al tamaño del dispositivo de despliegue y de esta manera el usuario puede seguir viendo el contenido completo del sitio web sin que falte o se desborde algún elemento.</li>
</ul>
<h2>Ejemplos de uso</h2>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/77e7376d-6209-408f-acb9-ebe0124ef2c4" />

---

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/b08739cd-2fc2-44ae-9f20-1dc79f19a8da" />

---

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/552537fb-d352-4f64-a677-7ebaeeea20e1" />

---

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/59c831d7-ad36-406e-8c08-ece5f5f627c4" />

---

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ba9109ca-42fc-4f1f-b0af-fba40dc40266" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8752bc7e-428d-4afb-8f95-9ba0a80ccd69" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e9f9b34e-c4f0-4e11-a02c-9d3d9da715ca" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/11bbb190-ec66-4ab2-815d-989c4d7ee18b" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/29e67474-b765-4b92-8db4-109a4626af97" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3fb2171a-91eb-404f-9a3b-345aeafcb5b8" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cee628fb-7d84-4068-96a2-01e23e739d70" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/957a6572-8356-4935-a6d0-d283b9bf3cdf" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/825f3fee-7ac6-4608-9405-6dc96d7a0c5d" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1dfb2437-bd6e-4117-8a06-f1a4fdb5f036" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ea8aabe4-8e07-4742-8a65-ee144b3fd8f2" />

---

<img width="1727" height="1080" alt="image" src="https://github.com/user-attachments/assets/7645022b-0790-4249-a755-1a4eac9f51ef" />

---

<img width="1607" height="1080" alt="image" src="https://github.com/user-attachments/assets/1d336943-ddcc-4790-ba6b-a11fca157570" />

---

<img width="1420" height="1080" alt="image" src="https://github.com/user-attachments/assets/3fdf5c73-6d26-4c3a-b7cf-04b04b128dc2" />

---

<img width="1307" height="1080" alt="image" src="https://github.com/user-attachments/assets/6be557d1-0ab2-440e-a59e-7d647d39b72f" />

---

<img width="1115" height="1080" alt="image" src="https://github.com/user-attachments/assets/3097b57f-7b1c-4b49-8622-84458368eb53" />

---

<img width="1008" height="1080" alt="image" src="https://github.com/user-attachments/assets/94f30495-3140-46c5-8de7-26be9063894f" />

---

<img width="919" height="1080" alt="image" src="https://github.com/user-attachments/assets/2cc11dc7-bc06-4cd4-8682-d788b4193a8c" />

---

<img width="827" height="1080" alt="image" src="https://github.com/user-attachments/assets/6ba6cd27-de6c-4779-b86e-04878449ef0b" />

---

<img width="676" height="1080" alt="image" src="https://github.com/user-attachments/assets/d6a42f00-ec78-4170-931b-8b17a411a174" />

---

<img width="576" height="1080" alt="image" src="https://github.com/user-attachments/assets/c7d101ad-d29c-456c-8a33-c7ca49eb990d" />

---

<img width="502" height="1080" alt="image" src="https://github.com/user-attachments/assets/2990e85c-d5bf-4769-9cca-38932e1e85b4" />

---

<img width="502" height="1080" alt="image" src="https://github.com/user-attachments/assets/ea661750-8849-437c-8c5c-17fe27e9ea70" />

---

<img width="502" height="1080" alt="image" src="https://github.com/user-attachments/assets/5c2411f0-b457-4968-84f3-a29a6ccdbf81" />

---

<img width="502" height="1080" alt="image" src="https://github.com/user-attachments/assets/c334505c-9994-462e-8a34-003f8fd76869" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9cb0c4bc-054b-4acb-b851-90d5f60a42bb" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fe4e0805-0538-4606-8900-517445d3ece8" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/792ce219-99cb-4f2a-bd44-5cda18fcdc45" />

---

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/536b334e-e0ef-4811-9371-c01e88753704" />

---

## <p align="center"><a href="https://github.com/adnalotrebla741202">REGRESAR</a></p>
