# data
A repository that can be used to attach anonymized data for testing

## usage

The github releases feature for this repository is used to present binary datasets that can be easily downloaded for use in testing.

For example this command downloads a single series of an MR scan:
```
curl -L "https://github.com/dcmjs-org/data/releases/download/MRHead/MRHead.zip" > MRHead.zip
```

If you have comments or questions about the data, such as how the data is encoded or what the fields mean, please open an issue on this repository and reference the particular dataset.

## contributing

Make abolutely sure you can share the data according to any applicable regulations (e.g. policies of your employer or government).  Also be sure you are comfortable sharing the data with the general pubic because it may get used for purposes over which you have no control.

To share:
* You need to join this repository, which means getting to know one of the dcmjs-org organization owners well enough that they trust you to contribute data legitimately
* Create a new release on this repository
* Attach the data (e.g. drag and drop a zip file)
* Provide an informative description
