# -DOCTYPE-html-head-meta-http-equiv-X-UA-Compatible-content-IE-edge-meta-name-v
&lt;!DOCTYPE html> &lt;head>     &lt;meta http-equiv="X-UA-Compatible" content="IE=edge" />     &lt;meta name="viewport" content="width=device-width, initial-scale=1">     &lt;script src="https://www.paypalobjects.com/api/checkout.js">&lt;/script> &lt;/head> &lt;body>     &lt;div id="paypal-button">&lt;/div>     &lt;script>         paypal.Button.render({             env: 'production', // Or 'sandbox',             commit: true, // Show a 'Pay Now' button             payment: function() {                 // Set up the payment here             },             onAuthorize: function(data, actions) {                 // Execute the payment here            }         }, '#paypal-button');     &lt;/script> &lt;/body>
