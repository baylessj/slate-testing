--- 

title: Snippets API 

language_tabs: 
   - shell 

toc_footers: 
   - <a href='#'>Sign Up for a Developer Key</a> 
   - <a href='https://github.com/lavkumarv'>Documentation Powered by lav</a> 

includes: 
   - errors 

search: true 

--- 

# Introduction 

Test description 

**Version:** v1 

# Authentication 

|basic|*Basic*|
|---|---| 

# /ACCOUNTS/CHANGE-PASSWORD/
## ***POST*** 

**Description:** Change the user password.

### HTTP Request 
`***POST*** /accounts/change-password/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /ACCOUNTS/LOGIN/
## ***POST*** 

**Description:** Logs in the user via given login and password.

### HTTP Request 
`***POST*** /accounts/login/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /ACCOUNTS/LOGOUT/
## ***POST*** 

**Description:** Logs out the user. returns an error if the user is not
authenticated.

### HTTP Request 
`***POST*** /accounts/logout/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /ACCOUNTS/PROFILE/
## ***GET*** 

**Description:** Get or set user profile.

### HTTP Request 
`***GET*** /accounts/profile/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***POST*** 

**Description:** Get or set user profile.

### HTTP Request 
`***POST*** /accounts/profile/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

## ***PUT*** 

**Description:** Get or set user profile.

### HTTP Request 
`***PUT*** /accounts/profile/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PATCH*** 

**Description:** Get or set user profile.

### HTTP Request 
`***PATCH*** /accounts/profile/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***DELETE*** 

**Description:** Get or set user profile.

### HTTP Request 
`***DELETE*** /accounts/profile/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 204 |  |

# /ACCOUNTS/REGISTER-EMAIL/
## ***POST*** 

**Description:** Register new email.

### HTTP Request 
`***POST*** /accounts/register-email/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /ACCOUNTS/REGISTER/
## ***POST*** 

**Description:** Register new user.

### HTTP Request 
`***POST*** /accounts/register/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /ACCOUNTS/RESET-PASSWORD/
## ***POST*** 

**Description:** Reset password, given the signature and timestamp from the link.

### HTTP Request 
`***POST*** /accounts/reset-password/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /ACCOUNTS/SEND-RESET-PASSWORD-LINK/
## ***POST*** 

**Description:** Send email with reset password link.

### HTTP Request 
`***POST*** /accounts/send-reset-password-link/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /ACCOUNTS/VERIFY-EMAIL/
## ***POST*** 

**Description:** Verify email via signature.

### HTTP Request 
`***POST*** /accounts/verify-email/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /ACCOUNTS/VERIFY-REGISTRATION/
## ***POST*** 

**Description:** Verify registration via signature.

### HTTP Request 
`***POST*** /accounts/verify-registration/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /API/{VERSION}/CARS/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /api/{version}/cars/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| version | path |  | Yes | string |
| page | query | A page number within the paginated result set. | No | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***POST*** 

**Description:** 

### HTTP Request 
`***POST*** /api/{version}/cars/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /API/{VERSION}/CARS/{ID}/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /api/{version}/cars/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this car. | Yes | integer |
| version | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PUT*** 

**Description:** 

### HTTP Request 
`***PUT*** /api/{version}/cars/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this car. | Yes | integer |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PATCH*** 

**Description:** 

### HTTP Request 
`***PATCH*** /api/{version}/cars/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this car. | Yes | integer |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***DELETE*** 

**Description:** 

### HTTP Request 
`***DELETE*** /api/{version}/cars/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this car. | Yes | integer |
| version | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 204 |  |

# /API/{VERSION}/ODOMSNAPSHOTS/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /api/{version}/odomsnapshots/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| version | path |  | Yes | string |
| page | query | A page number within the paginated result set. | No | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***POST*** 

**Description:** 

### HTTP Request 
`***POST*** /api/{version}/odomsnapshots/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /API/{VERSION}/ODOMSNAPSHOTS/{ID}/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /api/{version}/odomsnapshots/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this odom snapshot. | Yes | integer |
| version | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PUT*** 

**Description:** 

### HTTP Request 
`***PUT*** /api/{version}/odomsnapshots/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this odom snapshot. | Yes | integer |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PATCH*** 

**Description:** 

### HTTP Request 
`***PATCH*** /api/{version}/odomsnapshots/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this odom snapshot. | Yes | integer |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***DELETE*** 

**Description:** 

### HTTP Request 
`***DELETE*** /api/{version}/odomsnapshots/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this odom snapshot. | Yes | integer |
| version | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 204 |  |

# /API/{VERSION}/REFUELINGS/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /api/{version}/refuelings/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| version | path |  | Yes | string |
| page | query | A page number within the paginated result set. | No | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***POST*** 

**Description:** 

