# Clothing's sizing and dimension measurements
This folder contains the dimension measurements of different sizes for a clothing product.

1. Each ```.txt``` file contains a python dictionary data structutre.
2.  Keys in the dictionary are available sizes (e.g., S/M/L or 8/10/12... etc.) for this product. Values in the dictionary are lists of dimension measurements.
3. The dimensions are measured in centimeters.

## Example file
```
{"M": [{"dimension_id": "1", "dimension_name": "Bust", "value": "120cm"},
       {"dimension_id": "3", "dimension_name": "Waist", "value": "118cm"}, 
       {"dimension_id": "5", "dimension_name": "Hip", "value": "126cm"}, 
       {"dimension_id": "7", "dimension_name": "Length - shoulder to hem", "value": "71-75cm"},
       {"dimension_id": "15", "dimension_name": "Sleeve Length - neck to hem", "value": "65cm"}]
}
```

Note: the sizing and dimension measurements are automatically mined from the Sizing Guide section on the product's webpage (from [birdsnest](https://birdsnest.com.au/)). For details on where these dimensions correspond to, please check out the webpage's Sizing Guide section.
