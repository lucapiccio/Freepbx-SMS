# Freepbx-SMS
Configuration for enabling SMS on Freepbx Asterisk

In "Settings - Advanced Settings" to enable modern pjsip and old sip protocol set:
SIP Channel Driver = both

In "Settings - Asterisk SIP Settings - SIP Legacy Settings" add at bottom the follow "Other SIP settings":
accept_outofcall_message = yes
outofcall_message_context = astsms
auth_message_requests = yes
