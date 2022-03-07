To build the slides, do the following: 

First, install reveal with the following command: 
git clone https://github.com/hakimel/reveal.js/

Then, build the presentation with the following command:

jupyter-nbconvert --to slides NYC_2021_Crash_Visualizations.ipynb --reveal-prefix=reveal.js --TagRemovePreprocessor.remove_input_tags={\"to_remove\"} --SlidesExporter.reveal_scroll=True