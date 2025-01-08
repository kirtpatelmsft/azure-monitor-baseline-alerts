---
title: Frequently Asked Questions (FAQs)
weight: 20
---
# Frequently Asked Questions - Azure Monitor Baseline Alerts

This FAQ page provides answers to common questions about Azure Monitor Baseline Alerts (AMBA). It covers a variety of topics, including the types of alerts that can be monitored, how to deploy AMBA, best practices, and where to find additional monitoring learning resources. Whether you're just getting started or looking to deepen your understanding of AMBA, this FAQ page has you covered!

## General Questions

1. **What type of alerts can AMBA monitor?**

   AMBA supports a wide range of alert metrics that can be monitored, including:
   - CPU Utilization
   - Memory Usage
   - Networking Traffic
   - Application Response Times
   - Quota Utilization
   - and many more

2. **How do I deploy AMBA within my Azure environment?**
   
    AMBA can be deployed for both Azure resources, and specific Azure Patterns/Scenarios through the provided deployment templates within the AMBA site. Current deployment options include ARM, Bicep, Policy, and Deploy to Azure buttons.

3. **Where can I find best practices for implementing Azure Monitor Baseline Alerts?**
   
    Best practices for implementing alerting within your environment follow the Azure Well-Architected framework, by prioritizing Reliability, Security, Cost optimization, Operational excellence, and Performance efficiency. For more guidance on best practices within each of these WAF Pillars, please browse our documentation [here](https://learn.microsoft.com/en-us/azure/azure-monitor/best-practices-alerts). Furthur resources are also showcased on our homepage.

4. **How do I debug or view issues with any AMBA alerts I have created?**
   
   To view or debug issues for you created alerts, it is recommended to check the Activity Log within the Azure Monitor section. This log provides details that can help you understand, debug, and resolve any issues that arise with triggered alerts.

5. **Where can I find more resources to learn about AMBA and monitoring?**
    
   For learning resources, please refer to our monitoring journey table on the AMBA homepage. Additionally, helpful quick links on the homepage will guide you to a plethora of AMBA and monitoring-specific documentation.
   
{{< hint type=tip >}}

Got an unanswered question? Create a [GitHub Issue](https://github.com/Azure/azure-monitor-baseline-alerts/issues) so we can get it answered and added here for everyone's benefit 👍

{{< /hint >}}

{{< toc >}}
