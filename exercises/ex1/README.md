# Exercise 1 - Access and explore the SAP Integration Suite

In this exercise, you will

- get familiar with the landing page of the SAP Integration Suite UI 
- get introduced to different capabilities and explore navigation across different aspects of SAP Integration Suite tooling.

## Login to SAP Integration Suite tenant

After completing these steps you will be able to see the SAP Integration Suite landing page and view the Migration Assessment and Cloud Integration capabilities offered as part of the SAP Integration Suite

> [!NOTE]
> <b>For USER01-USER45</b>
> 1. Click on the link https://teched2024-us01.integrationsuite.cfapps.us21.hana.ondemand.com/shell/home
> - <b>Please copy these values into Notepad as it would ne needed later</b>
> 3. Process Integration Client ID: <br>sb-a8427d4e-c96e-49c7-b46b-0c2044abbb96!b27512|it-rt-teched2024-us01!b46</>
> 4. Process Integration Client Secret: <br>429f0e43-1a70-4806-8dc2-81b074b2c27a$xI-cB39sZgxuvEGYGV5yNF3fyQnJ-st-HFggFyyiIL8=</>
> 5. Token URL: <br>https://teched2024-us01.authentication.us21.hana.ondemand.com/oauth/token</>
> 6. API Management API Access Client ID: <br>sb-231d16df-5248-49cd-ae22-ae1ede5adae2!b27512|it-rt-teched2024-us01!b46</>
> 7. API Management API Access Client Secret: <br>56580e85-5bbd-4fc3-9e09-bee5f5f66b22$NNVyGGXwFdV0NLBXB3EHN7vwro39m2sRo3y3AteKLm0=</>

> [!NOTE]
> <b>For USER46-USER99</b>
> 1. Click on the link https://teched2024-us02.integrationsuite.cfapps.us20.hana.ondemand.com/shell/home
> - <b>Please copy these values into Notepad as it would ne needed later</b>
> 3. Process Integration Client ID: <br>sb-8c6c4c93-e22d-4fa7-b68c-f493fb9215f0!b23471|it-rt-teched2024-us02!b34</>
> 4. Process Integration Client Secret: <br>beaf470e-9ab7-4c01-8789-784dfcdd780a$ZZ0GdH71M9y9cZxDlAYpLHZEQ_W3fpgek9W1ckUKOPA=</>
> 5. Token URL: <br>https://teched2024-us02.authentication.us20.hana.ondemand.com/oauth/token</>
> 6. API Management API Access Client ID: <br>sb-2fbefac2-b4b1-4207-b612-55779f98040e!b23471|it-rt-teched2024-us02!b34</>
> 7. API Management API Access Client Secret: <br>f62a2f8a-a0bb-4e98-b1cf-694406de5cba$YBhS4a-v0oADWfIc3Tc8rCNfL7VWknF1wNtrzDo-ymo=</>

Enter User as <b>USERXX</b> (where XX is from 00 to 99) and Password as <b>Welcome1</b> and Click on <b>Log On</b>.
   <br>![](/exercises/ex1/images/Login.png)

## Explore SAP Integration Suite tooling

 Now let´s explore the different capabilities and navigations of SAP Integration Suite tooling. <br>

> [!NOTE]
> The screenshots below show more items than the ones you have access to with your user. This is because your user has only the access required to complete the exercises. The screenshots were taken with a user who has admin access in the tenant and the intention is to show you all the capabilities available in SAP Integration Suite.

**Home** is the first screen that you will land upon logging in to SAP Integration Suite. Click on the three-line icon (also called the _hamburger_ icon) in the top left corner to expand the navigation menu items. <br>

![](/exercises/ex1/images/ex1_1.png)

The first section of interest within the Home region is the **Recent** Activities & **Monitoring**, which gives you a snapshot of what´s going on with the SAP Integration Suite tenant. It lists the artifacts that you/ other users have recently worked on and also the monitoring status of the deployed artifacts. You can navigate to them directly from here. <br>

![](/exercises/ex1/images/ex1_2.png)

Then you will see the list of **Capabilities** that are activated in this tenant. SAP Integration Suite provides many different capabilities like Cloud Integration, API Management, Integration Advisor, Trading Partner Management, Open Connectors, Integration Assessment, and Migration Assessment to address all your integration requirements. <br>

![](/exercises/ex1/images/ex1_3.png)


Last section of the Home page is the **Resources** segment, where links to documentation, tutorials, and also an option to request for addititional features. <br><br>

![](/exercises/ex1/images/ex1_4.png)


Now if you look at the different navigation sections on the left, after Home, you will see **Discover**, which opens up a repository of all standard pre-built content (integrations, APIs and type systems) shipped by SAP. Based on your specific integration need, you can explore, search and copy them to your Design workspace to kick-start your integration development. <br><br>

![](/exercises/ex1/images/ex1_5.png)


**Design** is your local workspace where you can design and configure integrations, APIs, message implementation guidelines, mapping guidelines, scripts and other integration artifacts. <br><br>

![](/exercises/ex1/images/ex1_6.png)


**Test** your APIs and analyse the response you get from them <br><br>

![](/exercises/ex1/images/ex1_7.png)



Use this section to **Configure** API Proxies, API Providers, Certificates,  Key Value Maps and Policy Templates for your APIs <br><br>

![](/exercises/ex1/images/ex1_8.png)



In the **Monitor** section, you can check the deployment status, look at message processing logs, manage security materials, data stores, message queues and all that you need to monitor and operate your integrations across multiple runtimes. <br><br>

![](/exercises/ex1/images/ex1_9.png)


The **Analyze** section gives you useful pre-built analytical charts and dashboards for an API Administrator and Business personnel to gauge the health, engagement and operational insights of the deployed APIs.

![](/exercises/ex1/images/ex1_10.png)

**Inspect** enables you to assess the overall resource situation of the tenant, like identifying hotspots, breakdown of resource consumed by each integration flow, resource usage trends. <br><br>

![](/exercises/ex1/images/ex1_11.png)


You can use **Monetize** to define rate plans for the API Products that you build and check the API usage pattern. The in-built billing engine also generates the bills for you, which can be accessed across multiple channels. <br><br>

![](/exercises/ex1/images/ex1_12.png)



If you have a Tenant Admin role assigned, you will be able to access **Settings**. Here you can configure settings that are applicable for the entire tenant like managing runtime profiles, configuring transport management, setting up API Management, customization of MIGs & MAGs, etc. <br><br>

![](/exercises/ex1/images/ex1_13.png)

![](/exercises/ex1/images/ex1_14.png)

## Summary

Congratulations! You have successfully completed the Exercise **Access and explore the SAP Integration Suite.**

Now that you have explored the different capabilities and navigations of SAP Integration Suite tooling you can move to [Exercise2 - SAP Process Integration walkthrough](../ex2/README.md)


