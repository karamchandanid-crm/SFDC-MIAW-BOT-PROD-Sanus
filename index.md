<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D600000007Dpt',
				'Github_Sanus_Live_Chat_Messaging_Channel',
				'https://legrandav.my.site.com/ESWGithubSanusLiveChat1740465772633',
				{
					scrt2URL: 'https://legrandav.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://legrandav.my.site.com/ESWGithubSanusLiveChat1740465772633/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
