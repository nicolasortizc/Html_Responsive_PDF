# Html Responsive PDF 

* Etiqueta <code>iframe</code> para incrustar PDF en HTML

* Podemos usarlo para incrustar PDF en HTML. Podemos especificar la ruta del archivo PDF en el atributo <code>src</code>. Podemos establecer la altura y el ancho del PDF dentro de la etiqueta.

  Por ejemplo, escriba la etiqueta <code>iframe</code> y establezca el atributo src en <code>files/ejemplo.jpg</code>. <code>ejemplo.jpg</code> es el archivo PDF a incrustar que se encuentra en el directorio <code>files</code>. El archivo HTML y el directorio <code>files</code> se encuentran en el mismo directorio. Establezca la altura y el ancho del PDF en 100%. El PDF cubrirá la ventana gráfica. El uso de la etiqueta iframe proporciona una barra de desplazamiento vertical al PDF. De esta forma, podemos incrustar un archivo PDF en HTML usando la etiqueta <code>iframe</code>.

* Código de ejemplo:
```
<iframe src="files/ejemplo.pdf" height="100%" width="100%"></iframe>
```

* Código del CSS Responsive:
```
.responsive-pdf {
	min-height: 700px;
	@media (max-width: 767.98px) {
		min-height: 500px;
	}
}
```
# Demo

* <a href="https://nicolasortizc.github.io/Html_Responsive_PDF/">Link</a>

![image](https://user-images.githubusercontent.com/107442821/177465801-7ecb6c28-3a6b-4a23-aaf9-c42fca551901.png)

