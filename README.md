# Raptors LookAlike Demo
An implementation of Azure Cognitive Services Facial Recognition API to find out what Player on the Toronto Raptors team you look most like

## Introduction 
To showcase how you can use cognitive services API's to recognize faces, we will add a selection of the Toronto Raptors 2018-2019 players as "Persons", then add them to a "Person Group" and train it. 
Following that, we will add a new, unknown face, and then run it against the Raptors Person Group and see which player is returned.

## Instructions
* Either using the [Free Tier](https://azure.microsoft.com/en-us/try/cognitive-services/) or the [Marketplace version](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/Microsoft.CognitiveServicesFace), create a Face API Resource and get the key and endpoint 
* Open the [Azure Notebook]() containing the code
* Run each cell, making sure to get a 200 or 202 response
* Ensure that Cell 7 has the maxNumOfCandidatesReturned is set to 1 and the confidenceThreshold is set to 0

## Resources Used 
* Azure Portal - Cognitive Services 
* Azure Notebooks - Python 3 
* Face API Reference Page 
