 [![Open in GitHub Codespaces](
  https://img.shields.io/badge/Open%20in%20GitHub%20Codespaces-333?logo=github)](
  https://codespaces.new/dwave-training/ocean-composites?quickstart=1)

# Ocean Composites
[Composites](https://docs.dwavequantum.com/en/latest/concepts/samplers.html#composites) are available in several packages in the D-Wave Ocean SDK.
Composites inherit their name from the design pattern they follow, the [Composite Pattern](https://en.wikipedia.org/wiki/Composite_pattern).

Using one or more composites, a sampler can be composed with a number of pre- and post-processing layers.

Note: As it stands, composites can only be used to compose [samplers](https://docs.dwavequantum.com/en/latest/concepts/samplers.html#samplers-and-solvers) for Binary Quadratic Model problems.

## Composites covered in lecture material
The lecture notebook covers several composites, exploring how they can be used and why they are useful!

* [StructureComposite](https://docs.dwavequantum.com/en/latest/ocean/api_ref_dimod/sampler_composites.html#module-dimod.reference.composites.structure)
* [EmbeddingComposite](https://docs.dwavequantum.com/en/latest/ocean/api_ref_system/composites.html#embeddingcomposite)
* [FixedEmbeddingComposite](https://docs.dwavequantum.com/en/latest/ocean/api_ref_system/composites.html#dwave.system.composites.FixedEmbeddingComposite)
* [TruncateComposite](https://docs.dwavequantum.com/en/latest/ocean/api_ref_dimod/sampler_composites.html#module-dimod.reference.composites.truncatecomposite)
* [FixVariablesComposite](https://docs.dwavequantum.com/en/latest/ocean/api_ref_preprocessing/api_ref.html#fix-variables)
* [TrackingComposite](https://docs.dwavequantum.com/en/latest/ocean/api_ref_dimod/sampler_composites.html#module-dimod.reference.composites.tracking)
* [SteepestDescentComposite](https://docs.dwavequantum.com/en/latest/ocean/api_ref_samplers/api_ref.html#steepestdescentcomposite)

## Installation

You can run this example without installation in cloud-based IDEs that support 
the [Development Containers specification](https://containers.dev/supporting)
(aka "devcontainers").

For development environments that do not support ``devcontainers``, install 
requirements:

    pip install -r requirements.txt

If you are cloning the repo to your local system, working in a 
[virtual environment](https://docs.python.org/3/library/venv.html) is 
recommended.

## Usage

Your development environment should be configured to 
[access the Leap Service](https://docs.dwavequantum.com/en/latest/ocean/sapi_access_basic.html).
You can see information about [supported IDEs](https://docs.dwavequantum.com/en/latest/leap_sapi/dev_env.html) and [authorizing access to the 
Leap Service](https://docs.dwavequantum.com/en/latest/ocean/leap_authorization.html#authorizing-access-to-the-leap-service).  

The notebook can be opened by clicking on the 
``Ocean-Composites.ipynb`` file in VS Code-based IDEs. 

To run a locally installed notebook:

```bash
jupyter notebook
```

## License

Released under the Apache License 2.0. See LICENSE file.
