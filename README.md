#ToolReflection

This is a benchmark and a instruction tuning data which aim to enhance and assess tool usage capabilities of LLMs.

### Benchmark

The list of APIs used

- Units conversion API https://github.com/hgrecco/pint

- Geolocation API https://geocoder.readthedocs.io

- Time conversion API https://pypi.org/project/pytz/

- Nutrition analysis API https://api.edamam.com

The data can be found in the ```data``` folder

* ```original_data.json``` contains evaluation examples 

* ```parameter_descriptions_data.json``` contains evaluation examples with detailed parameter descriptions

* ```parameter_descriptions_and_usage_examples_data.json``` contains evaluation examples with detailed parameter descriptions and a single usage example


### Evaluation

To evaluate your model, please follow the [scripts/generate.sh](./scripts/generate.sh) 

### Instruction data

The dataset consits of 141 diverse tool and parameter descriptions. For each tool up to 23 examples of tool usage were generated. The data can be found in the 
    



