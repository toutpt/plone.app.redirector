'''Proposer:''' Jean-Michel FRANCOIS (toutpt) [[BR]]
[[BR]]
== Motivation ==
plone.app.redirector provide redirection triggered on 404. 

I want to provide a UI over the redirections database. 

Uses cases are:

* import / export of redirections throw a controlpanel
* create, remove, update of a redirection
* browse redirections with a filter

== Assumptions ==
Redirections are managed in a controlpanel.

Redirections are not alias (confusion is made in Products.RedirectionTool). An alias is a real URL (content) not a redirection.

== Proposal & Implementation ==

A new controlpanel must be added to cover all uses cases. Mock ups will be released soon

== Deliverables ==

A new version of plone.app.controlpanel and plone.app.redirector

== Risks ==
I don't see any risks here, no need to migrate data (only register a new controlpanel)

== Participants ==
JeanMichel FRANCOIS (toutpt)


== Progress ==

I have done a first work of backporting Products.RedirectionControlPanel in https://github.com/toutpt/plone.app.redirector/tree/toutpt-addui but this code should be moved to plone.app.controlpanel. 


