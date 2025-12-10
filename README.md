# DATASCI 350 - Data Science Computing

## Quiz 02: Creating a Website with Quarto and GitHub Pages

### Instructions

In this quiz, you will create a website using Quarto and GitHub Pages as shown in our previous lectures. The website will contain four pages:

- An index (home) page with a title, one sentence about the Gapminder dataset, and links to the other three pages.
- A page with a graph showing the relationship between hdi_index and co2_consump over time.
- A page analysing the relationship between hdi_index and services.
- A page analysing changes in hdi_index, co2_consump, and services for a specific country over time.

The website should be published on GitHub Pages and the link to the website should be submitted on Canvas. You can use either R or Python to create the graphs and the analysis. A short description of the dataset is provided here: <https://www.kaggle.com/datasets/albertovidalrod/gapminder-dataset>.

The dataset is available in this repository as `gapminder_data.csv`, and it contains 8 columns and 3,675 rows. The columns are: `country`, `continent`, `year`, `life_exp`, `hdi_index`, `co2_consump`, `gdp`, and `services`. The dataset contains information about these variables in 195 countries over the years 1998 to 2018. 

### Tasks

1. Fork this repository to your GitHub account and clone it to your computer.

2. Create a new Quarto website project in your local cloned folder (use `.` if asked to choose your directory).

3. In your local folder, create another folder named `docs` to store the rendered website. This is the folder that will be published on GitHub Pages.

4. Modify the `_quarto.yml` file to include navigation links to your pages and direct the output to the `docs` folder.

5. Modify the `index.qmd` file to include a title, a one-line description of the Gapminder dataset, and links to the other website pages.

6. Create a page entitled `hdi-co2.qmd` analysing the relationship between `hdi_index` and `co2_consump`. Give it a title, a brief introduction, and a graph. Show your code. Also give it a link in the index page with the text "HDI and CO2 Consumption".

7. Create a page entitled `hdi-services.qmd` analysing the relationship between `hdi_index` and `services`. Do the same as in the previous task, but change the title and the link text to "HDI and Services".

8. Create a page entitled `country.qmd` analysing changes in `hdi_index`, `co2_consump`, and `services` for a specific country over time. Give it a title, a brief introduction, and a graph. Show your code. Also give it a link in the index page with the text "Country Analysis".

9. Ensure the `_quarto.yml` file includes navigation links with custom names.

10. Change the theme of the website to one of Quarto's available themes. You can find the list of themes here: <https://quarto.org/docs/output-formats/html-themes.html>.

11. Render the website and output the files to the `docs` folder.

12. Add, commit, and push the changes to your forked repository.

13. Go the repository settings on GitHub and enable GitHub Pages to publish the website. Remember to select the `docs` folder as the source.

14. Check that the website is live and all pages are accessible.

15. Copy the GitHub Pages link and submit it on Canvas as instructed.

### Bonus Questions

16. Enhance the website's appearance by adding a custom CSS file.

17. Include an interactive map showing countries' `hdi_index` or `co2_consump`. For this task, you can use the `plotly` library in Python, the `leaflet` library in R, or any other library you prefer.