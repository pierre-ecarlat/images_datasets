# images_datasets

This API will provide an easy way to download images datasets, to convert them into different supported formats (tfRecords, VOC, ...) and should also be flexible to classification, detection, and semantic segmentation datasets.
This is still work in progress, the stable, low-level, and not very flexible current version can be found in the [version 1](https://github.com/pierre-ecarlat/datasets.git) (only for detection so far).

Intended works on the next week:
- [ ] Build the architecture of the API (factories for datasets types, for datasets format)
- [ ] Define the default format (base for all the conversions)
- [ ] Refactor the download scripts from v1
- [ ] Refactor the conversion scripts from v1, from the default format, to any other format
- [ ] Extract the main difference (annotation reader, directory architectures, etc) and implement them in separate helpers / objects
- [ ] Full support of Pascal VOC (detection)
- [ ] Study how to add multiple versions of Pascal VOC (VOC2007 vs VOC20012, vs both, etc)
- [ ] Study how to add Pascal VOC for classification in a generic way, add it
- [ ] Study how to add Pascal VOC for semantic segmentation in a generic way, add it
- [ ] Full support for UECseries
- [ ] Refactor the scripts for OpenImages

Extensions then:
- [ ] GUI to deal with all the options
- [ ] Full support of the compute_characteristics script (with graphs)
- [ ] Ability to reduce a dataset
- [ ] Ability to sample a dataset
- [ ] Basic support for other state of the art images datasets
- [ ] Creation of dataset via Google Images



