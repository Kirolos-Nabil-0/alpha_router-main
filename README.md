# Ⲁ_router
Ⲁ(alpha) router is an open source PHP routing library that provides high security routing (Dont worry about XSS || CSRF )

## How to use ?
1. Download the files
2. in the file that you write in the whole routes  `require_once __DIR__.'/a_router.php';` 
3. Create object from the class Router
4. start using the method to Route evrey thing
---
## simple explainig : 
1. We Have 5 methods :
* get()--> for get requests
* post()-->for post requests
* delete()-->for delete requests
* patch()-->for patch requests
* any()-->for any kind of requests
---
## exampels:
>`require_once __DIR__.'/a_router.php';`

### Static GET  Routing
<br />
>`$router = new Router`;
<br />
>`$router->get('/','/views/index') ; `
<br />
### Dynamic GET Routing
>`$router = new Router`;
<br />
>`$router->get('/User/$name/','/views/mens') ; `


