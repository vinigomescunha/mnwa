# mnwa
http://mnwa.cf config CNAME

https://help.github.com/articles/tips-for-configuring-an-a-record-with-your-dns-provider/

With your DNS provider, create A records that resolve to the following IP addresses:

192.30.252.153
192.30.252.154

To confirm that your A records have been set correctly, use the dig command:

dig example.com +nostats +nocomments +nocmd
;example.com
example.com.   73  IN  A 192.30.252.153
example.com.   73  IN  A 192.30.252.154

Domain in freenom
