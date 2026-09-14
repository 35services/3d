

```
Installing plugin "OctoPrint-ipOnConnect" from https://github.com/jneilliii/OctoPrint-ipOnConnect/archive/master.zip...
```
https://github.com/jneilliii/OctoPrint-ipOnConnect

```
Installing plugin "OctoPrint-ipOnConnect" from https://github.com/jneilliii/OctoPrint-ipOnConnect/archive/master.zip...
/usr/local/bin/python3.10 -m pip --disable-pip-version-check install file:///tmp/tmpsg92czsm/OctoPrint-ipOnConnect-master.zip --no-cache-dir --use-pep517 --no-build-isolation
Processing /tmp/tmpsg92czsm/OctoPrint-ipOnConnect-master.zip
Preparing metadata (pyproject.toml): started
Preparing metadata (pyproject.toml): finished with status 'done'
Requirement already satisfied: OctoPrint in /usr/local/lib/python3.10/site-packages (from OctoPrint-ipOnConnect==0.2.4) (1.11.8)
Requirement already satisfied: limits<5 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (4.8.0)
Requirement already satisfied: OctoPrint-FirmwareCheck>=2025.7.23 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2025.7.23)
Requirement already satisfied: blinker<1.9.0,>=1.8.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.8.2)
Requirement already satisfied: Click!=8.2.0,<8.3,>=8.1.8 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (8.2.1)
Requirement already satisfied: colorlog<7,>=6.9.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (6.10.1)
Requirement already satisfied: filetype<2,>=1.2.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.2.0)
Requirement already satisfied: tornado<6.6,>=6.5.1 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (6.5.7)
Requirement already satisfied: OctoPrint-PiSupport>=2025.7.23 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2025.7.23)
Requirement already satisfied: psutil<7,>=6.1.1 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (6.1.1)
Requirement already satisfied: libpass<2,>=1.8.1 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.9.3)
Requirement already satisfied: Flask-Assets<3,>=2.1.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.1.0)
Requirement already satisfied: OctoPrint-FileCheck>=2025.7.23 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2025.7.23)
Requirement already satisfied: pytz in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2026.2)
Requirement already satisfied: flask<3.1,>=3.0.3 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.0.3)
Requirement already satisfied: Flask-Babel<5,>=4.0.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (4.0.0)
Requirement already satisfied: wrapt<1.18,>=1.17.2 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.17.3)
Requirement already satisfied: Flask-Limiter<3.9,>=3.8 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.8.0)
Requirement already satisfied: netifaces<0.12,>=0.11.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (0.11.0)
Requirement already satisfied: unidecode in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.4.0)
Requirement already satisfied: wheel in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (0.45.1)
Requirement already satisfied: websocket-client<1.9,>=1.8.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.8.0)
Requirement already satisfied: requests<3,>=2.32.3 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.34.2)
Requirement already satisfied: future in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.0.0)
Requirement already satisfied: sarge==0.1.7.post1 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (0.1.7.post1)
Requirement already satisfied: werkzeug<3.1,>=3.0.6 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.0.6)
Requirement already satisfied: frozendict<3,>=2.4.6 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.4.7)
Requirement already satisfied: markdown<3.8,>=3.7 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.7)
Requirement already satisfied: packaging in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (24.2)
Requirement already satisfied: pathvalidate<4,>=3.2.1 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.3.1)
Requirement already satisfied: setuptools in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (65.5.1)
Requirement already satisfied: more-itertools>=10.5.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (11.1.0)
Requirement already satisfied: PyYAML<7,>=6.0.2 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (6.0.3)
Requirement already satisfied: semantic_version<3,>=2.10.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.10.0)
Requirement already satisfied: regex in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2026.5.9)
Requirement already satisfied: pyserial<4,>=3.5 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.5)
Requirement already satisfied: netaddr<1.4,>=1.3.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.3.0)
Requirement already satisfied: feedparser<7,>=6.0.11 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (6.0.12)
Requirement already satisfied: pydantic<3,>=2.10.6 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.13.4)
Requirement already satisfied: cachelib<0.14,>=0.13.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (0.13.0)
Requirement already satisfied: zipstream-ng<2.0.0,>=1.8.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.9.2)
Requirement already satisfied: emoji<3,>=2.14.1 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.15.0)
Requirement already satisfied: sentry-sdk<3,>=2.20.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.63.0)
Requirement already satisfied: pylru<2,>=1.2.1 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.3.1)
Requirement already satisfied: watchdog<5,>=4.0.2 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (4.0.2)
Requirement already satisfied: argon2-cffi>=23.1.0 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (25.1.0)
Requirement already satisfied: zeroconf<0.137,>=0.136.2 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (0.136.2)
Requirement already satisfied: Babel<2.17,>=2.16 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.16.0)
Requirement already satisfied: Flask-Login<0.7,>=0.6.3 in /usr/local/lib/python3.10/site-packages (from OctoPrint->OctoPrint-ipOnConnect==0.2.4) (0.6.3)
Requirement already satisfied: argon2-cffi-bindings in /usr/local/lib/python3.10/site-packages (from argon2-cffi>=23.1.0->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (25.1.0)
Requirement already satisfied: sgmllib3k in /usr/local/lib/python3.10/site-packages (from feedparser<7,>=6.0.11->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.0.0)
Requirement already satisfied: Jinja2>=3.1.2 in /usr/local/lib/python3.10/site-packages (from flask<3.1,>=3.0.3->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.1.6)
Requirement already satisfied: itsdangerous>=2.1.2 in /usr/local/lib/python3.10/site-packages (from flask<3.1,>=3.0.3->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.2.0)
Requirement already satisfied: webassets>=2.0 in /usr/local/lib/python3.10/site-packages (from Flask-Assets<3,>=2.1.0->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.0.0)
Requirement already satisfied: typing-extensions>=4 in /usr/local/lib/python3.10/site-packages (from Flask-Limiter<3.9,>=3.8->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (4.15.0)
Requirement already satisfied: rich<14,>=12 in /usr/local/lib/python3.10/site-packages (from Flask-Limiter<3.9,>=3.8->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (13.9.4)
Requirement already satisfied: ordered-set<5,>4 in /usr/local/lib/python3.10/site-packages (from Flask-Limiter<3.9,>=3.8->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (4.1.0)
Requirement already satisfied: deprecated>=1.2 in /usr/local/lib/python3.10/site-packages (from limits<5->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (1.3.1)
Requirement already satisfied: typing-inspection>=0.4.2 in /usr/local/lib/python3.10/site-packages (from pydantic<3,>=2.10.6->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (0.4.2)
Requirement already satisfied: pydantic-core==2.46.4 in /usr/local/lib/python3.10/site-packages (from pydantic<3,>=2.10.6->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.46.4)
Requirement already satisfied: annotated-types>=0.6.0 in /usr/local/lib/python3.10/site-packages (from pydantic<3,>=2.10.6->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (0.7.0)
Requirement already satisfied: urllib3<3,>=1.26 in /usr/local/lib/python3.10/site-packages (from requests<3,>=2.32.3->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.7.0)
Requirement already satisfied: idna<4,>=2.5 in /usr/local/lib/python3.10/site-packages (from requests<3,>=2.32.3->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.18)
Requirement already satisfied: certifi>=2023.5.7 in /usr/local/lib/python3.10/site-packages (from requests<3,>=2.32.3->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2026.6.17)
Requirement already satisfied: charset_normalizer<4,>=2 in /usr/local/lib/python3.10/site-packages (from requests<3,>=2.32.3->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.4.7)
Requirement already satisfied: MarkupSafe>=2.1.1 in /usr/local/lib/python3.10/site-packages (from werkzeug<3.1,>=3.0.6->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.0.3)
Requirement already satisfied: async-timeout>=3.0.0 in /usr/local/lib/python3.10/site-packages (from zeroconf<0.137,>=0.136.2->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (5.0.1)
Requirement already satisfied: ifaddr>=0.1.7 in /usr/local/lib/python3.10/site-packages (from zeroconf<0.137,>=0.136.2->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (0.2.0)
Requirement already satisfied: pygments<3.0.0,>=2.13.0 in /usr/local/lib/python3.10/site-packages (from rich<14,>=12->Flask-Limiter<3.9,>=3.8->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.20.0)
Requirement already satisfied: markdown-it-py>=2.2.0 in /usr/local/lib/python3.10/site-packages (from rich<14,>=12->Flask-Limiter<3.9,>=3.8->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (4.2.0)
Requirement already satisfied: zope-dottedname>=6.0 in /usr/local/lib/python3.10/site-packages (from webassets>=2.0->Flask-Assets<3,>=2.1.0->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (7.1)
Requirement already satisfied: cffi>=1.0.1 in /usr/local/lib/python3.10/site-packages (from argon2-cffi-bindings->argon2-cffi>=23.1.0->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (2.0.0)
Requirement already satisfied: pycparser in /usr/local/lib/python3.10/site-packages (from cffi>=1.0.1->argon2-cffi-bindings->argon2-cffi>=23.1.0->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (3.0)
Requirement already satisfied: mdurl~=0.1 in /usr/local/lib/python3.10/site-packages (from markdown-it-py>=2.2.0->rich<14,>=12->Flask-Limiter<3.9,>=3.8->OctoPrint->OctoPrint-ipOnConnect==0.2.4) (0.1.2)
Building wheels for collected packages: OctoPrint-ipOnConnect
Building wheel for OctoPrint-ipOnConnect (pyproject.toml): started
Building wheel for OctoPrint-ipOnConnect (pyproject.toml): finished with status 'done'
Created wheel for OctoPrint-ipOnConnect: filename=OctoPrint_ipOnConnect-0.2.4-py3-none-any.whl size=3467 sha256=5138b18f1830590b1f9d7c639b8c64b6a16bddeea92885738d21f4907f654e71
Stored in directory: /tmp/pip-ephem-wheel-cache-lafst8v3/wheels/f2/21/38/d2d127ffe5f4057bc00177b224f345a8ecc9d0ad54d3671b08
Successfully built OctoPrint-ipOnConnect
Installing collected packages: OctoPrint-ipOnConnect
Successfully installed OctoPrint-ipOnConnect-0.2.4
WARNING: Running pip as the 'root' user can result in broken permissions and conflicting behaviour with the system package manager. It is recommended to use a virtual environment instead: https://pip.pypa.io/warnings/venv
Done!
```
