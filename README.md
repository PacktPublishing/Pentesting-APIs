> [!NOTE]
> To download the utils folder containing the tools mentioned in chapter 4, you can download the file from here: [[Utils-folder]](https://packt.link/gbz/9781837633166)

# Pentesting APIs

<a href="https://www.packtpub.com/en-in/product/pentesting-apis-9781837633166"><img src="https://content.packt.com/_/image/xxlarge/B19657/cover_image_large.jpg" alt="no-image" height="256px" align="right"></a>

This is the code repository for [Pentesting APIs](https://www.packtpub.com/en-in/product/pentesting-apis-9781837633166), published by Packt.

**A practical guide to discovering, fingerprinting,and exploiting APIs**

## What is this book about?
A comprehensive book that equips you with essential techniques to assess, exploit, and secure APIs against cyber threats.

This book covers the following exciting features:
* Get an introduction to APIs and their relationship with security
* Set up an effective pentesting lab for API intrusion
* Conduct API reconnaissance and information gathering in the discovery phase
* Execute basic attacks such as injection, exception handling, and DoS
* Perform advanced attacks, including data exposure and business logic abuse
* Benefit from expert security recommendations to protect APIs against attacks

If you feel this book is for you, get your [copy](https://www.amazon.com/Pentesting-APIs-discovering-fingerprinting-exploiting/dp/1837633169) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, chapters/chapter04.

The code will look like the following:
```
<env:Header>
  <BA:BlockA xmlns:BA="http://mysoap.com"
   env:role="http://mysoap.com/role/A" env:mustUnderstand="true">
   ...
  </BA:BlockA>
  <BB:BlockB xmlns:BB="http://mysoap.com"
   env:role="http://mysoap.com/role/B" env:relay="true">
   ...
  </BB:BlockB>
</env:Header>

```

**Following is what you need for this book:**
This book is for security engineers, particularly those focused on application security, as well as security analysts, application owners, web developers, pentesters, and all curious enthusiasts who want to learn about APIs, effective testing methods for their robustness, and how to protect them against cyber attacks. Basic knowledge of web development, familiarity with API concepts, and a foundational understanding of cybersecurity principles will help you get started with this book.

With the following software and hardware list you can run all code files present in the book (Chapter 4-9). This is the directory structure:
```bash
.
├── LICENSE
├── README.md
└── chapters
    ├── chapter04
    │   ├── bypass_access_control_ex1.py
    │   ├── bypass_access_control_ex2.py
    │   ├── bypass_access_control_ex3.py
    │   ├── common_credentials.sh
    │   ├── fixed_bfla.go
    │   ├── fixed_bola.py
    │   ├── oauth_initial_code.py
    │   ├── oauth_scopes.py
    │   ├── session.py
    │   ├── vulnerable_bfla.go
    │   └── vulnerable_bola.py
    ├── chapter05
    │   ├── input_validation.java
    │   ├── sanitize_html.java
    │   ├── sanitize_query_parameters.py
    │   └── validate_file_uploads.java
    ├── chapter06
    │   ├── fuzz_with_uploads.sh
    │   ├── identify_error_codes.py
    │   └── vulnerable_code_to_fuzz.py
    ├── chapter07
    │   ├── circumvent_rate_limit.py
    │   ├── rate_limit_nginx.conf
    │   └── scapy_dos.py
    ├── chapter08
    │   ├── api_sensitive_data.py
    │   ├── generate_sensitive_data.sh
    │   ├── jwt_with_flask_jwt.py
    │   └── log_generator.sh
    └── chapter09
        ├── business_logic
        │   └── api_business_logic.py
        ├── credential_stuffing
        │   ├── Dockerfile
        │   ├── api_credential.py
        │   ├── credentials.txt
        │   └── requirements.txt
        ├── data_scraping
        │   ├── api_scraping.py
        │   └── bruteforce_spider.py
        └── parameter_tampering
            ├── api_tampering.py
            ├── manipulate_authorization.py
            ├── manipulate_role.py
            └── manipulate_transaction_status.py

```
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-10 | VirtualBox | Linux |


### Related products
* Defending APIs [[Packt]](https://www.packtpub.com/en-in/product/defending-apis-9781804617120) [[Amazon]](https://www.amazon.com/Defending-APIs-against-Cyber-Attack/dp/1804617121)

* Offensive Security Using Python [[Packt]](packtpub_link) [[Amazon]](https://www.amazon.com/Offensive-Security-Using-Python-Handbook/dp/1835468160)

## Get to Know the Author
**Maurício Harley**
holds an MSc in cybersecurity, a Bachelor of Science in electrical engineering, and a technologist degree in telematics. He’s CISSP and double CCIE certified.
He has written offensive security articles for some magazines. He has 30 years of combined experience in areas such as application security and forensic analysis. He has delivered security talks at Brazilian, European, and Latin American events, such as RootDay, RootSec, AWS LATAM Security Talks, AWS Security Workshops, EMEA AeroSpace Smart Factory, and OWASP LATAM@Home.
He has participated in various security projects in Latin America and Europe, Middle East, and Africa (EMEA), delivering professional services in Angola, Austria, Bahrain, Brazil, Finland, France, Germany, Netherlands, Spain, South Africa, and the United Kingdom.



