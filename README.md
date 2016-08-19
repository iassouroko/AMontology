# AMontology

This repository contains an OWL ontology of concepts of additive manufacturing produced as part of NIST's [Systems Integration  for Additive Manufacturing](http://www.nist.gov/el/msid/lifecycle/sifam.cfm) project. 

The AM ontology has been developed following two major milestones. The ontology developed within the first milestone include AMProcessOntology, ModelOntology and AMOntology files. AMProcessOntology contains the set of entities used to capture knowledge about additive manufacturing processes. ModelOntology contains the set of entities used to capture knowledge about modeling concepts that represent (possibly) multi-physics multi-scale processes. AMOntology uses AMProcessOntology and ModelOntology files to describe entities that capture knowledge about characteristics of computational models for AM processes.

The AM ontology developed in the second milestone, under the file AMOntology-vFinal1, focus more on a formal explicit representation of the assumptions and approximations used along the development of computational models for AM. It also provides insight into potential qualitative indicators of the fidelity of these models. 

The only one ontology file that matters for future work, in the current repository, is the file AMOntology-vFinal1, which uses AMOntology_v3 and Laser-Thermal-Microstructure files, by direct import.

## Contacts
* Paul Witherell: paul.witherell@nist.gov, 301-975-3385
* Felipe Lopez: felipe.lopez@nist.gov, 301-975-5858
* Ibrahim Assouroko: ibrahim.assouroko@nist.gov, 301-975-2285


##Disclaimers

The use of any software or hardware by the project does not imply a recommendation or endorsement by NIST.

The use of the project results in other software or hardware products does not imply a recommendation or endorsement by NIST of those products.

We would appreciate acknowledgement if any of the project results are used, however, the use of the NIST logo is not allowed.

NIST-developed software is provided by NIST as a public service. You may use, copy and distribute copies of the software in any medium, provided that you keep intact this entire notice. You may improve, modify and create derivative works of the software or any portion of the software, and you may copy and distribute such modifications or works. Modified works should carry a notice stating that you changed the software and should note the date and nature of any such change. Please explicitly acknowledge the National Institute of Standards and Technology as the source of the software.

NIST-developed software is expressly provided “AS IS.” NIST MAKES NO WARRANTY OF ANY KIND, EXPRESS, IMPLIED, IN FACT OR ARISING BY OPERATION OF LAW, INCLUDING, WITHOUT LIMITATION, THE IMPLIED WARRANTY OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT AND DATA ACCURACY. NIST NEITHER REPRESENTS NOR WARRANTS THAT THE OPERATION OF THE SOFTWARE WILL BE UNINTERRUPTED OR ERROR-FREE, OR THAT ANY DEFECTS WILL BE CORRECTED. NIST DOES NOT WARRANT OR MAKE ANY REPRESENTATIONS REGARDING THE USE OF THE SOFTWARE OR THE RESULTS THEREOF, INCLUDING BUT NOT LIMITED TO THE CORRECTNESS, ACCURACY, RELIABILITY, OR USEFULNESS OF THE SOFTWARE.

You are solely responsible for determining the appropriateness of using and distributing the software and you assume all risks associated with its use, including but not limited to the risks and costs of program errors, compliance with applicable laws, damage to or loss of data, programs or equipment, and the unavailability or interruption of operation. This software is not intended to be used in any situation where a failure could cause risk of injury or damage to property. The software developed by NIST employees is not subject to copyright protection within the United States.
