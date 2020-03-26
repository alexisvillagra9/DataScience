## Style Transfer (CNN VGG16)   <img src="https://image.flaticon.com/icons/png/512/107/107796.png" width=20>

*El objetivo es logar una tranferencia de estilo a partir de 2 imagenes de entrada 
(una que respetara el contenido de la imagen y otra a la que se le respetara el estilo y forma).*

## Comenzando <img src="https://image.flaticon.com/icons/png/512/82/82302.png" width=20>
*Para que el proyecto corra correctamente se debe instalar un par de librerias previamente:*

>Si se le agrega el ! todo se instala dentro del entorno ejecutado
```
conda install jupyter (Tambien se puede correr en Google Colab)
!pip install numpy
!pip install Keras
!pip install Pillow==2.2.1
!pip install -U scipy==1.2.0
!pip install matplotlib
!pip install imageio
```
## Algunos Resultados Obtenidos <img src="https://image.flaticon.com/icons/png/512/45/45903.png" width=20>
*Utilizando lagunas imagenes de pinturas conocidas como estilo obtuve los siguientes resultados:*
\
<img src="https://raw.githubusercontent.com/alexisvillagra9/DataScience/master/Deep%20Learning/Neural%20Style%20Transfer/Raw%20Images/Alexis.jpeg" height=150>
<img src="https://raw.githubusercontent.com/alexisvillagra9/DataScience/master/Deep%20Learning/Neural%20Style%20Transfer/Styles/Art7.jpg" height=150>
<img src="https://github.com/alexisvillagra9/DataScience/blob/master/Deep%20Learning/Neural%20Style%20Transfer/Final%20Images/Alexis-Art7100.jpg" height=150>
\
<img src="https://raw.githubusercontent.com/alexisvillagra9/DataScience/master/Deep%20Learning/Neural%20Style%20Transfer/Raw%20Images/Alexis.jpeg" height=150>
<img src="https://raw.githubusercontent.com/alexisvillagra9/DataScience/master/Deep%20Learning/Neural%20Style%20Transfer/Styles/Art3.jpg" height=150>
<img src="https://raw.githubusercontent.com/alexisvillagra9/DataScience/master/Deep%20Learning/Neural%20Style%20Transfer/Final%20Images/Alexis-Art3100.jpg" height=150>
\
<img src="https://raw.githubusercontent.com/alexisvillagra9/DataScience/master/Deep%20Learning/Neural%20Style%20Transfer/Raw%20Images/Alexis.jpeg" height=150>
<img src="https://raw.githubusercontent.com/alexisvillagra9/DataScience/master/Deep%20Learning/Neural%20Style%20Transfer/Styles/Art8.jpg" height=150>
<img src="https://raw.githubusercontent.com/alexisvillagra9/DataScience/master/Deep%20Learning/Neural%20Style%20Transfer/Final%20Images/Alexis-Art8100.jpg" height=150>
