This repository is to set up working enviornments for the Nvidia DGX Spark to be used as a remote personal data science lab for personal projects that expand on my schooling.

00 sets up and validates a fully functional full stack data science (pandas foundation) system running without gpu acceleration. This enviornment will be used on smaller, easily managable datasets. This enviornment is suitable for datasets up to aprox. 4gb of loaded memory.

01 sets up and validates a fully functional full stack data science (rapids foundation) system running with gpu acceleration. This enviornment will be used on larger, normally harder to manage dataset. This enviornment is best for datasets 4gb of loaded memory and above.

00-01 enviornments are available in the .yml files

02-06 is a benchmarking project testing and analyzing new york taxicab data in the mentioned enviornments. The datasets used are available to the public at  https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page and are in .parquet format.

.CSVs of the results are available in the "reports" directory along with any perceived important figures.