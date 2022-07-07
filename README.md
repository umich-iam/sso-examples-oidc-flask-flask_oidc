Taken from https://github.com/puiterwijk/flask-oidc/blob/master/example.py

This seems to want client_secret_post

flask-oidc needs a downrev version of itsdangerous (<=2.0.1), otherwise you'll run into
ImportError: cannot import name 'JSONWebSignatureSerializer' from 'itsdangerous'
https://github.com/puiterwijk/flask-oidc/issues/147

If you get ssl.SSLCertVerificationError, This is annoying but relevant
https://stackoverflow.com/questions/19421538/parameters-of-httplib2-http-request

