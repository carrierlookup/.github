## CarrierLookup

**Original carrier, line type and allocation lookups.**

Look up the carrier a phone number was originally allocated to, with line type, country and allocation region, in the same HTTP response. Up to 100 numbers per synchronous request.

[**Website**](https://carrierlookup.online) · [**API documentation**](https://carrierlookup.online/api-docs) · [**Pricing**](https://carrierlookup.online/pricing) · [**Get an API key**](https://carrierlookup.online/register)

### Official API example repositories

| Repository | Product code | Contents |
|---|---|---|
| **[Original Carrier Lookup](https://github.com/carrierlookup/phone-carrier-lookup-api)** | `carrier` | OpenAPI contract, `product.json`, `llms.txt`, examples in 7 languages |
| [carrierlookup-resources](https://github.com/carrierlookup/carrierlookup-resources) | — | Technical notes, guides and announcements |

Every example repository carries a machine-readable `product.json`, an `llms.txt` summary for AI clients, an OpenAPI 3.0 contract, and runnable examples in Python, Node.js, Go, Java, C#, PHP and Shell. All request paths, response fields and limits are taken from the live product pages and the published API documentation.

### One key, one balance

Every product on CarrierLookup uses the same API key, the same `X-API-Key` header and the same `code` / `msg` / `data` envelope, and draws from the same account balance.

### Responsible use

Results are **point-in-time signals**: they describe what a provider reported at the moment of the check. They are not identity verification, not proof of ownership, and not permission to contact anyone. Use the API only for identifiers you are authorized to process, and comply with applicable privacy laws and platform terms. Third-party trademarks belong to their respective owners; no affiliation or endorsement is implied.
