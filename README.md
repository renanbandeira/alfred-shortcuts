# alfred-shortcuts
Repositório simples com alguns atalhos úteis do Alfred. 
 
Have fun!!! 
To use it, basically copy and paste the following commands in alfred's search field. 


## Open jira issue: 
```
alfred://customsearch/search%20jira%20for%20%22%7Bquery%7D%22/jira/utf8/noplus/https://jira.greenmile.com/browse/{query}
```

## Open wiki greenmile
```
alfred://customsearch/Search%20Wiki%20GM%20For%20%27%7Bquery%7D%27/wiki/utf8/plus/http://wiki.greenmile.com/dosearchsite.action?queryString={query}
```

## Search in Gmail: first account (0)
```
alfred://customsearch/Search%20Mail%20Sagarana%20For%20%27%7Bquery%7D%27/gmail/utf8/plus/https://mail.google.com/mail/u/0/#search/{query})
```

## Search salesforce 
```
alfred://customsearch/Search%20Salesforce%20for%20%27%7Bquery%7D%27/sf/utf8/noplus/https://na11.salesforce.com/_ui/search/ui/UnifiedSearchResults?searchType=2&sen=00a&sen=001&sen=003&sen=00T&sen=500&sen=00U&sen=005&sen=800&sen=00O&str={query})
```

## Search docs greenmile

```
alfred://customsearch/Search%20Docs%20For%20%27%7Bquery%7D%27/docs/utf8/noplus/http://docs.greenmile.com/dosearchsite.action?queryString={query})
```

## Open project in Githug greenmile
```
alfred://customsearch/Open%20Git%20Project%20%27%7Bquery%7D%27/git/utf8/noplus/https://github.com/greenmilellc-org/{query})
```

## Create QR Code
```
alfred://customsearch/Create%20QR%20Code%20For%20%27%7Bquery%7D%27/qrcode/utf8/noplus/https://api.qrserver.com/v1/create-qr-code/?data={query})
```

## Create QR Code For http://{query}.greenmile.com
```
alfred://customsearch/Create%20QR%20Code%20For%20GreenMile%20on%20%27%7Bquery%7D%27/qrcode%20gm/utf8/noplus/https://api.qrserver.com/v1/create-qr-code/?data=http%3A%2F%2F{query}.greenmile.com)
```

## Query on Jira considering the Salesforce case number ql=case in crmRecords("{query}")
```
alfred://customsearch/Jira%20Salesforce%20For%20%7Bquery%7D/jirasf/utf8/%2B/https%3A%2F%2Fjira.greenmile.com%2Fissues%2F%3Fjql%3Dcase%20in%20crmRecords%28%22%7Bquery%7D%22%29
```
