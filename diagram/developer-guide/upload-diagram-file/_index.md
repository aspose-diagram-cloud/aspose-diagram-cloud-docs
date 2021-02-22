---
title: "Upload Diagram File"
type: docs
url: /upload-diagram-file/
weight: 40
---

## **Introduction**
With [PUT /diagram/{name}/upload](https://apireference.aspose.cloud/diagram/#!/DiagramFile/DiagramFile_PutUpload) API you can upload diagram file to Aspose Cloud Storage.
### **Resource URI**
[Aspose.Diagram Cloud APIs Swagger UI](https://apireference.aspose.cloud/diagram/) lets you call this REST API directly from the browser. The description of the API and its parameters are also given there. 
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

// First get Access Token
// Get Client Secret and Client Id from https://dashboard.aspose.cloud/

curl -v "https://api.aspose.cloud/oauth2/token" \
-X POST \
-d 'grant_type=client_credentials&client_id=0B17F60A-6D69-426B-9ABD-79F35A6E9F7B&client_secret=53b8b19adffa41a3e87dbbd8858977ae' \
-H "Content-Type: application/x-www-form-urlencoded" \
-H "Accept: application/json"



// cURL example to upload Diagram file

curl -v "https://api.aspose.cloud/v1.1/diagram/file_get_1.vdx/upload?IsOverwrite=true" \
-X PUT \
-H "Content-Type: application/json" \
-H "Accept: application/json" \
-H "Content-Length: 0" \
-H "Authorization: Bearer MkXEvgOqmZKDaDR2hz3cGEKg8xT7llGJrWqnmFvzu8zM6XzgZ3mFsko--AmqZfQPIIjkEL4G8ONGqcEMHjsgqf7QK6IqjQyHzkDtZ_osOvOQvjolhibZ0dy238Tq_C4PgOQgL82N2l0bz4RksV56oByU8mdb0l_mI-yhNeQqLuZHxjF7Dmqdkigitkb4Lo2CtN5ANnnTYB9ueS2GVwuqwsEm04qk8eGvYvg1DqYYThGki0vKKpHBQh3q7mliSSRKs5W8opSqWdJ76RExKDyJjrOMLub431t4BzdOhSA8E52-_OJM7fND5hOr2kxXpvwl9AMADRR7CxLtX89UqrNwqhcw1FHuEEZtRdln5k1r-t9dWTdKxJeMpUEGaLnvTNBKtt4s6IAevbdtdkKYMSsSOhZhww9Cfvc6RSEk6ipBLMrE4Tdo"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {"Code":200,"Status":"OK"

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
Using an SDK (API client) is the quickest way for a developer to speed up the development. An SDK takes care of a lot of low-level details of making requests and handling responses and lets you focus on writing code specific to your particular project. Checkout our [GitHub repository](https://github.com/aspose-diagram-cloud) for a complete list of Aspose.Diagram Cloud SDKs along with working examples, to get you started in no time. Please check [Available SDKs](/diagram/available-sdks/) article to learn how to add an SDK to your project.
### **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="Java" tabName3="Node.js" tabName4="Python" tabName5="PHP" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "7dc5932f6637bce774d0b90a9cb10365" "PutUpload.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "f4514c834e8a9e661e8a8beab0b0dc39" "UploadFile.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}



{{< gist "" "f4514c834e8a9e661e8a8beab0b0dc39" "upload_file.js" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "f4514c834e8a9e661e8a8beab0b0dc39" "UploadFile.py" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "f4514c834e8a9e661e8a8beab0b0dc39" "UploadFile.php" >}}

{{< /tab >}}

{{< /tabs >}}



