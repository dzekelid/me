{
  "info": {
    "name": "Kaltura VPaaS Get Service Batch Action Addmediainfo",
    "_postman_id": "29a11d09-cf27-4991-8b14-3aab4d9347f0",
    "description": "batch addMediaInfoAction action saves a media info object",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "dcc16b89-c98e-48ad-b775-facb0a637f3f",
          "name": "batch.addBulkUploadResult",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/addBulkUploadResult?bulkUploadResult[accessControlProfileId]=%7B%7D&bulkUploadResult[action]=%7B%7D&bulkUploadResult[appearInList]=%7B%7D&bulkUploadResult[bulkUploadJobId]=%7B%7D&bulkUploadResult[bulkUploadResultObjectType]=%7B%7D&bulkUploadResult[categoryId]=%7B%7D&bulkUploadResult[categoryReferenceId]=%7B%7D&bulkUploadResult[category]=%7B%7D&bulkUploadResult[city]=%7B%7D&bulkUploadResult[contentType]=%7B%7D&bulkUploadResult[contributionPolicy]=%7B%7D&bulkUploadResult[conversionProfileId]=%7B%7D&bulkUploadResult[country]=%7B%7D&bulkUploadResult[creatorId]=%7B%7D&bulkUploadResult[dateOfBirth]=%7B%7D&bulkUploadResult[defaultPermissionLevel]=%7B%7D&bulkUploadResult[description]=%7B%7D&bulkUploadResult[email]=%7B%7D&bulkUploadResult[entitledUsersEdit]=%7B%7D&bulkUploadResult[entitledUsersPublish]=%7B%7D&bulkUploadResult[entryId]=%7B%7D&bulkUploadResult[entryStatus]=%7B%7D&bulkUploadResult[errorCode]=%7B%7D&bulkUploadResult[errorDescription]=%7B%7D&bulkUploadResult[errorType]=%7B%7D&bulkUploadResult[firstName]=%7B%7D&bulkUploadResult[gender]=%7B%7D&bulkUploadResult[group]=%7B%7D&bulkUploadResult[inheritanceType]=%7B%7D&bulkUploadResult[lastName]=%7B%7D&bulkUploadResult[lineIndex]=%7B%7D&bulkUploadResult[moderation]=%7B%7D&bulkUploadResult[name]=%7B%7D&bulkUploadResult[objectErrorDescription]=%7B%7D&bulkUploadResult[objectId]=%7B%7D&bulkUploadResult[objectStatus]=%7B%7D&bulkUploadResult[objectType]=%7B%7D&bulkUploadResult[ownerId]=%7B%7D&bulkUploadResult[owner]=%7B%7D&bulkUploadResult[parentSystemName]=%7B%7D&bulkUploadResult[parentType]=%7B%7D&bulkUploadResult[partnerData]=%7B%7D&bulkUploadResult[partnerId]=%7B%7D&bulkUploadResult[partnerSortValue]=%7B%7D&bulkUploadResult[permissionLevel]=%7B%7D&bulkUploadResult[pluginsData]=%7B%7D&bulkUploadResult[privacy]=%7B%7D&bulkUploadResult[referenceId]=%7B%7D&bulkUploadResult[relativePath]=%7B%7D&bulkUploadResult[requiredObjectStatus]=%7B%7D&bulkUploadResult[resourceId]=%7B%7D&bulkUploadResult[rowData]=%7B%7D&bulkUploadResult[scheduleEndDate]=%7B%7D&bulkUploadResult[scheduleStartDate]=%7B%7D&bulkUploadResult[screenName]=%7B%7D&bulkUploadResult[sshKeyPassphrase]=%7B%7D&bulkUploadResult[sshPrivateKey]=%7B%7D&bulkUploadResult[sshPublicKey]=%7B%7D&bulkUploadResult[state]=%7B%7D&bulkUploadResult[status]=%7B%7D&bulkUploadResult[systemName]=%7B%7D&bulkUploadResult[tags]=%7B%7D&bulkUploadResult[templateEntryId]=%7B%7D&bulkUploadResult[thumbnailSaved]=%7B%7D&bulkUploadResult[thumbnailUrl]=%7B%7D&bulkUploadResult[title]=%7B%7D&bulkUploadResult[type]=%7B%7D&bulkUploadResult[updateMethod]=%7B%7D&bulkUploadResult[url]=%7B%7D&bulkUploadResult[userId]=%7B%7D&bulkUploadResult[userJoinPolicy]=%7B%7D&bulkUploadResult[zip]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch addBulkUploadResultAction action adds KalturaBulkUploadResult to the DB"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04827821-a900-485b-b821-2e7755fe73b6"
            }
          ]
        },
        {
          "id": "eb90c9b6-b253-4387-9ce7-e91358dc10e8",
          "name": "batch.addMediaInfo",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/addMediaInfo?mediaInfo[audioBitRateMode]=%7B%7D&mediaInfo[audioBitRate]=%7B%7D&mediaInfo[audioChannels]=%7B%7D&mediaInfo[audioCodecId]=%7B%7D&mediaInfo[audioDuration]=%7B%7D&mediaInfo[audioFormat]=%7B%7D&mediaInfo[audioResolution]=%7B%7D&mediaInfo[audioSamplingRate]=%7B%7D&mediaInfo[complexityValue]=%7B%7D&mediaInfo[containerBitRate]=%7B%7D&mediaInfo[containerDuration]=%7B%7D&mediaInfo[containerFormat]=%7B%7D&mediaInfo[containerId]=%7B%7D&mediaInfo[containerProfile]=%7B%7D&mediaInfo[contentStreams]=%7B%7D&mediaInfo[fileSize]=%7B%7D&mediaInfo[flavorAssetId]=%7B%7D&mediaInfo[isFastStart]=%7B%7D&mediaInfo[maxGOP]=%7B%7D&mediaInfo[multiStreamInfo]=%7B%7D&mediaInfo[multiStream]=%7B%7D&mediaInfo[rawData]=%7B%7D&mediaInfo[scanType]=%7B%7D&mediaInfo[videoBitRateMode]=%7B%7D&mediaInfo[videoBitRate]=%7B%7D&mediaInfo[videoCodecId]=%7B%7D&mediaInfo[videoDar]=%7B%7D&mediaInfo[videoDuration]=%7B%7D&mediaInfo[videoFormat]=%7B%7D&mediaInfo[videoFrameRate]=%7B%7D&mediaInfo[videoHeight]=%7B%7D&mediaInfo[videoRotation]=%7B%7D&mediaInfo[videoWidth]=%7B%7D&mediaInfo[writingLib]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch addMediaInfoAction action saves a media info object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e001219f-8406-4292-a1ee-e463bc871e77"
            }
          ]
        }
      ]
    }
  ]
}