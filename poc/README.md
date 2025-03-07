# POC for Dependency Analysis on React

![image](https://github.com/user-attachments/assets/7a126104-c5d6-4b33-8215-718150d5a7fe)


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

In this document, we are creating the Proof of Concept (POC) for **Dependency Scanning** in a React app using the `npm audit` command.The goal is to identify and analyze security vulnerabilities in the project's dependencies.



---

## POC Steps

### 1. Update Packages

Run the following commands to update your system:

```bash
sudo apt update
```

__
### 2. Clone your React project
Clone the React project repository to your local machine.
___
### 3. Install npm
If npm is not already installed, you can install it using the following command:
``` bash
sudo apt install npm -y
```
![Screenshot 2025-03-07 214813](https://github.com/user-attachments/assets/279db0df-e701-4e87-8327-632d047370ce)
___
### 4. Perform Dependency Checks
Run the ```npm audit``` command to analyze the project’s dependencies for security vulnerabilities:
 ```
npm audit
```
This command will generate a report detailing any vulnerabilities found in the dependencies.
![image](https://github.com/user-attachments/assets/ca29ae81-92ed-4d8e-8774-4a80af08421f)

___
### 5. To generate the html report, Use following command
You can generate an HTML report of the dependency audit using this command:
```
npm audit --ouput -html > report.html
```

___
## Report Link

- [Dependency check Report]()  

___
## **Conclusion**

This POC demonstrates how to use the npm audit command to identify and analyze security vulnerabilities in a React application's dependencies. By following these steps, you can ensure that your project dependencies are secure and up-to-date.

___
## Contact Information 


| **Name** | **Email address**            | **Github ID**
|----------|-------------------------------|-------------------|
| Nikita joshi    | Nikita.Joshi@mygurukulam.co    | https://github.com/jnikita19  |

___
## References


| **Links**                                           | **Description**         |
|-----------------------------------------------------|-------------------------|
| npm audit | Follow the [Link](https://docs.npmjs.com/cli/v7/commands/npm-audit) |

