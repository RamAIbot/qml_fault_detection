# QML-for-Conspicuity-Detection-in-Production
Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:
  - Maximum team size = 2
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:
  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with Fraunhofer ITWM. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:
  - Click [here](https://drive.google.com/file/d/1AcctFeXjchtEhYzPUsHpP_b4HGlI4kq9/view?usp=sharing) to view the project description.
  - YouTube recording of the project description - [link](https://youtu.be/Ac1ihFcTRTc?si=i6AIVfQQh8ymYQYp)

## Project Submission:
All information in this section will be considered for project submission and judging.

Ensure your repository is public and submitted by **August 9, 2024, 23:59pm US ET**.

Ensure your repository does not contain any personal or team tokens/access information to access backends. Ensure your repository does not contain any third-party intellectual property (logos, company names, copied literature, or code). Any resources used must be open source or appropriately referenced.

### Team Information:
Team Name : Quantum Codex
Team Member 1:
 - Full Name: Ramachandran Sekanipuram Srikanthan
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx):WQ24-INlrVKg0yQiodqC


Team Member 2:
 - Full Name: Shruti Taksali
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx):


### Project Solution:
_Include a comprehensive summary of all important information about your project solution here._
All necessary code files and any additional information required to judge your project solution should be included in the repository. 

Results  - https://github.com/RamAIbot/qml_fault_detection/tree/master/Final_results

In this project, we have explored the usage of Deep learning techniques and Quantum Machine learning (QML)  techniques to perform classification of Welded structures whether it is a good weld or a defective item. We have also categorized the detective item into various buckets of the weld defects in an automated way.

In the case of the binary classification into good welds and defects, the classical deep learning (DL)  model Resnet18 was able to achieve an accuracy of 97% while the hybrid QML model achieved 92%. It can be noted that the hybrid QML model was able to achieve good results like the DL model with a lesser number of parameters in the linear layer.

In the case of the multi class classification into good welds and also categorizing defects into various categories -  burn through, contamination, lack of fusion, misalignment, lack of penetration, the classical deep learning model Resent18 was able to achieve 79% while the less complex DL model VGG19 was able to achieve 82%. This is due to the fact that an imbalanced dataset and complex model like Resnet18 are much prone to overfitting. On the other hand, the hybrid QML models were able to perform slightly less than the DL model with an accuracy of 59%. Even Though, we can see that the training and validation accuracies in hybrid QML models are more than 95%, it was not able to work well because of class imbalances, classical DL overfitting and Barren plateaus. 

We can note that convergence for the loss curve doesn’t change that much with an increase in depth from 4 to 8. This is due to the fact that, even though we have a large number of trainable parameters with increase in depth, due to the Barren plateauing effect (where the optimization landscape becomes much flatter), we are not able to leverage the advantages of a large number of trainable parameters.

On the other hand, with an increase in the number of qubits from 4 to 8 and having the same depth of 4, the convergence becomes faster. So, we can note that having a large number of qubits with lesser depth is better than having a smaller number of qubits with large depth.

[A project report is added in this repo for comprehensive details].

### Project Presentation Deck:
_Upload/ Link a 3min. presentation deck here._

See project presentation guidelines [here](https://docs.google.com/document/d/13nWF8AxFAfFYTWEYPT3BpPdYkqtxxSAjmuXj_zcMh-E/edit?usp=sharing)

[Added Presentation slides in this repo]

Link 
<a href="https://docs.google.com/presentation/d/1Y6sKyRknrugQWlMf_0_BX-oy2uqRKXIuiIbhJxYlUgI/edit?usp=sharing">https://docs.google.com/presentation/d/1Y6sKyRknrugQWlMf_0_BX-oy2uqRKXIuiIbhJxYlUgI/edit?usp=sharing</a>
