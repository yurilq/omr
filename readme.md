# Aspose.OMR for Cloud

[Aspose.OMR for Cloud](https://products.aspose.cloud/omr/) is a REST API that helps you to perform optical mark recognition in the cloud. We provide a series of [SDKs](https://github.com/aspose-omr-cloud). Along with that, you can get [binaries](https://github.com/aspose-omr-cloud/aspose-omr-cloud-dotnet/releases) to start working immediately and recognize various OMR forms.

Developers can embed [optical recognition](https://en.wikipedia.org/wiki/Optical_mark_recognition) in any type of application to extract data from images of tests, exams, questionnaires, surveys, etc. In the repository you can find examples on how to start using [Aspose.OMR API](https://docs.aspose.cloud/display/omrcloud/OMR+API+Specification) in your project.

## Quickstart

You can perform tasks out of the box without writing a single line of code with our [GUI client](https://github.com/aspose-omr-cloud/aspose-omr-cloud-dotnet/releases). You can also refer to the [client documentation](https://docs.aspose.cloud/display/omrcloud/Aspose.OMR.Client+Application).

## Using OMR Cloud API in your Python projects

This Python package is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:

- API version: 1.1
- Package version: 18.8.0
- Build package: io.swagger.codegen.languages.PythonClientCodegen

### Requirements.

Python 2.7+

## Installation



### Clone repository

Clone `aspose-omr-cloud` **with submodules**:
```sh
git clone https://github.com/aspose-omr-cloud/aspose-omr-cloud-python.git --recurse-submodules
```



### pip install

If the python package is hosted on Github, you can install directly from Github

```sh
pip install git+https://github.com/aspose-omr-cloud/aspose-omr-cloud-python.git
```
(you may need to run `pip` with root permission: `sudo pip install git+https://github.com/aspose-omr-cloud/aspose-omr-cloud-python.git`)

Then import the package:
```python
import aspose-omr-cloud 
```

### Setuptools

Install via [Setuptools](http://pypi.python.org/pypi/setuptools).

```sh
python setup.py install --user
```
(or `sudo python setup.py install` to install the package for all users)

Then import the package:
```python
import aspose-omr-cloud
```
## Optional requirements

To take full advantage of Aspose.OMR for Cloud, _asposestoragecloud_ is required. Just run &#x60;pip install asposestoragecloud&#x60;. You may refer to official [Aspose Storage SDK](https://github.com/aspose-storage-cloud/aspose-storage-cloud-python) to get more information.

## Usage

### Receive Cloud Keys
Aspose.Cloud credentials are required to use Aspose.OMR for Cloud API. You can acquire App SID and App Key by registrating at [Aspose Cloud Dashboard](https://dashboard.aspose.cloud). It will take only a couple of minutes.


### Update submodule 
Make sure you've cloned [aspose-omr-cloud-demo-data](https://github.com/aspose-omr-cloud/aspose-omr-cloud-demo-data) submodule, that contains all data required to run demo.
In case you are missing submodules use the following git commands to initialize and update them:
```sh
git submodule init
git submodule update --remote --merge
```


### Code example
You can check out [OMR Demo](demo) project to get started with Aspose.OMR for Cloud.

## Documentation for API Endpoints

All URIs are relative to *https://api.aspose.cloud/v1.1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*OmrApi* | [**post_run_omr_task**](docs/OmrApi.md#post_run_omr_task) | **POST** /omr/{name}/runOmrTask | Run specific OMR task


## Documentation For Models

 - [AsposeResponse](docs/AsposeResponse.md)
 - [FileInfo](docs/FileInfo.md)
 - [OMRFunctionParam](docs/OMRFunctionParam.md)
 - [OMRResponseDetails](docs/OMRResponseDetails.md)
 - [OmrResponseContent](docs/OmrResponseContent.md)
 - [OmrResponseInfo](docs/OmrResponseInfo.md)
 - [Payload](docs/Payload.md)
 - [RecognitionStatistics](docs/RecognitionStatistics.md)
 - [ServerStat](docs/ServerStat.md)
 - [OMRResponse](docs/OMRResponse.md)


## Authentication

Library uses OAUTH2 internally

## Author

Aspose Pty Ltd (https://www.aspose.com)



