SipUnit
-------

* SipUnit 2.0.0 is out !

The following are the highlights of the release. Thanks to George Vagenas for his recent major contributions to SipUnit and also to S. Pitucha for contributing patches.

  * MESSAGE handling has been added, including support for authentication and MESSAGE with or without an existing dialog.
  * JUnit 4 support was added with static assertions in new SipAssert class.
  * SipUnit is now mavenized!
  * Convenience methods were added to get the contact URI as javax.sip.address.URI from SipContact, the call ID from SipCall, and retransmission count from SipStack. Also, support was added for deregistration using wildcard Contact Header and a new waitForAuthorisation() method for when the far end should send 401 or 407.
  * TLS support has been verified.
  * JAIN SIP stack was updated.

### Get the latest release either as a [http://sourceforge.net/projects/mobicents/files/Mobicents%20SipUnit/ binary] or [https://oss.sonatype.org/content/groups/public/org/cafesip/sipunit/sipunit/2.0.0/ Maven dependency]

For SipUnit history/archive information please visit http://cafesip.sourceforge.net/site/projects/sipunit/
