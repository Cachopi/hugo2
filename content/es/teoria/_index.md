+++
title = 'BLOG'
date = 2023-09-25T08:59:45+02:00
draft = false
+++

# esto es h1 
## esto es h2
### esto es h3
#### esto es h4
##### esto es h5
###### esto es h6

esto es un parrafo de escritura lo que en html seria 

esto seria 
un salto de 
linea.

Y aqui
otro salto de linea.

**texto en negrita**

<!-- LINK -->
[**LINK**][somelinkID]

[somelinkID]: https://mcshelby.github.io/hugo-theme-relearn/index.html "Go to example domain"

## codigo 
{{< highlight lineNos="true" lineNoStart="1" hl_lines="2-3"type="php" >}}
# the hardest part is to start writing code; here's a kickstart; just copy and paste this; it's free; the next lines will cost you serious credits
print("Hola")
print("Mundo  ")
print("!")
{{< /highlight >}}

{{< highlight lineNos="true" hl_lines="1" lineNoStart="1" type="php" >}}
echo "hola mundo"
{{< /highlight >}}




<!-- youtube -->
## video 
{{<youtube j9WyKTGAO2w>}}



<!-- botton -->
{{% button href="http://manuel.infenlaces.com/dwes/docs/2_hugo/4_shortcode/" style="tip" %}}Pagina de Manuel{{% /button %}}

<!-- Descargas -->
{{% attachments sort="asc" /%}}

<!-- badge -->
{{% badge style="warning" %}}Breaking{{% /badge %}}

<!-- Notice -->

{{% notice style="tip" %}}
con tres *** podras poner ***cursiva***
{{% /notice %}}
<!-- mermaid -->

{{< mermaid zoom="false" >}}
pie title Lenguajes
    "JAVA" : 50
    "C++" : 35
    "PHP" : 40
{{< /mermaid >}}


<!-- tabla -->

{{< tabs groupid="main" style="primary" title="lenguajes"  >}}
{{< tab title="mas usados" >}}
  un texto facil es posible aqui...
  {{< tabs groupid="tabs-example-language" >}}
  {{% tab title="python" %}}
  Python es **super** facil

  - mayor parte del tiempo.
  - si no quieres sacar unicode
  {{% /tab %}}
   {{% tab title="php" %}}
  - Php es nuevo para mi.

  
  {{% /tab %}}
  
  {{< /tabs >}}
{{< /tab >}}

{{< tab title="menos usados" style="primary" color="green" >}}
  era una broma
  {{< tabs groupid="tabs-example-language" >}}
  {{% tab title="javascript" %}}
  - para navegadores
  {{% /tab %}}
  {{% tab title="java" %}}
  - primer lenguaje
  {{% /tab %}}
  {{< /tabs >}}
{{< /tab >}}
{{< /tabs >}}







