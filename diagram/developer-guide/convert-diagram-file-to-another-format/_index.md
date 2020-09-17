---
title: "Convert Diagram File To Another Format"
type: docs
url: /convert-diagram-file-to-another-format/
weight: 30
---

# **Introduction**
With [POST /diagram/{name}/SaveAs](https://apireference.aspose.cloud/diagram/#!/DiagramFile/DiagramFile_PutUpload) API you can convert diagram file to another format.
## **Resource URI**
[Aspose.Diagram Cloud APIs Swagger UI](https://apireference.aspose.cloud/diagram/) lets you call this REST API directly from the browser. The description of the API and its parameters are also given there. 
## **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

// First get Access Token
// Get App Key and App SID from https://dashboard.aspose.cloud/

curl -v "https://api.aspose.cloud/oauth2/token" \
-X POST \
-d 'grant\_type=client\_credentials&client\_id=0B17F60A-6D69-426B-9ABD-79F35A6E9F7B&client\_secret=53b8b19adffa41a3e87dbbd8858977ae' \
-H "Content-Type: application/x-www-form-urlencoded" \
-H "Accept: application/json"



// cURL example to convert Diagram file to another format

curl -v "https://api.aspose.cloud/v1.1/diagram/file\_get\_1.vdx/SaveAs?IsOverwrite=true&newfilename=file\_get\_1.pdf" \
-X POST \
-d '{"Format":"pdf"}' \
-H "Content-Type: application/json" \
-H "Accept: application/json" \
-H "Authorization: Bearer Ddc-erbNb\_b1GGm-s0T\_vATc72hQdgCPlmsWQJzSiuLWiYYLa1aIZQC2p64xDV5rjdVCYaR-4PIy\_Djgvc2mqlN6uu13O90fvu66TKKAPWLJi-50D0WxpZr1l-7en2VkkDUnMgkMphdmGGN3IWRgc22XxMXab72oh0njvfDVoAskGjbFDrl3jxDBYnGDbfqGF5\_YHnliYJ2gq40uc2\_rVgoDNJoGz6PMs2bNDm2zuUXTD7Hy07qxE5nWxNkaYNMY3RxuDXvLrQommIB9Nboyt8v40G5yJ0nDCFUKgsmM6BhEGe9afDFLd3vQQTRqfWYlWSsi8kfhKW5pCqNqaHe\_NJkzkmhYdqFxrUJhaJrp5xEGUAh2eH8V3G\_sTaP0DxhMRQB7VSCIqyHsUgqPBVrHH5pujM-nEaPCPQK9gsiblvkPjXka"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "SaveResult": {

    "SourceDocument": {

      "Href": "file\_get\_1.vdx",

      "Rel": null,

      "Title": null,

      "Type": null

    },

    "DestDocument": {

      "Href": "file\_get\_1.pdf",

      "Rel": null,

      "Title": null,

      "Type": null

    },

    "AdditionalItems": null

  },

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
Using an SDK (API client) is the quickest way for a developer to speed up the development. An SDK takes care of a lot of low-level details of making requests and handling responses and lets you focus on writing code specific to your particular project. Checkout our [GitHub repository](https://github.com/aspose-diagram-cloud) for a complete list of Aspose.Diagram Cloud SDKs along with working examples, to get you started in no time. Please check [Available SDKs](/available-sdks/) article to learn how to add an SDK to your project.
## **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="Java" tabName3="Node.js" tabName4="Python" tabName5="PHP" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "7dc5932f6637bce774d0b90a9cb10365" "PostSaveAs.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "f4514c834e8a9e661e8a8beab0b0dc39" "SaveFileAsAnotherFormat.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}



{{< gist "" "f4514c834e8a9e661e8a8beab0b0dc39" "save\_file\_as\_another\_format.js" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "f4514c834e8a9e661e8a8beab0b0dc39" "SaveFileAsAnotherFormat.py" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "f4514c834e8a9e661e8a8beab0b0dc39" "SaveFileAsAnotherFormat.php" >}}

{{< /tab >}}

{{< /tabs >}}



