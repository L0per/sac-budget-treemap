# Sacramento 2018 Budget Treemap

See the interactive chart [HERE](https://l0per.github.io/sac-budget-treemap-2018/).

![preview image](https://github.com/L0per/sac-budget-treemap-2018/blob/master/images/preview.PNG?raw=true)

Originally displaying the 2015/2016 budget, a new json file had to be generated from the budget data `FY15__FY16__FY17__FY18.csv`. This will eventually replace the treemap found [HERE](http://openbudgetsac.org/departments-programs/).

* `csv_to_json.ipynb` uses pandas to generate the json file after loading `FY15__FY16__FY17__FY18.csv`.
* `sacbudget_v2.json` is the new json file, `sacbudget_v2.json` was the old file used for json structure reference.
* While the overall json structure is simple, the difficulty comes with limiting the number of children each "layer" of the treemap has.

## To-do

* Modify coloring if there was no budget for 2017.
* Verify department names for 2017 vs 2018 as there seems to be many "new" departments in 2018.
* Add descriptions.
