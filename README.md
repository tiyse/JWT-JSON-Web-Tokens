# JWT-JSON-Web-Tokens

<script src="https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.1.1/crypto-js.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.1.1/enc-base64.min.js"></script>

var to_sign = create_token();
very_bas64_key(btoa('This is a printable string.\n'), to_sign);
very_secret(btoa('This is a printable string.\n'), to_sign);
