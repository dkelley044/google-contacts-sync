Google Contacts Sync
====================

This is a small tool which helps you to sync and merge your Google contacts.
Edits: Updated to support oauth2, also fixes for syncing google contacts with users who also use outlook with google apps sync( brings some fun extended attributes from outlook and/or people that have a google plus account linked via email address... google has failed to define a ns3 namespace in teir default xml definitions so it will fail with fun errors like:
File "/usr/local/lib/python2.7/dist-packages/atom/core.py", line 520, in parse
    tree = ElementTree.fromstring(xml_string)
  File "<string>", line 106, in XML
cElementTree.ParseError: unbound prefix: line 667, column 2839
more to come.... filest to be uploaded soon.
would appreciate any help in fine tuning the oauth2 to be more automatic, and/or someone writing a guid and a fork to support domain wide authentication.
and also need to find a way to sync contact photos....

