# COVID-19 Adjustment

## Why

This small project is using **COVID-19** data and display it in a tabular format (yet another) and allows you to adjust the tatal case based on the death rate of any other country (or a custom one that you can specify).

This is to visualize how many real case are out there in a specific country given the big discrepancy of death rate between countries most likely (also) due to the understimation of the real infected people.

This has not a scientific value but just an empirical estimation based on the country that you would trust the most (or based on the one that has done more tests - Korea, Germany).

## Dataset

The data used for this specific project can be found [here](https://github.com/BlankerL/DXY-COVID-19-Data). The page uses the [JSON](https://github.com/BlankerL/DXY-COVID-19-Data/blob/master/json/DXYArea.json) formatted data and does simple transformations (see [percentages](https://en.wikipedia.org/wiki/Percentage) and [proportionality](<https://en.wikipedia.org/wiki/Proportionality_(mathematics)>))

## Technology

Nothing fancy has been used. Just pure HTML, vanilla JavaScript and [bootstrap](https://getbootstrap.com/).

## Where to find it

You can find it in the file in the [docs](docs/) folder or at [this link](https://mirgj.github.io/covid-19-adjustment/index.html).
