npm version patch
npm publish
npm run dev

# get-npm-packages

Get NPM Packages is a lightweight & easy to use Javascript library designed for easy retrieval of all packages from an account on the npmjs website. It simplifies access to an accounts package information, enabling developers to integrate the data in their applications like portfolios, etc.

## Installation

```bash
npm i get-npm-packages
```

## Simple Usage

```javascript
const data = await getPackages("garvsl"); // Desired username

console.log(data);
```

## Sample output

```json
{
  "total": 3,
  "username": "garvsl",
  "packages": [
    {
      "id": 6878961,
      "title": "get-hackathons",
      "description": "Easy retrieval of Hackathon data from the Devpost website",
      "version": "2.0.0",
      "updated": "2 hours ago",
      "downloads": 0,
      "link": "https://www.npmjs.com/package/get-hackathons"
    },
    {
      "id": 6821262,
      "title": "snap-locator",
      "description": "Snap Locator is a lightweight JavaScript library designed for easy retrieval of location data from the Snap Locator website. It simplifies access to store information, enabling developers to integrate location-based services into their applications effort",
      "version": "1.0.1",
      "updated": "a month ago",
      "downloads": 132,
      "link": "https://www.npmjs.com/package/snap-locator"
    },
    {
      "id": 6597803,
      "title": "screencapturekit-node-wrapper",
      "description": "Added some ease of use capabilities and made into package for simple integration. No Audio recording",
      "version": "1.0.8",
      "updated": "6 days ago",
      "downloads": 660,
      "link": "https://www.npmjs.com/package/screencapturekit-node-wrapper"
    }
  ]
}
```
