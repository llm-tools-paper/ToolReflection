Here, along with the original `GPT4Tools` fine-tuning and evaluation pipeline, we present a benchmark and an instruction tuning dataset aimed at enhancing and assessing the tool-usage capabilities of LLMs.

### Benchmark

The list of APIs used:

- [Units conversion API](https://github.com/hgrecco/pint)  
- [Geolocation API](https://geocoder.readthedocs.io)  
- [Time conversion API](https://pypi.org/project/pytz/)  
- [Nutrition analysis API](https://api.edamam.com)  

The data can be found in the `data` folder:

- `original_data.json`: Contains evaluation examples.  
- `parameter_descriptions_data.json`: Contains evaluation examples with detailed parameter descriptions.  
- `parameter_descriptions_and_usage_examples_data.json`: Contains evaluation examples with detailed parameter descriptions and a single usage example.  

### Instruction Data

The dataset consists of 141 diverse tools and parameter descriptions. For each tool, up to 23 examples of tool usage were generated.  
The instruction tuning data is contained in the `data/fake_tools_data.json` file.

### Evaluation

To evaluate your model, please follow the instructions in [scripts/generate.sh](./scripts/generate.sh).


