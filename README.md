









```
r language BS6, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis  , echo = (language == "TR")
## BS6 -  {#sec-BS6 }
```


```
asis  , echo = (language == "EN")
## BS6 -  {#sec-BS6 }
```






```
r BS6 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS6-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS6/HE.html",
  file = "./screenshots/BS6-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link







```
asis, echo = (language == "TR")

****


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS6-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS6/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS6/HE.html)
```

```
asis, echo = (language == "EN")

****

[![Click for Full Screen WSI](./screenshots/BS6-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS6/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS6/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS6/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS6/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```






:::::
