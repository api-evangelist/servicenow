---
title: "CMDB - Certificate Lifecycle Management: A ServiceNow Approach"
url: "https://www.servicenow.com/community/developer-blog/cmdb-certificate-lifecycle-management-a-servicenow-approach/ba-p/3527734"
date: "Fri, 17 Apr 2026 16:53:52 GMT"
author: "ersureshbe"
feed_url: "https://www.servicenow.com/community/s/cgfwn76974/rss/board?board.id=developer-blog"
---
<p class="lia-align-justify"><font color="#FF00FF"><u><em><strong>Use case:&nbsp;</strong></em></u></font><br />The procedure for managing the life cycle of certificates within the ServiceNow ecosystem. Understanding and advancing in certificate life cycle management.</p>
<p class="lia-align-justify">&nbsp;</p>
<p class="lia-align-justify"><font color="#FF00FF"><em><u><strong>Solution:</strong></u></em></font></p>
<p class="lia-align-justify">In the context of CMDB CI, Certificate Management plays a crucial role in the business environment. The management of the certificate life cycle outlines the processes for purchasing, revoking, discovering, and maintaining the end-of-life status of each business certificate.</p>
<p class="lia-align-justify">&nbsp;</p>
<p class="lia-align-justify">To enable Certificate Management in ServiceNow, it is necessary to activate the following plugin: Certificate Inventory Management (sn_disco_certmgmt).</p>
<p class="lia-align-justify">&nbsp;</p>
<p class="lia-align-justify">After activating the plugin, the following components will be enabled in the system:</p>
<p class="lia-align-justify">1. Certificate Management &gt; Under 'Workspace' Menu.</p>
<p class="lia-align-justify"><span class="lia-inline-image-display-wrapper lia-image-align-center" style="width: 400px;"><img alt="ersureshbe_0-1776443334845.png" src="https://www.servicenow.com/community/image/serverpage/image-id/510917i15FE332653A06D0E/image-size/medium?v=v2&amp;px=400" title="ersureshbe_0-1776443334845.png" /></span></p>
<p class="lia-align-justify">&nbsp;</p>
<p class="lia-align-justify">2. Access the portal (SP (Service Portal) or ESC (Employee Center)).</p>
<p class="lia-align-justify"><span class="lia-inline-image-display-wrapper lia-image-align-center" style="width: 400px;"><img alt="ersureshbe_1-1776443410431.png" src="https://www.servicenow.com/community/image/serverpage/image-id/510919i25DA5533219ADE99/image-size/medium?v=v2&amp;px=400" title="ersureshbe_1-1776443410431.png" /></span></p>
<p class="lia-align-justify">&nbsp;</p>
<p class="lia-align-justify">Once verified and successfully activated, it is essential to comprehend the End-to-End architecture. In the architecture below, I have included two systems: a. Microsoft b. DigiCert.</p>
<p class="lia-align-justify">Microsoft - This system does not have a connector. You should utilize the out-of-the-box (OOB) capabilities to develop the solution.</p>
<p class="lia-align-justify">DigiCert - A connector is available; you can install it and proceed with a plug-and-play approach.</p>
<p class="lia-align-justify">&nbsp;</p>
<p class="lia-align-justify">In the architecture diagram below, the initial step involves initiating the request, renewal, and revocation actions from the ServiceNow portal. For the Microsoft system, a custom solution should be developed using IntegrationHub and PowerShell scripts to integrate Microsoft and execute the request, renewal, and revocation operations. The DigiCert connector can simply be purchased from the ServiceNow Store and installed. Once installation is complete, you must configure the 'API Key' from ServiceNow, which will establish a connection between ServiceNow and DigiCert.</p>
<p class="lia-align-justify">&nbsp;</p>
<p class="lia-align-center"><span class="lia-inline-image-display-wrapper lia-image-align-inline" style="width: 400px;"><img alt="ersureshbe_2-1776443462812.png" src="https://www.servicenow.com/community/image/serverpage/image-id/510920iF6DED0F9272D0A1A/image-size/medium?v=v2&amp;px=400" title="ersureshbe_2-1776443462812.png" /></span></p>
<p>&nbsp;</p>
<p>When you perform the aforementioned activity phase-1, it supports the request, revocation, and renewal activities. Subsequently, we must populate the certificate details into the ServiceNow CMDB tables. To accomplish this task, it is necessary to enable Certificate Discovery within the instance. The following steps are required to enable Certificate Discovery.</p>
<p>&nbsp;</p>
<p><font color="#0000FF"><em><u>Step-1:</u></em></font> Install the Mid Server, which serves as a connection between ServiceNow and the Microsoft or DigiCert System.</p>
<p><font color="#0000FF"><em><u>Step-2</u></em></font>: Configure Certificate Discovery in ServiceNow. To do this, navigate to the left menu &gt; type 'Discovery Schedule' &gt; Click 'New'</p>
<p class="lia-align-justify">&nbsp;</p>
<p class="lia-align-center"><span class="lia-inline-image-display-wrapper lia-image-align-inline" style="width: 400px;"><img alt="ersureshbe_4-1776444003864.png" src="https://www.servicenow.com/community/image/serverpage/image-id/510922i07DD59DF62D67D3C/image-size/medium?v=v2&amp;px=400" title="ersureshbe_4-1776444003864.png" /></span></p>
<p>You select the Certificate Discovery type in the configuration.</p>
<p><em><font color="#0000FF">a. URL‑based discovery</font></em> - “Go to this URL or IP, perform a TLS handshake, and record the certificate that the server presents.”</p>
<p><span class="lia-inline-image-display-wrapper lia-image-align-center" style="width: 400px;"><img alt="ersureshbe_6-1776444412165.png" src="https://www.servicenow.com/community/image/serverpage/image-id/510924i6EF09B9B10D49F23/image-size/medium?v=v2&amp;px=400" title="ersureshbe_6-1776444412165.png" /></span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><font color="#0000FF"><em>b. CA Trust discovery</em></font> - “Scan this machine or device and list all certificates it trusts or stores.”</p>
<p><span class="lia-inline-image-display-wrapper lia-image-align-center" style="width: 400px;"><img alt="ersureshbe_5-1776444261216.png" src="https://www.servicenow.com/community/image/serverpage/image-id/510923iFE46BC33D8E66D7A/image-size/medium?v=v2&amp;px=400" title="ersureshbe_5-1776444261216.png" /></span></p>
<p class="lia-align-justify">Once it has been successfully configured within the discovery schedules, it will execute according to the time set in the schedule. After the discovery process is complete, you should verify the 'cmdb_ci_certificate' table. This table will present the pertinent certificates resulting from the discovery.</p>
<p class="lia-align-justify">&nbsp;</p>
<p>Regards,</p>
<p>Suresh.</p>
