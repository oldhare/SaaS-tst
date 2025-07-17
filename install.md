PS D:\Visual Studio\SaaS\SaaS-Foundations> python -m venv venv
PS D:\Visual Studio\SaaS\SaaS-Foundations> .\venv\Scripts\activate
(venv) PS D:\Visual Studio\SaaS\SaaS-Foundations> # with venv activated
(venv) PS D:\Visual Studio\SaaS\SaaS-Foundations> pip install pip --upgrade && pip install -r requirements.txt
строка:1 знак:27
+ pip install pip --upgrade && pip install -r requirements.txt
+                           ~~
Лексема "&&" не является допустимым разделителем операторов в этой версии.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException       
    + FullyQualifiedErrorId : InvalidEndOfLine

(venv) PS D:\Visual Studio\SaaS\SaaS-Foundations>  pip install -r requirements.txt          
Collecting Django<5.1,>=5.0 (from -r requirements.txt (line 1))
  Downloading Django-5.0.14-py3-none-any.whl.metadata (4.1 kB)
Collecting gunicorn (from -r requirements.txt (line 2))
  Downloading gunicorn-23.0.0-py3-none-any.whl.metadata (4.4 kB)
Collecting python-decouple (from -r requirements.txt (line 3))
  Downloading python_decouple-3.8-py3-none-any.whl.metadata (14 kB)
Collecting dj-database-url (from -r requirements.txt (line 5))
  Downloading dj_database_url-3.0.1-py3-none-any.whl.metadata (14 kB)
Collecting requests (from -r requirements.txt (line 6))
  Downloading requests-2.32.4-py3-none-any.whl.metadata (4.9 kB)
Collecting whitenoise (from -r requirements.txt (line 7))
  Downloading whitenoise-6.9.0-py3-none-any.whl.metadata (3.6 kB)
Collecting django-allauth-ui (from -r requirements.txt (line 9))
  Downloading django_allauth_ui-1.8.1-py3-none-any.whl.metadata (4.2 kB)
Collecting django-widget-tweaks (from -r requirements.txt (line 10))
  Downloading django_widget_tweaks-1.5.0-py3-none-any.whl.metadata (13 kB)
Collecting stripe (from -r requirements.txt (line 11))
  Downloading stripe-12.3.0-py2.py3-none-any.whl.metadata (2.9 kB)
Collecting psycopg[binary] (from -r requirements.txt (line 4))
  Downloading psycopg-3.2.9-py3-none-any.whl.metadata (4.5 kB)
