# Update the presence of a Genesys Cloud user based upon an incoming Communicate Call

This Genesys Cloud Developer Blueprint explains how to set up Genesys Cloud to update a Genesys Cloud user's presence the user receives an inbound GC Communicate (non-ACD or PBX) call.

When an Architect workflow receives a communicate call trigger, a Genesys Cloud Public API call is made to update the presence of the Genesys Cloud user receiving the Communicate call.

![Inbound Communicate Call Genesys Cloud user presence flow](blueprint/images/inbound-communicate-call-gc-presence-workflow.png "Genesys Cloud presence update from an inbound Communicate call")

![Outbound Communicate Call Genesys Cloud user presence flow](blueprint/images/outbound-communicate-call-gc-presence-workflow.png "Genesys Cloud presence update from an outbound Communicate call")

The following shows the end-to-end user experience that this solution enables.

![End-to-end user experience](blueprint/images/GCtoMSTeamsPresenceUpdatesbasedonGCPresenceChanges.gif "End-to-end user experience")
