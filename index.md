<html>
  <body>
    <script type='text/javascript'>
    function initEmbeddedMessaging() {
      try {
        embeddedservice_bootstrap.settings.language = 'pt_BR'; // For example, enter 'en' or 'en-US'

        embeddedservice_bootstrap.init(
          '00D6u0000000Mmk',
          'MIAW_Web_Chat',
          'https://uhgbrasil--coepoc.sandbox.my.site.com/ESWMIAWWebChat1686936709891',
          {
            scrt2URL: 'https://uhgbrasil--coepoc.sandbox.my.salesforce-scrt.com'
          }
        );
      } catch (err) {
        console.error('Error loading Embedded Messaging: ', err);
      }
    };
  </script>
  <script type='text/javascript' src='https://uhgbrasil--coepoc.sandbox.my.site.com/ESWMIAWWebChat1686936709891/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
 </body>
</html>
