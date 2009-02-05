Seesmic-AS3-XMPP is an all new XMPP 1.0 compliant library for Flash 9+. It features an easy to understand event-driven style, starttls support (using a modified Hurlant TLS lib), and a plugin based architecture for easy extending.

We encourage you to use this with the Seesmic XMPP API.
Howto (in Flex Builder)

1. Install Subclipse

    Help -> Software Updates -> Find and Install -> Search for new features to install -> Subclipse 

2. Create new project for hurlant_tls, seesmic-as3-xmpp, and demo.

    File -> New -> Other -> SVN -> http://seesmic-as3-xmpp.googlecode.com/svn/trunk/seesmic-as3-xmpp
    File -> New -> Other -> SVN -> http://seesmic-as3-xmpp.googlecode.com/svn/trunk/hurlant_tls
    File -> New -> Other -> SVN -> http://seesmic-as3-xmpp.googlecode.com/svn/trunk/demo

3. Link hurlant and seesmic-as3-xmpp libraries to the demo.

    Right click demo -> Properties -> Flex Build Path -> Library Path -> Add Project -> seesmic-as3-xmpp
    Add Project -> hurlant_tls

4. Run the demo.

    Highlight Flex Navigator -> demo -> src -> demo.mxml
    Press F11.
    Set your Jabber ID: user@server.tld (you can include a resource)
    Set your password.
    Set your server (if different from JID). For Google Talk, use talk.google.com
    Click Connect.
