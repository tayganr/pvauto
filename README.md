# Azure Purview Automation

Azure Purview provides several mechanisms in which we can interact with the underlying platform in an automated and programmatic fashion, spanning both the control plane (i.e. Azure Resource Manager) and the data plane (e.g. catalog, scanning, administration, etc). This article provides a summary of the options available, and guidance on what to use when.

| Tool Type | Tool | Scenario |
| --- | --- | --- |
**Command Line** | <ul><li><a href="https://docs.microsoft.com/en-us/rest/api/purview/" target="_blank">Azure CLI</a></li><li>Azure Az PowerShell</li></ul> | Interactive
**API** | <ul><li>REST API</li></ul> | Batch
**Streaming** | <ul><li>Apache Kafka</li></ul> | Real-Time
**SDK** | <ul><li>.NET</li><li>Java</li><li>JavaScript</li><li>Python</li></ul> | Custom Development
