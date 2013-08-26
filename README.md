googlemaps-ts
==

This repository makes the Google Maps API TypeScript definitions from [DefinitelyTyped](https://github.com/borisyankov/DefinitelyTyped) available on [Bower](http://bower.io) as `googlemaps-ts`. If you want Google Maps API type definitions by you're not using Bower, get the type definitions from the DefinitelyTyped repository as they will always be at least as current as my copy and quite likely ahead.

This repository will be periodically refreshed from DefinitelyTyped as changes are made.

Getting the Google Maps API type definitions
--
Method 1:
`bower install googlemaps-ts`

Method 2:

Add `googlemaps-ts` to your bower.json `"dependencies"` list:

    {
      "name": "myApp",
      "version": "0.1.0",
      "dependencies": {
        "googlemaps-ts": "latest"
      }
    }

TypeScript and Google Maps API versions
--
I make no promises regarding the version of TypeScript and Google Maps API currently supported by these type definitions. However, I have noticed that, as of this writing, DefinitelyTyped is targeted to the latest stable versions of both TypeScript and Google Maps API. I have no plans to support multiple versions (although I may create tags as necessary) as this is just a copy of a subset of DefinitelyTyped.