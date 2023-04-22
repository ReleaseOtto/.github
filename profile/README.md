## Release Otto :robot:
The idea behind Release Otto, is automated release chaining, meaning that one release of can trigger some kind of action elsewhere, effectively chaining releases of different kidns together. Effectively minimizing maintainance needed and always staying up to date.

This for example can be:
- Auto-generated API clients based on AsyncAPI documents (same applies for OpenAPI). FoFor example when the API version change, so does the clients to interact with it, without anyone moving a finger. This includes correctly versioning the auto-generated clients.
- Auto-generated x based on JSON Schema documents, for example using [Modelina](https://github.com/asyncapi/modelina).


## Users :family:

Who uses Release Otto and for what?

| 🧙 **<a href="https://github.com/ModelinaModels">AsyncAPI Types</a>** | 👩‍💻 **<a href="https://github.com/GamingAPI">GamingAPI</a>** |
|---|---|
| Auto-generated types for strongly types languages that can represent an AsyncAPI document  | Auto-generate clients to interact with different applications within the GamingAPI ecosystem.  |
| _The AsyncAPI community maintain <a href="https://github.com/asyncapi/spec-json-schemas/">official JSON Schema documents</a>, that can validate AsyncAPI documents against the <a href="https://www.asyncapi.com/docs/reference">specification</a>. These JSON Schema documents are used to automatically generate types in Java, TypeScript, etc, that can be used to create, simple parse, and interact with AsyncAPI documents_ | _Based on <a href="https://github.com/GamingAPI/definitions">official AsyncAPI documents</a> that describe both public applications and internal ones. Libraries are auto-generated to enable easy and strict interaction between them._ |
