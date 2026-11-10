# Sponsor integrations

| Folder | Sponsor | What goes here |
|---|---|---|
| paypal/ | PayPal | Auth token, fetch disputes and transactions, submit evidence, verify webhooks |
| channel3/ | Channel3 | Product search and product details for e-commerce discovery |
| aggrid/ | AG Grid | Turn AG Grid's sort/filter/page requests into MongoDB queries and send back rows |
| bryntum/ | Bryntum | Turn evidence and dispute milestones into the timeline format Bryntum expects |

Keep sponsor API calls only inside this folder. Controllers call these files, never the sponsor APIs directly.
