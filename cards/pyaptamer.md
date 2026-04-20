In ESoC 2025, the package `pyaptamer` has been built in collaboration between ecoSPECS and the German Center for Open Source AI, to enable easy use of AI based in-silico aptamer generation.

## Applications Precondition

These projects can be used to get familiar with the pyaptamer library. If you want to apply for the European Summer of Code 2026 full projects, you should first become familiar with the library and open at least one substantial PR, either fixing bugs or contributing a feature enhancement. The PR does not need to be merged at the time your application is reviewed.

Applicants are also encouraged to actively use the library and identify bugs that may have been missed by contributors. We expect potential applicants to communicate before tackling issues and filing PRs. For easier issues, a quick note is enough, but for harder ones we expect a more detailed implementation plan.

Please note that while the use of AI is allowed, relying on automated AI agents or opening multiple PRs or issues without verifying their output can adversely affect the applicant.

## Full 2026 Projects

### Adding AptaDiff Algorithm
Currently we have 2 algorithms as part of suite, and would like to increase algorithm coverage for the `pyaptamer` repository, this would require adapting the entire [AptaDiff](https://github.com/wz-create/AptaDiff) algorithm from scratch in sklearn API format and according to the current public API format with tests.

Goals:
- develop the `pyaptamer.aptadiff` API and adapt with current `MoleculeLoader` dataloader 
- write tests for the implementation.
- build a notebook, showcasing the public API with current and new datasets.


**Expected Time**: 300 hours<br>
**Difficulty Rating**: Hard<br>
**Required Skills**: Python, familiarity with deep learning, pytorch, lightning and scikit-learn<br>

### Adding DeepAptamer Algorithm

We would like to increase algorithm coverage for the `pyaptamer` repository, this would require adapting [DeepAptamer](https://github.com/TMBJ-lab/DeepAptamer) algorithm in sklearn API format and according to the current public API format with tests.

For more detail refer to these discussions: [#98](https://github.com/gc-os-ai/pyaptamer/pull/98) and [#110](https://github.com/gc-os-ai/pyaptamer/issues/110)


**Expected Time**: 250 hours<br>
**Difficulty Rating**: Hard<br>
**Required Skills**: Python, familiarity with deep learning, pytorch, lightning and scikit-learn<br>