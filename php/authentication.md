### Authentication 

#### Connecting with a store

Using the Bigcommerce PHP library, you can establish a connection with a store in the following way.

<pre>
    require 'vendor/autoload.php';
    use Bigcommerce\Api\Client as Bigcommerce;

    Bigcommerce::configure(array(
    'store_url' => 'https://store-xxx.mybigcommerce.com',
    'username' => 'admin',
    'api_key' => 'xxxxxx'
    ));
    Bigcommerce::setCipher('RC4-SHA')
    Bigcommerce::verifyPeer(false);
    
</pre>
