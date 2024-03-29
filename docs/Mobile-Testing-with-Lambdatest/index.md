---
title: Mobile Testing using Lambdatest 
intro: 'Mobile Application Testing with ContextQA and LambdaTest Integration'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Pages
children:
  - /login-to-contextqa
  - /link-jira-with-portal
  - /create-test-case-in-portal
  - /view-test-case-in-jira
shortTitle: Get started
---
**Mobile Application Testing with ContextQA and LambdaTest Integration**

- **Step1: Application Upload:**
  - Navigate to the LambdaTest platform -> Real Devices ->App Testing

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.001.png)

- Upload your Android or iOS application and Select the particular device like example iphone 13 and click on start
- Upon successful upload, a unique URL for your application will be generated by LambdaTest
- Copy this URL for later use

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.002.png)

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.003.png)

- **Step2: URL Retrieval:**

**Click on UI Inspector** 

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.004.png)

**Click on relaunch the app and you will see a message ‘App relaunched successfully’**

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.005.png)

Click on the Elements and copy the xpath and create element in ContextQA Element dictionary.

Now Create Test steps.


- **Test Case Creation:**
  - Open ContextQA and initiate a new test case.
  - Ensure the 'mobile testing' option is activated.

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.006.png)

- Utilize ContextQA's elements and low-code/no-code steps.



- **Test Suite and Plan:**
  - Construct a new test suite and outline your test plan within ContextQA.

Create a new Test Suite

Click on Create

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.007.png)

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.008.png)

Click on Add Testcases

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.009.png)


Created Test Suite will reflect like this

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.010.png)

Test Plan

Click on Create Test Plan

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.011.png)

Add all the details and Click on Next

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.012.png)

Click on Add Test Suites

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.013.png)

Select the Test Suites that you would like to add

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.014.png)


Select Test Suites checkbox and click on Add Machine Device

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.015.png)

Add all the required details

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.016.png)

Under Desired capabilities, Add app URL and the label to it

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.017.png)![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.018.png)![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.019.png)

Click on Next

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.020.png)


Click on Create

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.021.png)

You have successfully created Test Plan


![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.022.png)

- **Execution:**
  - ContextQA will handle the automation process and begin the test on the selected device via LambdaTest.

Click on Run Now

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.023.png)

- **Results and Logs:**
  - Once the test is completed, results will be accessible within ContextQA.
  - Detailed recordings, logs, and traces will be provided for analysis.

You can check Results by going to ContextQA Run Results – Click on particular Test plan -> Testcase



![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.024.png)

Where to get app URL from

Go to Lambdatest device that you uploaded and click on settings icon

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.025.png)

Now copy the app\_id

![](../Mobile-Testing-with-Lambdatest/mobile-images/Aspose.Words.7d631ad0-db57-4dbb-b7d3-b7218ed71d68.026.png)







