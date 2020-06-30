# About

The One Year of Actigraphy (OYA) project is exploring new methods of sleep/circadian data analysis. The main target is to search for predictive algorithms from consecutive wrist actigraphy recordings of a free-living single subject using a [MotionWatch8 (CamNtech Ltd)](https://www.camntech.com/products/motionwatch/motionwatch-8-overview) system on the non-dominant wrist for an entire year. The single subject was a 62 year-old male who wore the device between June 2016 and June 2017.

For more information, visit the [data creator's actigraphy project website](http://www.actigraphy.eu/actigraphy-analysis-project.html) and [read his IARIA conference presentation](http://www.thinkmind.org/index.php?view=article&articleid=sensordevices_2018_10_40_28007). In August 2019, the data creator released a [follow-up article about the project](http://www.thinkmind.org/index.php?view=article&articleid=lifsci_v11_n12_2019_8).

## Citation and acknowledgement

When using this dataset, please cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)
>
> [Actigraphy Analysis Project: Predictive algorithms of individual wrist actigraphy for real life. (http://www.actigraphy.eu/actigraphy-analysis-project.html)](http://www.actigraphy.eu/actigraphy-analysis-project.html)

Please include the following text in the Acknowledgements:

> The National Sleep Research Resource was supported by the National Heart, Lung, and Blood Institute (R24 HL114473, 75N92019R002).

## Notes about the data

- Each data record represents 1 second of data. Each record has an associated date, time, activity count, and light exposure level.
- Original data are in .MTN format (https://camntech.com).
- Marker has been used to signal when the unit was not at the wrist.
- Since Marker signal is not exported at one second epoch, time intervals around markers have been deleted as "not available". Then data has been exported as .CSV in a spreadsheet (OpenOffice Calc) and "not available" has been changed in "-1".
- It is not possible to check the position of the recorder and therefore the ligh information is difficult to evaluate.
- The light data uses different formats, depending on the intensity of the light ([see MW8 user manual](https://www.camntech.com/images/products/MotionWatch/The%20MotionWatch%20User%20Guide.pdf)). In order to simplify data management, Lux decimals are in a separate column.
- Original .MTN data are available on request.

## Recent Changes

- Find a complete list of changes in the [CHANGELOG.md](:pages_path:/CHANGELOG.md)
