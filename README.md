# ecce-root-style

ECCE ROOT style, based on sPHENIX, adapted from ATLAS Style

Add these two files anywhere in your ROOT macro path (usually set in your <tt>~.rootrc</tt>), and add this to your <tt>.rootlogon.C</tt>:

<pre>
gROOT->LoadMacro("ECCEStyle.C");
SetECCEStyle();
<pre>
