# 微信登录

## 根据 jsCode 获取用户 session 信息

API:

```php
$ret = $app->auth->session(string $code);
```
## 根据登录返回参数获取用户手机号

$app->encryptor->decryptData($ret['session_key'], $iv, $encrypted_data);

