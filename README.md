# Update the presence of a Genesys Cloud user based upon the answer of a Communicate call

This Genesys Cloud Developer Blueprint explains how to set up Genesys Cloud to update a Genesys Cloud user's presence when the user answers an inbound GC Communicate (non-ACD or PBX) call.

When an Architect workflow receives a communicate call trigger, a Genesys Cloud Public API call is made to update the presence of the Genesys Cloud users on the Communicate call when someone answers the Communicate Call.

![Inbound Communicate Call Genesys Cloud user presence flow](blueprint/images/inbound-communicate-call-gc-presence-workflow.png "Genesys Cloud presence update from an inbound Communicate call")

![Outbound Communicate Call Genesys Cloud user presence flow](blueprint/images/outbound-communicate-call-gc-presence-workflow.png "Genesys Cloud presence update from an outbound Communicate call")

The following shows the end-to-end user experience that this solution enables.

![End-to-end user experience](blueprint/images/GCPresenceUpdateonCommunicateCall.gif "End-to-end user experience")
