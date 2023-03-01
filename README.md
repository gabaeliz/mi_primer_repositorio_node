# mi_primer_repositorio_node
Mi primer repositorio con Node.JS, en el READ.ME encontraras los pasos a seguir para instalación en Windows, Linux y Mac. No dudes en contactarme por cualquier duda. ¡Diviértete! :smiley:

:computer: **<h2>Instalación en Windows</h2>**
Ve a la pagina oficial de Node.js: https://nodejs.org/en/download/ y seleccionar el paquete correspondiente a tu sistema operativo, en este caso sera Winsdows.

![Screenshot_20230301_095913](https://user-images.githubusercontent.com/98141605/222193951-6d2ce385-4f04-4493-a7b0-7a476f5df7a1.png)

Una vez descargado, abre el archivo con terminación **.msi**. El cual abrira la ventana para iniciar la instalación de Node.js.

![Screenshot 2023-03-01 100337](https://user-images.githubusercontent.com/98141605/222194937-64947047-6443-45b3-8532-c7e92a4973b8.jpg)

Da clic en el botón **NEXT**. A continuación te aparecera una nueva ventana con los terminos y condiciones, activa la casilla de **"I accept the terms in the License Agreement"** y da clic en el botón **Next**.

Despues, aparecera la ruta de instalación, esta te permite seleccionar una ruta en especifico si asi lo deseas o dejar la recomendada por Node. Si no tienes problemas con esta, te recomiendo dejar la recomendada por Node. 

![Screenshot_20230301_101117](https://user-images.githubusercontent.com/98141605/222196998-2547915b-3cca-4491-a8d7-b7e369b8f09d.png)

Da clic en **Next**, a continuación observaremos la pantalla de **Custom Setup**. De momoento no realizaremos configuraciones adicionales. Presiona el boton **Next** para pasar a la siguiente pantalla. 

![Screenshot_20230301_101459](https://user-images.githubusercontent.com/98141605/222198010-4c6d2617-dc49-4cf4-95da-83ceadb3adcb.png)

A continuación aparecera **"Tools for Native Modules"** en el cual se instalaran herramientas adicionales a Node. No es necesario seleccionar la casilla **Automatically install the neccessary tools..."** ya que haremos nuestra propia instalacion de paqueteria y modulos mas adelante presiona el boton **Next**.

![Screenshot_20230301_102155](https://user-images.githubusercontent.com/98141605/222199824-59917211-b40a-4863-ac02-f70f558d50ba.png)

Nos aparecera **Ready to Install Node.js** presiona el botón de **Install** el cual iniciara el proceso de instalación. 

![Screenshot_20230301_102501](https://user-images.githubusercontent.com/98141605/222200670-a778f26b-b4b8-47db-8962-406dbd13f7bb.png)

:pencil2:**<h2>NOTA: </h2>** Puede que Windows te solicite habilitar permisos de Administrador, habilitalos de ser el caso. 
![allow-uac-registry-mrnoob](https://user-images.githubusercontent.com/98141605/222206808-0ca4082b-6015-464f-b19f-f602eecca234.png)

:notebook_with_decorative_cover:**<h2>Ejemplo de como ser ve en pantalla el permiso de Administrador</h2>**:notebook_with_decorative_cover:

Proceso de instalación:
![Screenshot 2023-03-01 102729](https://user-images.githubusercontent.com/98141605/222203135-f82f295a-b2cb-4da6-92c7-23fe49065175.jpg)

Finalmente veras la pantala de **Completed the Node.js Setup Wizard** da clic en el botón de **Finish** para finalizar.

![Screenshot_20230301_103731](https://user-images.githubusercontent.com/98141605/222203849-eeea70a2-2bbf-4e97-9f2d-1f80dfda1738.png)

Para verificar que se ha instalado Node.js ve a la terminal que se encuentra en Visual Studio Code y escribe el siguiente comando:</b>
<code>node -v</code></b>
El comando anterior te mostrara la versión que se ha instalado en tu computadora como se observa en la imagen siguiente.
![Screenshot_20230301_094831](https://user-images.githubusercontent.com/98141605/222192694-d829189f-70fe-44ec-af8f-e97919b1245d.png)

Para confirmar la instalación de **NPM** utilizaremos el siguiente comando <code>npm -v</code>. 

![Screenshot 2023-03-01 104645](https://user-images.githubusercontent.com/98141605/222206278-2123217f-50b1-4416-9800-72cfa45981e7.jpg)
 
:computer: **<h2>Instalación en Mac</h2>** 
Es un proceso similar al de Windows. Aquí, Node proporciona un instalador **.pkg** para Mac: https://nodejs.org/en/download/

Haz clic en la opción "Instalador de macOS" para descargar el instalador **.pkg**. Asegurate de descargarlo en la ubicación deseada.

![Screenshot_20230301_095913](https://user-images.githubusercontent.com/98141605/222193951-6d2ce385-4f04-4493-a7b0-7a476f5df7a1.png)

Ahora, tu instalador está listo para ejecutarse. 
Para verificar si se ha instalado correctamente Node.js en tu macOS, ejecuta el siguiente comando en tu terminal:
<code> node -v node -v </code>

Node.js no actualiza automáticamente la versión de npm. Escribe el siguiente comando para actualizar la versión de npm: <code> $ sudo npm install npm --global</code>

