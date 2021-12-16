# Base_64_encoding<br />
**Created Date:** 9/29/2008<br />
**Last Updated:** 10/11/2010<br />
**Description:** Functions to encode ascii text to base64. Based upon code submitted to Synergy-l by Nigel White. (Update for Synergy 9.5 compatibility)<br />
**Platforms:** Windows; Unix; OpenVMS<br />
**Products:** Synergy DBL<br />
**Minimum Version:** 8.1<br />
**Author:** Tod Phillips
<hr>

**Additional Information:**
Descriptions
------------

BASE64.DBL
This code for the BASE64 conversion was created by Tod Phillips (January 22nd 2009). It accepts the same
parameters as the Synergy-l BASE64 submission by Nigel White (August 17th 2008), plus optional parameters
to force MIME-style encoding of the returned Base64 string (used in SMTP routines in which a CRLF is required
after every 76th character). William Hawkins has also contributed to the code by adding Synergy v9 parameter
syntax.
