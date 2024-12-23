---
# For reference on model card metadata, see the spec: https://github.com/huggingface/hub-docs/blob/main/modelcard.md?plain=1
# Doc / guide: https://huggingface.co/docs/hub/model-cards
{{ card_data }}
---

# Model Card for {{ model_id | default("Model ID", true) }}

<!-- Provide a quick summary of what the model is/does. -->

{{ model_summary | default("", true) }}

## Model Details

### Model Description
    Aris is designed to be an integral part of a comprehensive plan to address Canada’s housing crisis and ultimately create a better world where equal opportunity is not just a slogan but a way of life. This long-term 100-year agenda aims to eliminate poverty and struggle through a unified approach to replacing labor-intensive jobs with mechanical advancements and streamlined work planning processes. Ultimately, our careers will be directed towards the benefit, survival, and comfort of humanity, eliminating the need for money through technological progress.
 
        With technological advancements, everyone will have access to all the necessities, leisure activities, personal technologies, and recreational items they desire, without anyone going without. The only requirement will be dedicating 8-12 hours a day, 5 days a week, to an action defined as a job that benefits mankind. As well as a required voting process which allows all citizens to receive the related informative video to their personal device and vote via the same platform using technological advancements for verifications from the comfort of your home in its solution to inflation, poverty, and all the burdens they place on our modern society. we expect in solving the housing crisis we allow the minds of those related will than be open to the next large problems of society.
 
       Aris will assist Canadians in solving our housing crisis by implementing an efficient work plan for the construction industry. It will monitor the production of individual builds that purchase our products, speeding up the process by fastracking the application process, creating building design plans, and providing a real-time interactive platform for both builders and customers to visualize the 3D model. This allows homeowners to quickly communicate their preferences and ensure that the home meets building code standards.
 
      Aris will also provide an immediate price difference and explanation of the material cost evaluation, making it easy for homeowners to understand the differences. Additionally, they have the option to revert without wasting time or money.
       
       The model will create an intractable platform between the bank, the builder, and the homeowner to monitor the spending of financed builds. To ensure accuracy, the labor force will be required to photograph the progress every pay period, allowing the AI to evaluate the progress and the amount earned in relation to the work completed and left remaining, which aligns with the agreed-upon price. 
    
      Object recognition technology will use GPS coordinates from workers’ cell phones to ensure the accuracy of tasks. The AI will analyze photos, specifically looking for key pre-determined completed tasks related to specific tasks. For instance, when floor joists are being installed, the scan should detect the rim board and joists attached with the correct nailing pattern to indicate that the task is complete for that section of the work. This approach will enable builders to take on larger workloads while simultaneously delivering high-quality builds at a lower cost. The intended savings will be passed on to home buyers, allowing them to spend more money in the community and fostering a thriving economy for the next hundred years. Once this goal is achievable, we can implement the technology.
<!-- Provide a longer summary of what this model is. -->

{{ model_description | default("", true) }}

- **Developed by:** {{ Lucas Ferris | default("[Director of Revolutions Do Not Expire Building Co. Inc.]", true)}}
- **Funded by [optional]:** {{ Lucas Ferris | default("[Director of Revolutions Do Not Expire Building Co. Inc.]", true)}}
- **Shared by [optional]:** {{ shared_by | default("[More Information Needed]", true)}}
- **Model type:** {{ model_type | default("[More Information Needed]", true)}}
- **Language(s) (NLP):** {{ language | default("[More Information Needed]", true)}}
- **License:** {{ license | default("[More Information Needed]", true)}}
- **Finetuned from model [optional]:** {{ base_model | default("[More Information Needed]", true)}}

### Model Sources [Lucas Ferris's brain]

<!-- Provide the basic links for the model. -->

- **Repository:** {{ repo | default("[wouldnt you like to know?]", true)}}
- **Paper [optional]:** {{ paper | default("[More Information Needed]", true)}}
- **Demo [optional]:** {{ demo | default("[soon]", true)}}

## Uses

<!-- Address questions around how the model is intended to be used, including the foreseeable users of the model and those affected by the model. -->

### Direct Use

<!-- This section is for the model use without fine-tuning or plugging into a larger ecosystem/app. -->

{{ direct_use | default("[valid subscription holders]", true)}}

### Downstream Use [optional]

<!-- This section is for the model use when fine-tuned for a task, or when plugged into a larger ecosystem/app -->

{{ downstream_use | default("[The Builder's Assistant mobile app(ios,android, The Builder's assistant - Banking app/TBA_bank - app-(ios,android)]", true)}}

### Out-of-Scope Use

Aris was designed for 2 purposes to fund and assist in the solution to canada's housing crisis. any unpaid use is unethical and morally inconcievable with the expected use and intended use of all profits may you rot in hell anyone who wishes to spit in the face of morals and selfess actions.
<!-- This section addresses misuse, malicious use, and uses that the model will not work well for. -->

