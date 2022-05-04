| [Home](https://github.com/fortinet-fortisoar/solution-pack-chatops/blob/develop/README.md) |
|--------------------------------------------|

# Installation

To install a solution pack, click **Content Hub** > **Discover**.   
From the list of solution packs that appears, search for and select **ChatOps**.    
Click the **ChatOps** solution pack card.   
Click **Install** on the bottom to begin installation.

> All [dependencies](#prerequisites), if not already installed, are installed automatically.

## Prerequisites

|Solution Pack|Purpose|
| :- | :- |
|SOAR Framework 1.0.0|Required for Incident Response modules|

# Configuration

For optimal performance of **ChatOps** solution pack, you must configure:

* A connector that provides a geolocation service
    * To To configure and use the IPStack as a geolocation service provider, refer to [Configuring IPStack](https://docs.fortinet.com/document/fortisoar/1.0.0/ipstack/1/ipstack-v1-0-0)
* Threat intelligence connectors to enrich context of a given indicator
    * To configure and use the VirusTotal connector as a source of threat intelligence, refer to [Configuring Virus Total](https://docs.fortinet.com/document/fortisoar/2.1.0/virustotal/166/virustotal-v2-1-0#Configuration_parameters)

