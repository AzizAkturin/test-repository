**Endpoints tested**: 48
**Endpoints passed**: 0
**Endpoints failed**: 48## Endpoint: /v1/admin/items/{item_id}

### Success: False

**Method:** DELETE
**Test ID** `missing-auth`

**Expected Outputs:** [401 403]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/admin/items/{item_id}

### Success: False

**Method:** DELETE
**Test ID** `invalid-auth-token`

**Expected Outputs:** [401 403]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/admin/items/{item_id}

### Success: False

**Method:** DELETE
**Test ID** `missing-required-header-authorization`

**Expected Outputs:** [401 403]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/admin/items/{item_id}

### Success: False

**Method:** DELETE
**Test ID** `wrong-header-value-authorization`

**Expected Outputs:** [401 403]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/admin/items/{item_id}

### Success: False

**Method:** DELETE
**Test ID** `success-valid-request`

**Expected Outputs:** [200]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/admin/items/{item_id}

### Success: False

**Method:** DELETE
**Test ID** `missing-required-path-item-id`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/admin/items/{item_id}

### Success: False

**Method:** DELETE
**Test ID** `wrong-type-path-item-id`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/admin/items/{item_id}

### Success: False

**Method:** DELETE
**Test ID** `below-min-path-item-id`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/debug/failure-demo

### Success: False

**Method:** GET
**Test ID** `missing-auth`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/debug/failure-demo

### Success: False

**Method:** GET
**Test ID** `missing-required-header-authorization`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/debug/failure-demo

### Success: False

**Method:** GET
**Test ID** `wrong-header-value-authorization`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/debug/failure-demo

### Success: False

**Method:** GET
**Test ID** `success-valid-request`

**Expected Outputs:** [200]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/debug/failure-demo

### Success: False

**Method:** GET
**Test ID** `missing-required-query-n`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/debug/failure-demo

### Success: False

**Method:** GET
**Test ID** `wrong-type-query-n`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/debug/failure-demo

### Success: False

**Method:** GET
**Test ID** `below-min-query-n`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/debug/failure-demo

### Success: False

**Method:** GET
**Test ID** `above-max-query-n`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `missing-auth`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `missing-required-header-authorization`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `wrong-header-value-authorization`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `success-valid-request`

**Expected Outputs:** [200]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `missing-required-path-item-id`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `missing-required-query-include-history`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `wrong-type-path-item-id`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `below-min-path-item-id`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `wrong-type-query-include-history`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `invalid-enum-query-include-history`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `wrong-type-query-verbosity`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `below-min-query-verbosity`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/items/{item_id}

### Success: False

**Method:** GET
**Test ID** `above-max-query-verbosity`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `missing-auth`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `missing-required-header-authorization`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `wrong-header-value-authorization`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `missing-required-header-content-type`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `wrong-header-value-content-type`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `success-valid-request`

**Expected Outputs:** [200]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `missing-required-query-model-version`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `wrong-type-query-model-version`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `below-min-query-model-version`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `above-max-query-model-version`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `wrong-type-query-mode`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `invalid-enum-query-mode`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/score

### Success: False

**Method:** POST
**Test ID** `rate-limit-exceeded-5`

**Expected Outputs:** [429]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/users

### Success: False

**Method:** POST
**Test ID** `missing-auth`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/users

### Success: False

**Method:** POST
**Test ID** `missing-required-header-authorization`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/users

### Success: False

**Method:** POST
**Test ID** `wrong-header-value-authorization`

**Expected Outputs:** [401]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/users

### Success: False

**Method:** POST
**Test ID** `missing-required-header-content-type`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/users

### Success: False

**Method:** POST
**Test ID** `wrong-header-value-content-type`

**Expected Outputs:** [422]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```## Endpoint: /v1/users

### Success: False

**Method:** POST
**Test ID** `success-valid-request`

**Expected Outputs:** [200]
**Booted Code:** 404

**Booted Output:**
```
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>
```