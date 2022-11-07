# net0_datamodel
Data Model for processing building energy data, including business/organisational, meta data and context.

This data model is to standardise building and energy data for working through data analysis tools. The tools we started developing are grounded in the [Energy Information Handbook: Application for Energy-Efficient Building Operations](https://buildings.lbl.gov/publications/energy-information-handbook).

## draft structure of building energy data
```
mysensor:
{
    "name": "sensor name",
    "ts": [('2022-01-01 00:00:00',val1), ...],
    "metadata":{
        #some meta data I think
    },
    "context":{
        #some context 
    }
}
```