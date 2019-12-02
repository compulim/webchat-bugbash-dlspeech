# Bug bash for Direct Line Speech with Web Chat and C#/JavaScript bot

# Steps

## Create Azure Speech resource

1. Create a new Azure Speech resource, either by
  1. [Use this link](https://ms.portal.azure.com/#blade/Microsoft_Azure_Marketplace/MarketplaceOffersBlade/selectedMenuItemId/CognitiveServices_MP/dontDiscardJourney/true/launchingContext/%7B%22source%22%3A%22Resources%20Microsoft.CognitiveServices%2Faccounts%22%7D)
  1. On Portal
     1. Click "Create a resource"
     1. Click "AI + Machine Learning"
     1. Click "See all" (next to "Featured" on top)
     1. On "Cognitive Services" section, click "See More"
     1. Select "Speech"
1. In Quick Start, write down subscription key and endpoint

## Create a Web App bot

> You must [create Azure Speech resource](#create-azure-speech-resource) first.

1. Create a new Web App Bot
1. Select C# Echo Bot for bot template
1. Click "Test in Web Chat", make sure it is working
1. Go to Channels settings
   1. Adds a new "Direct Line Speech" channel
   1. Cognitive service account, select your Azure Speech resource
