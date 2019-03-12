S3 Functions
---

Config example:
````
"@voicenter/voicenter_pastash_command_aws": {
    "pluginFieldName": "FileFetch",
    "outputFileField": "destFilePath",
    "nameField": "fileName",
    "bucketField": "bucketName",
    "buckets": {
        "fetchBucket": {
            "accessKeyId": "KEY_ID",
            "secretAccessKey": "KEY"
        }
    }
}
````

Request example:
````
"FileFetch": {
    "destFilePath": "/tmp/",
    "fileName": "file.mp3",
    "bucketName": "fetchBucket"
}
````

Commands list:
````
s3Fetch();
s3Delete();
````