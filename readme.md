Web Security Headers
======================

> A response headers config demo which follow OWASP HTTP Security HEADERS spec.


### Category

1. HTTP STRICT TRANSPORT SECURITY(HSTS)
2. X-FRAME-OPTIONS
3. EXPECT-CT
4. CONTENT-SECURITY-POLICY
   ```
   Content-Security-Policy - Directives
    Keywords:
    *
    , none, self, hosts
    Content-Security-Policy:
    default-src Serves as a fallback for the other fetch directives
    font-src Specifies valid sources for fonts loaded
    frame-src Sources for nested contexts such as <frame> and <iframe>
    img-src Sources of images and favicons
    media-src Valid sources for loading <audio>, <video> & <track>
    object-src Sources for the <object>, <embed> and <applet> elements
    script-src Specifies valid sources for JavaScript
    style-src Specifies valid sources for stylesheets
    report-uri Reports violations
   ```
5. X-XSS-PROTECTION
6. X-CONTENT-TYPEOPTIONS
7. Feature-Policy https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Feature-Policy
8. X-Permitted-Cross-Domain-Policies 
9. Referrer-Policy
10. X-Download-Options:  The X-Download-Options is specific to IE 8, and is related to how IE 8 handles downloaded HTML files. Turns out if you download an HTML file from a web page and chooses to "Open" it in IE, it will execute in the context of the web site.

### tools

Check Website HTTP Response Header
– https://gf.dev/http-headers-test Secure Headers Test
– https://gf.dev/secure-headers-test Scott Helme – Security Header Scanner
– https://securityheaders.com HTTP Headers Reference
– https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers HTTP Compatibility Among Browsers
– https://caniuse.com