### Download Yelp Dataset
To download and extract `yelp_academic_dataset_business.json` and `yelp_academic_dataset_review.json`, paste the following into your terminal. 

> **Note:** You must replace the URL below with the temporary link from the [Yelp Dataset Page](https://www.yelp.com).

```bash
# Define your unique download URL here
YELP_URL="INSERT_YOUR_LINK_HERE"

curl -L "$YELP_URL" -o yelp_dataset.tar

# Extract the JSON files
tar -xvf yelp_dataset.tar
