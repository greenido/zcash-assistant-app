# Actions on Google - Zcash Info

This assistant app will give you details on Zcash.
For example: 
* Price.
* Market cap.
* Volume in the last 24h.


![zcash logo](https://lh5.googleusercontent.com/YuCzUMnzjLaj9gJMdOmpVPwEe01x1_z7vHul47d_x57P-6uL_kWQsLczmL5Aj_j_wgVRtZ0qa0lQeaAzde58M19pKXK81cIMyGOZ3HMZa7eNSlC3X3OZ=w1175)

## Setup Instructions

### Pre-requisites
 1. API.AI account: [https://api.ai](https://api.ai)
 2. Google Cloud project: [https://console.cloud.google.com/project](https://console.cloud.google.com/project)

See the developer guide and release notes at [https://developers.google.com/actions/](https://developers.google.com/actions/) for more details.

### Steps
1. Create a new agent in API.AI [https://api.ai](https://api.ai). You can also take this repo as a zip and import it to API.AI
2. Deploy this action to your preferred hosting environment
 (we recommend [Google Cloud Functions](https://cloud.google.com/functions/docs/tutorials/http)).
3. Set the "Fulfillment" webhook URL to the hosting URL.
4. In any relevant intents (*price* and *total*), enable the Fulfillment for the response.
5. Build out your agent and business logic by adding function handlers for API.AI actions.
6. For each API.AI action, and set the intent in the  **zcash.php** in case you wish to add/edit them.
1. Make sure all domains are turned off.
1. Enable Actions on Google in the Integrations.
1. Provide an invocation name for the action.
1. Authorize and preview the action in the [web simulator](https://developers.google.com/actions/tools/web-simulator).

For more detailed information on deployment, see the [documentation](https://developers.google.com/actions/samples/).

## References and How to report bugs
* Actions on Google documentation: [https://developers.google.com/actions/](https://developers.google.com/actions/).
* If you find any issues, please open a bug here on GitHub.
* Questions are answered on [StackOverflow](https://stackoverflow.com/questions/tagged/actions-on-google).

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md.

## License
See LICENSE.md.

## Terms
Your use of this sample is subject to, and by using or downloading the sample files you agree to comply with, the [Google APIs Terms of Service](https://developers.google.com/terms/).

## Google+
Actions on Google Developers Community on Google+ [https://g.co/actionsdev](https://g.co/actionsdev).
