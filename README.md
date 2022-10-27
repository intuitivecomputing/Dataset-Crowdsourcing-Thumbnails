# Crowdsourcing Thumbnail Captions via Time-Constrained Methods
Carlos Aguirre, Amama Mahmood and Chien-Ming Huang


## Data 
For more information in how we collected this data please see [paper](https://dl.acm.org/doi/pdf/10.1145/3490099.3511136?casa_token=XZ9esozU_OAAAAAA:KM2ffus3kAZAPhEu2lbAFJhJHuND_ooOI0J-tr4jOVJaNn8B-FOWXtnk-aO4v2qatdUhzpQ9dOfj)

### Image Descritions
Image descriptions are stored in `descriptions.csv`. The file has the following columns:
- `image_name` - the ID of the image that matches MSCOCO image-ID
- `condition` - the name of the interface used to collect this description
- `description` - the text of the description
- `time` - amount of time in miliseconds (ms) that the worker took to write the description
- `id` - description ID, unique in this file


### Human Ratings of Descriptions
A subset of the descriptions in `descriptions.csv` was rated based on 3 metrics: grammar, correctness, detail. The file contains the following columns:
- `description_id` - matches to `id` in `descriptions.csv`
- `image_name` - the ID of the image that matches MSCOCO image-ID
- `fluency` - (0-100) fluency of the description language
- `correctness` - (0-100) correctness of the description details based on image 
- `detail` - (0-100) amount of detail contained in the description


### Citing this Dataset
When referencing this dataset in your own manuscripts and publications, please use the following full citations:

[1] Aguirre, Carlos A., Amama Mahmood, and Chien-Ming Huang. "Crowdsourcing Thumbnail Captions via Time-Constrained Methods." 27th International Conference on Intelligent User Interfaces. 2022.
