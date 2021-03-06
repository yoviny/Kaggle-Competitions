<img src="https://raw.githubusercontent.com/yoviny/Deep-learning-Competitions/master/Bristol-Myers%20Squibb%20%E2%80%93%20Molecular%20Translation/thumbnail.jpg" width="128">

# Bristol-Myers Squibb – Molecular Translation (03/03/2021 - 04/06/2021)
**Translating chemical images to text format (InChI)**

**Competition leaderboard ranking - 123/874 (top 15%)**
**Final mean Levenshtein distance - 2.61**

Organic chemists frequently draw out molecular work with the Skeletal formula, a structural notation used for centuries. Recent publications are also annotated with machine-readable chemical descriptions (InChI), but there are decades of scanned documents that can't be automatically searched for specific chemical depictions. Automated recognition of optical chemical structures, with the help of machine learning, could speed up research and development efforts.

Unfortunately, most public data sets are too small to support modern machine learning models. Existing tools produce 90% accuracy but only under optimal conditions. Historical sources often have some level of image corruption, which reduces performance to near zero. In these cases, time-consuming, manual work is required to reliably convert scanned chemical structure images into a machine-readable format.

In this competition, participants are asked to interpret old chemical images. With access to a large set of synthetic image data generated by Bristol-Myers Squibb, the images will be converted back to the underlying chemical structure annotated as InChI text.
[source:https://www.kaggle.com/c/bms-molecular-translation/overview/descriptionn]

# Evaluation metric
Submissions are evaluated on the mean Levenshtein distance between the InChi strings you submit and the ground truth InChi values.
