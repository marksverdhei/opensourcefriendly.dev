# opensourcefriendly.dev
A website to keep track on Open-source products, companies and developer friendly integrations.

## OSF-1 score  
Open-source-friendliness v1, OSF-1 is a metric used to score the open-source friendlyness of a product.  

Categorical score:
0: Fully open-source with permissive license  
0.1: Open source-code with somewhat limited / copyleft license
0.2: Open source-code with limited / noncommercial license / obscure licenses, e.g. openrail
0.3: Proprietary optional / swappable software for customizable hardware
0.5: Partially closed-open-source - weighted based on code importance
0.7: Closed source, developer friendly with SDK / consumer API
1.0: Fully proprietary with DRM  

Should calculate weighted average of feature volume.


## Data types  

Early sketch of data types  

ProductType:
```json
{
    "name": "<name>",
}
```

Product:
```json
{
    "name": "<name>",
    "description": "<description>",
    "company_name": "<company_name>",
    "OSF-1": 0,
    "price": 0,
    "used-price": 0,
    "links": [
        "<web-shop-url>",
        "<manufacturer-url>"
    ]
}
```

Company:
```json
{
    "name": "<name>",
}
```