# Unified Naming Convention
aka UNC, is an organization between executor developers to provide a unified scripting API for our scripters.

Join The Discord To Know When The UNC Script Is Updated! https://discord.gg/a5fKH43Hbm
## UNC Has Returned

Who would've thought That Unified Naming Convention Would Return We did not And The reason why we returned is because of the new Owner dcooke072711

He will Be taking Over Unified Naming Convention And Adding Functions For the New Unified Naming Convention Test

I Hope Yall Enjoy The New Owner.

## Why?
Over the years scripting has gotten more and more complex to support multiple executors. This is because of the many unique naming conventions various executors use.

Consider the following scenario. You want to know if a function belongs to the executor or not. In order for this code to be cross compatiable with all executors code like this is needed:
```lua
local is_executor_closure = is_syn_closure or is_fluxus_closure or is_sentinel_closure or is_krnl_closure or is_proto_closure or is_calamari_closure or is_electron_closure or is_elysian_closure
```
This is reality for scripters who want cross compatibilty in their scripts. Scripters shouldn't have to do such laborous work just to attain cross compatability. The UNC seeks to solve this problem using naming conventions everyone agrees upon and follows.

One variant of a script should naturally work on all script executors which have their environment properly fitted to the UNC. 

## How?
The UNC provides standards for naming conventions as well as API functionality. The standard is written in markdown on this GitHub. Edits or additions are done through pull requests. Edits and additions are manually approved by the UNC council and discussed by everyone.

## Supporting UNC
As a product owner, your support of UNC by following the API will result in a far smoother experience for scripters, as they are able to work on scripts that they can confidently say will work on **most** products. Once you have implemented UNC's API, you can display so by adding the badge to your website, thread or application.


This will notify people of your alliance in providing scripters with an easier method of engineering scripts that your consumers can enjoy.

NOTICE: If you, as a product owner, do not have all of these functions but yet support the ones you do - you then support UNC! You are more than able to display the badge on your website.

## Checking your environment

You can run the UNC environment checking script to see how well your executor environment supports the UNC standard. Find the script [here.](UNCCheckEnv.lua) The script determines what is missing, and writes the results to file under workspace.

## Contributing
Go [here](CONTRIBUTING.md) for a guide on contributing.
