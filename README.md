# Ocean Composites
[Composites](https://docs.ocean.dwavesys.com/en/stable/concepts/samplers.html#composites) are available in several packages in the D-Wave Ocean SDK.
Composites inherit their name from the design pattern they follow, the [Composite Pattern](https://en.wikipedia.org/wiki/Composite_pattern).

Using one or more composites, a sampler can be composed with a number of pre- and post-processing layers.

Note: As it stands, composites only can only be used to compose [samplers](https://docs.ocean.dwavesys.com/en/stable/concepts/samplers.html#samplers) for Binary Quadratic Model problems.

## Composites covered in lecture material
The lecture notebooks cover several composites, exploring how they can be used and why they are useful!

* [FixVariablesComposite](https://docs.ocean.dwavesys.com/en/stable/docs_preprocessing/reference/composites.html#fix-variables-composite)
* [SteepestDescentComposite](https://docs.ocean.dwavesys.com/en/stable/docs_greedy/reference/composites.html#steepestdescentcomposite)
* [EmbeddingComposite](https://docs.ocean.dwavesys.com/en/stable/docs_system/reference/composites.html#embeddingcomposite)
* [FixedEmbeddingComposite](https://docs.ocean.dwavesys.com/en/stable/docs_system/reference/composites.html#fixedembeddingcomposite)
* [StructureComposite](https://docs.ocean.dwavesys.com/en/stable/docs_dimod/reference/sampler_composites/composites.html#module-dimod.reference.composites.structure)
* [TruncateComposite](https://docs.ocean.dwavesys.com/en/stable/docs_dimod/reference/sampler_composites/composites.html#module-dimod.reference.composites.truncatecomposite)