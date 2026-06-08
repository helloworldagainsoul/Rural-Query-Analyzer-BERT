# Rural Query Analyzer using Multilingual BERT

## Overview

Rural Query Analyzer is an AI-powered system that uses Multilingual BERT to classify rural citizen queries and recommend the appropriate government department, service, and portal.

The goal of this project is to simplify access to public services by automatically understanding citizen complaints and directing them to relevant grievance redressal channels.

---



## Problem Statement

Rural citizens often face difficulties in identifying the correct government department, service, or online portal for their complaints and requests. 
This challenge is further amplified by language diversity, limited digital awareness, and the complexity of navigating multiple government platforms.
As a result, many grievances are delayed, misdirected, or left unresolved.

This project addresses this challenge by leveraging Multilingual BERT to automatically understand citizen queries, 
classify them into relevant service categories, and recommend the appropriate government department, service, 
and portal for faster and more accessible grievance resolution.



## Features

- Multilingual query understanding using BERT
- Rural complaint classification
- Government department recommendation
- Service recommendation
- Portal recommendation
- Support for multiple service categories

## Project Workflow

## Project Workflow

1. Citizen submits a query.
2. Multilingual BERT processes the query.
3. The query is classified into a service category.
4. The relevant government department is identified.
5. Appropriate service recommendations are generated.
6. The corresponding government portal is suggested.


## Technology Stack

- Python
- Pandas
- NumPy
- PyTorch
- Hugging Face Transformers
- Multilingual BERT
- Google Colab


## Categories Supported

- Electricity
- Agriculture
- Education
- Healthcare
- Roads
- Government Services
- Plumbing
- Sanitation

## Sample Outputs

### Example 1

**Query**

```text
PM Kisan registration problem
```

**Output**

```text
Category: Government
Department: Citizen Service Center
Service: Government Schemes
Portal: https://www.india.gov.in
```

### Example 2

**Query**

```text
scholarship apply karni hai
```

**Output**

```text
Category: Education
Department: Education Department
Service: Scholarship Information
Portal: https://scholarships.gov.in
```

### Example 3

**Query**

```text
bijli nahi aa rahi
```

**Output**

```text
Category: Electricity
Department: State Electricity Board
Service: Electricity Complaint Registration
Portal: https://pgportal.gov.in
```


## Future Improvements

- Increase dataset size for improved classification accuracy.
- Support additional regional languages and dialects.
- Integrate real-time government service APIs.
- Deploy as a web or mobile application.
- Incorporate computer vision techniques for infrastructure issue detection and monitoring.
- Extend the platform with AI-powered infrastructure analysis and workflow automation.
- Enhance recommendations using Generative AI assistance.

---

## Project Conclusion

This project demonstrates the application of Multilingual BERT for rural query classification & government service recommendation.
By automating complaint understanding and service guidance, it aims to improve accessibility to public services
& lays the foundation for future AI-driven rural infrastructure management solutions.
