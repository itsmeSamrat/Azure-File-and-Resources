<div align="center">
    <a href="https://github.com/itsmeSamrat" target="_blank">
        <img src="https://github.com/itsmeSamrat/Azure-File-and-Resources/blob/main/Draw%20your%20Own%20Architecture/icon%20used/azure.jpg?raw=true" 
        alt="Logo" width="700" height="500">
    </a>
</div>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=1000&center=true&vCenter=true&width=435&lines=Draw+Your+Own+Architecture">
</div>

[Getting Started](#getting-started)

## Description

This is all about drawing our own architecture. We have a problem statement which is below. We need to find an solution for this problem using Azure Resources and make an architecture with profession clean icons. The icons are taken from Microsoft Azure [Documentation](https://learn.microsoft.com/en-us/azure/architecture/icons/) and some of them are being uploaded in the directory. We have used [this](https://app.diagrams.net) online tool to create the solution. For more details, please read the pdf file.

### PROBLEM STATEMENT

The STK company is a brand new start up responsible to deliver 95% of all the products sold by Amazon in Canada. This company is using SAP, ORACLE, and Microsoft Dynamics 365 CRM, as the main data sources. The company also has some data stored in a blob storage service on Azure (CSV files and unstructured data). The main idea is to move ALL the data to a cloud instance (Azure). They need a unique place to store all the data and to help them to explore the data, generating data analysis, and prep the structure for future AI projects.

## SUMMARY

To conclude, we have made an Azure based architecture to tackle our problem. All the input data source are taken in by Azure Data Factory and is stored on Azure Data Lake. After that, for modification and data pre processing, the Azure Synapse Services is used. Followed by that, we used Azure Synapse Analytics to perform data analytics. The result after the data analytics, were taken in by PowerBI , where we were able to make a dashboard for insight identification and extraction.

For the AI part, all the data necessary for training the model is taken from Azure Synapse Service. The trained model is deployed to Azure Kubernetes Service and is monitored through Azure Monitor. After checking the log file, we can decide if we need to retrain the model or not.

The data for future AI projects can be stored in one Azure Synapse Service and can be reused again and again as the data has been pre processed.

<!-- Back to the top -->

[Return Back to Top ⬆️](#getting-started)
