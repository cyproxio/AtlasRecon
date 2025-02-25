# AtlasRecon: Subdomain Enumeration and Active Recon using SSL Scanning

**AtlasRecon**  is a powerful  **subdomain enumeration**  framework designed to perform  **active recon**  by scanning the IP ranges of major internet service providers. It analyzes SSL certificates found on port 443 and helps uncover  **subdomains**  through  **active recon**  techniques. This repository collects and shares the results of these  **active reconnaissance**  activities, focusing on  **SSL certificate analysis**  and  **subdomain discovery**.

This repository contains data for  subdomain enumeration  on the following  **cloud service providers**:
- **AWS (Amazon Web Services)**
- **Akamai**
- **Cloudflare**
- **Fastly**
- **GCP (Google Cloud Platform)**
- **Oracle**

The data shared includes only the results of  **SSL certificate analysis**  and the  **subdomains**  discovered through  **active SSL scanning**.


## Data Structure
In this repository, the data is provided in  **JSON format**. Each file represents a collection of  **SSL certificate data**  and  **subdomain enumeration results**  obtained from a specific provider and date.

```json
{
  "results": [
    {
      "host": "3.5.140.169",
      "ip": "3.5.140.169",
      "port": 443,
      "tlsVersion": "TLSv1.2",
      "subjectCN": "*.s3.ap-northeast-2.amazonaws.com",
      "subjectAltName": "DNS:*.s3.ap-northeast-2.amazonaws.com, DNS:s3.ap-northeast-2.amazonaws.com"
    },
    {
      "host": "3.5.140.238",
      "ip": "3.5.140.238",
      "port": 443,
      "tlsVersion": "TLSv1.2",
      "subjectCN": "*.s3.ap-northeast-2.amazonaws.com",
      "subjectAltName": "DNS:*.s3.ap-northeast-2.amazonaws.com, DNS:s3.ap-northeast-2.amazonaws.com"
    }
  ]
}
```
You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## About AtlasRecon
[AtlasRecon](https://github.com/atlasproject)  is an open-source project aimed at conducting  **active reconnaissance**  on internet infrastructures to identify potential security vulnerabilities.  **AtlasRecon**  is part of this initiative, utilizing  **active SSL scanning**  to uncover  **subdomains**  and assist in  **security research**.

## About Cyprox
**Cyprox**  is a tool developed for  **subdomain discovery**,  **port scanning**, and other cybersecurity analyses. It integrates with  **AtlasRecon**  for  **active recon**  and  **subdomain enumeration**, enabling more effective and efficient analysis.  **Cyprox**  allows users to leverage  **AtlasRecon’s SSL certificate analysis**  and  **subdomain discovery**  techniques for free, making it a valuable tool for those conducting  **active recon**. For more information about  **Cyprox**, visit  [here](https://linkto.cyprox.com/).
