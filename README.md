# parsekit

## Notes

```
POST https://sendgrid.com/developer/reply
Content-Type: application/x-www-form-urlencoded
reply_option[hostname]:dude.com
reply_option[url]:http://test.com/somewhere
Cookie:sf_details=eyJtYyI6IkRpcmVjdCIsIm1jZCI6Imh0dHBzOi8vZ2l0aHViLmNvbS9zY290dG1vdHRlL3dyaXRpbmdzL2Jsb2IvbWFzdGVyL2FydGljbGVzL2Jvb2ttYXJrcy5tZCIsImdhaWQiOm51bGwsImt3IjpudWxsfQ%3D%3D; _sendgrid_rails_session=BAh7B0kiD3Nlc3Npb25faWQGOgZFRkkiJTNjMTdlOGJkODNhNGViNmIzNzA3MTIxOTEyMjYyODMzBjsAVEkiEF9jc3JmX3Rva2VuBjsARkkiMVAyUndINmsxTlF6bUJlcWMzSlpLampYcWNCeFRFUXIzSGk2ekV2LzMvNjA9BjsARg%3D%3D--6ba1147d7e6200d8d94d99c6471a1d3e1462d6e7; optimizelyEndUserId=oeu1407917278505r0.042970029870048165; km_ai=viF0XyHm6wpUtaZazGvEgohxQD0%3D; _br_uid_1=uid%3D6259234871250; __qca=P0-19877498-1407917656338; __csess=1407919182503.5KDLZP.; cvo_sid1=QDSQCJBTP7CA; __cdrop=.FP7M4U.; cvo_tid1=B4nn7ZGC9dg|1407917681|1407917991|0; km_lv=x; _br_uid_2=uid%3D6259234871250%3Av%3D11.5%3Ats%3D1407917280796%3Ahc%3D27; recently_viewed=%7B%22user%22%3A%7B%22username%22%3A%22arango-pluma%22%2C%22id%22%3A1385065%7D%7D%7C%7C%7B%22user%22%3A%7B%22username%22%3A%22pawpad%22%2C%22id%22%3A823186%7D%7D; __utma=43679271.1630871015.1407917280.1408725315.1408728150.3; __utmc=43679271; __utmz=43679271.1407918573.1.1.utmcsr=(direct)|utmccn=(direct)|utmcmd=(none); _session_id=fea3bcb3b50909888189125defcd589e; km_uq=; is_returning=1; optimizelySegments=%7B%22174319933%22%3A%22gc%22%2C%22174357559%22%3A%22referral%22%2C%22174489618%22%3A%22false%22%7D; optimizelyBuckets=%7B%221784422616%22%3A%221775252721%22%7D; sendgrid_frontend=117a1d12377983e9cdce1d44a742d5b0:d0a41d3338e3c6002805b51eac80797854ee4144; SnapABugRef=https%3A%2F%2Fsendgrid.com%2Faccount%2Foverview%20https%3A%2F%2Fsendgrid.com%2Fmarketing%2Flogin; SnapABugHistory=1#; SnapABugVisit=6#1408750645; cvo_sid1=QDSQCJBTP7CA; _ga=GA1.2.1630871015.1407917280; totango.heartbeat.last_module=Developer; totango.heartbeat.last_ts=1408750703486; _mkto_trk=id:467-KXI-123&token:_mch-sendgrid.com-1407917279772-57567; __ar_v4=CHIIL5P3SNCFHKCJWGFWUB%3A20140821%3A4%7CN27AJKSVQNGTFIUBGCE3YJ%3A20140821%3A1%7CZVEDT7DG35H77DAZW5W7GG%3A20140821%3A2%7CL7VY5F545RFKRLXP6B6OFA%3A20140814%3A6%7CLQ62LOLKIBCYLEUQIZTCIJ%3A20140812%3A4%7CHWYX4RR7EJEBJIW3P4RQ6W%3A20140812%3A24%7CSYFMXPWDD5BYNDV7PHXGWZ%3A20140812%3A24%7CHIRPMHJSV5GQJGPYENED3A%3A20140812%3A4%7CSBOYNCQOLNHFRAETDK23SX%3A20140812%3A1%7CIPUCGKLPE5CMDLJFIZFNMD%3A20140820%3A1%7CKTMMLJNTUZBSRBE3N225DW%3A20140821%3A1; cvo_tid1=B4nn7ZGC9dg|1407917681|1408750704|0; kvcd=1408750704830; km_vs=1; _gali=reply-add
```

```
curl -X POST --cookie "COOKIEHERE" https://sendgrid.com/developer/reply -d "reply_option[hostname]=dude.com" -d "reply_option[url]=http://test.com/somewhere"
curl -X POST --cookie "sendgrid_frontend=0b0bsomedata02ec158ba48bc11a190fec0ca220c24b82bb16c8" https://sendgrid.com/developer/reply -d "reply_option[hostname]=dude.com" -d "reply_option[url]=http://test.com/somewhere"
```

```
curl -X POST https://sendgrid.com/login -d "login[username]=login" -d "login[password]=pass" -v
```

```
sendgrid_frontend=somecookie:02ec158ba48bc11a190fec0ca220c24b82bb16c8; expires=Sun, 21-Sep-2014 23:49:49 GMT; path=/; secure; httponly
```
