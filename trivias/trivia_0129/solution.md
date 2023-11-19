# Solution

**D**

base64.urlsafe_b64encode() is similar to base64.b64decode() as it encode a bytes-like object or ASCII string into base64. The difference however is that the resulting encoded object will be a Base64URL one instead of Base64. Base64URL use a different set of character and padding method which, unlike Base64, is safe for data encoded in URLs, query parameters or path segments.