{{ out_of_scope_use | default("[unpaid-use-defined-in-the-subscription-document,
the copying of any portion of code used in this software/a.i. aris which was not owned prior to its creation, 
Unauthorized download in any form singular or plural,
any alteration of this code without written consent in front of a legal witness in written verifiable form.
any combination of this codes functions to produce a similar action
any function to produyce a similar or same calculation or calculations,
any process combinations not previously combined to prpoduce a fubnction,action, process or calculation are illegal. 
any automations not previously automated including processes,induistries, combinations, services,calculations,industry secrets,anything which may qualify as patentable-require written concent while we hold the right to decide all terms charge, deligate all terms, calculate all terms, conditions, and or time stipulances in contracted form.
]", true)}}

## Bias, Risks, and Limitations

<!-- This section is meant to convey both technical and sociotechnical limitations. -->

{{ bias_risks_limitations | default("[More Information Needed]", true)}}

### Recommendations

<!-- This section is meant to convey recommendations with respect to the bias, risk, and technical limitations. -->

{{ bias_recommendations | default("Users (both direct and downstream) should be made aware of the risks, biases and limitations of the model. More information needed for further recommendations.", true)}}

## How to Get Started with the Model

Use the code below to get started with the model.

{{ get_started_code | default("[More Information Needed]", true)}}

## Training Details

### Training Data

<!-- This should link to a Dataset Card, perhaps with a short stub of information on what the training data is all about as well as documentation related to data pre-processing or additional filtering. -->

{{ training_data | default("[More Information Needed]", true)}}

### Training Procedure

<!-- This relates heavily to the Technical Specifications. Content here should link to that section when it is relevant to the training procedure. -->

#### Preprocessing [optional]

{{ preprocessing | default("[More Information Needed]", true)}}


#### Training Hyperparameters

- **Training regime:** {{ training_regime | default("[More Information Needed]", true)}} <!--fp32, fp16 mixed precision, bf16 mixed precision, bf16 non-mixed precision, fp16 non-mixed precision, fp8 mixed precision -->

#### Speeds, Sizes, Times [optional]

<!-- This section provides information about throughput, start/end time, checkpoint size if relevant, etc. -->

{{ speeds_sizes_times | default("[More Information Needed]", true)}}

## Evaluation

<!-- This section describes the evaluation protocols and provides the results. -->

### Testing Data, Factors & Metrics

#### Testing Data

<!-- This should link to a Dataset Card if possible. -->

{{ testing_data | default("[More Information Needed]", true)}}

#### Factors

<!-- These are the things the evaluation is disaggregating by, e.g., subpopulations or domains. -->

{{ testing_factors | default("[More Information Needed]", true)}}

#### Metrics

<!-- These are the evaluation metrics being used, ideally with a description of why. -->

{{ testing_metrics | default("[More Information Needed]", true)}}

### Results

{{ results | default("[More Information Needed]", true)}}

#### Summary

{{ results_summary | default("", true) }}

## Model Examination [optional]

<!-- Relevant interpretability work for the model goes here -->

{{ model_examination | default("[More Information Needed]", true)}}

## Environmental Impact

<!-- Total emissions (in grams of CO2eq) and additional considerations, such as electricity usage, go here. Edit the suggested text below accordingly -->

Carbon emissions can be estimated using the [Machine Learning Impact calculator](https://mlco2.github.io/impact#compute) presented in [Lacoste et al. (2019)](https://arxiv.org/abs/1910.09700).

- **Hardware Type:** {{ hardware_type | default("[More Information Needed]", true)}}
- **Hours used:** {{ hours_used | default("[More Information Needed]", true)}}
- **Cloud Provider:** {{ cloud_provider | default("[More Information Needed]", true)}}
- **Compute Region:** {{ cloud_region | default("[More Information Needed]", true)}}
- **Carbon Emitted:** {{ co2_emitted | default("[More Information Needed]", true)}}

## Technical Specifications [optional]

### Model Architecture and Objective

{{ model_specs | default("[More Information Needed]", true)}}

### Compute Infrastructure

{{ compute_infrastructure | default("[More Information Needed]", true)}}

#### Hardware

{{ hardware_requirements | default("[More Information Needed]", true)}}

#### Software

{{ software | default("[More Information Needed]", true)}}

## Citation [optional]

<!-- If there is a paper or blog post introducing the model, the APA and Bibtex information for that should go in this section. -->

**BibTeX:**

{{ citation_bibtex | default("[More Information Needed]", true)}}

**APA:**

{{ citation_apa | default("[More Information Needed]", true)}}

## Glossary [optional]

<!-- If relevant, include terms and calculations in this section that can help readers understand the model or model card. -->

{{ glossary | default("[More Information Needed]", true)}}

## More Information [optional]

{{ more_information | default("[]", true)}}

## Model Card Authors [Lucas Gavin Conor Ferris]

{{ model_card_authors | default("[More Information Needed]", true)}}

## Model Card Contact

{{ model_card_contact | default("[Lucas Ferris:
thebuildersassistant@revolutionsdonootexpire.com ]", true)}}
