Seesmic-AS3-XMPP is an all new XMPP 1.0 compliant library for Flash 9+. It features an easy to understand event-driven style, starttls support (using a modified Hurlant TLS lib), and a plugin based architecture for easy extending.

We encourage you to use this with the Seesmic XMPP API.

### About the Author ###
Nathan Fritz wrote and currently maintains this lib under the employ of Seesmic.  He is known for other XMPP libs such as XMPPHP and SleekXMPP.

### Howto (in Flex Builder) ###

1. Install Subclipse

> Help -> Software Updates -> Find and Install -> Search for new features to install -> Subclipse

2. Create new project for hurlant\_tls, seesmic-as3-xmpp, and demo.

> File -> New -> Other -> SVN -> http://seesmic-as3-xmpp.googlecode.com/svn/trunk/seesmic-as3-xmpp<br />
> File -> New -> Other -> SVN -> http://seesmic-as3-xmpp.googlecode.com/svn/trunk/hurlant_tls<br />
> File -> New -> Other -> SVN -> http://seesmic-as3-xmpp.googlecode.com/svn/trunk/demo<br />

3. Link hurlant and seesmic-as3-xmpp libraries to the demo.

> Right click demo -> Properties -> Flex Build Path -> Library Path -> Add Project -> seesmic-as3-xmpp<br />
> Add Project -> hurlant\_tls<br />

4. Run the demo.

> Highlight Flex Navigator -> demo -> src -> main.mxml<br />
> Press F11.<br />
> Set your Jabber ID: user@server.tld (you can include a resource)<br />
> Set your password.<br />
> Set your server (if different from JID). For Google Talk, use talk.google.com<br />
> Click Connect.