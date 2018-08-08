# About

The One Year of Actigraphy (OYA) project is exploring new methods of sleep/circadian data analysis. The main target is to search for predictive algorithms from consecutive wrist actigraphy recordings of a free-living single subject using a MotionWatch8 (CamNtech Ltd) system on the non-dominant wrist that span a full year.

For more information, visit the [dataset creator's actigraphy project website](http://www.medricerca.it/actigraphy-analysis-project.html).

## Notes about the data

- Original data are in .MTN format (https://camntech.com).
- Marker has been used to signal when the unit was not at the wrist.
- Since Marker signal is not exported at one second epoch, time intervals around markers have been deleted as "not available". Then data has been exported as .CSV in a spreadsheet (OpenOffice Calc) and "not available" has been changed in "-1".
- It is not possible to check the position of the recorder and therefore the ligh information is difficult to evaluate.
- The light data uses different formats, depending on the intensity of the light (see MW8 user manual). In order to simplify data management, Lux decimals are in a separate column.
- Original .MTN data are available on request.

## Recent Changes

- Find a complete list of changes in the [CHANGELOG.md](:pages_path:/CHANGELOG.md)

## Citation

When citing this dataset please use:

1. Dean DA 2nd, Goldberger AL, Mueller R, Kim M, Rueschman M, Mobley D, Sahoo SS, Jayapandian CP, Cui L, Morrical MG, Surovec S, Zhang GQ, Redline S. [**Scaling Up Scientific Discovery in Sleep Medicine: The National Sleep Research Resource.**](https://www.ncbi.nlm.nih.gov/pubmed/27070134) Sleep. 2016 May 1;39(5):1151-64. doi: 10.5665/sleep.5774. Review. PubMed PMID: 27070134; PubMed Central PMCID: PMC4835314.
2. Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. [**The National Sleep Research Resource: towards a sleep data commons.**](https://www.ncbi.nlm.nih.gov/pubmed/29860441) J Am Med Inform Assoc. 2018 May 31. doi: 10.1093/jamia/ocy064. [Epub ahead of print] PubMed PMID: 29860441.
