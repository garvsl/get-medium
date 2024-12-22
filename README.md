# get-npm-packages

Get Medium is a lightweight & easy to use Javascript library designed for easy retrieval of all articles from an account on the Medium website. It simplifies access to an accounts article information, enabling developers to integrate the data in their applications like portfolios, etc.

## Installation

```bash
npm i get-medium
```

## Simple Usage

```javascript
const data = await getMedium("garvsl"); // Desired username

console.log(data);
```

## Sample output

```json
[
  {
    "id": "2322ff8e0ec7",
    "title": "I met with the FBI 3 days into launching my startup",
    "previewImage": {
      "id": "1*vJfnx244qLxXUe-vsQUJHw.png",
      "__typename": "ImageMetadata",
      "focusPercentX": null,
      "focusPercentY": null,
      "alt": null
    },
    "extendedPreviewContent": {
      "subtitle": "When we launched our startup, I never imagined my first “investor meeting” would involve the FBI. There I was, in a crowded coffee shop…",
      "__typename": "PreviewContent",
      "isFullContent": false
    },
    "__typename": "Post",
    "creator": {
      "id": "21a8b02c0df4",
      "name": "Garv",
      "__typename": "User",
      "viewerEdge": [Object],
      "bio": "",
      "imageId": "0*h9bI7s7B1FyvwK3q",
      "membership": [Object],
      "username": "garvsl",
      "customDomainState": [Object],
      "hasSubdomain": false,
      "verifications": [Object]
    },
    "isPublished": true,
    "mediumUrl": "https://blog.garvsl.com/i-met-with-the-fbi-3-days-into-launching-my-startup-2322ff8e0ec7",
    "collection": null,
    "isLimitedState": false,
    "allowResponses": true,
    "postResponses": { "count": 3, "__typename": "PostResponses" },
    "visibility": "PUBLIC",
    "clapCount": 102,
    "isLocked": false,
    "firstPublishedAt": 1733520029162,
    "latestPublishedAt": 1733520029162,
    "pinnedAt": 0,
    "readingTime": 5.1946540880503145,
    "sequence": null,
    "isSeries": false,
    "uniqueSlug": "i-met-with-the-fbi-3-days-into-launching-my-startup-2322ff8e0ec7",
    "pinnedByCreatorAt": 0
  }
]
```
