# dokumentumszerkesztési technikák
> 
> preferált online editor https://www.overleaf.com
> 
> preferált offline editor: [TEXStudio](https://www.texstudio.org/) és [MikTex](https://miktex.org/) fordító hozzá
> 
> minta doksi: https://github.com/ABC-iRobotics/diplomamunka-latex-template helyett inkább: https://github.com/kerecsenszabo/diplomamunka-latex-template


# LaTex alapok:
Csomagok behívása:
- `\usepackage{tikz}` - vektorgrafikus képeket lehet beilleszteni
- `\usepackage{flafter}` - segít strukturálni, parmaéterezin a stílusfájltól eltérő szekciózást
- `\usepackage{rotating}` - képek forgatása
- `\usepackage{graphicx}` - képekhez
- `\usepackage{hyperref}` - linkekhez
- `\usepackage[magyar]{babel}` - magyar nyelv értlemezése, ékezetek, stb

Dokumentum szerkezete:
- törzs megadása: `\begin{document}` és `\end{document}` közé kerül

Címsorok helyett:
- `\chapter`
- `\section`

Megjegyzés: `%`


Forrásokhoz használunk egy stílusfájlt, ami `.sty` kiterjesztésű. Ezen kívűl van egy `.bst` fájl ami a `.bib` fájlban megadott referenciák stílusát tartalmazza. 


# Forrásmegjelölés
> https://www.zotero.org - online és dekstop valamint böngészőkiegészítő isntalálása is mind ajánlott!
> 
> Wordhöz forsámegjelölés zoteroban: https://www.zotero.org/support/word_processor_plugin_installation

Ha LaTexben szeretnénk ezt akkor egy `.bib` fájl kerül mellé, és abba kerülnek a hivatkozások, pl:
```Bib
@article{covid2020post,
  title={Post-COVID-19 global health strategies: the need for an interdisciplinary approach},
  author={COVID, Gemelli Against and Post-Acute Care Study Group and others},
  journal={Aging Clinical and Experimental Research},
  pages={1},
  year={2020},
  publisher={Nature Publishing Group}
}
```
Ez a hivatkozás a dokumentumban így hívható: `\cite{covid2020post}`

# LaTEx Powerpointban
Ha nem egy latex dokumentumot szeretnénk kiexportálni powerpoitba hane m powerpointban szerkeszteni latex szerűen akkor hasznos lehet: http://www.jonathanleroux.org/software/iguanatex/


