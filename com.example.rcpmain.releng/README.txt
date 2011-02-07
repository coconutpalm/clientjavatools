Status:
=======

Update code was easy enough to find.
There's now an example in Application.java showing how to specify p2 repos.

Questions: 
* How to specify create/remove install sites?
* How do IFeatureReferences map to IInstallableUnits?
* How does P2 handle nested features that may be scattered across multiple p2 repos.
* If someone gives you a list of RCP Features/versions to provision, how do you convert that into IInstallOperations?


Self-updating P2 app documentation can be found at:
---------------------------------------------------

Good-->http://www.ralfebert.de/blog/eclipsercp/p2_updates_tutorial_36/<--Good

http://www.slideshare.net/PascalRapicault/discovering-the-p2-api <<== See Slide 25 here

http://wiki.eclipse.org/Equinox/p2/Adding_Self-Update_to_an_RCP_Application#Headless_Updating_on_Startup

http://www.slideshare.net/susanfmccourt/simplifying-rcp-update-and-install

http://www.google.com/search?sourceid=chrome&ie=UTF-8&q=p2+operations+api

http://www.slideshare.net/kartben/p2-the-new-eclipse-provisioning-system-presentation

http://wiki.eclipse.org/Equinox/p2/Customizing_Metadata


Related to the work we'd like to do at Eclipse:
-----------------------------------------------

https://bugs.eclipse.org/bugs/show_bug.cgi?id=281226

