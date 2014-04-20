# kudogen

> Helping co-workers recognize their noteworthiness

kudogen is an app that helps co-workers, particularly those spread across disparate locations, get together and recognize each other ...

their successes and suckcesses,
their brilliance and bone-headedness,
and their ah-sweet's and oh-shit's

Our team meets once a week to catch up. We intend to use kudogen to nominate each other for "awards". Some you're happy to be nominated for, others ... not so much.

## Implementation

Until we update this, we're still building it. The plan is to host a [ASP.NET Web API](http://www.asp.net/web-api) endpoint in [Azure](http://www.azure.microsoft.com/) and use [Angular](http://angularjs.org) and [Breeze](http://breezejs.com) for the frontend. More on this as it develops.

## Round 2

Initially we were going to use [Azure Mobile Services](http://azure.microsoft.com/en-us/services/mobile-services/) since there will likely be mobile apps to consume the API down the road, but reconsidered. It's still around in the [initial-approach](https://github.com/IntergenUSA/kudogen/tree/initial-approach) branch (the readme has more rationale), but we didn't get too far before changing our minds. Don't get us wrong, we like Azure Mobile Services and use it on other projects. We just decided not to use it on this one.

