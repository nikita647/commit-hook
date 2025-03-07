# POC for Dependency Analysis on React

| **Author** | **Created on** | **Version** | **Last updated by**|**Last Edited On**|**Level** |**Reviewer** |
|------------|---------------------------|-------------|----------------|-----|-------------|-------------|
| Nikita Joshi|  07-03-2025           | v1         | Nikita Joshi    |07-03-2025    |  internal review | komal jaiswal | 

---

## Table of Contents
- [Introduction](#introduction)
- [POC Steps](#poc-steps)
- [Report Link](#report-link)
- [Conclusion](#conclusion)
- [Contact](#contact)
- [References](#references)

---

## Introduction

In this document, we are creating the Proof of Concept (POC) for **Dependency Scanning** in a React app using the `npm audit` command.

---

## POC Steps

### 1. Update Packages and Install npm

Run the following commands to update your system and install npm:

```bash
sudo apt update
```


### 2. Clone your React project
Clone the React project repository to your local machine.
### 3. Install npm
``` bash
sudo apt install npm -y
```
![Screenshot 2025-03-07 214813](https://github.com/user-attachments/assets/279db0df-e701-4e87-8327-632d047370ce)

### 4. Perform Dependency Checks
Run the ```npm audit``` command to analyze the project’s dependencies for security vulnerabilities:
 ```
npm audit
```
![image](https://github.com/user-attachments/assets/ca29ae81-92ed-4d8e-8774-4a80af08421f)


### 5. To generate the html report, Use following command
You can generate an HTML report of the dependency audit using this command:
```
npm audit --ouput -html > report.html
```


## Report Link

- [Dependency check Report]()  





## Contact Information 


| **Name** | **Email address**            | **Github ID**
|----------|-------------------------------|-------------------|
| Nikita joshi    | Nikita.Joshi@mygurukulam.co    | https://github.com/jnikita19  |


## References


| **Links**                                           | **Description**         |
|-----------------------------------------------------|-------------------------|
| [Document]()  |  Detailed Documentation |

