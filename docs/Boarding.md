# Boarding API

The AccessOne Omaha/North boarding API is a web service which will allow Partners’ to programmatically submit MPA’s and retrieve the submitted MPAs’ processing statuses in real-time. The boarding API utilizes the AccessOne platform and boarding functionality to interface with Omaha/North mainframe. 

 The same validations that are implemented within the AccessOne boarding UI are present in the API  
 A success or failure message is returned, if a failure message is received the reason for the failure is included in the messaging as well


## Boarding API Requirements 

- Internal or external IT developer
- Knowledge of XML build out
- On-going support to update/add functionality released such as Compliance updates and new product launches
- Trouble shooting errors/issues 
- Internal boarding expert to provide guidance on how the AccessOne UI works and possibly business strategy to assist the API Product Owner in providing guidance on the mapping.
- Project manager is helpful but not required 


## Available Boarding API Calls

> **SubmitMpa**
> 
> - Submit the MPA to AccessOne.

> **ResubmitMpa**
> 
> *North only*
> 
> - Resubmit the MPA to AccessOne in case of errors returned from North BE after submitting an MPA.

> **RetrieveMpaXml**
> 
> - Retrieve xml of a successfully submitted MPA.

> **GetStatusByMpaId**
> 
> - Get status of a successfully submitted MPA.

> **GetStatusByTimeSpan**
> 
> - Get statuses of all successfully submitted MPA.

> **SearchByExtRefId**
> 
> - Get status of an MPA using the ExtRefId.

> **ResubmitToBOS**
> 
> - *Retail only*
> - Resubmit the MPA to the BOS team if they decline the MPA for additional information.

> **ResubmitToCreditUnderwriting**
> 
> - *Retail only*
> - Resubmit the MPA to the Credit Underwriting team if they decline the MPA for additional information.

> **ResubmitToAcceptTier2**
> 
> - *Omaha Only*
> - Resubmit the MPA to accept as Tier 2.
