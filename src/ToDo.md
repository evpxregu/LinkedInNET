
API definition
---------------------------------

- [x] APIs are grouped as `<ApiGroup />`  
- [x] Extract UrlPathParameters from `<ApiMethod Path="/v1/people/id={MemberToken}" />`  
- [x] Declare `<ReturnType />` and `<ApiMethod ReturnType="Person" />`
- [ ] Add SecureUrls in configuration and use `secure-urls=true`  
- [ ] People  
- [ ] Companies  
- [ ] Groups  
- [ ] Jobs  
- [ ] Everything else  

Code generation
---------------------------------

- [x] Setup .tt file and generation class  
- [x] Generate API groups  
- [x] Generate API group  
- [x] Generate basic return types  
- [x] Generate basic methods  
- [x] Support 1 level of field selectors `/v1/people/id=12345:(first-name,last-name)`  
- [ ] Support all levels of field selectors   
- [ ] Collections of ResultType  
- [ ] Fix generation of sub-fields (ex: location:(name))  

API other items
---------------------------------

- [ ] Profile: Some members have profiles in multiple languages. To specify the language you prefer, pass an Accept-Language HTTP header.  
- [ ] Pagination: start=0, count=500  
- [ ] `/v1/companies?is-company-admin=true`  



- [ ]   

- [ ] to do 
- [ ] partial support 
- [x] done  
