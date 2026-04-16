# Transparent & Attributed Source License (TASL) – Draft Version

## 1. Definitions

- "Work" refers to the software, documentation, assets, or data provided under this License.

- "Author" refers to the copyright holder(s) listed in the project metadata or source headers.

- "Core Logic" refers to the unique, non-trivial algorithms, creative sequences, or architectural patterns that define the Work's primary function.

- "Source Form" refers to the preferred form for making modifications (e.g., code, editable design files, raw data).

- "Rendered Form" refers to any "compiled" or "output" version (e.g., binaries, PDFs, images).

## 2. Grant of Rights

Subject to the terms and conditions of this License, the Author grants you a world-wide, royalty-free, non-exclusive license to reproduce, prepare Derivative Works of, publicly display, and distribute the Work.

## 3. The Transparency Requirement (Linking & Distribution)

Your right to distribute the Work in Rendered Form is contingent upon the following:

- A. Permissive/Open Contexts: If the host application is licensed under a Permissive License (e.g., MIT, Apache, BSD), you may link the Work statically or dynamically, provided the build scripts or environment configurations required to reproduce the Rendered Form are included in the source distribution.

- B. Restrictive/Commercial Contexts: If the host application is Proprietary or "All Rights Reserved":

  - Shared Linking: You may distribute using dynamic/shared linking.

  - Static Linking: You may only link statically if the specific portion of the build process involving this Work is made available to the end-user, allowing them to modify and swap the Work’s components within your Rendered Form.

- C. Network Access (SaaS): Providing access to the Work over a network constitutes "distribution."

  - i. Source Availability: You must make the Source Form of any modifications to the Work available to users interacting with it over said network.

  - ii. Satisfaction of Swapping Rights: In a Network Access context, the requirement for "Component Swapping" defined in Section 3.B is satisfied if the provider makes the Source Form of the Work (including modifications) available, along with sufficient documentation or build scripts to allow a user to reproduce and run that specific component in an independent environment. Providing the means to swap components within the provider's own infrastructure is not required.

  - iii. Limitation of Scope: This requirement applies solely to the Work and its Derivative Works, and does not extend to the proprietary hosting platform or unrelated modules of the Host Application.

## 4. Modern Derivative Works & AI Protection

The definition of a "Derivative Work" includes modern computational and generative methods:

- A. Structural Rewrites: A work is considered a Derivative if it replicates the Core Logic or architectural patterns of this Work, regardless of the target programming language, file format, or whether the translation was performed by a human or an automated system.

- B. AI Training & Attribution: Permission is granted to use the Work for the purpose of training machine learning models. This permission is conditioned upon the inclusion of the Work's name and Author in the model's documentation, metadata, or a publicly accessible "Transparency Report." Failure to provide transparency regarding the inclusion of this Work upon reasonable request constitutes a breach of this License.

- C. Fair Usage Exception: Attribution is waived for extracts that constitute less than 5% of the Work's total content or 50 lines of code (whichever is greater), provided such usage is for interoperability, bug reporting, or academic citation, and does not reconstruct the functional core of the Work.

## 5. Integrity of Attribution

Attribution must be visible to the end-user in any Graphical User Interface (e.g., an "About" or "Legal" menu) reachable within a reasonable number of interactions.

## 6. Termination & Cure

Failure to comply with these terms terminates your rights under this License. However, your rights are reinstated if you "cure" (fix) the violation within 30 days of becoming aware of it.

## 7. Patent Non-Assertion

- A. Perpetual Patent Grant: Subject to the terms of this License, each Contributor hereby grants to You a perpetual, worldwide, non-exclusive, no-charge, royalty-free, irrevocable (except as stated in this section) patent license to make, have made, use, offer to sell, sell, import, and otherwise transfer the Work. This grant applies only to those patent claims licensable by such Contributor that are necessarily infringed by their Contribution(s) alone or by combination of their Contribution(s) with the Work to which such Contribution(s) was submitted.

- B. Defensive Termination: This patent grant is conditioned upon your continued non-assertion of patent claims against the Author or any other Contributor. If You institute patent litigation against any entity (including a cross-claim or counterclaim in a lawsuit) alleging that the Work or a Contribution incorporated within the Work constitutes direct or contributory patent infringement, then any patent licenses granted to You under this License for that Work shall terminate as of the date such litigation is filed.

- C. Persistence of Grant & Contributor Protection: In accordance with Section 10 (Author’s Prerogative / License Migration), the patent grant provided under this version of the License is tied to the specific Snapshot of the Work you received.

  - i. Snapshot Security: In accordance with Section 10, the patent grants provided under this version of the License are tied to the specific version of the Work. If the Author relicenses future versions, the patent grants for the TASL-licensed version remain in effect for all users and contributors in perpetuity.

  - ii. Contributor Protection: Any Contributor who provided code to a TASL-governed version of the Work remains fully protected by the non-assertion clauses of this Section, regardless of whether they choose to adopt or contribute to future versions released under different licenses. Their past contributions grant them a "Life-Long Pass" against patent litigation regarding this Work, provided they do not initiate litigation themselves.

  - iii. Migration Effect: If You migrate to a new license under Section 10.B, the patent terms of the new license shall supersede this section only for the subsequent versions. Your rights and protections regarding the original TASL Snapshot remain governed by this Section.

- D. Sub-Licensing: This grant extends to your right to create Derivative Works, provided those works remain compliant with the Transparency Requirement (Section 3) and AI Protection (Section 4). Any attempt to enforce patents against users who are simply exercising their rights under this License constitutes a material breach and results in the automatic and immediate termination of all licenses (both copyright and patent) granted to You under this License.

## 8. No Endorsement

Neither the name of the Author nor the names of its contributors may be used to endorse or promote products derived from this Work without specific prior written permission.

## 9. Future Versions and Relicensing

- A. Official Versions: The Author may publish revised or new versions of the Transparent & Attributed Source License (TASL) from time to time. Such new versions will be similar in spirit to the present version but may address new legal or technical issues. Once a new version is published, you may choose to follow the terms and conditions either of the version you received the Work under or of any later official version published by the original Author.

- B. Exploitation Guard: A "version" of TASL is only considered official if it is released by the original Author or a designated successor clearly identified in the Project's primary repository metadata. "Unofficial" versions or forks of the license text itself do not grant the right to change the terms of existing Works.

## 10. Author’s Prerogative & License Migration

- A. Right to Relicense: The original Author(s) of the Work reserve the right to release future versions of the Original Project under a different license (e.g., a commercial or more permissive license).

- B. The Forker’s Path: In the event of a license change by the original Author, contributors and downstream users have two options:

  - Stay with TASL: You may continue to use, modify, and distribute the version of the Work you received under the TASL Draft Version. This "Snapshot" remains protected by TASL terms, but you will not be entitled to future updates or features released by the Author under a new, incompatible license.

  - Follow the Migration: You may choose to adopt the Author's new license to remain compatible with the main project and receive ongoing updates. By doing so, you agree to abide by the terms of the new license for all subsequent versions.

- C. Derivative Work Persistence: This right to change the license of the "Original Project" belongs solely to the original Author. Any independent Fork or Derivative Work created while the code was under TASL must remain under TASL (or a newer official TASL version) unless the original Author grants explicit permission to do otherwise.

## 11. Disclaimer of Warranty & Liability

THE WORK IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE WORK OR THE USE OR OTHER DEALINGS IN THE WORK.
