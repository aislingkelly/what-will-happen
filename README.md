# What will happen (working title)

## Project description

The project will try to answer the question "What will climate change look like near me?"

The user will be able to input their location and see the consequences on their region at different levels of climate change. These would be represented in charts/graphs for rainfall and temperature at 2c and 4c.

## Goals for Version 1

Connect to the Met Office climate projections API. Get temperature and rainfall data for London. Display this data through charts in Streamlit.

## Libraries / Other Technology Needed

API Client Library
https://github.com/ukcp-data/ukcp-api-client

Met Office API Client Library
https://github.com/ukcp-data/ukcp-api-client

Streamlit
https://streamlit.io


## Risks

_Risk_
Complexity of matching user input to API data.
_Mitigate_
Simplify input to countries only. Display only certain regions.

_Risk_
Having data from several different resources - different countries/different postcodes.
_Mitigate_
Use UK only data from Met Office.

_Risk_
Interpreting complicated data, such as the worldwide CMIP5. Trying to simplify this into basic outputs.
_Mitigate_
Use UK only data from Met Office.

