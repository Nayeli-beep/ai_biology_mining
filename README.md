# Crecimiento de la Inteligencia Artificial en las Ciencias Biológicas (2000-2025): Búsquedas semi-automatizadas en PubMed 🔬

## **Introducción**
La información y el uso de nuevas herramientas han ido en aumento en las últimas décadas, por lo que en este proyecto se realiza un análisis semiautomatizado para estudiar la evolución y crecimiento de la aplicación de la Inteligencia Artificial en diferentes campos de las áreas biológicas. Se hace uso de la API de PubMed para extraer, procesar y visualizar datos de las publicaciones científicas. 


## **¿Qué se puede realizar con este código?**

- Es posible realizar la extracción semiautomatizada de los metadatos de artículos en PubMed mediante los términos de búsqueda sobre la inteligencia artificial aplicadas a las ciencias biológicas.
- Análisis de palabras clave y su frecuencia de aparición en el texto usando términos MeSH y en texto libre [Title/Abstract].
- Es posible visualizar los términos clave en nubes de palabras.
- Se obtienen las tendencias de las publicaciones por disciplina biológica entre 2000 a 2025.
- Se elabora una gráfica donde se observa la distribución temporal de las menciones totales de la IA dentro las ciencias biológicas.

## **Resultados**

   - Dentro del código es posible encontrar listas para modificar las solicitudes de búsqueda y están divididos como:
   ```Campo de la biología: Bioinformática, Biología, Biomedicina, Ecología, Genética. Términos de la IA: Inteligencia Artificial, Machine Learning, Deep Learning.```
   - Las búsquedas se limitan a 500 artículos por combinación de términos, en un periodo de 2000-2025
   - Visualización de datos
     - Palabras clave más frecuentes
     - Nube de palabras
     - Gráfica por disciplina biológica
     - Total de menciones de IA
    
## **Metodología**

- Definición de términos de búsqueda: Combinación de términos de IA y campo de biología.
- Búsqueda y extracción de metadatos: Por medio del uso de Entrez/Pubmed, se procesaron los registros.
- Limpieza de datos: Eliminación de duplicados y homogeneizar los términos
- Análisis: Extracción y conteo de palabras clave.
- Visualizacón: Generación de gráficos.

## **Instalación** 

*Bibliotecas*
```pip install Biopython pandas matplotlib seaborn wordcloud numpy``` 
**El codigo se realizó en el ambiente de Google Colab**

*Configura tu email*
Para ingresar a la API de NCBI de esta manera en caso de recibir alguna alerta, NCBI se pondrá en contacto por este medio. Asegúrate de tener internet.

```
Entrez.email = "youremail@example.com"
```


*Requirements*


## Resultados

**Palabras clave más frecuentes**
![common_keywords](https://github.com/user-attachments/assets/7579523f-c79f-43df-9175-a1814ec2b037)


**Nube de palabras**
![wordcloud_freq](https://github.com/user-attachments/assets/049f336a-6a3e-40aa-8f60-79e7eb4d83f4)

**Gráfica por disciplina biológica**
![barplot_count](https://github.com/user-attachments/assets/9cd08c01-c983-421f-9711-6c6c4844aafe)

**Total de menciones de IA**
![total_pub](https://github.com/user-attachments/assets/ecdf4228-a2dd-4617-83bf-7df776ea19be)


