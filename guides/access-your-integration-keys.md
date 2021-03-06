
# Access your integration keys

To be able to test and use Easy Checkout you need a set of **integration keys** (API keys) to **identify** your webshop and make the integration **secure**.


## Before you start

- Create an [Easy Portal account](create-account.md)

## Integration keys
Your unique integration keys make your integration with Nets Easy secure. There are two sets of integration keys: one for the **test** environment and one for the **live** environment. 

For each environment, **two keys** are provided:
- The **Secret API key** which your backend sends to Nets Easy for authentication. The private API key should be kept secret and should never be passed from your frontend code. 
- The **Checkout key** which is a public identifier for your webshop. This key can be passed from your frontend to Nets Easy as a public identifier.

## Copy your keys
To access your keys, navigate to [Company Integration](https://portal.dibspayment.eu/integration) in Easy portal. Depending on what environment you are using, copy the relevant set of integration keys as demonstrated in the following screenshot:


![Easy Portal Company Integration](images/easy-portal-company-integration.png)