Collecting django-allauth[socialaccount] (from -r requirements.txt (line 8))
  Downloading django_allauth-65.10.0.tar.gz (1.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.9/1.9 MB 1.1 MB/s eta 0:00:00
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting asgiref<4,>=3.7.0 (from Django<5.1,>=5.0->-r requirements.txt (line 1))
  Downloading asgiref-3.9.1-py3-none-any.whl.metadata (9.3 kB)
Collecting sqlparse>=0.3.1 (from Django<5.1,>=5.0->-r requirements.txt (line 1))
  Downloading sqlparse-0.5.3-py3-none-any.whl.metadata (3.9 kB)
Collecting tzdata (from Django<5.1,>=5.0->-r requirements.txt (line 1))
  Downloading tzdata-2025.2-py2.py3-none-any.whl.metadata (1.4 kB)
Collecting packaging (from gunicorn->-r requirements.txt (line 2))
  Using cached packaging-25.0-py3-none-any.whl.metadata (3.3 kB)
Collecting psycopg-binary==3.2.9 (from psycopg[binary]->-r requirements.txt (line 4))
  Downloading psycopg_binary-3.2.9-cp313-cp313-win_amd64.whl.metadata (3.0 kB)
Collecting charset_normalizer<4,>=2 (from requests->-r requirements.txt (line 6))
  Downloading charset_normalizer-3.4.2-cp313-cp313-win_amd64.whl.metadata (36 kB)
Collecting idna<4,>=2.5 (from requests->-r requirements.txt (line 6))
  Downloading idna-3.10-py3-none-any.whl.metadata (10 kB)
Collecting urllib3<3,>=1.21.1 (from requests->-r requirements.txt (line 6))
  Downloading urllib3-2.5.0-py3-none-any.whl.metadata (6.5 kB)
Collecting certifi>=2017.4.17 (from requests->-r requirements.txt (line 6))
  Downloading certifi-2025.7.14-py3-none-any.whl.metadata (2.4 kB)
Collecting oauthlib<4,>=3.3.0 (from django-allauth[socialaccount]->-r requirements.txt (line 8))
  Downloading oauthlib-3.3.1-py3-none-any.whl.metadata (7.9 kB)
Collecting pyjwt<3,>=2.0 (from pyjwt[crypto]<3,>=2.0; extra == "socialaccount"->django-allauth[socialaccount]->-r requirements.txt (line 8))
  Downloading PyJWT-2.10.1-py3-none-any.whl.metadata (4.0 kB)
Collecting cryptography>=3.4.0 (from pyjwt[crypto]<3,>=2.0; extra == "socialaccount"->django-allauth[socialaccount]->-r requirements.txt (line 8))
  Downloading cryptography-45.0.5-cp311-abi3-win_amd64.whl.metadata (5.7 kB)
Collecting slippers<0.7.0,>=0.6.2 (from django-allauth-ui->-r requirements.txt (line 9))
  Downloading slippers-0.6.2-py3-none-any.whl.metadata (3.2 kB)
Collecting PyYAML>=5.4.0 (from slippers<0.7.0,>=0.6.2->django-allauth-ui->-r requirements.txt (line 9))
  Downloading PyYAML-6.0.2-cp313-cp313-win_amd64.whl.metadata (2.1 kB)
Collecting typeguard<3.0.0,>=2.13.3 (from slippers<0.7.0,>=0.6.2->django-allauth-ui->-r requirements.txt (line 9))
  Downloading typeguard-2.13.3-py3-none-any.whl.metadata (3.6 kB)
Collecting typing-extensions>=4.4.0 (from slippers<0.7.0,>=0.6.2->django-allauth-ui->-r requirements.txt (line 9))
  Downloading typing_extensions-4.14.1-py3-none-any.whl.metadata (3.0 kB)
Collecting cffi>=1.14 (from cryptography>=3.4.0->pyjwt[crypto]<3,>=2.0; extra == "socialaccount"->django-allauth[socialaccount]->-r requirements.txt (line 8))
  Downloading cffi-1.17.1-cp313-cp313-win_amd64.whl.metadata (1.6 kB)
Collecting pycparser (from cffi>=1.14->cryptography>=3.4.0->pyjwt[crypto]<3,>=2.0; extra == "socialaccount"->django-allauth[socialaccount]->-r requirements.txt (line 8))
  Downloading pycparser-2.22-py3-none-any.whl.metadata (943 bytes)
Downloading Django-5.0.14-py3-none-any.whl (8.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.2/8.2 MB 1.1 MB/s eta 0:00:00
Downloading asgiref-3.9.1-py3-none-any.whl (23 kB)
Downloading gunicorn-23.0.0-py3-none-any.whl (85 kB)
Downloading python_decouple-3.8-py3-none-any.whl (9.9 kB)
Downloading psycopg-3.2.9-py3-none-any.whl (202 kB)
Downloading psycopg_binary-3.2.9-cp313-cp313-win_amd64.whl (2.9 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.9/2.9 MB 916.6 kB/s eta 0:00:00
Downloading dj_database_url-3.0.1-py3-none-any.whl (8.8 kB)
Downloading requests-2.32.4-py3-none-any.whl (64 kB)
Downloading charset_normalizer-3.4.2-cp313-cp313-win_amd64.whl (105 kB)
Downloading idna-3.10-py3-none-any.whl (70 kB)
Downloading urllib3-2.5.0-py3-none-any.whl (129 kB)
Downloading whitenoise-6.9.0-py3-none-any.whl (20 kB)
Downloading oauthlib-3.3.1-py3-none-any.whl (160 kB)
Downloading PyJWT-2.10.1-py3-none-any.whl (22 kB)
Downloading django_allauth_ui-1.8.1-py3-none-any.whl (68 kB)
Downloading django_widget_tweaks-1.5.0-py3-none-any.whl (9.0 kB)
Downloading slippers-0.6.2-py3-none-any.whl (61 kB)
Downloading typeguard-2.13.3-py3-none-any.whl (17 kB)
Downloading stripe-12.3.0-py2.py3-none-any.whl (1.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.6/1.6 MB 1.1 MB/s eta 0:00:00
Downloading certifi-2025.7.14-py3-none-any.whl (162 kB)
Downloading cryptography-45.0.5-cp311-abi3-win_amd64.whl (3.4 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.4/3.4 MB 1.1 MB/s eta 0:00:00
Downloading cffi-1.17.1-cp313-cp313-win_amd64.whl (182 kB)
Downloading PyYAML-6.0.2-cp313-cp313-win_amd64.whl (156 kB)
Downloading sqlparse-0.5.3-py3-none-any.whl (44 kB)
Downloading typing_extensions-4.14.1-py3-none-any.whl (43 kB)
Using cached packaging-25.0-py3-none-any.whl (66 kB)
Downloading pycparser-2.22-py3-none-any.whl (117 kB)
Downloading tzdata-2025.2-py2.py3-none-any.whl (347 kB)
Building wheels for collected packages: django-allauth
  Building wheel for django-allauth (pyproject.toml) ... done
  Created wheel for django-allauth: filename=django_allauth-65.10.0-py3-none-any.whl size=1700502 sha256=00d80e7732dac8fe55657be69fe98c1fe670b69294283f25481732ec1c12ff04
  Stored in directory: c:\users\павел\appdata\local\pip\cache\wheels\c7\67\28\aebc6778edd1780c48b7192ff4c4e68a803ae705008a2fd3f0
Successfully built django-allauth
Installing collected packages: python-decouple, whitenoise, urllib3, tzdata, typing-extensions, typeguard, sqlparse, PyYAML, pyjwt, pycparser, psycopg-binary, packaging, oauthlib, idna, django-widget-tweaks, charset_normalizer, certifi, asgiref, requests, psycopg, gunicorn, Django, cffi, stripe, slippers, django-allauth, dj-database-url, cryptography, django-allauth-ui
Successfully installed Django-5.0.14 PyYAML-6.0.2 asgiref-3.9.1 certifi-2025.7.14 cffi-1.17.1 charset_normalizer-3.4.2 cryptography-45.0.5 dj-database-url-3.0.1 django-allauth-65.10.0 django-allauth-ui-1.8.1 django-widget-tweaks-1.5.0 gunicorn-23.0.0 idna-3.10 oauthlib-3.3.1 packaging-25.0 psycopg-3.2.9 psycopg-binary-3.2.9 pycparser-2.22 pyjwt-2.10.1 python-decouple-3.8 requests-2.32.4 slippers-0.6.2 sqlparse-0.5.3 stripe-12.3.0 typeguard-2.13.3 typing-extensions-4.14.1 tzdata-2025.2 urllib3-2.5.0 whitenoise-6.9.0