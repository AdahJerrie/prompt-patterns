1. ## The unstructured text I chose to use
### Unstructured text 1
"Although these developments are encouraging to researchers, much is still a mystery. “We often have a black box between the brain and the effect we see in the periphery,” says Henrique Veiga-Fernandes, a neuroimmunologist at the Champalimaud Centre for the Unknown in Lisbon. “If we want to use it in the therapeutic context, we actually need to understand the mechanism.“" 

## Template prompt
Extract the name of places in the following text. 
Desired format:
Place: <comma_separated_list_of_places>
Input: "Although these developments are encouraging to researchers, much is still a mystery. “We often have a black box between the brain and the effect we see in the periphery,” says Henrique Veiga-Fernandes, a neuroimmunologist at the Champalimaud Centre for the Unknown in Lisbon. “If we want to use it in the therapeutic context, we actually need to understand the mechanism.“"

### AI's output
```JSON
{
  "Place": [
    "Champalimaud Centre for the Unknown",
    "Lisbon"
  ]
}
```

### Unstructured text 2
Input: Jeremy Ben, age 28, lives in Nigeria and works as a software engineer. He has a little brother in Manchester, Europe, who is 22 years of age, his name is Ben Paulo and he is a fotballer. 

## Template prompt 2
"Extract the following fields from the text: Name, Age, Location, Occupation. Return the output in JSON format." 
Desired format: return the output in JSON format 
Place: <comma_separated_list_of_places>

Input: Jeremy Ben, age 28, lives in Nigeria and works as a software engineer. He has a little brother in Manchester, Europe, who is 22 years of age, his name is Ben Paulo and he is a footballer. 

### AI's output
```JSON
{
  "people": [
    {
      "Name": "Jeremy Ben",
      "Age": 28,
      "Location": "Nigeria",
      "Occupation": "Software engineer"
    },
    {
      "Name": "Ben Paulo",
      "Age": 22,
      "Location": "Manchester, Europe",
      "Occupation": "Footballer"
    }
  ]
}
```

3. ## Output validation and reflection
The output is validated and is confirmed to be consistent. This pattern of prompting generates a very consistent answer and limits the output to only the very important things. The output is given in the structure and format as specified in the prompt.
