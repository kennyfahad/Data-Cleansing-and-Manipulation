# Data Cleansing using basic Python Operations
* `csv` Library
* `functions`
* data types and conversions

# About Artworks Data

### [`data.csv`](https://github.com/kennyfahad/DataCleansing/raw/main/DataCleansing_WithBasicPythonTechniques/data.csv)

## Museum of Modern Art Collection
The Museum of Modern Art (MoMA) acquired its first artworks in 1929, the year it was established. Today, the Museum’s evolving collection contains almost 200,000 works from around the world spanning the last 150 years. The collection includes an ever-expanding range of visual expression, including painting, sculpture, printmaking, drawing, photography, architecture, design, film, and media and performance art.

MoMA is committed to helping everyone understand, enjoy, and use our collection. The Museum’s website features 72,706 artworks from 20,956 artists. The artworks dataset contains 130,262 records, representing all of the works that have been accessioned into MoMA’s collection and cataloged in our database. It includes basic metadata for each work, including title, artist, date, medium, dimensions, and date acquired by the Museum. Some of these records have incomplete information and are noted as “not curator approved.” 

The follwoing work is down on the artiest dataset which contains 16,730 records, representing all the artists who have work in MoMA's collection and have been cataloged in MOMA's database. The dataset includes information about 'Title', 'Artist', 'Nationality', 'BeginDate', 'EndDate', 'Gender', 'Date' and 'Department'. It has been already enhanced from the dataset shared by MOMA which included basic metadata for each artist, including name, nationality, gender, birth year, and death year.

[Click here for more information on this dataset available on Kaggle](https://www.kaggle.com/datasets/momanyc/museum-collection?resource=download)

# Data Cleansing Problems Resolved 
* Unwanted special characters removed
* Standardized datasets to correct datatypes for e.g. `text > int`
* Missing values in 'Nationalities' and 'Gender' identified and replaced
* Dates standardized to address conventional use

### Cleaned dataset is available as csv [`artists_updated.csv`](https://github.com/kennyfahad/DataCleansing/raw/main/DataCleansing_WithBasicPythonTechniques/artists_updated.csv)
