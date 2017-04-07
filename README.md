# api documentation for  [twilio (v2.11.1)](https://github.com/twilio/twilio-node#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-twilio.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-twilio) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-twilio.svg)](https://travis-ci.org/npmdoc/node-npmdoc-twilio)
#### A Twilio helper library

[![NPM](https://nodei.co/npm/twilio.png?downloads=true)](https://www.npmjs.com/package/twilio)

[![apidoc](https://npmdoc.github.io/node-npmdoc-twilio/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-twilio_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-twilio/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-twilio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-twilio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kevin Whinnery",
        "email": "kevin.whinnery@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/twilio/twilio-node/issues"
    },
    "contributors": [
        {
            "name": "twilio-node contributors",
            "url": "https://github.com/twilio/twilio-node/graphs/contributors"
        }
    ],
    "dependencies": {
        "deprecate": "^0.1.0",
        "jsonwebtoken": "5.4.x",
        "q": "0.9.7",
        "request": "2.74.x",
        "scmp": "0.0.3",
        "string.prototype.startswith": "^0.2.0",
        "underscore": "1.x"
    },
    "description": "A Twilio helper library",
    "devDependencies": {
        "express": "3.x",
        "jasmine-node": "2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "451099467313c56b3767994df2d19062f10ef8c4",
        "tarball": "https://registry.npmjs.org/twilio/-/twilio-2.11.1.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "e69304af9959c36a9f562c9a87ab63294ab978bc",
    "homepage": "https://github.com/twilio/twilio-node#readme",
    "license": "MIT",
    "main": "./lib",
    "maintainers": [
        {
            "name": "dougblack",
            "email": "doug@dougblack.io"
        },
        {
            "name": "evanfossier",
            "email": "evan.fossier@gmail.com"
        },
        {
            "name": "jingming",
            "email": "niu@jingming.ca"
        },
        {
            "name": "kwhinnery",
            "email": "kevin.whinnery@gmail.com"
        },
        {
            "name": "praser05",
            "email": "praser05@gmail.com"
        },
        {
            "name": "twiliomatt",
            "email": "matt@twilio.com"
        }
    ],
    "name": "twilio",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/twilio/twilio-node.git"
    },
    "scripts": {
        "test": "jasmine-node --captureExceptions spec"
    },
    "version": "2.11.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module twilio](#apidoc.module.twilio)
1.  [function <span class="apidocSignatureSpan">twilio.</span>AccessToken (accountSid, keySid, secret, opts)](#apidoc.element.twilio.AccessToken)
1.  [function <span class="apidocSignatureSpan">twilio.</span>AccessToken.ConversationsGrant (options)](#apidoc.element.twilio.AccessToken.ConversationsGrant)
1.  [function <span class="apidocSignatureSpan">twilio.</span>AccessToken.IpMessagingGrant (options)](#apidoc.element.twilio.AccessToken.IpMessagingGrant)
1.  [function <span class="apidocSignatureSpan">twilio.</span>AccessToken.VideoGrant (options)](#apidoc.element.twilio.AccessToken.VideoGrant)
1.  [function <span class="apidocSignatureSpan">twilio.</span>AccessToken.VoiceGrant (options)](#apidoc.element.twilio.AccessToken.VoiceGrant)
1.  [function <span class="apidocSignatureSpan">twilio.</span>Capability (sid, tkn)](#apidoc.element.twilio.Capability)
1.  [function <span class="apidocSignatureSpan">twilio.</span>IpMessagingClient (sid, tkn, options)](#apidoc.element.twilio.IpMessagingClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>IpMessagingClient.super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.IpMessagingClient.super_)
1.  [function <span class="apidocSignatureSpan">twilio.</span>LookupsClient (sid, tkn, options)](#apidoc.element.twilio.LookupsClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>MonitorClient (sid, tkn, options)](#apidoc.element.twilio.MonitorClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>PricingClient (sid, tkn, options)](#apidoc.element.twilio.PricingClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>RestClient (sid, tkn, options)](#apidoc.element.twilio.RestClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TaskRouterCapability (accountSid, authToken, workspaceSid, channelId)](#apidoc.element.twilio.TaskRouterCapability)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TaskRouterClient (sid, tkn, workspaceSid, options)](#apidoc.element.twilio.TaskRouterClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TaskRouterTaskQueueCapability (accountSid, authToken, workspaceSid, taskQueueSid)](#apidoc.element.twilio.TaskRouterTaskQueueCapability)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TaskRouterWorkerCapability (accountSid, authToken, workspaceSid, workerSid)](#apidoc.element.twilio.TaskRouterWorkerCapability)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TaskRouterWorkspaceCapability (accountSid, authToken, workspaceSid)](#apidoc.element.twilio.TaskRouterWorkspaceCapability)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TrunkingClient (sid, tkn, options)](#apidoc.element.twilio.TrunkingClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TwimlResponse ()](#apidoc.element.twilio.TwimlResponse)
1.  [function <span class="apidocSignatureSpan">twilio.</span>validateExpressRequest (request, authToken, opts)](#apidoc.element.twilio.validateExpressRequest)
1.  [function <span class="apidocSignatureSpan">twilio.</span>validateRequest (authToken, twilioHeader, url, params)](#apidoc.element.twilio.validateRequest)
1.  [function <span class="apidocSignatureSpan">twilio.</span>webhook ()](#apidoc.element.twilio.webhook)
1.  object <span class="apidocSignatureSpan">twilio.</span>AccessToken.ConversationsGrant.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>AccessToken.IpMessagingGrant.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>AccessToken.VideoGrant.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>AccessToken.VoiceGrant.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>AccessToken.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>Capability.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>IpMessagingClient.super_.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>RestClient.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>TaskRouterCapability.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>TaskRouterTaskQueueCapability.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>TaskRouterWorkerCapability.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>TaskRouterWorkspaceCapability.prototype
1.  object <span class="apidocSignatureSpan">twilio.</span>utils
1.  object <span class="apidocSignatureSpan">twilio.</span>webhooks

#### [module twilio.AccessToken](#apidoc.module.twilio.AccessToken)
1.  [function <span class="apidocSignatureSpan">twilio.</span>AccessToken (accountSid, keySid, secret, opts)](#apidoc.element.twilio.AccessToken.AccessToken)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.</span>ConversationsGrant (options)](#apidoc.element.twilio.AccessToken.ConversationsGrant)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.</span>IpMessagingGrant (options)](#apidoc.element.twilio.AccessToken.IpMessagingGrant)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.</span>VideoGrant (options)](#apidoc.element.twilio.AccessToken.VideoGrant)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.</span>VoiceGrant (options)](#apidoc.element.twilio.AccessToken.VoiceGrant)
1.  object <span class="apidocSignatureSpan">twilio.AccessToken.</span>ALGORITHMS
1.  string <span class="apidocSignatureSpan">twilio.AccessToken.</span>DEFAULT_ALGORITHM

#### [module twilio.AccessToken.ConversationsGrant](#apidoc.module.twilio.AccessToken.ConversationsGrant)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.</span>ConversationsGrant (options)](#apidoc.element.twilio.AccessToken.ConversationsGrant.ConversationsGrant)

#### [module twilio.AccessToken.ConversationsGrant.prototype](#apidoc.module.twilio.AccessToken.ConversationsGrant.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.ConversationsGrant.prototype.</span>toPayload ()](#apidoc.element.twilio.AccessToken.ConversationsGrant.prototype.toPayload)
1.  string <span class="apidocSignatureSpan">twilio.AccessToken.ConversationsGrant.prototype.</span>key

#### [module twilio.AccessToken.IpMessagingGrant](#apidoc.module.twilio.AccessToken.IpMessagingGrant)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.</span>IpMessagingGrant (options)](#apidoc.element.twilio.AccessToken.IpMessagingGrant.IpMessagingGrant)

#### [module twilio.AccessToken.IpMessagingGrant.prototype](#apidoc.module.twilio.AccessToken.IpMessagingGrant.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.IpMessagingGrant.prototype.</span>toPayload ()](#apidoc.element.twilio.AccessToken.IpMessagingGrant.prototype.toPayload)
1.  string <span class="apidocSignatureSpan">twilio.AccessToken.IpMessagingGrant.prototype.</span>key

#### [module twilio.AccessToken.VideoGrant](#apidoc.module.twilio.AccessToken.VideoGrant)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.</span>VideoGrant (options)](#apidoc.element.twilio.AccessToken.VideoGrant.VideoGrant)

#### [module twilio.AccessToken.VideoGrant.prototype](#apidoc.module.twilio.AccessToken.VideoGrant.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.VideoGrant.prototype.</span>toPayload ()](#apidoc.element.twilio.AccessToken.VideoGrant.prototype.toPayload)
1.  string <span class="apidocSignatureSpan">twilio.AccessToken.VideoGrant.prototype.</span>key

#### [module twilio.AccessToken.VoiceGrant](#apidoc.module.twilio.AccessToken.VoiceGrant)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.</span>VoiceGrant (options)](#apidoc.element.twilio.AccessToken.VoiceGrant.VoiceGrant)

#### [module twilio.AccessToken.VoiceGrant.prototype](#apidoc.module.twilio.AccessToken.VoiceGrant.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.VoiceGrant.prototype.</span>toPayload ()](#apidoc.element.twilio.AccessToken.VoiceGrant.prototype.toPayload)
1.  string <span class="apidocSignatureSpan">twilio.AccessToken.VoiceGrant.prototype.</span>key

#### [module twilio.AccessToken.prototype](#apidoc.module.twilio.AccessToken.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.prototype.</span>addGrant (grant)](#apidoc.element.twilio.AccessToken.prototype.addGrant)
1.  [function <span class="apidocSignatureSpan">twilio.AccessToken.prototype.</span>toJwt (algorithm)](#apidoc.element.twilio.AccessToken.prototype.toJwt)

#### [module twilio.Capability](#apidoc.module.twilio.Capability)
1.  [function <span class="apidocSignatureSpan">twilio.</span>Capability (sid, tkn)](#apidoc.element.twilio.Capability.Capability)

#### [module twilio.Capability.prototype](#apidoc.module.twilio.Capability.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.Capability.prototype.</span>allowClientIncoming (clientName)](#apidoc.element.twilio.Capability.prototype.allowClientIncoming)
1.  [function <span class="apidocSignatureSpan">twilio.Capability.prototype.</span>allowClientOutgoing (appSid, params)](#apidoc.element.twilio.Capability.prototype.allowClientOutgoing)
1.  [function <span class="apidocSignatureSpan">twilio.Capability.prototype.</span>allowEventStream (filters)](#apidoc.element.twilio.Capability.prototype.allowEventStream)
1.  [function <span class="apidocSignatureSpan">twilio.Capability.prototype.</span>generate (timeout)](#apidoc.element.twilio.Capability.prototype.generate)

#### [module twilio.IpMessagingClient](#apidoc.module.twilio.IpMessagingClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>IpMessagingClient (sid, tkn, options)](#apidoc.element.twilio.IpMessagingClient.IpMessagingClient)
1.  [function <span class="apidocSignatureSpan">twilio.IpMessagingClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.IpMessagingClient.super_)

#### [module twilio.IpMessagingClient.super_](#apidoc.module.twilio.IpMessagingClient.super_)
1.  [function <span class="apidocSignatureSpan">twilio.IpMessagingClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.IpMessagingClient.super_.super_)

#### [module twilio.IpMessagingClient.super_.prototype](#apidoc.module.twilio.IpMessagingClient.super_.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.IpMessagingClient.super_.prototype.</span>getBaseUrl ()](#apidoc.element.twilio.IpMessagingClient.super_.prototype.getBaseUrl)
1.  [function <span class="apidocSignatureSpan">twilio.IpMessagingClient.super_.prototype.</span>request (options, callback)](#apidoc.element.twilio.IpMessagingClient.super_.prototype.request)

#### [module twilio.LookupsClient](#apidoc.module.twilio.LookupsClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>LookupsClient (sid, tkn, options)](#apidoc.element.twilio.LookupsClient.LookupsClient)
1.  [function <span class="apidocSignatureSpan">twilio.LookupsClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.LookupsClient.super_)

#### [module twilio.MonitorClient](#apidoc.module.twilio.MonitorClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>MonitorClient (sid, tkn, options)](#apidoc.element.twilio.MonitorClient.MonitorClient)
1.  [function <span class="apidocSignatureSpan">twilio.MonitorClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.MonitorClient.super_)

#### [module twilio.PricingClient](#apidoc.module.twilio.PricingClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>PricingClient (sid, tkn, options)](#apidoc.element.twilio.PricingClient.PricingClient)
1.  [function <span class="apidocSignatureSpan">twilio.PricingClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.PricingClient.super_)

#### [module twilio.RestClient](#apidoc.module.twilio.RestClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>RestClient (sid, tkn, options)](#apidoc.element.twilio.RestClient.RestClient)
1.  [function <span class="apidocSignatureSpan">twilio.RestClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.RestClient.super_)

#### [module twilio.RestClient.prototype](#apidoc.module.twilio.RestClient.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.RestClient.prototype.</span>request (options, callback)](#apidoc.element.twilio.RestClient.prototype.request)

#### [module twilio.TaskRouterCapability](#apidoc.module.twilio.TaskRouterCapability)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TaskRouterCapability (accountSid, authToken, workspaceSid, channelId)](#apidoc.element.twilio.TaskRouterCapability.TaskRouterCapability)

#### [module twilio.TaskRouterCapability.prototype](#apidoc.module.twilio.TaskRouterCapability.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>_generate (ttl, extraAttributes)](#apidoc.element.twilio.TaskRouterCapability.prototype._generate)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>_setupResource ()](#apidoc.element.twilio.TaskRouterCapability.prototype._setupResource)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>_validateJWT ()](#apidoc.element.twilio.TaskRouterCapability.prototype._validateJWT)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>addPolicy (url, method, allowed, queryFilter, postFilter)](#apidoc.element.twilio.TaskRouterCapability.prototype.addPolicy)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allow (url, method, queryFilter, postFilter)](#apidoc.element.twilio.TaskRouterCapability.prototype.allow)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowDelete ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowDelete)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowDeleteSubresources ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowDeleteSubresources)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowFetchSubresources ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowFetchSubresources)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowTaskReservationUpdates ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowTaskReservationUpdates)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowUpdates ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowUpdates)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowUpdatesSubresources ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowUpdatesSubresources)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowWorkerActivityUpdates ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowWorkerActivityUpdates)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowWorkerFetchAttributes ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowWorkerFetchAttributes)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>deny (url, method, queryFilter, postFilter)](#apidoc.element.twilio.TaskRouterCapability.prototype.deny)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>generate (ttl)](#apidoc.element.twilio.TaskRouterCapability.prototype.generate)

#### [module twilio.TaskRouterClient](#apidoc.module.twilio.TaskRouterClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TaskRouterClient (sid, tkn, workspaceSid, options)](#apidoc.element.twilio.TaskRouterClient.TaskRouterClient)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.TaskRouterClient.super_)

#### [module twilio.TaskRouterTaskQueueCapability](#apidoc.module.twilio.TaskRouterTaskQueueCapability)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TaskRouterTaskQueueCapability (accountSid, authToken, workspaceSid, taskQueueSid)](#apidoc.element.twilio.TaskRouterTaskQueueCapability.TaskRouterTaskQueueCapability)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterTaskQueueCapability.</span>super_ (accountSid, authToken, workspaceSid, channelId)](#apidoc.element.twilio.TaskRouterTaskQueueCapability.super_)

#### [module twilio.TaskRouterTaskQueueCapability.prototype](#apidoc.module.twilio.TaskRouterTaskQueueCapability.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterTaskQueueCapability.prototype.</span>_setupResource ()](#apidoc.element.twilio.TaskRouterTaskQueueCapability.prototype._setupResource)

#### [module twilio.TaskRouterWorkerCapability](#apidoc.module.twilio.TaskRouterWorkerCapability)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TaskRouterWorkerCapability (accountSid, authToken, workspaceSid, workerSid)](#apidoc.element.twilio.TaskRouterWorkerCapability.TaskRouterWorkerCapability)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterWorkerCapability.</span>super_ (accountSid, authToken, workspaceSid, channelId)](#apidoc.element.twilio.TaskRouterWorkerCapability.super_)

#### [module twilio.TaskRouterWorkerCapability.prototype](#apidoc.module.twilio.TaskRouterWorkerCapability.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterWorkerCapability.prototype.</span>_setupResource ()](#apidoc.element.twilio.TaskRouterWorkerCapability.prototype._setupResource)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterWorkerCapability.prototype.</span>allowActivityUpdates ()](#apidoc.element.twilio.TaskRouterWorkerCapability.prototype.allowActivityUpdates)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterWorkerCapability.prototype.</span>allowReservationUpdates ()](#apidoc.element.twilio.TaskRouterWorkerCapability.prototype.allowReservationUpdates)

#### [module twilio.TaskRouterWorkspaceCapability](#apidoc.module.twilio.TaskRouterWorkspaceCapability)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TaskRouterWorkspaceCapability (accountSid, authToken, workspaceSid)](#apidoc.element.twilio.TaskRouterWorkspaceCapability.TaskRouterWorkspaceCapability)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterWorkspaceCapability.</span>super_ (accountSid, authToken, workspaceSid, channelId)](#apidoc.element.twilio.TaskRouterWorkspaceCapability.super_)

#### [module twilio.TaskRouterWorkspaceCapability.prototype](#apidoc.module.twilio.TaskRouterWorkspaceCapability.prototype)
1.  [function <span class="apidocSignatureSpan">twilio.TaskRouterWorkspaceCapability.prototype.</span>_setupResource ()](#apidoc.element.twilio.TaskRouterWorkspaceCapability.prototype._setupResource)

#### [module twilio.TrunkingClient](#apidoc.module.twilio.TrunkingClient)
1.  [function <span class="apidocSignatureSpan">twilio.</span>TrunkingClient (sid, tkn, options)](#apidoc.element.twilio.TrunkingClient.TrunkingClient)
1.  [function <span class="apidocSignatureSpan">twilio.TrunkingClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.TrunkingClient.super_)

#### [module twilio.utils](#apidoc.module.twilio.utils)
1.  [function <span class="apidocSignatureSpan">twilio.utils.</span>initializeTokens (obj, type, sid, tkn)](#apidoc.element.twilio.utils.initializeTokens)

#### [module twilio.webhooks](#apidoc.module.twilio.webhooks)
1.  [function <span class="apidocSignatureSpan">twilio.webhooks.</span>validateExpressRequest (request, authToken, opts)](#apidoc.element.twilio.webhooks.validateExpressRequest)
1.  [function <span class="apidocSignatureSpan">twilio.webhooks.</span>validateRequest (authToken, twilioHeader, url, params)](#apidoc.element.twilio.webhooks.validateRequest)
1.  [function <span class="apidocSignatureSpan">twilio.webhooks.</span>webhook ()](#apidoc.element.twilio.webhooks.webhook)



# <a name="apidoc.module.twilio"></a>[module twilio](#apidoc.module.twilio)

#### <a name="apidoc.element.twilio.AccessToken"></a>[function <span class="apidocSignatureSpan">twilio.</span>AccessToken (accountSid, keySid, secret, opts)](#apidoc.element.twilio.AccessToken)
- description and source-code
```javascript
function AccessToken(accountSid, keySid, secret, opts) {
  if (!accountSid) { throw new Error('accountSid is required'); }
  if (!keySid) { throw new Error('keySid is required'); }
  if (!secret) { throw new Error('secret is required'); }
  opts = opts || {};

  this.accountSid = accountSid;
  this.keySid = keySid;
  this.secret = secret;
  this.ttl = opts.ttl || 3600;
  this.identity = opts.identity;
  this.nbf = opts.nbf;
  this.grants = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.AccessToken.ConversationsGrant"></a>[function <span class="apidocSignatureSpan">twilio.</span>AccessToken.ConversationsGrant (options)](#apidoc.element.twilio.AccessToken.ConversationsGrant)
- description and source-code
```javascript
function ConversationsGrant(options) {
  options = options || {};
  this.configurationProfileSid = options.configurationProfileSid;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.AccessToken.IpMessagingGrant"></a>[function <span class="apidocSignatureSpan">twilio.</span>AccessToken.IpMessagingGrant (options)](#apidoc.element.twilio.AccessToken.IpMessagingGrant)
- description and source-code
```javascript
function IpMessagingGrant(options) {
  options = options || {};
  this.serviceSid = options.serviceSid;
  this.endpointId = options.endpointId;
  this.deploymentRoleSid = options.deploymentRoleSid;
  this.pushCredentialSid = options.pushCredentialSid;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.AccessToken.VideoGrant"></a>[function <span class="apidocSignatureSpan">twilio.</span>AccessToken.VideoGrant (options)](#apidoc.element.twilio.AccessToken.VideoGrant)
- description and source-code
```javascript
function VideoGrant(options) {
  options = options || {};
  this.configurationProfileSid = options.configurationProfileSid;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.AccessToken.VoiceGrant"></a>[function <span class="apidocSignatureSpan">twilio.</span>AccessToken.VoiceGrant (options)](#apidoc.element.twilio.AccessToken.VoiceGrant)
- description and source-code
```javascript
function VoiceGrant(options) {
  options = options || {};
  this.outgoingApplicationSid = options.outgoingApplicationSid;
  this.outgoingApplicationParams = options.outgoingApplicationParams;
  this.pushCredentialSid = options.pushCredentialSid;
  this.endpointId = options.endpointId;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.Capability"></a>[function <span class="apidocSignatureSpan">twilio.</span>Capability (sid, tkn)](#apidoc.element.twilio.Capability)
- description and source-code
```javascript
function Capability(sid, tkn) {
    if(!(this instanceof Capability)) {
      return new Capability(sid, tkn);
    }

    utils.initializeTokens(this, 'Capability', sid, tkn);
    this.capabilities = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.IpMessagingClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>IpMessagingClient (sid, tkn, options)](#apidoc.element.twilio.IpMessagingClient)
- description and source-code
```javascript
function IpMessagingClient(sid, tkn, options) {
    options = options || {};
    IpMessagingClient.super_.call(
        this, sid, tkn,
        options.host || 'ip-messaging.twilio.com',
        options.apiVersion || 'v1',
        options.timeout
    );

    var servicesResource = require('./resources/ip_messaging/Services')(this);
    this.services = servicesResource;

    var credentialsResource = require('./resources/ip_messaging/Credentials')(this);
    this.credentials = credentialsResource;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.IpMessagingClient.super_"></a>[function <span class="apidocSignatureSpan">twilio.</span>IpMessagingClient.super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.IpMessagingClient.super_)
- description and source-code
```javascript
function Client(sid, tkn, host, api_version, timeout) {
    //Required client config
    if (!sid || !tkn) {
        if (process.env.TWILIO_ACCOUNT_SID && process.env.TWILIO_AUTH_TOKEN) {
            this.accountSid = process.env.TWILIO_ACCOUNT_SID;
            this.authToken = process.env.TWILIO_AUTH_TOKEN;
        }
        else {
            throw 'Client requires an Account SID and Auth Token set explicitly ' +
                'or via the TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN environment variables';
        }
    }
    else {
        //if auth token/SID passed in manually, trim spaces
        this.accountSid = sid.replace(/ /g, '');
        this.authToken = tkn.replace(/ /g, '');
    }

    //Optional client config
    this.host = host || defaultHost;
    this.apiVersion = api_version || defaultApiVersion;
    this.timeout = timeout || 31000; // request timeout in milliseconds
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.LookupsClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>LookupsClient (sid, tkn, options)](#apidoc.element.twilio.LookupsClient)
- description and source-code
```javascript
function LookupsClient(sid, tkn, options) {
    //Required client config
    options = options || {};
    LookupsClient.super_.call(this, sid, tkn, options.host || 'lookups.twilio.com', options.apiVersion || 'v1', options.timeout);

    var phoneNumbersResource = require('./resources/lookups/PhoneNumbers')(this);
    this.phoneNumbers = phoneNumbersResource;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.MonitorClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>MonitorClient (sid, tkn, options)](#apidoc.element.twilio.MonitorClient)
- description and source-code
```javascript
function MonitorClient(sid, tkn, options) {
    //Required client config
    options = options || {};
    MonitorClient.super_.call(this, sid, tkn, options.host || 'monitor.twilio.com', options.apiVersion || 'v1', options.timeout);

    //REST Resource - shorthand for just "event" and "events" to match the REST API
    var eventResource = require('./resources/monitor/Events')(this);
    this.events = eventResource;
    var alertResource = require('./resources/monitor/Alerts')(this);
    this.alerts = alertResource;

    //mix the account object in with the client object - assume master account for resources
    _.extend(this, eventResource);
    _.extend(this, alertResource);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.PricingClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>PricingClient (sid, tkn, options)](#apidoc.element.twilio.PricingClient)
- description and source-code
```javascript
function PricingClient(sid, tkn, options) {
    options = options || {};
    PricingClient.super_.call(this, sid, tkn, options.host || 'pricing.twilio.com', options.apiVersion || 'v1', options.timeout);

    var voiceResource = require('./resources/pricing/Voice')(this);
    this.voice = voiceResource;

    var phoneNumbersResource = require('./resources/pricing/PhoneNumbers')(this);
    this.phoneNumbers = phoneNumbersResource;

    var messagingResource = require('./resources/pricing/Messaging')(this);
    this.messaging = messagingResource;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.RestClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>RestClient (sid, tkn, options)](#apidoc.element.twilio.RestClient)
- description and source-code
```javascript
function RestClient(sid, tkn, options) {
    options = options || {};
    RestClient.super_.call(this, sid, tkn, options.host, options.apiVersion, options.timeout);

    //REST Resource - shorthand for just "account" and "accounts" to match the REST API
    var accountResource = require('./resources/Accounts')(this);
    this.accounts = accountResource;

    //mix the account object in with the client object - assume master account for resources
    _.extend(this,accountResource);

    //Messaging shorthand
    this.sendSms = this.accounts.sms.messages.post;
    this.sendMms = this.accounts.messages.post;
    this.sendMessage = this.accounts.messages.post;
    this.listSms = this.accounts.sms.messages.get;
    this.listMessages = this.accounts.messages.get;
    this.getSms = function(messageSid, callback) {
        this.accounts.sms.messages(messageSid).get(callback);
    };
    this.getMessage = function(messageSid, callback) {
        this.accounts.messages(messageSid).get(callback);
    };


    //Calls shorthand
    this.makeCall = this.accounts.calls.post;
    this.listCalls = this.accounts.calls.get;
    this.getCall = function(callSid, callback) {
        this.accounts.calls(callSid).get(callback);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability"></a>[function <span class="apidocSignatureSpan">twilio.</span>TaskRouterCapability (accountSid, authToken, workspaceSid, channelId)](#apidoc.element.twilio.TaskRouterCapability)
- description and source-code
```javascript
function TaskRouterCapability(accountSid, authToken, workspaceSid, channelId) {
    this.accountSid = accountSid;
    this.authToken = authToken;
    this.policies = [];

    this.workspaceSid = workspaceSid;
    this.channelId = channelId;

    this._baseUrl = taskRouterUrlBase + '/' + taskRouterVersion + '/Workspaces/' + this.workspaceSid;

    this._validateJWT();

    this._setupResource();

    var eventsUrl = eventUrlBase + '/' + this.accountSid + '/' + channelId;

    // add permissions to GET and POST to the event-bridge channel
    this.allow(eventsUrl, 'GET');
    this.allow(eventsUrl, 'POST');

    // add permission to fetch the instance resource
    this.allow(this._resourceUrl, 'GET');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>TaskRouterClient (sid, tkn, workspaceSid, options)](#apidoc.element.twilio.TaskRouterClient)
- description and source-code
```javascript
function TaskRouterClient(sid, tkn, workspaceSid, options) {
    //Required client config
    if (!workspaceSid) {
        if (process.env.TWILIO_WORKSPACE_SID) {
            this.workspaceSid = process.env.TWILIO_WORKSPACE_SID;
        }
        else {
            throw 'Client requires a Workspace SID set explicitly or via the TWILIO_WORKSPACE_SID environment variables';
        }
    }
    else {
        //trim spaces
        this.workspaceSid = workspaceSid.replace(/ /g, '');
    }
    options = options || {};
    TaskRouterClient.super_.call(this, sid, tkn, options.host || 'taskrouter.twilio.com', options.apiVersion || 'v1', options.timeout
);

    //REST Resource - shorthand for just "workspace" and "workspaces" to match the REST API
    var workspaceResource = require('./resources/task_router/Workspaces')(this);
    this.workspaces = workspaceResource;
    this.workspace = workspaceResource(this.workspaceSid);

    //mix the account object in with the client object - assume master account for resources
    _.extend(this, workspaceResource);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterTaskQueueCapability"></a>[function <span class="apidocSignatureSpan">twilio.</span>TaskRouterTaskQueueCapability (accountSid, authToken, workspaceSid, taskQueueSid)](#apidoc.element.twilio.TaskRouterTaskQueueCapability)
- description and source-code
```javascript
function TaskRouterTaskQueueCapability(accountSid, authToken, workspaceSid, taskQueueSid) {
    TaskRouterCapability.call(this, accountSid, authToken, workspaceSid, taskQueueSid);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterWorkerCapability"></a>[function <span class="apidocSignatureSpan">twilio.</span>TaskRouterWorkerCapability (accountSid, authToken, workspaceSid, workerSid)](#apidoc.element.twilio.TaskRouterWorkerCapability)
- description and source-code
```javascript
function TaskRouterWorkerCapability(accountSid, authToken, workspaceSid, workerSid) {
    TaskRouterCapability.call(this, accountSid, authToken, workspaceSid, workerSid);

    this.reservationsUrl = this._baseUrl + "/Tasks/**";
    this.activityUrl = this._baseUrl + "/Activities";
    this.workerReservationsUrl = this._resourceUrl + "/Reservations/**";

    // add permissions fo fetch the list of activities, tasks and worker reservations
    this.allow(this.activityUrl, "GET");
    this.allow(this.reservationsUrl, "GET");
    this.allow(this.workerReservationsUrl, "GET");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterWorkspaceCapability"></a>[function <span class="apidocSignatureSpan">twilio.</span>TaskRouterWorkspaceCapability (accountSid, authToken, workspaceSid)](#apidoc.element.twilio.TaskRouterWorkspaceCapability)
- description and source-code
```javascript
function TaskRouterWorkspaceCapability(accountSid, authToken, workspaceSid) {
    TaskRouterCapability.call(this, accountSid, authToken, workspaceSid, workspaceSid);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TrunkingClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>TrunkingClient (sid, tkn, options)](#apidoc.element.twilio.TrunkingClient)
- description and source-code
```javascript
function TrunkingClient(sid, tkn, options) {
    options = options || {};
    TrunkingClient.super_.call(
        this, sid, tkn,
        options.host || 'trunking.twilio.com',
        options.apiVersion || 'v1',
        options.timeout
    );

    var trunkResource = require('./resources/trunking/Trunks')(this);
    this.trunks = trunkResource;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TwimlResponse"></a>[function <span class="apidocSignatureSpan">twilio.</span>TwimlResponse ()](#apidoc.element.twilio.TwimlResponse)
- description and source-code
```javascript
TwimlResponse = function () {
    return new Node({
        topLevel:true,
        name:'Response',
        legalNodes:['Say', 'Play', 'Gather', 'Record', 'Sms', 'Dial', 'Enqueue', 'Task', 'Leave', 'Hangup', 'Redirect', 'Reject', '
Pause', 'Message']
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.validateExpressRequest"></a>[function <span class="apidocSignatureSpan">twilio.</span>validateExpressRequest (request, authToken, opts)](#apidoc.element.twilio.validateExpressRequest)
- description and source-code
```javascript
validateExpressRequest = function (request, authToken, opts) {
    var options = opts||{}, webhookUrl;
    if (options.url) {
        // Let the user specify the full URL
        webhookUrl = options.url;
    } else {
        // Use configured host/protocol, or infer based on request
        var protocol = options.protocol||request.protocol;
        var host = options.host||request.headers.host;
        webhookUrl = url.format({
            protocol: protocol,
            host: host,
            pathname: request.originalUrl
        });
    }

    return exports.validateRequest(
        authToken,
        request.header('X-Twilio-Signature'),
        webhookUrl,
        request.body||{}
    );
}
```
- example usage
```shell
...
    console.error('[Twilio]: Error - Twilio auth token is required for webhook request validation.');
    response
        .type('text/plain')
        .status(500)
        .send('Webhook Error - we attempted to validate this request without first configuring our auth token.');
} else {
    // Check that the request originated from Twilio
    valid = exports.validateExpressRequest(request, opts.authToken, {
        url: opts.url,
        host: opts.host,
        protocol: opts.protocol
    });
    if (valid) {
        next();
    } else {
...
```

#### <a name="apidoc.element.twilio.validateRequest"></a>[function <span class="apidocSignatureSpan">twilio.</span>validateRequest (authToken, twilioHeader, url, params)](#apidoc.element.twilio.validateRequest)
- description and source-code
```javascript
validateRequest = function (authToken, twilioHeader, url, params) {
    Object.keys(params).sort().forEach(function(key, i) {
        url = url + key + params[key];
    });

    return scmp(twilioHeader, crypto.createHmac('sha1', authToken).update(new Buffer(url, 'utf-8')).digest('Base64'));
}
```
- example usage
```shell
...
        webhookUrl = url.format({
            protocol: protocol,
            host: host,
            pathname: request.originalUrl
        });
    }

    return exports.validateRequest(
        authToken,
        request.header('X-Twilio-Signature'),
        webhookUrl,
        request.body||{}
    );
};
...
```

#### <a name="apidoc.element.twilio.webhook"></a>[function <span class="apidocSignatureSpan">twilio.</span>webhook ()](#apidoc.element.twilio.webhook)
- description and source-code
```javascript
webhook = function () {
    var opts = {
        validate:true,
        includeHelpers:true
    };

    // Process arguments
    var tokenString;
    for (var i = 0, l = arguments.length; i<l; i++) {
        var arg = arguments[i];
        if (typeof arg === 'string') {
            tokenString = arg;
        } else {
            opts = _.extend(opts, arg);
        }
    }

    // set auth token from input or environment variable
    opts.authToken = tokenString ? tokenString : process.env.TWILIO_AUTH_TOKEN;

    // Create middleware function
    return function hook(request, response, next) {
        // Add helpers, unless disabled
        if (opts.includeHelpers) {
            var oldSend = response.send;
            response.send = function() {
                // This is a special TwiML-aware version of send.  If we detect
                // A twiml response object, we'll set the content-type and
                // automatically call .toString()
                if (arguments.length == 1 && arguments[0].legalNodes) {
                    response.type('text/xml');
                    oldSend.call(response,arguments[0].toString());
                } else {
                    // Continue with old version of send
                    oldSend.apply(response,arguments);
                }
            };
        }

        // Do validation if requested
        if (opts.validate) {
            // Check for a valid auth token
            if (!opts.authToken) {
                console.error('[Twilio]: Error - Twilio auth token is required for webhook request validation.');
                response
                    .type('text/plain')
                    .status(500)
                    .send('Webhook Error - we attempted to validate this request without first configuring our auth token.');
            } else {
                // Check that the request originated from Twilio
                valid = exports.validateExpressRequest(request, opts.authToken, {
                    url: opts.url,
                    host: opts.host,
                    protocol: opts.protocol
                });
                if (valid) {
                    next();
                } else {
                    return response
                        .type('text/plain')
                        .status(403)
                        .send('Twilio Request Validation Failed.');
                }
            }
        } else {
            next();
        }
    };
}
```
- example usage
```shell
...
for XML (TwiML) rendering.  Default true.
- host: manually specify the host name used by Twilio in a number's webhook config
- protocol: manually specify the protocol used by Twilio in a number's webhook config

Returns a middleware function.

Examples:
var webhookMiddleware = twilio.webhook();
var webhookMiddleware = twilio.webhook('asdha9dhjasd'); //init with auth token
var webhookMiddleware = twilio.webhook({
validate:false // don't attempt request validation
});
var webhookMiddleware = twilio.webhook({
host: 'hook.twilio.com',
protocol: 'https'
...
```



# <a name="apidoc.module.twilio.AccessToken"></a>[module twilio.AccessToken](#apidoc.module.twilio.AccessToken)

#### <a name="apidoc.element.twilio.AccessToken.AccessToken"></a>[function <span class="apidocSignatureSpan">twilio.</span>AccessToken (accountSid, keySid, secret, opts)](#apidoc.element.twilio.AccessToken.AccessToken)
- description and source-code
```javascript
function AccessToken(accountSid, keySid, secret, opts) {
  if (!accountSid) { throw new Error('accountSid is required'); }
  if (!keySid) { throw new Error('keySid is required'); }
  if (!secret) { throw new Error('secret is required'); }
  opts = opts || {};

  this.accountSid = accountSid;
  this.keySid = keySid;
  this.secret = secret;
  this.ttl = opts.ttl || 3600;
  this.identity = opts.identity;
  this.nbf = opts.nbf;
  this.grants = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.AccessToken.ConversationsGrant"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.</span>ConversationsGrant (options)](#apidoc.element.twilio.AccessToken.ConversationsGrant)
- description and source-code
```javascript
function ConversationsGrant(options) {
  options = options || {};
  this.configurationProfileSid = options.configurationProfileSid;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.AccessToken.IpMessagingGrant"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.</span>IpMessagingGrant (options)](#apidoc.element.twilio.AccessToken.IpMessagingGrant)
- description and source-code
```javascript
function IpMessagingGrant(options) {
  options = options || {};
  this.serviceSid = options.serviceSid;
  this.endpointId = options.endpointId;
  this.deploymentRoleSid = options.deploymentRoleSid;
  this.pushCredentialSid = options.pushCredentialSid;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.AccessToken.VideoGrant"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.</span>VideoGrant (options)](#apidoc.element.twilio.AccessToken.VideoGrant)
- description and source-code
```javascript
function VideoGrant(options) {
  options = options || {};
  this.configurationProfileSid = options.configurationProfileSid;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.AccessToken.VoiceGrant"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.</span>VoiceGrant (options)](#apidoc.element.twilio.AccessToken.VoiceGrant)
- description and source-code
```javascript
function VoiceGrant(options) {
  options = options || {};
  this.outgoingApplicationSid = options.outgoingApplicationSid;
  this.outgoingApplicationParams = options.outgoingApplicationParams;
  this.pushCredentialSid = options.pushCredentialSid;
  this.endpointId = options.endpointId;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.AccessToken.ConversationsGrant"></a>[module twilio.AccessToken.ConversationsGrant](#apidoc.module.twilio.AccessToken.ConversationsGrant)

#### <a name="apidoc.element.twilio.AccessToken.ConversationsGrant.ConversationsGrant"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.</span>ConversationsGrant (options)](#apidoc.element.twilio.AccessToken.ConversationsGrant.ConversationsGrant)
- description and source-code
```javascript
function ConversationsGrant(options) {
  options = options || {};
  this.configurationProfileSid = options.configurationProfileSid;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.AccessToken.ConversationsGrant.prototype"></a>[module twilio.AccessToken.ConversationsGrant.prototype](#apidoc.module.twilio.AccessToken.ConversationsGrant.prototype)

#### <a name="apidoc.element.twilio.AccessToken.ConversationsGrant.prototype.toPayload"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.ConversationsGrant.prototype.</span>toPayload ()](#apidoc.element.twilio.AccessToken.ConversationsGrant.prototype.toPayload)
- description and source-code
```javascript
toPayload = function () {
  var grant = {};
  if (this.configurationProfileSid) {
    grant.configuration_profile_sid = this.configurationProfileSid;
  }
  return grant;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.AccessToken.IpMessagingGrant"></a>[module twilio.AccessToken.IpMessagingGrant](#apidoc.module.twilio.AccessToken.IpMessagingGrant)

#### <a name="apidoc.element.twilio.AccessToken.IpMessagingGrant.IpMessagingGrant"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.</span>IpMessagingGrant (options)](#apidoc.element.twilio.AccessToken.IpMessagingGrant.IpMessagingGrant)
- description and source-code
```javascript
function IpMessagingGrant(options) {
  options = options || {};
  this.serviceSid = options.serviceSid;
  this.endpointId = options.endpointId;
  this.deploymentRoleSid = options.deploymentRoleSid;
  this.pushCredentialSid = options.pushCredentialSid;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.AccessToken.IpMessagingGrant.prototype"></a>[module twilio.AccessToken.IpMessagingGrant.prototype](#apidoc.module.twilio.AccessToken.IpMessagingGrant.prototype)

#### <a name="apidoc.element.twilio.AccessToken.IpMessagingGrant.prototype.toPayload"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.IpMessagingGrant.prototype.</span>toPayload ()](#apidoc.element.twilio.AccessToken.IpMessagingGrant.prototype.toPayload)
- description and source-code
```javascript
toPayload = function () {
  var grant = {};
  if (this.serviceSid) { grant.service_sid = this.serviceSid; }
  if (this.endpointId) { grant.endpoint_id = this.endpointId; }
  if (this.deploymentRoleSid) {
    grant.deployment_role_sid = this.deploymentRoleSid;
  }
  if (this.pushCredentialSid) {
    grant.push_credential_sid = this.pushCredentialSid;
  }
  return grant;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.AccessToken.VideoGrant"></a>[module twilio.AccessToken.VideoGrant](#apidoc.module.twilio.AccessToken.VideoGrant)

#### <a name="apidoc.element.twilio.AccessToken.VideoGrant.VideoGrant"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.</span>VideoGrant (options)](#apidoc.element.twilio.AccessToken.VideoGrant.VideoGrant)
- description and source-code
```javascript
function VideoGrant(options) {
  options = options || {};
  this.configurationProfileSid = options.configurationProfileSid;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.AccessToken.VideoGrant.prototype"></a>[module twilio.AccessToken.VideoGrant.prototype](#apidoc.module.twilio.AccessToken.VideoGrant.prototype)

#### <a name="apidoc.element.twilio.AccessToken.VideoGrant.prototype.toPayload"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.VideoGrant.prototype.</span>toPayload ()](#apidoc.element.twilio.AccessToken.VideoGrant.prototype.toPayload)
- description and source-code
```javascript
toPayload = function () {
  var grant = {};
  if (this.configurationProfileSid) {
    grant.configuration_profile_sid = this.configurationProfileSid;
  }
  return grant;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.AccessToken.VoiceGrant"></a>[module twilio.AccessToken.VoiceGrant](#apidoc.module.twilio.AccessToken.VoiceGrant)

#### <a name="apidoc.element.twilio.AccessToken.VoiceGrant.VoiceGrant"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.</span>VoiceGrant (options)](#apidoc.element.twilio.AccessToken.VoiceGrant.VoiceGrant)
- description and source-code
```javascript
function VoiceGrant(options) {
  options = options || {};
  this.outgoingApplicationSid = options.outgoingApplicationSid;
  this.outgoingApplicationParams = options.outgoingApplicationParams;
  this.pushCredentialSid = options.pushCredentialSid;
  this.endpointId = options.endpointId;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.AccessToken.VoiceGrant.prototype"></a>[module twilio.AccessToken.VoiceGrant.prototype](#apidoc.module.twilio.AccessToken.VoiceGrant.prototype)

#### <a name="apidoc.element.twilio.AccessToken.VoiceGrant.prototype.toPayload"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.VoiceGrant.prototype.</span>toPayload ()](#apidoc.element.twilio.AccessToken.VoiceGrant.prototype.toPayload)
- description and source-code
```javascript
toPayload = function () {
  var grant = {};
  if (this.outgoingApplicationSid) {
    grant.outgoing = {};
    grant.outgoing.application_sid = this.outgoingApplicationSid;

    if (this.outgoingApplicationParams) {
      grant.outgoing.params = this.outgoingApplicationParams;
    }
  }

  if (this.pushCredentialSid) {
    grant.push_credential_sid = this.pushCredentialSid;
  }
  if (this.endpointId) {
    grant.endpoint_id = this.endpointId;
  }
  return grant;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.AccessToken.prototype"></a>[module twilio.AccessToken.prototype](#apidoc.module.twilio.AccessToken.prototype)

#### <a name="apidoc.element.twilio.AccessToken.prototype.addGrant"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.prototype.</span>addGrant (grant)](#apidoc.element.twilio.AccessToken.prototype.addGrant)
- description and source-code
```javascript
addGrant = function (grant) {
  this.grants.push(grant);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.AccessToken.prototype.toJwt"></a>[function <span class="apidocSignatureSpan">twilio.AccessToken.prototype.</span>toJwt (algorithm)](#apidoc.element.twilio.AccessToken.prototype.toJwt)
- description and source-code
```javascript
toJwt = function (algorithm) {
  algorithm = algorithm || AccessToken.DEFAULT_ALGORITHM;
  if (!_.contains(AccessToken.ALGORITHMS, algorithm)) {
    throw new Error('Algorithm not supported. Allowed values are ' +
      AccessToken.ALGORITHMS.join(', '));
  }

  var grants = {};
  if (_.isString(this.identity)) { grants.identity = this.identity; }

  _.each(this.grants, function(grant) {
    grants[grant.key] = grant.toPayload();
  });

  var now = Math.floor(Date.now() / 1000);
  var payload = {
    jti: this.keySid + '-' + now,
    grants: grants
  };
  if (_.isNumber(this.nbf)) { payload.nbf = this.nbf; }

  return jwt.sign(payload, this.secret, {
    headers: {
      cty: 'twilio-fpa;v=1',
      typ: 'JWT'
    },
    algorithm: algorithm,
    issuer: this.keySid,
    subject: this.accountSid,
    expiresIn: this.ttl
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.Capability"></a>[module twilio.Capability](#apidoc.module.twilio.Capability)

#### <a name="apidoc.element.twilio.Capability.Capability"></a>[function <span class="apidocSignatureSpan">twilio.</span>Capability (sid, tkn)](#apidoc.element.twilio.Capability.Capability)
- description and source-code
```javascript
function Capability(sid, tkn) {
    if(!(this instanceof Capability)) {
      return new Capability(sid, tkn);
    }

    utils.initializeTokens(this, 'Capability', sid, tkn);
    this.capabilities = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.Capability.prototype"></a>[module twilio.Capability.prototype](#apidoc.module.twilio.Capability.prototype)

#### <a name="apidoc.element.twilio.Capability.prototype.allowClientIncoming"></a>[function <span class="apidocSignatureSpan">twilio.Capability.prototype.</span>allowClientIncoming (clientName)](#apidoc.element.twilio.Capability.prototype.allowClientIncoming)
- description and source-code
```javascript
allowClientIncoming = function (clientName) {
    this.clientName = clientName;
    this.capabilities.push(scopeUriFor('client', 'incoming', {
        clientName:clientName
    }));

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.Capability.prototype.allowClientOutgoing"></a>[function <span class="apidocSignatureSpan">twilio.Capability.prototype.</span>allowClientOutgoing (appSid, params)](#apidoc.element.twilio.Capability.prototype.allowClientOutgoing)
- description and source-code
```javascript
allowClientOutgoing = function (appSid, params) {
    this.outgoingScopeParams = {
        appSid:appSid
    };

    if (params) {
        this.outgoingScopeParams.appParams = qs.stringify(params);
    }

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.Capability.prototype.allowEventStream"></a>[function <span class="apidocSignatureSpan">twilio.Capability.prototype.</span>allowEventStream (filters)](#apidoc.element.twilio.Capability.prototype.allowEventStream)
- description and source-code
```javascript
allowEventStream = function (filters) {
    var scopeParams = {
        path:'/2010-04-01/Events'
    };

    if (filters) {
        scopeParams.params = filters;
    }

    this.capabilities.push(scopeUriFor('stream', 'subscribe', scopeParams));
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.Capability.prototype.generate"></a>[function <span class="apidocSignatureSpan">twilio.Capability.prototype.</span>generate (timeout)](#apidoc.element.twilio.Capability.prototype.generate)
- description and source-code
```javascript
generate = function (timeout) {
    var capabilities = this.capabilities.slice(0),
        expires = timeout||3600;

    //Build outgoing scope params lazily to use clientName (if it exists)
    if (this.outgoingScopeParams) {
        if (this.clientName) {
            this.outgoingScopeParams.clientName = this.clientName;
        }
        capabilities.push(scopeUriFor('client', 'outgoing', this.outgoingScopeParams));
    }

    var payload = {
        scope: capabilities.join(' '),
        iss: this.accountSid,
        exp: Math.floor(new Date() / 1000) + expires
    };

    return jwt.sign(payload, this.authToken);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.IpMessagingClient"></a>[module twilio.IpMessagingClient](#apidoc.module.twilio.IpMessagingClient)

#### <a name="apidoc.element.twilio.IpMessagingClient.IpMessagingClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>IpMessagingClient (sid, tkn, options)](#apidoc.element.twilio.IpMessagingClient.IpMessagingClient)
- description and source-code
```javascript
function IpMessagingClient(sid, tkn, options) {
    options = options || {};
    IpMessagingClient.super_.call(
        this, sid, tkn,
        options.host || 'ip-messaging.twilio.com',
        options.apiVersion || 'v1',
        options.timeout
    );

    var servicesResource = require('./resources/ip_messaging/Services')(this);
    this.services = servicesResource;

    var credentialsResource = require('./resources/ip_messaging/Credentials')(this);
    this.credentials = credentialsResource;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.IpMessagingClient.super_"></a>[function <span class="apidocSignatureSpan">twilio.IpMessagingClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.IpMessagingClient.super_)
- description and source-code
```javascript
function Client(sid, tkn, host, api_version, timeout) {
    //Required client config
    if (!sid || !tkn) {
        if (process.env.TWILIO_ACCOUNT_SID && process.env.TWILIO_AUTH_TOKEN) {
            this.accountSid = process.env.TWILIO_ACCOUNT_SID;
            this.authToken = process.env.TWILIO_AUTH_TOKEN;
        }
        else {
            throw 'Client requires an Account SID and Auth Token set explicitly ' +
                'or via the TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN environment variables';
        }
    }
    else {
        //if auth token/SID passed in manually, trim spaces
        this.accountSid = sid.replace(/ /g, '');
        this.authToken = tkn.replace(/ /g, '');
    }

    //Optional client config
    this.host = host || defaultHost;
    this.apiVersion = api_version || defaultApiVersion;
    this.timeout = timeout || 31000; // request timeout in milliseconds
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.IpMessagingClient.super_"></a>[module twilio.IpMessagingClient.super_](#apidoc.module.twilio.IpMessagingClient.super_)

#### <a name="apidoc.element.twilio.IpMessagingClient.super_.super_"></a>[function <span class="apidocSignatureSpan">twilio.IpMessagingClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.IpMessagingClient.super_.super_)
- description and source-code
```javascript
function Client(sid, tkn, host, api_version, timeout) {
    //Required client config
    if (!sid || !tkn) {
        if (process.env.TWILIO_ACCOUNT_SID && process.env.TWILIO_AUTH_TOKEN) {
            this.accountSid = process.env.TWILIO_ACCOUNT_SID;
            this.authToken = process.env.TWILIO_AUTH_TOKEN;
        }
        else {
            throw 'Client requires an Account SID and Auth Token set explicitly ' +
                'or via the TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN environment variables';
        }
    }
    else {
        //if auth token/SID passed in manually, trim spaces
        this.accountSid = sid.replace(/ /g, '');
        this.authToken = tkn.replace(/ /g, '');
    }

    //Optional client config
    this.host = host || defaultHost;
    this.apiVersion = api_version || defaultApiVersion;
    this.timeout = timeout || 31000; // request timeout in milliseconds
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.IpMessagingClient.super_.prototype"></a>[module twilio.IpMessagingClient.super_.prototype](#apidoc.module.twilio.IpMessagingClient.super_.prototype)

#### <a name="apidoc.element.twilio.IpMessagingClient.super_.prototype.getBaseUrl"></a>[function <span class="apidocSignatureSpan">twilio.IpMessagingClient.super_.prototype.</span>getBaseUrl ()](#apidoc.element.twilio.IpMessagingClient.super_.prototype.getBaseUrl)
- description and source-code
```javascript
getBaseUrl = function () {
    return 'https://' + this.accountSid + ':' + this.authToken + '@' + this.host + '/' + this.apiVersion;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.IpMessagingClient.super_.prototype.request"></a>[function <span class="apidocSignatureSpan">twilio.IpMessagingClient.super_.prototype.</span>request (options, callback)](#apidoc.element.twilio.IpMessagingClient.super_.prototype.request)
- description and source-code
```javascript
request = function (options, callback) {
    var client = this;
    var deferred = Q.defer();

    //Prepare request options
    // Add base URL if we weren't given an absolute one
    if (!options.url.indexOf('http') !== 0) {
        options.url = client.getBaseUrl() + options.url;
    }
    options.headers = {
        'Accept':'application/json',
        'Accept-Charset': 'utf-8',
        'User-Agent':'twilio-node/' + moduleinfo.version
    };
    options.timeout = client.timeout;

    // Manually create POST body if there's a form object. Sadly, request
    // turns multiple key parameters into array-ified queries, like this:
    // MediaUrl[0]=foo&MediaUrl[1]=bar. Node querystring does the right thing so
    // we use that here. Also see https://github.com/mikeal/request/issues/644
    if (options.form) {
        options.body = querystring.stringify(options.form).toString('utf-8');
        options.headers['Content-Type'] = 'application/x-www-form-urlencoded; charset=utf-8';
        options.form = null;
    }

    //Initiate HTTP request
    request(options, function (err, response, body) {
        var data;
        try {
            if (err) {
                data = err;
            } else {
                data = body ? JSON.parse(body) : null;
            }
        } catch (e) {
            data = { status: 500, message: (e.message || 'Invalid JSON body') };
        }

        //request doesn't think 4xx is an error - we want an error for any non-2xx status codes
        var error = null;
        if (err || (response && (response.statusCode < 200 || response.statusCode > 206))) {
            error = {};
            // response is null if server is unreachable
            if (response) {
                error.status = response.statusCode;
                error.message = data ? data.message : 'Unable to complete HTTP request';
                error.code = data && data.code;
                error.moreInfo = data && data.more_info;
            } else {
                error.status = err.code;
                error.message = 'Unable to reach host: "'+client.host+'"';
            }
        }

        // JavaScriptify properties of response if it exists
        data && processKeys(data);

        //hang response off the JSON-serialized data, as unenumerable to allow for stringify.
        data && Object.defineProperty(data, 'nodeClientResponse', {
            value: response,
            configurable: true,
            writeable: true,
            enumerable: false
        });

        // Resolve promise
        if (error) {
            deferred.reject(error);
        } else {
            deferred.resolve(data);
        }

    });

    // Return promise, but also support original node callback style
    return deferred.promise.nodeify(callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.LookupsClient"></a>[module twilio.LookupsClient](#apidoc.module.twilio.LookupsClient)

#### <a name="apidoc.element.twilio.LookupsClient.LookupsClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>LookupsClient (sid, tkn, options)](#apidoc.element.twilio.LookupsClient.LookupsClient)
- description and source-code
```javascript
function LookupsClient(sid, tkn, options) {
    //Required client config
    options = options || {};
    LookupsClient.super_.call(this, sid, tkn, options.host || 'lookups.twilio.com', options.apiVersion || 'v1', options.timeout);

    var phoneNumbersResource = require('./resources/lookups/PhoneNumbers')(this);
    this.phoneNumbers = phoneNumbersResource;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.LookupsClient.super_"></a>[function <span class="apidocSignatureSpan">twilio.LookupsClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.LookupsClient.super_)
- description and source-code
```javascript
function Client(sid, tkn, host, api_version, timeout) {
    //Required client config
    if (!sid || !tkn) {
        if (process.env.TWILIO_ACCOUNT_SID && process.env.TWILIO_AUTH_TOKEN) {
            this.accountSid = process.env.TWILIO_ACCOUNT_SID;
            this.authToken = process.env.TWILIO_AUTH_TOKEN;
        }
        else {
            throw 'Client requires an Account SID and Auth Token set explicitly ' +
                'or via the TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN environment variables';
        }
    }
    else {
        //if auth token/SID passed in manually, trim spaces
        this.accountSid = sid.replace(/ /g, '');
        this.authToken = tkn.replace(/ /g, '');
    }

    //Optional client config
    this.host = host || defaultHost;
    this.apiVersion = api_version || defaultApiVersion;
    this.timeout = timeout || 31000; // request timeout in milliseconds
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.MonitorClient"></a>[module twilio.MonitorClient](#apidoc.module.twilio.MonitorClient)

#### <a name="apidoc.element.twilio.MonitorClient.MonitorClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>MonitorClient (sid, tkn, options)](#apidoc.element.twilio.MonitorClient.MonitorClient)
- description and source-code
```javascript
function MonitorClient(sid, tkn, options) {
    //Required client config
    options = options || {};
    MonitorClient.super_.call(this, sid, tkn, options.host || 'monitor.twilio.com', options.apiVersion || 'v1', options.timeout);

    //REST Resource - shorthand for just "event" and "events" to match the REST API
    var eventResource = require('./resources/monitor/Events')(this);
    this.events = eventResource;
    var alertResource = require('./resources/monitor/Alerts')(this);
    this.alerts = alertResource;

    //mix the account object in with the client object - assume master account for resources
    _.extend(this, eventResource);
    _.extend(this, alertResource);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.MonitorClient.super_"></a>[function <span class="apidocSignatureSpan">twilio.MonitorClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.MonitorClient.super_)
- description and source-code
```javascript
function Client(sid, tkn, host, api_version, timeout) {
    //Required client config
    if (!sid || !tkn) {
        if (process.env.TWILIO_ACCOUNT_SID && process.env.TWILIO_AUTH_TOKEN) {
            this.accountSid = process.env.TWILIO_ACCOUNT_SID;
            this.authToken = process.env.TWILIO_AUTH_TOKEN;
        }
        else {
            throw 'Client requires an Account SID and Auth Token set explicitly ' +
                'or via the TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN environment variables';
        }
    }
    else {
        //if auth token/SID passed in manually, trim spaces
        this.accountSid = sid.replace(/ /g, '');
        this.authToken = tkn.replace(/ /g, '');
    }

    //Optional client config
    this.host = host || defaultHost;
    this.apiVersion = api_version || defaultApiVersion;
    this.timeout = timeout || 31000; // request timeout in milliseconds
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.PricingClient"></a>[module twilio.PricingClient](#apidoc.module.twilio.PricingClient)

#### <a name="apidoc.element.twilio.PricingClient.PricingClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>PricingClient (sid, tkn, options)](#apidoc.element.twilio.PricingClient.PricingClient)
- description and source-code
```javascript
function PricingClient(sid, tkn, options) {
    options = options || {};
    PricingClient.super_.call(this, sid, tkn, options.host || 'pricing.twilio.com', options.apiVersion || 'v1', options.timeout);

    var voiceResource = require('./resources/pricing/Voice')(this);
    this.voice = voiceResource;

    var phoneNumbersResource = require('./resources/pricing/PhoneNumbers')(this);
    this.phoneNumbers = phoneNumbersResource;

    var messagingResource = require('./resources/pricing/Messaging')(this);
    this.messaging = messagingResource;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.PricingClient.super_"></a>[function <span class="apidocSignatureSpan">twilio.PricingClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.PricingClient.super_)
- description and source-code
```javascript
function Client(sid, tkn, host, api_version, timeout) {
    //Required client config
    if (!sid || !tkn) {
        if (process.env.TWILIO_ACCOUNT_SID && process.env.TWILIO_AUTH_TOKEN) {
            this.accountSid = process.env.TWILIO_ACCOUNT_SID;
            this.authToken = process.env.TWILIO_AUTH_TOKEN;
        }
        else {
            throw 'Client requires an Account SID and Auth Token set explicitly ' +
                'or via the TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN environment variables';
        }
    }
    else {
        //if auth token/SID passed in manually, trim spaces
        this.accountSid = sid.replace(/ /g, '');
        this.authToken = tkn.replace(/ /g, '');
    }

    //Optional client config
    this.host = host || defaultHost;
    this.apiVersion = api_version || defaultApiVersion;
    this.timeout = timeout || 31000; // request timeout in milliseconds
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.RestClient"></a>[module twilio.RestClient](#apidoc.module.twilio.RestClient)

#### <a name="apidoc.element.twilio.RestClient.RestClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>RestClient (sid, tkn, options)](#apidoc.element.twilio.RestClient.RestClient)
- description and source-code
```javascript
function RestClient(sid, tkn, options) {
    options = options || {};
    RestClient.super_.call(this, sid, tkn, options.host, options.apiVersion, options.timeout);

    //REST Resource - shorthand for just "account" and "accounts" to match the REST API
    var accountResource = require('./resources/Accounts')(this);
    this.accounts = accountResource;

    //mix the account object in with the client object - assume master account for resources
    _.extend(this,accountResource);

    //Messaging shorthand
    this.sendSms = this.accounts.sms.messages.post;
    this.sendMms = this.accounts.messages.post;
    this.sendMessage = this.accounts.messages.post;
    this.listSms = this.accounts.sms.messages.get;
    this.listMessages = this.accounts.messages.get;
    this.getSms = function(messageSid, callback) {
        this.accounts.sms.messages(messageSid).get(callback);
    };
    this.getMessage = function(messageSid, callback) {
        this.accounts.messages(messageSid).get(callback);
    };


    //Calls shorthand
    this.makeCall = this.accounts.calls.post;
    this.listCalls = this.accounts.calls.get;
    this.getCall = function(callSid, callback) {
        this.accounts.calls(callSid).get(callback);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.RestClient.super_"></a>[function <span class="apidocSignatureSpan">twilio.RestClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.RestClient.super_)
- description and source-code
```javascript
function Client(sid, tkn, host, api_version, timeout) {
    //Required client config
    if (!sid || !tkn) {
        if (process.env.TWILIO_ACCOUNT_SID && process.env.TWILIO_AUTH_TOKEN) {
            this.accountSid = process.env.TWILIO_ACCOUNT_SID;
            this.authToken = process.env.TWILIO_AUTH_TOKEN;
        }
        else {
            throw 'Client requires an Account SID and Auth Token set explicitly ' +
                'or via the TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN environment variables';
        }
    }
    else {
        //if auth token/SID passed in manually, trim spaces
        this.accountSid = sid.replace(/ /g, '');
        this.authToken = tkn.replace(/ /g, '');
    }

    //Optional client config
    this.host = host || defaultHost;
    this.apiVersion = api_version || defaultApiVersion;
    this.timeout = timeout || 31000; // request timeout in milliseconds
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.RestClient.prototype"></a>[module twilio.RestClient.prototype](#apidoc.module.twilio.RestClient.prototype)

#### <a name="apidoc.element.twilio.RestClient.prototype.request"></a>[function <span class="apidocSignatureSpan">twilio.RestClient.prototype.</span>request (options, callback)](#apidoc.element.twilio.RestClient.prototype.request)
- description and source-code
```javascript
request = function (options, callback) {
    var client = this;

    // Force .json for Coke Classic API
    options.url = options.url + '.json';
    return RestClient.super_.prototype.request.call(this, options, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.TaskRouterCapability"></a>[module twilio.TaskRouterCapability](#apidoc.module.twilio.TaskRouterCapability)

#### <a name="apidoc.element.twilio.TaskRouterCapability.TaskRouterCapability"></a>[function <span class="apidocSignatureSpan">twilio.</span>TaskRouterCapability (accountSid, authToken, workspaceSid, channelId)](#apidoc.element.twilio.TaskRouterCapability.TaskRouterCapability)
- description and source-code
```javascript
function TaskRouterCapability(accountSid, authToken, workspaceSid, channelId) {
    this.accountSid = accountSid;
    this.authToken = authToken;
    this.policies = [];

    this.workspaceSid = workspaceSid;
    this.channelId = channelId;

    this._baseUrl = taskRouterUrlBase + '/' + taskRouterVersion + '/Workspaces/' + this.workspaceSid;

    this._validateJWT();

    this._setupResource();

    var eventsUrl = eventUrlBase + '/' + this.accountSid + '/' + channelId;

    // add permissions to GET and POST to the event-bridge channel
    this.allow(eventsUrl, 'GET');
    this.allow(eventsUrl, 'POST');

    // add permission to fetch the instance resource
    this.allow(this._resourceUrl, 'GET');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.TaskRouterCapability.prototype"></a>[module twilio.TaskRouterCapability.prototype](#apidoc.module.twilio.TaskRouterCapability.prototype)

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype._generate"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>_generate (ttl, extraAttributes)](#apidoc.element.twilio.TaskRouterCapability.prototype._generate)
- description and source-code
```javascript
_generate = function (ttl, extraAttributes) {
    var payload = {
        iss: this.accountSid,
        exp: (Math.floor(new Date() / 1000) + (ttl || 3600)),
        version: taskRouterVersion,
        friendly_name: this.channelId,
        policies: this.policies,
    };
    _.extend(payload, extraAttributes);
    return jwt.sign(payload, this.authToken);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype._setupResource"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>_setupResource ()](#apidoc.element.twilio.TaskRouterCapability.prototype._setupResource)
- description and source-code
```javascript
_setupResource = function () {
    if(this.channelId.startsWith('WS')) {
        this._resourceUrl = this._baseUrl;
    }else if(this.channelId.startsWith('WK')) {
        this._resourceUrl = this._baseUrl + '/Workers/' + this.channelId;

        var activityUrl = this._baseUrl + '/Activities';
        this.allow(activityUrl, "GET");

        var tasksUrl = this._baseUrl + '/Tasks/**';
        this.allow(tasksUrl, "GET");

        var workerReservationsUrl = this._resourceUrl + '/Reservations/**';
        this.allow(workerReservationsUrl, "GET");

    }else if(this.channelId.startsWith('WQ')) {
        this._resourceUrl = this._baseUrl + '/TaskQueues/' + this.channelId;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype._validateJWT"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>_validateJWT ()](#apidoc.element.twilio.TaskRouterCapability.prototype._validateJWT)
- description and source-code
```javascript
_validateJWT = function () {
    if(!this.accountSid || !this.accountSid.startsWith('AC')) {
        throw "Invalid AccountSid provided: "+this.accountSid;
    }
    if(!this.workspaceSid || !this.workspaceSid.startsWith('WS')) {
        throw "Invalid WorkspaceSid provided: "+this.workspaceSid;
    }
    if(!this.channelId) {
        throw "ChannelId not provided";
    }
    var prefix = this.channelId.substring(0,2);
    if(prefix != 'WS' && prefix != 'WK' && prefix != 'WQ') {
        throw "Invalid ChannelId provided: "+this.channelId;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.addPolicy"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>addPolicy (url, method, allowed, queryFilter, postFilter)](#apidoc.element.twilio.TaskRouterCapability.prototype.addPolicy)
- description and source-code
```javascript
addPolicy = function (url, method, allowed, queryFilter, postFilter) {
    var policy = {
        url: url,
        method: method
    };

    if (queryFilter) {
        policy.query_filter = queryFilter;
    } else {
        policy.query_filter = {};
    }

    if (postFilter) {
        policy.post_filter = postFilter;
    } else {
        policy.post_filter = {};
    }

    if (typeof allowed !== 'undefined') {
        policy.allow = allowed;
    } else {
        policy.allow = true;
    }
    this.policies.push(policy);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.allow"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allow (url, method, queryFilter, postFilter)](#apidoc.element.twilio.TaskRouterCapability.prototype.allow)
- description and source-code
```javascript
allow = function (url, method, queryFilter, postFilter) {
    this.addPolicy(url, method, true, queryFilter, postFilter);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.allowDelete"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowDelete ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowDelete)
- description and source-code
```javascript
allowDelete = function () {
    this.allow(this._resourceUrl, 'DELETE');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.allowDeleteSubresources"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowDeleteSubresources ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowDeleteSubresources)
- description and source-code
```javascript
allowDeleteSubresources = function () {
    this.allow(this._resourceUrl+'/**', 'DELETE');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.allowFetchSubresources"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowFetchSubresources ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowFetchSubresources)
- description and source-code
```javascript
allowFetchSubresources = function () {
    this.allow(this._resourceUrl+'/**', 'GET');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.allowTaskReservationUpdates"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowTaskReservationUpdates ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowTaskReservationUpdates)
- description and source-code
```javascript
allowTaskReservationUpdates = function () {
    if(this.channelId.startsWith('WK')) {
        deprecate('allowTaskReservationUpdates is deprecated. Please use TaskRouterWorkerCapability.allowReservationUpdates() instead
');
        this.allow(this._baseUrl + "/Tasks/**", "POST");
    }else {
        throw "Deprecated function not applicable to non Worker";
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.allowUpdates"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowUpdates ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowUpdates)
- description and source-code
```javascript
allowUpdates = function () {
    this.allow(this._resourceUrl, 'POST');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.allowUpdatesSubresources"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowUpdatesSubresources ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowUpdatesSubresources)
- description and source-code
```javascript
allowUpdatesSubresources = function () {
    this.allow(this._resourceUrl+'/**', 'POST');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.allowWorkerActivityUpdates"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowWorkerActivityUpdates ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowWorkerActivityUpdates)
- description and source-code
```javascript
allowWorkerActivityUpdates = function () {
    if(this.channelId.startsWith('WK')) {
        deprecate('allowWorkerActivityUpdates is deprecated. Please use TaskRouterWorkerCapability.allowWorkerActivityUpdates()
instead');
        this.allow(this._resourceUrl, 'POST', {}, {"ActivitySid": {'required': true}});
    }else {
        throw "Deprecated function not applicable to non Worker";
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.allowWorkerFetchAttributes"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>allowWorkerFetchAttributes ()](#apidoc.element.twilio.TaskRouterCapability.prototype.allowWorkerFetchAttributes)
- description and source-code
```javascript
allowWorkerFetchAttributes = function () {
    if(this.channelId.startsWith('WK')) {
        deprecate('allowWorkerFetchAttributes is deprecated. Please use TaskRouterWorkerCapability; added automatically in constructor
');
        this.allow(this._resourceUrl, 'GET');
    }else {
        throw "Deprecated function not applicable to non Worker";
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.deny"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>deny (url, method, queryFilter, postFilter)](#apidoc.element.twilio.TaskRouterCapability.prototype.deny)
- description and source-code
```javascript
deny = function (url, method, queryFilter, postFilter) {
    this.addPolicy(url, method, false, queryFilter, postFilter);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterCapability.prototype.generate"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterCapability.prototype.</span>generate (ttl)](#apidoc.element.twilio.TaskRouterCapability.prototype.generate)
- description and source-code
```javascript
generate = function (ttl) {
    var taskRouterAttributes = {
        'account_sid': this.accountSid,
        'channel': this.channelId,
        'workspace_sid': this.workspaceSid
    }

    if(this.channelId.startsWith('WK')) {
        taskRouterAttributes.worker_sid = this.channelId;
    }else if(this.channelId.startsWith('WQ')) {
        taskRouterAttributes.taskqueue_sid = this.channelId;
    }

    return this._generate(ttl, taskRouterAttributes);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.TaskRouterClient"></a>[module twilio.TaskRouterClient](#apidoc.module.twilio.TaskRouterClient)

#### <a name="apidoc.element.twilio.TaskRouterClient.TaskRouterClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>TaskRouterClient (sid, tkn, workspaceSid, options)](#apidoc.element.twilio.TaskRouterClient.TaskRouterClient)
- description and source-code
```javascript
function TaskRouterClient(sid, tkn, workspaceSid, options) {
    //Required client config
    if (!workspaceSid) {
        if (process.env.TWILIO_WORKSPACE_SID) {
            this.workspaceSid = process.env.TWILIO_WORKSPACE_SID;
        }
        else {
            throw 'Client requires a Workspace SID set explicitly or via the TWILIO_WORKSPACE_SID environment variables';
        }
    }
    else {
        //trim spaces
        this.workspaceSid = workspaceSid.replace(/ /g, '');
    }
    options = options || {};
    TaskRouterClient.super_.call(this, sid, tkn, options.host || 'taskrouter.twilio.com', options.apiVersion || 'v1', options.timeout
);

    //REST Resource - shorthand for just "workspace" and "workspaces" to match the REST API
    var workspaceResource = require('./resources/task_router/Workspaces')(this);
    this.workspaces = workspaceResource;
    this.workspace = workspaceResource(this.workspaceSid);

    //mix the account object in with the client object - assume master account for resources
    _.extend(this, workspaceResource);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterClient.super_"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.TaskRouterClient.super_)
- description and source-code
```javascript
function Client(sid, tkn, host, api_version, timeout) {
    //Required client config
    if (!sid || !tkn) {
        if (process.env.TWILIO_ACCOUNT_SID && process.env.TWILIO_AUTH_TOKEN) {
            this.accountSid = process.env.TWILIO_ACCOUNT_SID;
            this.authToken = process.env.TWILIO_AUTH_TOKEN;
        }
        else {
            throw 'Client requires an Account SID and Auth Token set explicitly ' +
                'or via the TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN environment variables';
        }
    }
    else {
        //if auth token/SID passed in manually, trim spaces
        this.accountSid = sid.replace(/ /g, '');
        this.authToken = tkn.replace(/ /g, '');
    }

    //Optional client config
    this.host = host || defaultHost;
    this.apiVersion = api_version || defaultApiVersion;
    this.timeout = timeout || 31000; // request timeout in milliseconds
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.TaskRouterTaskQueueCapability"></a>[module twilio.TaskRouterTaskQueueCapability](#apidoc.module.twilio.TaskRouterTaskQueueCapability)

#### <a name="apidoc.element.twilio.TaskRouterTaskQueueCapability.TaskRouterTaskQueueCapability"></a>[function <span class="apidocSignatureSpan">twilio.</span>TaskRouterTaskQueueCapability (accountSid, authToken, workspaceSid, taskQueueSid)](#apidoc.element.twilio.TaskRouterTaskQueueCapability.TaskRouterTaskQueueCapability)
- description and source-code
```javascript
function TaskRouterTaskQueueCapability(accountSid, authToken, workspaceSid, taskQueueSid) {
    TaskRouterCapability.call(this, accountSid, authToken, workspaceSid, taskQueueSid);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterTaskQueueCapability.super_"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterTaskQueueCapability.</span>super_ (accountSid, authToken, workspaceSid, channelId)](#apidoc.element.twilio.TaskRouterTaskQueueCapability.super_)
- description and source-code
```javascript
function TaskRouterCapability(accountSid, authToken, workspaceSid, channelId) {
    this.accountSid = accountSid;
    this.authToken = authToken;
    this.policies = [];

    this.workspaceSid = workspaceSid;
    this.channelId = channelId;

    this._baseUrl = taskRouterUrlBase + '/' + taskRouterVersion + '/Workspaces/' + this.workspaceSid;

    this._validateJWT();

    this._setupResource();

    var eventsUrl = eventUrlBase + '/' + this.accountSid + '/' + channelId;

    // add permissions to GET and POST to the event-bridge channel
    this.allow(eventsUrl, 'GET');
    this.allow(eventsUrl, 'POST');

    // add permission to fetch the instance resource
    this.allow(this._resourceUrl, 'GET');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.TaskRouterTaskQueueCapability.prototype"></a>[module twilio.TaskRouterTaskQueueCapability.prototype](#apidoc.module.twilio.TaskRouterTaskQueueCapability.prototype)

#### <a name="apidoc.element.twilio.TaskRouterTaskQueueCapability.prototype._setupResource"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterTaskQueueCapability.prototype.</span>_setupResource ()](#apidoc.element.twilio.TaskRouterTaskQueueCapability.prototype._setupResource)
- description and source-code
```javascript
_setupResource = function () {
    this._resourceUrl = this._baseUrl + '/TaskQueues/' + this.channelId;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.TaskRouterWorkerCapability"></a>[module twilio.TaskRouterWorkerCapability](#apidoc.module.twilio.TaskRouterWorkerCapability)

#### <a name="apidoc.element.twilio.TaskRouterWorkerCapability.TaskRouterWorkerCapability"></a>[function <span class="apidocSignatureSpan">twilio.</span>TaskRouterWorkerCapability (accountSid, authToken, workspaceSid, workerSid)](#apidoc.element.twilio.TaskRouterWorkerCapability.TaskRouterWorkerCapability)
- description and source-code
```javascript
function TaskRouterWorkerCapability(accountSid, authToken, workspaceSid, workerSid) {
    TaskRouterCapability.call(this, accountSid, authToken, workspaceSid, workerSid);

    this.reservationsUrl = this._baseUrl + "/Tasks/**";
    this.activityUrl = this._baseUrl + "/Activities";
    this.workerReservationsUrl = this._resourceUrl + "/Reservations/**";

    // add permissions fo fetch the list of activities, tasks and worker reservations
    this.allow(this.activityUrl, "GET");
    this.allow(this.reservationsUrl, "GET");
    this.allow(this.workerReservationsUrl, "GET");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterWorkerCapability.super_"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterWorkerCapability.</span>super_ (accountSid, authToken, workspaceSid, channelId)](#apidoc.element.twilio.TaskRouterWorkerCapability.super_)
- description and source-code
```javascript
function TaskRouterCapability(accountSid, authToken, workspaceSid, channelId) {
    this.accountSid = accountSid;
    this.authToken = authToken;
    this.policies = [];

    this.workspaceSid = workspaceSid;
    this.channelId = channelId;

    this._baseUrl = taskRouterUrlBase + '/' + taskRouterVersion + '/Workspaces/' + this.workspaceSid;

    this._validateJWT();

    this._setupResource();

    var eventsUrl = eventUrlBase + '/' + this.accountSid + '/' + channelId;

    // add permissions to GET and POST to the event-bridge channel
    this.allow(eventsUrl, 'GET');
    this.allow(eventsUrl, 'POST');

    // add permission to fetch the instance resource
    this.allow(this._resourceUrl, 'GET');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.TaskRouterWorkerCapability.prototype"></a>[module twilio.TaskRouterWorkerCapability.prototype](#apidoc.module.twilio.TaskRouterWorkerCapability.prototype)

#### <a name="apidoc.element.twilio.TaskRouterWorkerCapability.prototype._setupResource"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterWorkerCapability.prototype.</span>_setupResource ()](#apidoc.element.twilio.TaskRouterWorkerCapability.prototype._setupResource)
- description and source-code
```javascript
_setupResource = function () {
    this._resourceUrl = this._baseUrl + '/Workers/' + this.channelId;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterWorkerCapability.prototype.allowActivityUpdates"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterWorkerCapability.prototype.</span>allowActivityUpdates ()](#apidoc.element.twilio.TaskRouterWorkerCapability.prototype.allowActivityUpdates)
- description and source-code
```javascript
allowActivityUpdates = function () {
    this.allow(
        this._resourceUrl,
        "POST",
        {},
        {"ActivitySid": {'required': true}});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterWorkerCapability.prototype.allowReservationUpdates"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterWorkerCapability.prototype.</span>allowReservationUpdates ()](#apidoc.element.twilio.TaskRouterWorkerCapability.prototype.allowReservationUpdates)
- description and source-code
```javascript
allowReservationUpdates = function () {
    this.allow(
        this.reservationsUrl,
        "POST",
        {},
        {});
    this.allow(
        this.workerReservationsUrl,
        "POST",
        {},
        {});
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.TaskRouterWorkspaceCapability"></a>[module twilio.TaskRouterWorkspaceCapability](#apidoc.module.twilio.TaskRouterWorkspaceCapability)

#### <a name="apidoc.element.twilio.TaskRouterWorkspaceCapability.TaskRouterWorkspaceCapability"></a>[function <span class="apidocSignatureSpan">twilio.</span>TaskRouterWorkspaceCapability (accountSid, authToken, workspaceSid)](#apidoc.element.twilio.TaskRouterWorkspaceCapability.TaskRouterWorkspaceCapability)
- description and source-code
```javascript
function TaskRouterWorkspaceCapability(accountSid, authToken, workspaceSid) {
    TaskRouterCapability.call(this, accountSid, authToken, workspaceSid, workspaceSid);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TaskRouterWorkspaceCapability.super_"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterWorkspaceCapability.</span>super_ (accountSid, authToken, workspaceSid, channelId)](#apidoc.element.twilio.TaskRouterWorkspaceCapability.super_)
- description and source-code
```javascript
function TaskRouterCapability(accountSid, authToken, workspaceSid, channelId) {
    this.accountSid = accountSid;
    this.authToken = authToken;
    this.policies = [];

    this.workspaceSid = workspaceSid;
    this.channelId = channelId;

    this._baseUrl = taskRouterUrlBase + '/' + taskRouterVersion + '/Workspaces/' + this.workspaceSid;

    this._validateJWT();

    this._setupResource();

    var eventsUrl = eventUrlBase + '/' + this.accountSid + '/' + channelId;

    // add permissions to GET and POST to the event-bridge channel
    this.allow(eventsUrl, 'GET');
    this.allow(eventsUrl, 'POST');

    // add permission to fetch the instance resource
    this.allow(this._resourceUrl, 'GET');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.TaskRouterWorkspaceCapability.prototype"></a>[module twilio.TaskRouterWorkspaceCapability.prototype](#apidoc.module.twilio.TaskRouterWorkspaceCapability.prototype)

#### <a name="apidoc.element.twilio.TaskRouterWorkspaceCapability.prototype._setupResource"></a>[function <span class="apidocSignatureSpan">twilio.TaskRouterWorkspaceCapability.prototype.</span>_setupResource ()](#apidoc.element.twilio.TaskRouterWorkspaceCapability.prototype._setupResource)
- description and source-code
```javascript
_setupResource = function () {
    this._resourceUrl = this._baseUrl;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.TrunkingClient"></a>[module twilio.TrunkingClient](#apidoc.module.twilio.TrunkingClient)

#### <a name="apidoc.element.twilio.TrunkingClient.TrunkingClient"></a>[function <span class="apidocSignatureSpan">twilio.</span>TrunkingClient (sid, tkn, options)](#apidoc.element.twilio.TrunkingClient.TrunkingClient)
- description and source-code
```javascript
function TrunkingClient(sid, tkn, options) {
    options = options || {};
    TrunkingClient.super_.call(
        this, sid, tkn,
        options.host || 'trunking.twilio.com',
        options.apiVersion || 'v1',
        options.timeout
    );

    var trunkResource = require('./resources/trunking/Trunks')(this);
    this.trunks = trunkResource;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.twilio.TrunkingClient.super_"></a>[function <span class="apidocSignatureSpan">twilio.TrunkingClient.</span>super_ (sid, tkn, host, api_version, timeout)](#apidoc.element.twilio.TrunkingClient.super_)
- description and source-code
```javascript
function Client(sid, tkn, host, api_version, timeout) {
    //Required client config
    if (!sid || !tkn) {
        if (process.env.TWILIO_ACCOUNT_SID && process.env.TWILIO_AUTH_TOKEN) {
            this.accountSid = process.env.TWILIO_ACCOUNT_SID;
            this.authToken = process.env.TWILIO_AUTH_TOKEN;
        }
        else {
            throw 'Client requires an Account SID and Auth Token set explicitly ' +
                'or via the TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN environment variables';
        }
    }
    else {
        //if auth token/SID passed in manually, trim spaces
        this.accountSid = sid.replace(/ /g, '');
        this.authToken = tkn.replace(/ /g, '');
    }

    //Optional client config
    this.host = host || defaultHost;
    this.apiVersion = api_version || defaultApiVersion;
    this.timeout = timeout || 31000; // request timeout in milliseconds
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.utils"></a>[module twilio.utils](#apidoc.module.twilio.utils)

#### <a name="apidoc.element.twilio.utils.initializeTokens"></a>[function <span class="apidocSignatureSpan">twilio.utils.</span>initializeTokens (obj, type, sid, tkn)](#apidoc.element.twilio.utils.initializeTokens)
- description and source-code
```javascript
initializeTokens = function (obj, type, sid, tkn){
    // Initialize from environment variables, if present
    if (!sid || !tkn) {
        if (process.env.TWILIO_ACCOUNT_SID && process.env.TWILIO_AUTH_TOKEN) {
            obj.accountSid = process.env.TWILIO_ACCOUNT_SID;
            obj.authToken = process.env.TWILIO_AUTH_TOKEN;
        }
        else {
            throw type + ' requires an Account SID and Auth Token set explicitly ' +
                'or via the TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN environment variables';
        }
    }
    else {
        //if auth token/SID passed in manually, trim spaces
        obj.accountSid = sid.trim();
        obj.authToken = tkn.trim();
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.twilio.webhooks"></a>[module twilio.webhooks](#apidoc.module.twilio.webhooks)

#### <a name="apidoc.element.twilio.webhooks.validateExpressRequest"></a>[function <span class="apidocSignatureSpan">twilio.webhooks.</span>validateExpressRequest (request, authToken, opts)](#apidoc.element.twilio.webhooks.validateExpressRequest)
- description and source-code
```javascript
validateExpressRequest = function (request, authToken, opts) {
    var options = opts||{}, webhookUrl;
    if (options.url) {
        // Let the user specify the full URL
        webhookUrl = options.url;
    } else {
        // Use configured host/protocol, or infer based on request
        var protocol = options.protocol||request.protocol;
        var host = options.host||request.headers.host;
        webhookUrl = url.format({
            protocol: protocol,
            host: host,
            pathname: request.originalUrl
        });
    }

    return exports.validateRequest(
        authToken,
        request.header('X-Twilio-Signature'),
        webhookUrl,
        request.body||{}
    );
}
```
- example usage
```shell
...
    console.error('[Twilio]: Error - Twilio auth token is required for webhook request validation.');
    response
        .type('text/plain')
        .status(500)
        .send('Webhook Error - we attempted to validate this request without first configuring our auth token.');
} else {
    // Check that the request originated from Twilio
    valid = exports.validateExpressRequest(request, opts.authToken, {
        url: opts.url,
        host: opts.host,
        protocol: opts.protocol
    });
    if (valid) {
        next();
    } else {
...
```

#### <a name="apidoc.element.twilio.webhooks.validateRequest"></a>[function <span class="apidocSignatureSpan">twilio.webhooks.</span>validateRequest (authToken, twilioHeader, url, params)](#apidoc.element.twilio.webhooks.validateRequest)
- description and source-code
```javascript
validateRequest = function (authToken, twilioHeader, url, params) {
    Object.keys(params).sort().forEach(function(key, i) {
        url = url + key + params[key];
    });

    return scmp(twilioHeader, crypto.createHmac('sha1', authToken).update(new Buffer(url, 'utf-8')).digest('Base64'));
}
```
- example usage
```shell
...
        webhookUrl = url.format({
            protocol: protocol,
            host: host,
            pathname: request.originalUrl
        });
    }

    return exports.validateRequest(
        authToken,
        request.header('X-Twilio-Signature'),
        webhookUrl,
        request.body||{}
    );
};
...
```

#### <a name="apidoc.element.twilio.webhooks.webhook"></a>[function <span class="apidocSignatureSpan">twilio.webhooks.</span>webhook ()](#apidoc.element.twilio.webhooks.webhook)
- description and source-code
```javascript
webhook = function () {
    var opts = {
        validate:true,
        includeHelpers:true
    };

    // Process arguments
    var tokenString;
    for (var i = 0, l = arguments.length; i<l; i++) {
        var arg = arguments[i];
        if (typeof arg === 'string') {
            tokenString = arg;
        } else {
            opts = _.extend(opts, arg);
        }
    }

    // set auth token from input or environment variable
    opts.authToken = tokenString ? tokenString : process.env.TWILIO_AUTH_TOKEN;

    // Create middleware function
    return function hook(request, response, next) {
        // Add helpers, unless disabled
        if (opts.includeHelpers) {
            var oldSend = response.send;
            response.send = function() {
                // This is a special TwiML-aware version of send.  If we detect
                // A twiml response object, we'll set the content-type and
                // automatically call .toString()
                if (arguments.length == 1 && arguments[0].legalNodes) {
                    response.type('text/xml');
                    oldSend.call(response,arguments[0].toString());
                } else {
                    // Continue with old version of send
                    oldSend.apply(response,arguments);
                }
            };
        }

        // Do validation if requested
        if (opts.validate) {
            // Check for a valid auth token
            if (!opts.authToken) {
                console.error('[Twilio]: Error - Twilio auth token is required for webhook request validation.');
                response
                    .type('text/plain')
                    .status(500)
                    .send('Webhook Error - we attempted to validate this request without first configuring our auth token.');
            } else {
                // Check that the request originated from Twilio
                valid = exports.validateExpressRequest(request, opts.authToken, {
                    url: opts.url,
                    host: opts.host,
                    protocol: opts.protocol
                });
                if (valid) {
                    next();
                } else {
                    return response
                        .type('text/plain')
                        .status(403)
                        .send('Twilio Request Validation Failed.');
                }
            }
        } else {
            next();
        }
    };
}
```
- example usage
```shell
...
for XML (TwiML) rendering.  Default true.
- host: manually specify the host name used by Twilio in a number's webhook config
- protocol: manually specify the protocol used by Twilio in a number's webhook config

Returns a middleware function.

Examples:
var webhookMiddleware = twilio.webhook();
var webhookMiddleware = twilio.webhook('asdha9dhjasd'); //init with auth token
var webhookMiddleware = twilio.webhook({
validate:false // don't attempt request validation
});
var webhookMiddleware = twilio.webhook({
host: 'hook.twilio.com',
protocol: 'https'
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
