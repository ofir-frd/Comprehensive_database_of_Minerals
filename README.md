# Comprehensive database of Minerals

A Kaggle dataset.

Predict materials structures from a list of 3112 minerals, their chemical composition, and properties.


## About Data collection methodology

Data was collected from Wikipedia (https://en.wikipedia.org/wiki/List_of_minerals), The American Mineralogist Crystal Structure Database (http://rruff.geo.arizona.edu/AMS/amcsd.php), and the gemology project website (http://gemologyproject.com/wiki).

### Description of the data

Directory description:

```

Root Dir/
  - Comprehensive_database_of_Minerals.ipynb
  - Minerals_Database.csv
  - README.md
  - LICENSE.md
  - .gitignore

```

Features review:

```
Minerals_Database.csv/
  - Labels
    - Crystal Structure
  -  Numerical     
    - Mohs Hardness
    - Diaphaneity
    - Specific Gravity
    - Optical
    - Refractive Index
    - count
    - Molar Mass
    - Molar Volume
    - Calculated Density
    - 118 features: sum of atoms per molucule in the periodic table

```


### File formats

Code is written in Python on Jupyter '.ipynb'.

The data provided in this project is a '.csv' file with no separation between train and test datasets.

```
-50,000 3112 minerals, their chemical composition, and properties, format csv.
```

## Online Repository link

* [DataRepository](https://www.kaggle.com/vinven7/comprehensive-database-of-minerals)

## Author

* [ofir-frd](https://github.com/ofir-frd)


## License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](https://github.com/ofir-frd/Comprehensive_database_of_Minerals/blob/main/LICENSE) file for details

## Acknowledgments

* * Vineeth Venugopal, who collected and organized the data, and create the dataset in Kaggle
