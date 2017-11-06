# readiness
readiness

## Summary

- [ ] Provide a high level summary of this new product feature. Explain how this change will benefit GitLab customers. Enumerate the customer use-cases.
- [ ] What metrics, including business metrics, should be monitored to ensure will this feature launch will be a success?

## Architecture

- [ ] Add architecture diagrams to this issue of feature components and how they interact with existing GitLab components. Include internal dependencies, ports, security policies, etc.
- [ ] Describe each component of the new feature and enumerate what it does to support customer use cases.
- [ ] For each component and dependency, what is the blast radius of failures? Is there anything in the feature design that will reduce this risk?
- [ ] If applicable, explain how this new feature will scale and any potential single points of failure in the design.

## Operational Risk Assessment

- [ ] What are the potential scalability or performance issues that may result with this change?
- [ ] List the external and internal dependencies to the application (ex: redis, postgres, etc) for this feature and how the it will be impacted by a failure of that dependency.
- [ ] Were there any features cut or compromises made to make the feature launch?
- [ ] List the top three operational risks when this feature goes live.
- [ ] What are a few operational concerns that will not be present at launch, but may be a concern later?
- [ ] Can the new product feature be safely rolled back once it is live, can it be disabled using a feature flag?
- [ ] Document every way the customer will interact with this new feature and how customers will be impacted by a failure of each interaction.
- [ ] As a thought experiment, think of worst-case failure scenarios for this product feature, how can the blast-radius of the failure be isolated?