### HTTP Request 
`***POST*** /api/{version}/refuelings/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /API/{VERSION}/REFUELINGS/{ID}/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /api/{version}/refuelings/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this refueling. | Yes | integer |
| version | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PUT*** 

**Description:** 

### HTTP Request 
`***PUT*** /api/{version}/refuelings/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this refueling. | Yes | integer |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PATCH*** 

**Description:** 

### HTTP Request 
`***PATCH*** /api/{version}/refuelings/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this refueling. | Yes | integer |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***DELETE*** 

**Description:** 

### HTTP Request 
`***DELETE*** /api/{version}/refuelings/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this refueling. | Yes | integer |
| version | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 204 |  |

# /API/{VERSION}/TODOS/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /api/{version}/todos/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| version | path |  | Yes | string |
| page | query | A page number within the paginated result set. | No | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***POST*** 

**Description:** 

### HTTP Request 
`***POST*** /api/{version}/todos/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /API/{VERSION}/TODOS/{ID}/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /api/{version}/todos/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this todo. | Yes | integer |
| version | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PUT*** 

**Description:** 

### HTTP Request 
`***PUT*** /api/{version}/todos/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this todo. | Yes | integer |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PATCH*** 

**Description:** 

### HTTP Request 
`***PATCH*** /api/{version}/todos/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this todo. | Yes | integer |
| version | path |  | Yes | string |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***DELETE*** 

**Description:** 

### HTTP Request 
`***DELETE*** /api/{version}/todos/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this todo. | Yes | integer |
| version | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 204 |  |

# /AUTH/TOKEN/
## ***POST*** 

**Description:** Takes a set of user credentials and returns an access and refresh JSON web
token pair to prove the authentication of those credentials.

### HTTP Request 
`***POST*** /auth/token/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /AUTH/TOKEN/REFRESH/
## ***POST*** 

**Description:** Takes a refresh type JSON web token and returns an access type JSON web
token if the refresh token is valid.

### HTTP Request 
`***POST*** /auth/token/refresh/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /CARS/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /cars/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | A page number within the paginated result set. | No | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***POST*** 

**Description:** 

### HTTP Request 
`***POST*** /cars/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /CARS/{ID}/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /cars/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this car. | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PUT*** 

**Description:** 

### HTTP Request 
`***PUT*** /cars/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this car. | Yes | integer |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PATCH*** 

**Description:** 

### HTTP Request 
`***PATCH*** /cars/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this car. | Yes | integer |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***DELETE*** 

**Description:** 

### HTTP Request 
`***DELETE*** /cars/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this car. | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 204 |  |

# /ODOMSNAPSHOTS/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /odomsnapshots/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | A page number within the paginated result set. | No | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***POST*** 

**Description:** 

### HTTP Request 
`***POST*** /odomsnapshots/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /ODOMSNAPSHOTS/{ID}/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /odomsnapshots/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this odom snapshot. | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PUT*** 

**Description:** 

### HTTP Request 
`***PUT*** /odomsnapshots/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this odom snapshot. | Yes | integer |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PATCH*** 

**Description:** 

### HTTP Request 
`***PATCH*** /odomsnapshots/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this odom snapshot. | Yes | integer |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***DELETE*** 

**Description:** 

### HTTP Request 
`***DELETE*** /odomsnapshots/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this odom snapshot. | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 204 |  |

# /REFUELINGS/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /refuelings/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | A page number within the paginated result set. | No | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***POST*** 

**Description:** 

### HTTP Request 
`***POST*** /refuelings/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /REFUELINGS/{ID}/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /refuelings/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this refueling. | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PUT*** 

**Description:** 

### HTTP Request 
`***PUT*** /refuelings/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this refueling. | Yes | integer |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PATCH*** 

**Description:** 

### HTTP Request 
`***PATCH*** /refuelings/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this refueling. | Yes | integer |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***DELETE*** 

**Description:** 

### HTTP Request 
`***DELETE*** /refuelings/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this refueling. | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 204 |  |

# /TODOS/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /todos/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | A page number within the paginated result set. | No | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***POST*** 

**Description:** 

### HTTP Request 
`***POST*** /todos/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 |  |

# /TODOS/{ID}/
## ***GET*** 

**Description:** 

### HTTP Request 
`***GET*** /todos/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this todo. | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PUT*** 

**Description:** 

### HTTP Request 
`***PUT*** /todos/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this todo. | Yes | integer |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***PATCH*** 

**Description:** 

### HTTP Request 
`***PATCH*** /todos/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this todo. | Yes | integer |
| data | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 |  |

## ***DELETE*** 

**Description:** 

### HTTP Request 
`***DELETE*** /todos/{id}/` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | A unique integer value identifying this todo. | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 204 |  |

<!-- Converted with the swagger-to-slate https://github.com/lavkumarv/swagger-to-slate -->
