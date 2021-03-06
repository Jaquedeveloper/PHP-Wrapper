#ENGLISH VERSION:

Before you start testing the API system, you need to contact Easypay at <tec@easypay.pt>.  
We need to change the configuration of your account to be ready to receive notifications via API.  
If you don't have a Free Plan, you may request the "Test" environment as well.  
In all communications with Easypay, please send us your CIN (0000) and your USER ID (XXXX000000).

Now that you have your account configured, you may proceed to the installation process.

You can check the examples here, step by step:

* `EasypayCreatePaymentReferenceExample.php`  
   Shows you how to create a reference and use it to start the payment process.
   
* `EasypayPaymentNotificationExample.php`  
   After filling the client information, it will be redirected to this file.  
   That information will be saved on your database.
   
* `EasypayRequestPaymentExample.php`  
   Once the payment is realized, EasyPay will call this file, so you can store necessary info.
   
* `EasypayTransactionVerificationExample.php`  
   When a client authorizes a payment trough our credit card gateway our systems send you back a transaction key in the "visa-fwd" URL.


#PORTUGUESE VERSION:

Antes de começar a testar o Sistema de APIs, será necessário contactar a EasyPay através do seguinte endereço <tec@easypay.pt>.  
Necessitamos de alterar a configuração da sua conta, para que esta esteja apta a receber notificações via API.  
Se não tiver um Plano Gratuito, deverá pedir o plano de testes.  
Será necessário enviar o seu CIN (0000) e User ID (XXXX000000) em todas as comunicações que efectue com a EasyPay.

Agora que tem a sua conta configurada, deverá proceder ao processo de instalação.

Poderá ter em conta os exemplos aqui mencionados, passo-a-passo:

* `EasypayCreatePaymentReferenceExample.php`  
   Aqui poderá ver como criar uma referência e usá-la para o inicio do processo de pagamento.
 
* `EasypayPaymentNotificationExample.php`  
   Assim que o cliente tenha preenchido a informação necessária. poderá ser redireccionado para este mesmo ficheiro onde será armazenada na sua base de dados a informação referente a esta mesma transacção.

* `EasypayRequestPaymentExample.php`  
   Assim que o pagamento for realizado, a EasyPay chamará este ficheiro. assim conseguirá aceder á informação necessária.

* `EasypayTransactionVerificationExample.php`  
   Quando um cliente autoriza um pagamento através do nosso gateway de pagamento ser-lhe-á enviada a chave de transacção via "visa-fwd" URL.


                              




