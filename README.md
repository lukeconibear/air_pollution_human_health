# [Slides on Air Pollution and Human Health](https://lukeconibear.github.io/air_pollution_human_health/#/)  
Created by Luke Conibear (L.A.Conibear@leeds.ac.uk / [@lukeconibear](https://twitter.com/lukeconibear))  
Created using reveal.js, a HTML presentation framework [URL](https://revealjs.com) [GitHub](https://github.com/hakimel/reveal.js) 

## To recreate

- Set any cells to have their input removed by using the "Property Inspector" in the top right and adding the cell tag "remove_input"
- Set the slide type for each cell by going to "Slide Type" also within the "Property Inspector", and selecting Slide, Subslide, or Skip
- Then convert the Jupyter Notebook to reveal.js slides using:  
```bash
jupyter nbconvert index.ipynb --to slides --TagRemovePreprocessor.remove_input_tags "remove_input 
mv index.slides.html index.html
```
