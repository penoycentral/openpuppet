https://docs.puppetlabs.com/guides/style_guide.html

```
- Your module must be versioned.
- Must use two-space soft tabs
- All strings must be enclosed in single quotes, unless they contain variables or single quotes
- hard dependencies must be declared explicitly in your module’s metadata.json file
- Soft dependencies should be called out in the README.md, and must not be enforced as a hard requirement in your metadata.json. 
- You must use hash comments
- Every publicly available module must have metadata defined in the metadata.json file
- All resource titles must be quoted. 
- All of the hash rockets (=>) in a resource’s attribute/value list should be aligned. 
-If a resource declaration includes an ensure attribute, it should be the first attribute specified so a user can quickly see if the resource is being created or deleted
-Within a manifest, resources should be grouped by logical relationship to each other, rather than by resource type.
-Symbolic links must be declared with an ensure value of ensure => link and explicitly specify a value for the target attribute.
-POSIX numeric notation must be represented as 4 digits.
-POSIX symbolic notation must be a string.
