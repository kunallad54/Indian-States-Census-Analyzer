# Indian-States-Census-Analyzer

## USECASES : 

1. Ability for the analyser to load the Indian States Census Information from a csv file
   - Create a StateCensusAnalyser Class to load the State Census CSV Data
   - Create CSVStateCensus Class to load the CSV Data
   - Use Iterator to load the data
   - Check with StateCensusAnalyser to ensure
   - TC 1 : 
   Given the States Census CSV file, Check to ensure the Number
   of Record matches This is a Happy Test Case where the records
   are checked.
   - TC 2 :
   Given the State Census CSV File if incorrect Returns a custom
   Exception This is a Sad Test Case to verify if the
   exception is raised.
   - TC 3 :
   Given the State Census CSV File when correct but type incorrect
   Returns a custom Exception This is a Sad Test Case to verify if the type is
   incorrect then exception is raised.
   - TC 4:
   Given the State Census CSV File when correct but delimiter incorrect
   Returns a custom Exception This is a Sad Test Case to verify if the file
   delimiter is incorrect then exception is raised.
   - TC 5:
   Given the State Census CSV File when correct but csv header
   incorrect Returns a custom Exception This is a Sad Test Case to verify if the header is
   incorrect then exception is raised.
   
2. Ability for the analyser to load the Indian States Code Information from a csv file
   - Create CSVStates Class to load the CSV Data
   - Use Iterator to load the data
   - Check with StateCensusAnalyser to ensure number of record matches
   - Test Cases : Same as above Test Cases of UC1   
   
