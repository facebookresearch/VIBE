# Body measurements of models that wear the clothing
This folder contains the body measurements of the (human) model and which size she wears for a clothing product.

1. Each ```.txt``` file contains a python dictionary data structutre.
2.  Keys for the outermost dictionary are (human) models' names (e.g., Stacey, Rebecca).
3. Values for the outermost dictionary (i.e., a specific human model) are inner dictionaries. 
4. Inner dicionary contains key and value pairs of the human model's body measurements and which size (e.g., S/M/L or 8/10/12... etc.) she wears for this prodcut.
5. Body measurements are in centimeters.

## Example file
```
{"Stacey": {"bust": "101.0", 
            "waist": "80.0", 
            "height": "169.0", 
            "hips": "98.0", 
            "size": "M"}, 
"Rebecca": {"bust": "91.0", 
            "waist": "76.0", 
            "height": "175.0", 
            "hips": "102.0", 
            "size": "S"}
}
```