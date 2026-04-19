# Transparent & Attributed Source License (TASL)

The Modern Copyleft License for the AI and DevOps Era.

The Transparent & Attributed Source License (TASL) is designed to bridge the gap between traditional copyleft philosophy and modern software realities. It protects creators against AI plagiarism and "black-box" redistribution while remaining pragmatic for commercial and permissive ecosystems.

## How to Use

To apply this license to your project copy the contents of [`v1.0.md`](./v1.0.md) into a file named `LICENSE` or `LICENSE.md` in your project root.

## The TL;DR (Dos and Don'ts)

You **CAN**:

- **Use and Modify:** Use TASL-licensed code in both open-source and commercial applications.

- **Distribute Binaries:** Ship binaries with TASL code linked inside, provided you follow the transparency rules.

- **SaaS Usage:** Run the code on a server to provide a service (provided you share improvements).

- **Translate:** Rewrite the logic in a different programming language (as a protected Derivative Work).

You **MUST**:

- **Maintain Transparency:** Provide the build scripts (Dockerfiles, Makefiles) if you distribute a binary.

- **Enable Swapping:** Use dynamic linking for closed-source apps, or provide a way for users to swap the TASL component in static builds.

- **Attribute AI Training:** If you train a machine learning model on this code, you must cite the project in the model's metadata or documentation.

- **Keep UI Credits:** Ensure the Author is credited in an "About" or "Legal" menu within the software's interface.

## For Your Project's README

If you use TASL in your project, feel free to paste this helpful summary into your own README.md so your users understand their rights:

```markdown
## License
This project is licensed under the **Transparent & Attributed Source License (TASL) v1.0**.

TASL is a modern copyleft license that requires:
1. **Build Transparency:** Users must be able to see how the project is built and swap this library's version.
2. **AI Attribution:** Usage in AI training sets must be explicitly cited in the model's metadata.
3. **Derivative Protection:** Structural rewrites in other languages are considered derivative works.

[Read the full License here](./LICENSE.md)
```

## Contributing & Evolution

**Disclaimer:** I am not a lawyer. This license is a community-driven effort to define fair usage in the modern age. It has not been vetted by a court of law.

Suggestions and legal refinements are greatly appreciated! If you have ideas to close loopholes or improve clarity:

1. Open an Issue: To discuss high-level changes or concerns.

2. Submit a Pull Request:

   - If `draft.md` exists, modify it with your suggestions.

   - If no draft exists, create `draft.md` by copying the latest version (e.g., `v1.0.md`) and applying your changes there.

   - Proposed changes will be reviewed for a potential `v1.1` release.

## Why TASL?

Traditional licenses like the GPL were written before the rise of Cloud Computing (SaaS) and Large Language Models (AI). TASL ensures that if your logic is "borrowed" by a machine or hidden inside a proprietary container, the original creator still receives the credit and transparency they deserve.

## License Compatibility

TASL is more demanding than a standard MIT license. If you're mixing this code with other projects, you need to be aware of how these requirements (especially the AI and Translation clauses) interact with other licenses.

| License Type | Adding TASL code into that project | Using that project’s code in a TASL project | Notes |
| :--- | :--- | :--- | :--- |
| **Permissive** (MIT, Apache, BSD) | ✅ YES* | ✅ YES | *Permissive projects must still include build scripts and proper attribution. |
| **Weak Copyleft** (LGPL, MPL) | ✅ YES* | ✅ YES | *The TASL-governed files must remain under TASL. |
| **Strong & Network Copyleft** (GPLv2/v3, AGPL) | ❌ NO | ❌ NO | GPL forbids "additional requirements" like TASL’s AI attribution clause. |
| **Proprietary (Local/Binary)** | ✅ YES* | ❌ NO | *Allowed via dynamic linking or by providing a swapping mechanism. |
| **SaaS / Network Service** | ✅ YES* | ❌ NO | *Allowed if you open-source your modifications to the Work. |
