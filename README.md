# Dynamics-365-for-Finance-and-Operations-Xpp-Azure-Service-Bus-Queue-wrapper
Azure Service Bus Queue read/write interaction with Peek-Lock and Delete features

To write and read data from Azure Service Bus Queue:
1. Create Service Bus Namespace in Azure portal;
2. Create Service Bus Queue;
3. Create Queue SAS policy with read and write permissions (split permisiions in your prod);
4. Put your data from the Queue, Napespace and SAS key into AxClass_AzureServiceBusInteractionDemo.xpp
