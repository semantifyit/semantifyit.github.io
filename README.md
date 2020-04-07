# What is semantify.it
Semantify.it is a Software-as-a-service (SAAS) toolbox for working with semantic annotation related tasks.

# Features of semantify.it
The platform's comprehensive tool collection can be distinguished in three major categories: **annotations**, **Domain Specification** and **vocabularies**. The following sections will explain those categories and the tools in more detail.

## Annotation
The annotation module originally was the core of semantify.it and is still the most well known feature of the tool box. Besides that, it is also the first thing that pops the user's eye when visiting the platform.

### Creation
Annotation creation, also known as the creation of semantic content or semantic data, sometimes even called [LinkedData](https://en.wikipedia.org/wiki/Linked_data), is the process of adding semantic information to data. In other words the data is described with a vocabulary (an ontology). Originally semantify.it was soly based on schema.org. Meanwhile semantify.it also hosts custom vocabularies (see section [Vocabulary](#vocabulary)).

The different tools to create annotations are described below.

#### manual
##### annotation editor
##### instant Annotations
##### upload (single/bulk)
#### mapping
##### RocketRML
#### semi-automatic
##### classification and NER end-points
##### WordPress plugin
#### semantify.it actions
specific type of annotation creation)

### Hosting
#### MongoDB
#### Knowledge Graph
##### semantify.it graph
##### broker graph (through crawling of websites)

### Evaluation
#### verification (against DS)
#### validation (heuristics-based against Website)

### Deployment
#### API
#### WordPress plugin
#### Typo3 plugin
#### semantify.it pages (mini websites, based solely on annotations)
#### semantify.it actions

## Domain Specification

### Creation
#### DS editor
##### from scratch
##### replicate (and change) exiting DS
##### combine existing DS (and extend)

### Hosting
#### DS lists, hosted inside platform

### Deployment
#### References
##### ds.sti2.at
##### semantify.it/domainSpecifications/public
###### table view
###### tree view
###### graphical view
##### soon: everyone can host a own view of own list (JS snippet for visualization, 4 visualization options)
#### Annotation creation (see Annotation -> creation)
#### Evaluation
##### evaluation of annotations against DS
###### currently: against “the public DS list”
###### soon: against custom lists
##### soon: evaluation of Knowledge Graphs

## Vocabulary

### Creating
#### manually (and upload/link)
#### xlsx to RDF tool (and upload/link)
#### soon: editor & xlsx tool integrated into platform

### Hosting
#### Vocabulary lists, hosted inside platform

### Validation
#### on upload
#### on demand
against the semantify.it vocabulary creation guidelines (aligned with state-of-the-art ontology engineering)

### Deployment
#### creation of DS
#### evaluation of annotations
#### soon: reference
visualization module like for DS: different “styles” (schema.org like, tree, table, …)

## More
things that don’t fit the Annotation/DS/Vocab structure):

### Knowledge Graphs:
#### duplication detection for KG
#### verification for KG
#### assessment for KG

# Related Literature
## semantify.it
Kärle, E., Şimşek, U., & Fensel, D. (2017). semantify. it, a Platform for Creation, Publication and Distribution of Semantic Annotations. arXiv preprint arXiv:1706.10067.  
Web: https://www.arxiv-vanity.com/papers/1706.10067/ ([download PDF](https://arxiv.org/pdf/1706.10067))


## Domain Specifications
Şimşek, U., Kärle, E., Holzknecht, O., & Fensel, D. (2017, June). Domain specific semantic validation of schema. org annotations. In International Andrei Ershov Memorial Conference on Perspectives of System Informatics (pp. 417-429). Springer, Cham.  
Web: https://www.arxiv-vanity.com/papers/1706.06384 ([download PDF](https://arxiv.org/pdf/1706.06384))

## RocketRML
Simsek, U., Kärle, E., & Fensel, D. (2019). RocketRML-A NodeJS implementation of a use-case specific RML mapper. arXiv preprint arXiv:1903.04969.  
Web: https://www.arxiv-vanity.com/papers/1903.04969/ ([download PDF](https://arxiv.org/pdf/1903.04969))

## semantify.it actions
Şimşek, U., Kärle, E., & Fensel, D. (2018). Machine readable web apis with schema. org action annotations. Procedia Computer Science, 137, 255-261.  
Web: https://www.arxiv-vanity.com/papers/1805.05479/ ([download PDF](https://arxiv.org/pdf/1805.05479))

A project by ![STIInnsbruck](_media/sti-logo.png)

<p style="text-align: center;">Made with <img src="_media/heart.png" width="24"> in Tirol!</p>
