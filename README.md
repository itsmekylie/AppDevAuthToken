curl.exe -X POST -d "username=kylie&password=123" http://127.0.0.1:8000/api-token-auth/       
{"token":"cda38ed9cca2d8b22551095f48b41bd1e1a1a83b"}
curl.exe -H "Authorization: Token cda38ed9cca2d8b22551095f48b41bd1e1a1a83b" http://127.0.0.1:8000/secure-hello/
