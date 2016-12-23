# yii2-laravel-crypt
this is same as laravel(>=5.1) encrypt and decrypt function
example:

```
$cryption = new \Cryption\Encrypter("yourRandomString","AES-256-CBC");
$cryption->encrypt($result["business_response"]);

```